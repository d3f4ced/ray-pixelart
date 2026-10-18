# Ray PixelArt · Overworld Gallery

Portfolio responsive inspirado en la estética de Minecraft, creado con HTML, CSS y JavaScript puro.

## Abrir
Abre `index.html` en tu navegador. No necesitas instalar dependencias ni ejecutar un servidor.

## Añadir tus pixel arts
1. Copia el PNG o SVG a `assets/`.
2. Abre `script.js` y añade una entrada al array `artworks` con `id`, `name`, `file`, `category`, `resolution`, `color`, `description` y `rarity`.
3. Las categorías disponibles son `personajes`, `criaturas` y `objetos`.
4. Para cambiar el dibujo destacado del inicio, edita `assets/dracula.png` en el `<img class="showcase-art">` de `index.html`.

Se incluyen todos los PNG y SVG proporcionados, además del archivo fuente `sword_minecraft,svg.aseprite` (no se muestra como imagen porque es un archivo editable de Aseprite). El cursor usa `diamond-sword.svg`.

Las imágenes se muestran con `image-rendering: pixelated` para conservar los píxeles. La fuente de Google Fonts requiere internet, pero el sitio funciona sin ella.

Diseño fan-made inspirado en Minecraft, sin afiliación con Mojang ni Microsoft.
