# gymbroweb

Sitio público de GymBro, publicado con GitHub Pages en https://leodiazdev.github.io/gymbroweb/

- `index.html`: presentación de la app.
- `privacidad.html`: política de privacidad. **La app la abre desde Ajustes → Acerca de y la ficha de Google Play la enlaza**, así que no cambiar su nombre ni moverla. Si cambia lo que hace la app con los datos (permisos, servicios externos), actualizarla junto con la fecha de vigencia.
- `styles.css`: identidad "Volt", mismos colores que `theme/colors.ts` de la app.
- `fonts/`: Space Grotesk e Inter incluidas en el sitio (licencia SIL OFL en `fonts/OFL-*.txt`) para no cargar nada de servidores de terceros.
- `img/`: ícono, copiado de `assets/source/icon.svg` de la app.

Sitio estático sin build: se edita el HTML y se sube a `main`.

Para publicarlo: Settings → Pages → Build and deployment → Source "Deploy from a branch", branch `main`, carpeta `/ (root)`.
