# Ciencia hasta las tripas

Biblioteca gratuita de divulgación sobre EII, diseñada para móvil.

## Actualizar contenidos

Edita únicamente `contenidos.json`. Cada publicación tiene `titulo`, `formato`, `temas` (carpetas en las que aparece), `palabras_clave` (para búsquedas), `descripcion`, `url`, `portada` y `emoji`. `destacado: true` coloca el vídeo de presentación arriba. Las categorías se generan automáticamente a partir de `temas`: no hace falta editar JavaScript.

Para agregar una portada, sube una imagen al repositorio (por ejemplo `portadas/genetica.jpg`) y escribe esa ruta en `portada`. Las URLs de Instagram abren el reel original.

## Diseño

`index.html` contiene la cabecera y la estructura; `styles.css` contiene los colores y diseño; `script.js` gestiona carpetas, filtros y buscador.

## Publicación

Sube los cinco archivos a la raíz del repositorio y confirma los cambios. GitHub Pages publicará la nueva versión desde `main` / raíz.
