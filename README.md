# Plantilla para restaurantes en GitHub Pages

Sitio estático configurable para crear rápidamente una página de restaurante.

## Personalización

1. Edita `config.json` para cambiar el nombre, logo, teléfono de WhatsApp, dirección y textos.
2. Edita `menu.json` para agregar, quitar o modificar platos. Cada `image` debe apuntar a una imagen dentro de `menues/`.
3. Crea la carpeta `menues/` y agrega allí las imágenes de los platos (por ejemplo, `cazuela.jpg`, `pescado.jpg` y `ceviche.jpg`).
4. Cambia `config.json` para que `logo` apunte a la imagen que quieras mostrar como imagen principal.

El valor de `whatsapp` debe incluir el código de país, sin espacios ni símbolos. La página no requiere servidor: funciona directamente en GitHub Pages. Para probarla localmente, sirve la carpeta con cualquier servidor HTTP para que el navegador pueda leer los archivos JSON.
