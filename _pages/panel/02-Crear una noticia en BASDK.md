---
title: Crear una noticia en BASDK
chapter: "panel"
---

En la sección **Noticias** del área de trabajo, haga clic en **Adicionar Noticia**, se habilitará la ventana **Nueva Noticia**, y allí podrá completar la información básica de la misma para el proyecto escogido.

**Nota:** Por defecto, al abrir el formulario de nueva noticia, aparecerá activa la opción de publicar inmediatamente.

![]({{ site.baseurl }}/assets/images/image34.jpg)

**Título de la noticia**

En este campo se define el título o nombre de la noticia, el cual podrá tener un máximo de 140 caracteres.

**Descripción de la noticia**

En este campo, se describe detalladamente el contenido de la noticia, dicho contenido puede editarse utilizando el texto enriquecido. La descripción de la noticia no debe superar los 4000 caracteres.

![]({{ site.baseurl }}/assets/images/image35.jpg)

**Imagen asociada**

Para insertar una imagen relacionada a la noticia, seleccione el icono de imagen en la barra de herramientas. Se abrirá la ventana del explorador de archivos para seleccionar la imagen.

**Nota:** Cada imagen no podrá exceder el tamaño de 200KB; las
dimensiones que debe tener son: 250 Ancho \* 110 de Alto. Los formatos
permitidos para la imagen son: jpg, gif, bmp, png, jpeg.

a)  Seleccione la imagen deseada

b)  Presione el botón Subir, para cargar la imagen en el listado; todas las imágenes subidas, serán cargadas en un catálogo de imágenes almacenadas en el **AFS (Aranda FILE SERVER)**, las cuales podrán ser utilizadas por el usuario cuando lo requiera; las imágenes están organizadas por nombre, tamaño y fecha en que se actualizó la imagen.

c)  Seleccione una imagen del listado y presione el botón Aceptar, inmediatamente la imagen será incluida en la descripción de la noticia; después de haber insertado la imagen en la noticia, el usuario podrá cambiarla de posición, pero no podrá modificar su tamaño o duplicarla dentro del texto.

**Nota:** Si el usuario requiere borrar una imagen de la lista, podrá eliminar imágenes, siempre y cuando estas no se encuentren asociadas a una o más noticias.

![]({{ site.baseurl }}/assets/images/image36.jpg)

**Publicación Inmediata:** Al habilitar esta opción, la noticia creada será publicada de manera automática en la consola de usuario de USDK, sin embargo, no se activarán las opciones de programación de fecha y hora de publicación.

![]({{ site.baseurl }}/assets/images/image37.jpg)

**Programar publicación**

También, podrá configurar una fecha y una hora para publicar la noticia en la consola de usuario de USDK V8; esta fecha deberá ser superior a la fecha actual, en caso de ingresar una fecha de publicación no válida, no podrá guardar la noticia

![]({{ site.baseurl }}/assets/images/image38.jpg)

**Definir el orden de aparición de la noticia:**

En la parte inferior de la ventana Editar \> Noticia, se encuentra el campo orden, allí, se asigna un número que representa un orden secuencial de aparición del registro para su visualización posterior en la consola de usuario de USDK.

**Nota:** El listado de números disponibles en el campo orden de aparición varía dependiendo de la cantidad de noticias o registros creados previamente; si no existen noticias registradas, el orden de aparición no se puede seleccionar.

**Tiempo de novedad de la noticia:**

En este campo se define el tiempo, en días, durante el cual estará publicada la noticia en la consola de usuario USDK.

**Visualización de la noticia en inicio de sesión:**

Para activar la visualización de noticas en el inicio de sesión, ingrese a la consola **Blogik \> Consola de Usuario \> Opciones de Acceso** y marque "Visualizar módulo de noticias en el inicio de sesión".

![]({{ site.baseurl }}/assets/images/image39.jpg)

Para publicar las noticias ingrese a la opción **Configuración**, seleccione **Noticias**; posterior a la creación de la noticia, habilite la visualización de la noticia en inicio de sesión en el cuadro como lo muestra la imagen.

![]({{ site.baseurl }}/assets/images/image40.jpg)

Al marcar este cuadro se habilita la visualización de la noticia en la pantalla de inicio de sesión y se visualizará de esta forma:

![]({{ site.baseurl }}/assets/images/image41.jpg)

**Noticia prioritaria**:

