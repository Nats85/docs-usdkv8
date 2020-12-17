---
title: Encuestas pendientes
chapter: "panel"
---
Si tiene encuestas pendientes por responder, haga clic en el botón **Ver encuestas**:

![]({{ site.baseurl }}/assets/images/image56.jpg)

Se listarán las encuestas pendientes por cada uno de los casos; haga clic en **Responder**:

![]({{ site.baseurl }}/assets/images/image57.jpg)

Se abrirá la página de la encuesta, respóndala y haga clic en el botón **Enviar Encuesta.**

![]({{ site.baseurl }}/assets/images/image58.jpg)

### Registro de casos con el wizard

El wizard de creación de casos es un asistente que guía a los usuarios en el proceso para crear casos a través de una interfaz intuitiva sin omitir ningún detalle.

-   Se encuentra disponible a partir de la versión 8.14.0 del instalador

> "Aranda.ASDK.WebV8.Installer.exe" y versión de base de datos 8.0.72.

-   Puede habilitar o deshabilitar la creación de casos mediante wizard desde la consola Blogik.

-   El uso del Wizard sólo cambia la manera de crear un caso, no altera la funcionalidad de la consola de usuarios web USDKv8.

-   La la creación de caso con la funcionalidad de Wizard cuenta con las mismas opciones que en la creación de caso en la manera tradicional, con una mejora visual y un flujo más interactivo.

-   La configuración del Wizard afecta a todos los proyectos, no es por proyecto.

-   El Wizard también toma las configuraciones de branding aplicadas a la consola USDKv8.

-   El campo asunto ahora será diligenciado automáticamente con el nombre del servicio y la categoría seleccionada, esto para el método tradicional y el método Wizard en la creación de caso.

-   El usuario podrá borrar el contenido automático que la consola coloca en el asunto e ingresar uno personalizado.

### Configuración del wizard de creación de casos

La configuración del wizard solo se puede realizar en la consola de configuración web BASDK y es necesario tener las siguientes condiciones:

-   Contar con un usuario administrador

-   Estar asociado al menos a un proyecto

Ingrese a la consola de configuración web BASDK con usuario y contraseña válida de un administrador y diríjase a **Opciones \> Resumen**.

![]({{ site.baseurl }}/assets/images/image59.jpg)

En la sección de Opciones específicas, encontrará el recuadro para marcar y activar la creación de casos por Wizard USDK. Finalice guardando los cambios.

![]({{ site.baseurl }}/assets/images/image60.jpg)

Es necesario preparar los proyectos, servicios y las categorías de tal manera que que puedan visualizarse correctamente durante la creación de casos mediante wizard en USDK V8.

### Preparación de Proyectos

En la consola de configuración web BASDK, ingrese a **Opciones \> Proyectos**, elija el proyecto deseado y haga clic derecho para editar.

![]({{ site.baseurl }}/assets/images/image61.jpg)

> En la pantalla de edición del proyecto usted podrá modificar los siguientes datos:

-   Nombre

-   Descripción

-   Administrador

-   Estado

-   Imagen

**Nota:** Valide que el proyecto cuente con una descripción y de no ser
así, suministre una para que la tarjeta no se vea vacía al momento de
crear un caso. La descripción admite un máximo de 255 caracteres.

![]({{ site.baseurl }}/assets/images/image62.jpg)

Las dimensiones para las imágenes de los proyectos no deben ser mayores a: 200 \* 100

![]({{ site.baseurl }}/assets/images/image63.jpg)

Una vez realizada esta configuración para cada proyecto, las imágenes y las descripciones se visualizarán de esta manera:

![]({{ site.baseurl }}/assets/images/image64.jpg){width="2.365in" height="2.375in"}

### Preparación de Categorías

Ingrese a la consola de configuración web BASDK, opción **ITIL \> Categorías**.

![]({{ site.baseurl }}/assets/images/image65.jpg)

Seleccione la categoría deseada y haga clic en **Editar categoría**:

![]({{ site.baseurl }}/assets/images/image66.jpg)

Se desplegarán las opciones principales para la personalización de la categoría:

![]({{ site.baseurl }}/assets/images/image67.jpg)

**Nota:** Es necesario diligenciar el campo **Descripción** para que la
tarjeta no se vea vacía al momento de crear un caso. Este campo admite
un máximo de 4000 caracteres. Las tarjetas de categorías no incluyen
imagen.

Una vez realizada esta configuración, se visualiza la tarjeta de la categoría de esta manera:

![]({{ site.baseurl }}/assets/images/image68.jpg)

### Preparación de Servicios

Ingrese a la consola de configuración web BASDK y diríjase a **ITIL \> Categorías**. En la parte derecha, seleccione el servicio deseado y haga clic en **Editar**.

![]({{ site.baseurl }}/assets/images/image69.jpg)

Se desplegarán las opciones principales para la personalización del servicio como:

![]({{ site.baseurl }}/assets/images/image70.jpg)

**Nota**: Las dimensiones para la imagen del servicio no pueden ser
mayores a: 100 x 100

![]({{ site.baseurl }}/assets/images/image71.jpg)

**Nota:** Valide que el servicio cuente con una descripción y de no ser
así, suministre una para que la tarjeta no se vea vacía al momento de
crear un caso. El servicio admite un máximo de 4000 caracteres en la
descripción.

Una vez realizada esta configuración, la tarjeta del servicio se visualizará así:

![]({{ site.baseurl }}/assets/images/image72.jpg)

Luego de configurar cada categoría y cada proyecto, las imágenes y las descripciones se visualizarán de esta manera:

