MMLAB — Sitio editable para GitHub / Visual Studio Code

ESTA VERSION INCLUYE:
- Logo ampliado en el encabezado.
- Logo MMLAB en el bloque principal del pie de página en lugar del texto MMLAB.
- Carrusel de 4 imágenes en el hero.
- Imagen del Misti en Cobertura.
- Sección Proceso con 5 círculos de 120 px, iconos lineales y popups interactivos.
- Solo un popup del proceso puede estar abierto a la vez.
- El popup se cierra con X o haciendo clic fuera.
- En móvil, los pasos se organizan en columna.
- Servicios con iconos lineales SVG.
- Buscador de análisis con búsqueda, filtros por alfabeto, barra deslizante y áreas editables.

ESTRUCTURA:
index.html       -> estructura y textos de la página
estilos.css      -> diseño visual y responsive
script.js        -> interacción, carrusel, filtros y popups
config.json      -> datos generales, WhatsApp, email, estadísticas y áreas
examenes.json    -> catálogo de exámenes
img/             -> logo, Misti, carrusel y lupa

IMPORTANTE:
Abre el proyecto con Live Server en Visual Studio Code para que fetch() pueda cargar config.json y examenes.json.

PARA GITHUB:
Sube el CONTENIDO de esta carpeta al nivel principal del repositorio, de modo que index.html quede en la raíz.
No dejes index.html dentro de otra carpeta como MM_LAB_EDITABLE_FINAL/MM_LAB_EDITABLE_FINAL.
