# Nómada Tech

Práctico de Flexbox: tienda de tecnología con diseño adaptable y cuatro productos.

## Cómo se usa Flexbox

Flexbox permite distribuir y alinear los elementos de una página de forma flexible. En este proyecto se usa así:

- **Aviso superior (`.announcement`)**: `display: flex`, `align-items: center` y `justify-content: center` mantienen el mensaje centrado horizontal y verticalmente.
- **Encabezado (`.site-header`)**: `display: flex`, `align-items: center` y `justify-content: space-between` alinean el logo, el menú y el botón en una fila con espacio entre ellos.
- **Navegación (`.navigation`)**: `display: flex` y `gap` muestran los enlaces uno al lado del otro con separación uniforme.
- **Portada (`.hero`)**: Flexbox coloca el texto y la imagen lado a lado; `align-items: center` los centra verticalmente y `gap` establece el espacio entre ambos.
- **Galería (`.product-grid`)**: `display: flex` y `flex-wrap: wrap` ordenan los productos en filas y permiten que pasen a la siguiente línea cuando no hay espacio. Cada tarjeta usa `flex` para compartir el ancho disponible. En pantallas pequeñas cada fila muestra dos productos.
- **Imagen del producto (`.product-card__image`)**: Flexbox centra el contenido de la imagen vertical y horizontalmente.
- **Presentación (`.about`)**: `flex-direction: column` apila sus textos; `align-items: center` los centra horizontalmente.
- **Pie de página (`.site-footer`)**: Flexbox organiza la marca, la descripción y el contacto en una fila alineada. En pantallas estrechas, las reglas adaptables permiten que los elementos se acomoden en varias líneas.

Las reglas dentro de `@media` ajustan espacios, tamaños y distribución para celulares y tabletas.

## Archivos

- `index.html`: estructura, contenido y comentarios que explican el uso de Flexbox en cada sección.
- `styles.css`: estilos, distribución con Flexbox y adaptación a pantallas pequeñas.
- `LEEME.txt`: resumen e indicaciones del práctico.

## Cómo verlo

Abrí `index.html` en un navegador. La fuente DM Sans y las imágenes externas requieren conexión a internet.

