Descripción del Ejercicio: Galería con Menú Responsive
1. Estructura General
Crear una página web que tenga dos secciones principales:
Un header con un menú responsive.
Un main con una galería de imágenes.
2. Menú Responsive
El menú debe:
Ser visible horizontalmente en pantallas grandes.
Convertirse en un menú oculto que se despliega en pantallas pequeñas (menos de 600px de ancho).
Usar un botón para abrir y cerrar el menú en pantallas pequeñas.
Los enlaces del menú deben cambiar de estilo al pasar el ratón por encima (:hover).
Mostrar el icono ☰ para abrir el menú y ✖ para cerrarlo.
3. Galería con Grid
La galería debe:
Usar Grid Layout para colocar las imágenes en una cuadrícula.
Mostrar todas las imágenes en una fila horizontal en pantallas grandes.
Cambiar automáticamente a varias filas en pantallas pequeñas (usando media queries).
Aplicar un efecto visual a las imágenes cuando el ratón pase sobre ellas (:hover).
Asegurarse de que las imágenes sean adaptables al tamaño del contenedor (responsive).
4. Propiedades y Conceptos a Utilizar
Flexbox para el diseño del header y el menú.
Grid Layout para la galería de imágenes.
Media Queries para ajustar el diseño en pantallas pequeñas.
Pseudo-clases como :hover para efectos visuales.
Propiedades específicas como:
grid-template-columns con auto-fit y minmax para una cuadrícula adaptable.
transition para animaciones suaves.
box-shadow y transform para mejorar la apariencia de las imágenes.
position y visibility para manejar la visibilidad del menú.
Pistas para Organizar el Código
HTML:

Un <header> con un botón de menú (☰) y un <nav> con enlaces.
Un <main> con un contenedor (<div>) que agrupe varias imágenes.
CSS:

Define estilos básicos para el cuerpo y los encabezados (body, h1).
Diseña el menú y su interacción en pantallas grandes y pequeñas.
Crea una cuadrícula para la galería y añade efectos visuales para las imágenes.
JavaScript:

Haz que el menú se abra y cierre en pantallas pequeñas añadiendo y eliminando clases.
Recomendaciones para Resolverlo
Comienza por el HTML:

Crea la estructura básica (header, main, galería).
Añade imágenes y enlaces al menú.
Aplica los Estilos:

Diseña primero para pantallas grandes.
Luego adapta con media queries.
Añade Interactividad:

Usa JavaScript para mostrar y ocultar el menú en pantallas pequeñas.
Prueba y Ajusta:

Abre la página en tu navegador y prueba cómo se ve en diferentes tamaños de pantalla.
