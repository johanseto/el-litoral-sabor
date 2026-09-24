# Restaurant Template for GitHub Pages

Configurable static site template for quickly creating a restaurant page.


## Customization

1. Edit `config.json` to change the name, logo, WhatsApp number, address, and site copy.
2. Edit `menu.json` to add, remove, or update dishes. Each `image` value must point to an image inside `menues/`.
3. Add the dish images to the `menues/` directory (for example, `cazuela.jpg`, `pescado.jpg`, and `ceviche.jpg`).
4. Update `config.json` so `logo` points to the image you want to display as the main image.

The `whatsapp` value must include the country code without spaces or symbols. The page does not require a server and works directly on GitHub Pages. To test it locally, serve the directory with any HTTP server so the browser can read the JSON files.