Categoría:

![]({{ site.baseurl }}/assets/images/image73.jpg)

Proyecto:

![]({{ site.baseurl }}/assets/images/image74.jpg)

Servicio:

![]({{ site.baseurl }}/assets/images/image75.jpg)

Una vez realizada esta configuración, será posible crear casos con el nuevo wizard.

### Creación de casos con el wizard:

Ingrese a la consola de usuarios web USDK V8 con un usuario que tenga un proyecto asociado, haga clic en **Registrar caso** y siga los siguientes pasos:

![]({{ site.baseurl }}/assets/images/image76.jpg)

a)  Seleccione el proyecto

> Cada tarjeta de proyecto contiene una imagen representativa, el nombre del proyecto y la descripción del mismo.

![]({{ site.baseurl }}/assets/images/image77.jpg)

b)  Seleccione el servicio

> Cada tarjeta de servicio contiene una imagen representativa, el nombre del servicio y la descripción del mismo.

![]({{ site.baseurl }}/assets/images/image78.jpg)

c)  Seleccione la categoría

Una vez elegida la categoría, se abrirá el formulario de creación de casos.

![]({{ site.baseurl }}/assets/images/image79.jpg)

d)  Digite el asunto y la descripción del caso. De ser necesario puede adjuntar archivos y agregar datos adicionales. Por último, haga clic en **Crear caso**.

![]({{ site.baseurl }}/assets/images/image80.jpg)

Se confirmará la creación del caso y se redireccionará al listado de "Mis casos".

![]({{ site.baseurl }}/assets/images/image81.jpg)

**Navegación en línea de tiempo**: El usuario podrá regresar a cualquier paso de la creación del caso pulsando el punto al cual desea retornar.

![]({{ site.baseurl }}/assets/images/image82.jpg)

**Consulta y seguimiento de casos:** Al ingresar al portal, puede consultar y hacer seguimiento a sus casos de la siguiente manera:

1.  Haga clic en "Mis casos"

![]({{ site.baseurl }}/assets/images/image83.jpg)

2.  Busque y seleccione el caso del listado que se carga en pantalla

![]({{ site.baseurl }}/assets/images/image84.jpg)

> También puede usar la barra de búsqueda usando palabras clave del nombre del servicio, el asunto o el número del caso:

![]({{ site.baseurl }}/assets/images/image85.jpg)

![]({{ site.baseurl }}/assets/images/image87.jpg)

> Puede hacer uso de los filtros de búsqueda y de los parámetros de ordenamiento disponibles:

![]({{ site.baseurl }}/assets/images/image88.jpg)

> 3\. Luego de seleccionar el caso a consultar, en el panel derecho encontrará: **Detalle del caso**

![]({{ site.baseurl }}/assets/images/image89.jpg)

Allí puede ampliar el área de la descripción y de la solución (cuando
existan)

![]({{ site.baseurl }}/assets/images/image90.jpg)

**Datos adicionales**

Donde podrá visualizar información adicional que esté contenida en los campos adicionales que define el usuario de acuerdo a sus necesidades.

![]({{ site.baseurl }}/assets/images/image91.jpg)

**Notas**

Puede visualizar las notas y añadir nuevas haciendo clic en **Añadir nota**.

![]({{ site.baseurl }}/assets/images/image92.jpg)

Se visualizará la nueva nota con fecha y hora:

![]({{ site.baseurl }}/assets/images/image93.jpg)

**Adjuntos**

Puede visualizar los archivos adjuntos existentes o adjuntar nuevos

![]({{ site.baseurl }}/assets/images/image95.jpg)

### Uso de los CI en la consola de USDK

Al ingresar a la consola, haga clic en Servicio, seleccione la pestaña CI's y active la opción "Requerir CI para la creación de caso" el usuario podrá activar una o más de las siguientes opciones:

**Asociados al servicio:** El usuario en la USDK solo podrá ver y seleccionar los CI's asociados a este servicio. En la parte inferior derecha de la imagen podrán ver el icono de lupa para asociar los CI's al servicio.

**Responsable del CI:** El usuario en la USDK solo podrá ver y seleccionar los CI's en los cuales él sea el responsable.

**Todos:** El usuario en la USDK podrá ver y seleccionar todos los CI's del proyecto

![]({{ site.baseurl }}/assets/images/image96.jpg)

Al activar esta funcionalidad en la consola USDK será visible de la siguiente manera:

![]({{ site.baseurl }}/assets/images/image97.jpg)

### Consulta de artículos de la Base de Conocimiento

La base de conocimiento de Aranda es el centro de información que contiene la documentación generada de todos los contenidos que se administren en la consola.

### Consultar artículos:

Al ingresar al portal, puede consultar los artículos de la Base de Conocimiento de la siguiente manera:

a)  Haga clic en **Artículos**

![]({{ site.baseurl }}/assets/images/image98.jpg)

b)  En el panel central encontrará los artículos clasificados por Artículos más consultados, Artículos mejor calificados y Artículos nuevos

![]({{ site.baseurl }}/assets/images/image99.jpg)

c)  En el panel izquierdo encontrará las diferentes categorías para buscar los artículos

![]({{ site.baseurl }}/assets/images/image100.jpg)

d)  También puede buscar un artículo digitando una palabra clave en la barra de búsqueda:

![]({{ site.baseurl }}/assets/images/image101.jpg)

Por último, puede calificar el artículo dándole una puntuación y agregar un comentario.

![]({{ site.baseurl }}/assets/images/image102.jpg)
