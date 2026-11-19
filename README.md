# Web personal de Aylin Romero

Web personal de una sola página, creada con HTML, CSS y JavaScript. No necesita instalar nada ni utilizar frameworks.

## Archivos
- `index.html`: contenido y estructura de la web.
- `styles.css`: colores, tipografías y diseño adaptable.
- `script.js`: menú desplegable para móvil.

## Antes de publicarla
1. Abre `index.html` y revisa los textos para asegurarte de que te representan.
2. En el apartado de contacto, sustituye `TU_CORREO@EJEMPLO.COM` por tu correo real.
3. Si quieres añadir una fotografía tuya, puedes sustituir el bloque `.portrait-graphic` de `index.html` por una imagen, por ejemplo:
   `<img src="images/mi-foto.jpg" alt="Foto de Aylin">`
   y guardar la imagen en una carpeta `images`.
4. Revisa que quieres mostrar públicamente todos los datos personales incluidos.

## Publicar gratis con GitHub Pages
1. Entra en https://github.com e inicia sesión.
2. Crea un repositorio nuevo. Por ejemplo: `sobre-mi`.
3. Puedes dejarlo como **Public** y marcar la opción para añadir un README si quieres.
4. Pulsa **Add file → Upload files**.
5. Sube `index.html`, `styles.css` y `script.js` (no subas solamente el ZIP).
6. Pulsa **Commit changes**.
7. En el repositorio, entra en **Settings → Pages**.
8. En **Build and deployment**, elige **Deploy from a branch**.
9. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
10. Espera un momento. GitHub te mostrará la dirección pública de tu web en esa misma sección.

La URL normalmente tendrá este formato:
`https://TU-USUARIO.github.io/sobre-mi/`

## Personalización
Puedes cambiar los colores al principio de `styles.css`, dentro de `:root`. Las tipografías se cargan desde Google Fonts, por lo que para verlas se necesita conexión a internet. El resto de la web funciona como archivos estáticos.
