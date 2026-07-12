# OFFIXAUDIO

Sitio web de OFFIXAUDIO — Mantención, Restauración y Reparación de equipos de Audio HiFi Vintage (Santiago, Chile).

Publicado con GitHub Pages: https://kastchile2025-star.github.io/offixaudio/

## Cómo agregar o cambiar un logo de marca

1. Sube el archivo del logo (PNG con fondo transparente, idealmente ~500 px de ancho) a la carpeta `img/marcas/` (marcas de equipos) o `img/componentes/` (marcas de componentes electrónicos).
2. Abre `index.html` y busca la sección `Marcas que trabajamos` (marquesina) o la grilla de la pestaña Marcas.
3. Duplica una línea existente y cambia el nombre del archivo, por ejemplo:
   `<span class="mq-item"><img src="img/marcas/nueva-marca.png" alt="Nueva Marca" /></span>`
   (en la marquesina hay dos listas idénticas: agrégalo en ambas para que el bucle sea continuo).
4. Guarda, haz commit y push. GitHub Pages actualiza el sitio en ~1 minuto.

Los logos se muestran en escala de grises y recuperan su color al pasar el mouse.

## Créditos

Ver [CREDITS.md](CREDITS.md).
