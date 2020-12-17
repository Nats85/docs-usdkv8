---
title: Tipos de ingreso
chapter: "configuracion"
---

  Puede ingresar a la consola como usuario registrado, usuario anónimo o usuario nuevo:

  ### Usuario registrado

  Elija el tipo de autenticación según sea el caso (Propia: "Aranda" o Integrada al directorio activo: "Dominio empresa"), digite los datos del usuario y contraseña creados previamente en la herramienta y haga clic en **Acceder**.

  ![]({{ site.baseurl }}/assets/images/image12.jpg)

  ### Usuario anónimo

  Habilite la opción **Acceso anónimo** y haga clic en **Acceder**. Esta opción solo está disponible cuando el administrador de la herramienta decide habilitarla.

  ![]({{ site.baseurl }}/assets/images/image13.jpg)

  #### Cómo habilitar el acceso anónimo

  Para habilitar el acceso de usuarios anónimos a la consola USDK V8 realice la siguiente configuración:

  A.  En la consola de Usuarios y Seguridad Aranda Profile, cree un usuario genérico al cual se le va a asociar el ingreso anónimo.

  ![]({{ site.baseurl }}/assets/images/image14.jpg)

  B.  Luego, en la consola de Configuración y Administración Aranda Blogik (BASDK), asocie el usuario creado al proyecto, así: "**ITIL**" \> "**Usuarios por Proyecto**" \> "**Asociar**", y proceda a buscarlo y seleccionarlo.

  ![]({{ site.baseurl }}/assets/images/image15.jpg)

  C.  Luego, en BASDK, asocie el usuario a los servicios a los que tendrá acceso, así: "**ITIL**" \> "**Categorías**" \> busque en su respectivo Proceso y Categoría, uno a uno el **"Servicio**" y selecciónelo \> "**Editar**" \> "**Usuarios y Compañías**" \> "**Usuarios**" \> "**Asociar**" -- busque el usuario y selecciónelo.

  ![]({{ site.baseurl }}/assets/images/image16.jpg)

  D.  Haga clic en **Guardar**.

  ![]({{ site.baseurl }}/assets/images/image17.jpg)

  E.  Por último, vaya a "Consola de Usuario" \> "Opciones de Acceso" y marque la casilla "Habilitar acceso anónimo", busque el usuario creado y asócielo.

  ![]({{ site.baseurl }}/assets/images/image18.jpg)

  ### Usuario nuevo (registro)

  Esta opción solo está disponible si el administrador de la herramienta la habilita.

  a)  Seleccione la opción "Registrarse"

  ![]({{ site.baseurl }}/assets/images/image19.jpg)

  b)  Diligencie la información requerida y haga clic en el botón **Registrarse**.

  ![]({{ site.baseurl }}/assets/images/image20.jpg)

  c)  Por último, elija el tipo de autenticación Aranda, digite los datos del usuario, correo electrónico registrado y contraseña creados en el paso anterior y haga clic en **Acceder**.

  #### Cómo habilitar el registro de usuarios nuevos

  Habilite el registro de usuarios por base de datos siguiendo los siguientes pasos:

  A.  Modifique la tabla "SETINGENERAL" mediante un script de base de datos, así:

  **UPDATE SETINGENERAL SET SETVALUE = 1**

  **WHERE SETID = 2223; \--COMMIT; \--en Oracle**

  **Resultado:**

  ![]({{ site.baseurl }}/assets/images/image21.jpg)

  Donde para el SETID = 2223,

  Si SETVALUE = 1 Permite el registro de usuarios

  Si SETVALUE = 0 No Permite el registro de usuarios

  B.  Configure un proyecto y unos servicios por defecto

  El proyecto por defecto será aquel que cargue a todos los usuarios que se auto registren con la opción "Registrarse" e ingresen como nuevos.
  Así mismo, los servicios que se configuren por defecto, serán los que podrán solicitar estos usuarios.

  Para configurar el proyecto por defecto y sus servicios por defecto en la consola USDKV8, siga los siguientes pasos:

  a)  Para establecer el proyecto por defecto, modifique la tabla "SETINGENERAL" mediante un script de base de datos, así:

  UPDATE SETINGENERAL

  SET SETVALUE = \#

  WHERE SETID = 2128; \--COMMIT; \--en Oracle

  Para el SETID = 2128,

  Donde \# es el id (campo "FL_INT_ID") del proyecto que se desea configurar por defecto y que está en la tabla "ASDK_PROJECTS"

  **Ejemplo**: Si desea configurar el proyecto "Servicio al Cliente" por defecto, consulte la tabla "ASDK_PROJECTS" y obtenga su id "FL_INT_ID" select \* from ASDK_PROJECTS

  **Resultado: FL_INT_ID = 3**

  ![]({{ site.baseurl }}/assets/images/image22.jpg)

  Luego realice el UPDATE a la tabla "SETINGENERAL", así: UPDATE SETINGENERAL

  SET SETVALUE = 3

  WHERE SETID = 2128; \--COMMIT; \--en Oracle Resultado:

  ![]({{ site.baseurl }}/assets/images/image23.jpg)

  b)  Para establecer los servicios por defecto modifique la tabla "ASDK_SERVICE_PROJECT", mediante un script de base de datos, así:

  INSERT INTO ASDK_SERVICE_PROJECT

  (project_id, service_id) VALUES (\#, \$);

  \--COMMIT; \--en Oracle

  Donde \# es el id (campo "FL_INT_ID") del proyecto al que pertenece el servicio que se desea configurar por defecto y que está en la tabla "ASDK_PROJECTS"

  Donde \$ es el id (campo "FL_INT_SERVICE_ID") del servicio que se desea configurar por defecto y que está en la tabla "ASDK_SERVICE".

  **Ejemplo**: Si desea configurar por defecto el servicio "Sugerencias" del proyecto "Servicio al Cliente", consulte primero la tabla "ASDK_PROJECTS" y obtenga el id "FL_INT_ID" del proyecto

  select \* from ASDK_PROJECTS

  Resultado: FL_INT_ID = 3

  ![]({{ site.baseurl }}/assets/images/image24.jpg)

  Luego, consulte la tabla "ASDK_SERVICE" y obtenga el id "FL_INT_SERVICE_ID" del servicio, asegurándose de que coincida con el id del proyecto "FL_INT_PROJECT_ID" =3

  Select \*from ASDK_SERVICE

  Resultado: FL_INT_SERVICE_ID = 54, FL_INT_PROJECT_ID = 3

  ![]({{ site.baseurl }}/assets/images/image25.jpg)

  c)  Por último, realice el INSERT a la tabla "ASDK_SERVICE_PROJECT",
      así:

  INSERT INTO ASDK_SERVICE_PROJECT

  (project_id, service_id) VALUES (3, 54);

  \--COMMIT; \--en Oracle

  Resultado:

  ![]({{ site.baseurl }}/assets/images/image26.jpg)

  #### Cómo permitir el cambio de contraseña de los usuarios

  Para permitir que los usuarios modifiquen la contraseña, ingrese a la Consola de Administración BASDK y seleccione la opción **Detalles Cliente**, allí, marque el recuadro para habilitar la opción de permitir que el cliente edite sus detalles.

  ![]({{ site.baseurl }}/assets/images/image27.jpg)

  
