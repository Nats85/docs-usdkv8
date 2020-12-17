---
title: Autenticación LDAP Linux
chapter: "configuracion"
---

Para configurar la autenticación con LDAP Linux siga el siguiente procedimiento:

  a)  Haga clic en **Inicio \> Todos los programas \> Aranda Software \> Aranda Tools \> Profile**.

  b)  En la siguiente pantalla, seleccione **Tipo de Autenticación**

  ![]({{ site.baseurl }}/assets/images/image7.jpg)

  c)  Seleccione el tipo de autenticación y haga clic en **Nuevo**

  ![]({{ site.baseurl }}/assets/images/image8.jpg)

  d)  Diligencie el formulario:

![]({{ site.baseurl }}/assets/images/image9.jpg)

  -   **Nombre:** Digite el nombre exacto del dominio.

  -   **Seguridad:** Digite 0 sin seguridad -- 1 con seguridad.

  -   **Ruta:** Digite LDAP://ServidorDominio/NombreDominio

  -   **Cadena de usuario:** digite uid={0},ou=people,o=NombreDominio. Esto dependerá del dominio.

  e)  Haga clic en **Aceptar**.

  ![]({{ site.baseurl }}/assets/images/image10.jpg)

  **Nota**: Al escoger únicamente la opción de la autenticación con el
  Directorio Activo solo será posible ingresar a las soluciones de Aranda
  con dicha autenticación.

  Si desear tener un tipo de autenticación mixta (Autenticación Aranda y
  Autenticación con el Directorio Activo) se debe escoger la opción Mixta
  en el primer recuadro y luego señalar el tipo de autenticación que
  deseamos para la autenticación por defecto:

![]({{ site.baseurl }}/assets/images/image11.jpg)