En este campo se define la prioridad de la noticia marcando el recuadro, la noticia quedara marcada con una bandera que indica su prioridad.

![]({{ site.baseurl }}/assets/images/image42.jpg)

**URL de redirección**

Cuando la noticia está ubicada en una URL externa, es necesario copiar la URL y guardarla, de esta forma cuando el usuario haga clic sobre la misma, será direccionado a la URL.

![]({{ site.baseurl }}/assets/images/image43.jpg)

Y será visible de la siguiente manera:

![]({{ site.baseurl }}/assets/images/image44.jpg)

En el link externo de la noticia almacenada:

![]({{ site.baseurl }}/assets/images/image45.jpg)

**Guardar la noticia:**

Al terminar de modificar la noticia, presione el botón Guardar en la ventana Editar \> Noticia; si la opción publicar inmediatamente se encuentra habilitada, la noticia quedará publicada en la consola de usuario de USDK.

**Guardar borrador de noticia:**

Si presiona el botón **Guardar Borrador**, la noticia no será publicada en USDK (aunque tenga habilitada la opción respectiva), sino que quedará en estado borrador hasta que se guarde en forma definitiva.

![]({{ site.baseurl }}/assets/images/image46.jpg)

**Nota:** Después de guardar una noticia, ésta aparecerá inmediatamente
en la lista de noticias, donde se visualizará el orden, la fecha de
publicación, el estado, el título de la noticia y la frase inicial de la
descripción; si la noticia se encuentra o no publicada, determinará la
aparición de datos en la columna orden y fecha de publicación.

**Listado de noticias**

En la parte central del área de trabajo del módulo de Noticias, podrá acceder al listado de noticias disponibles, donde podrá editarlas, establecer el orden de aparición o eliminar los registros generados.

![]({{ site.baseurl }}/assets/images/image47.jpg)

**Edición de una noticia en configuración ASDK**

En la sección Listado de Noticias del área de trabajo, seleccione una noticia del listado creado y haga clic sobre el link del título de la noticia para modificar la información registrada.

![]({{ site.baseurl }}/assets/images/image48.jpg)

-   Se habilitará la ventana Editar/Noticia donde podrá modificar características, como el título, descripción, parámetros de publicación y orden de aparición.

![]({{ site.baseurl }}/assets/images/image49.jpg)

**Eliminación de una noticia en configuración ASDK**

-   En la parte central del área de trabajo de la sección de Noticias acceda al listado de noticias disponibles y en el campo Orden, haga clic en el cuadro correspondiente a la noticia o noticias que desea borrar o guardar como borrador.

-   Si presiona el botón **Borrar**, se habilitará un mensaje de advertencia para confirmar la eliminación; si aprueba la acción, los registros de las noticias serán eliminados.

-   Si presiona el botón **Guardar Borrador**, la noticia no será publicada en USDK y el registro queda en estado borrador hasta que se guarde en forma definitiva.

![]({{ site.baseurl }}/assets/images/image50.jpg)

**Nota:** Cuando el usuario elimina una noticia, si esta se encuentra publicada, dejará de aparecer en la consola de usuario de USDK.

**Buscar una noticia en BASDK**

Las noticias creadas pueden ser consultadas en la consola de Configuración ASDK a través de una búsqueda de noticias, por los campos título y descripción; para realizar la búsqueda de una noticia, siga los siguientes pasos:

-   En el área de trabajo de la sección Noticias identifique el campo de búsqueda (Como se ve en la imagen al final del procedimiento).

-   La consulta puede realizarla por título, nombre de la noticia o descripción del registro.

-   Defina el criterio de consulta en el campo de búsqueda y presione el botón Buscar para generar la consulta de las noticias.

![]({{ site.baseurl }}/assets/images/image51.jpg)

-   En la sección Listado de Noticias, se muestran los registros de noticias encontrados para el criterio o variable definido; seleccione el título de la noticia para acceder a la información del registro o editar la noticia consultada.

Para visualizar las noticias, que ahora están disponibles en la pantalla de inicio, como se visualiza en la siguiente imagen:

![]({{ site.baseurl }}/assets/images/image52.jpg)

Sólo basta con hacer clic sobre el título de la misma.

![]({{ site.baseurl }}/assets/images/image53.jpg)

Y se cargará la noticia en pantalla:

![]({{ site.baseurl }}/assets/images/image54.jpg)

O en caso de ser un link externo:

![]({{ site.baseurl }}/assets/images/image55.jpg)
