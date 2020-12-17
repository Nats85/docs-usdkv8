---
title: Autenticación con Directorio Activo
chapter: "configuracion"
---

Para configurar la autenticación con directorio activo se debe realizar el siguiente procedimiento:

a)  Haga clic en: **Inicio \> Todos los programas \> Aranda Software \> Aranda Tools \> Profile**.

b)  En la siguiente pantalla, seleccione **Tipo de Autenticación**:

![]({{ site.baseurl }}/assets/images/image2.jpg)

c)  Seleccione el tipo de autenticación y haga clic en la opción **Nuevo**:

![]({{ site.baseurl }}/assets/images/image3.jpg)

d)  Diligencie el formulario:

![]({{ site.baseurl }}/assets/images/image4.jpg)

-   **Nombre:** Digite el nombre exacto del dominio

-   **Seguridad:** Digite 0 sin seguridad -1 con seguridad

-   **Ruta:** Digite LDAP://IpServerActiveDirectory

-   **Cadena de usuario:** Digite {0} o NombreDominio\\{0}. Esto > dependerá del dominio.

e)  Haga clic en **Aceptar**.

![]({{ site.baseurl }}/assets/images/image5.jpg)

**Nota**: Al escoger únicamente la opción de la autenticación con el
Directorio Activo solo será posible ingresar a las soluciones de Aranda
con dicha autenticación.

Si desear tener un tipo de autenticación mixta (Autenticación Aranda y
Autenticación con el Directorio Activo), escoja la opción Mixta en el
primer recuadro y luego señale el tipo de autenticación que desea para
la autenticación por defecto:

![]({{ site.baseurl }}/assets/images/image6.jpg)

**Nota**: El servidor de Aranda debe tener visibilidad al servidor del Directorio Activo
