# Sección de Banner Principal en Shopify

Esta sección de Shopify (`.liquid`) te permite crear un banner principal versátil y responsivo para tu tienda. La sección está diseñada para ser altamente personalizable, permitiendo el uso de la misma imagen en todos los dispositivos y ajustando su visualización con configuraciones específicas para móviles y escritorio.

---

### Características Principales

* **Responsividad Adaptable:** Define anchos máximos y proporciones de aspecto (`aspect_ratio`) distintos para **escritorio** y **móvil**. Esto te da un control preciso sobre cómo se ve el banner en cada dispositivo.
* **Imagen Única:** Utiliza la misma imagen para ambas vistas (escritorio y móvil). El código se encarga de optimizar y ajustar la visualización de la imagen, eliminando la necesidad de subir dos imágenes diferentes.
* **Totalmente Clicable:** Toda la imagen del banner actúa como un enlace, lo que facilita la navegación para los usuarios.
* **Contenido Opcional:** Puedes agregar un título y un botón superpuestos sobre el banner, aunque el enlace principal siempre será el del banner completo.
* **Fácil de Personalizar:** Todas las configuraciones se gestionan directamente desde el editor de temas de Shopify, lo que no requiere conocimientos de código para su uso.

---

### Configuración de la Sección

El siguiente es un resumen de las opciones de configuración disponibles en el editor de temas:

#### Configuración de Banner
* **Imagen del Banner (`image_picker`)**: Sube la imagen principal para la sección.
* **Color de Fondo (`color`)**: El color que se muestra detrás del banner.

#### Ancho y Proporción (Escritorio)
* **Ancho Máximo (Escritorio) (`range`)**: Controla el ancho máximo del contenedor del banner en pantallas grandes.
* **Proporción de Aspecto (Escritorio) (`range`)**: Define la relación ancho/alto de la imagen del banner en escritorios (por ejemplo, `2.5:1`).

#### Ancho y Proporción (Móvil)
* **Ancho Máximo (Móvil) (`range`)**: Controla el ancho máximo del contenedor del banner en pantallas pequeñas.
* **Proporción de Aspecto (Móvil) (`range`)**: Define la relación ancho/alto de la imagen del banner en dispositivos móviles (por ejemplo, `1.5:1`).

#### Contenido (Opcional)
* **Título del Banner (`text`)**: Un título para superponer sobre la imagen.
* **Texto del Botón (`text`)**: El texto que se muestra en el botón.
* **Enlace del Botón (`url`)**: La URL a la que el banner completo y el botón dirigen.

---

### Instalación

1.  En tu panel de administración de Shopify, ve a **Online Store > Themes**.
2.  Busca tu tema actual y haz clic en **Acciones > Edit code**.
3.  En la carpeta **Sections**, haz clic en **Add a new section**.
4.  Crea un nuevo archivo con el nombre `seccion-banners-principales.liquid`.
5.  Copia y pega el código completo de esta sección en el archivo y guarda.
6.  Ahora puedes agregar la sección llamada **"Banner Principal"** desde el editor de temas de Shopify.