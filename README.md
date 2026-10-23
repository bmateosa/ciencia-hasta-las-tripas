# Ciencia hasta las tripas

Biblioteca gratuita de divulgación científica sobre las EII.

## Actualizar contenidos

Edita `contenidos.json` desde GitHub. Cada objeto corresponde a un contenido.

- `titulo`: título visible
- `formato`: Reel, Podcast, Artículo, etc.
- `temas`: lista de etiquetas (puede haber varias)
- `descripcion`: breve texto descriptivo
- `url`: enlace al contenido (Instagram, Spotify...)
- `portada`: ruta a imagen propia opcional (p. ej. `portadas/genetica.jpg`)
- `emoji`: ilustración provisional cuando no hay portada
- `destacado`: `true` solo para el vídeo que aparece en la sección de presentación

Los enlaces de Instagram se han simplificado quitando los parámetros de seguimiento.

**Pendiente:** confirmar título y etiquetas del reel `DejOk84CTKM` y, si se desea, añadir portadas.

Para subir esta versión al repositorio, sustituye los archivos de igual nombre en la raíz y confirma los cambios.

### Series de vídeos
Los reels de «Genética e inmunología» incluyen los campos `serie`, `parte`, `total_partes` y `relacionado` en `contenidos.json`. La ficha muestra «Parte 1 de 2» o «Parte 2 de 2» y un enlace a la otra parte.
