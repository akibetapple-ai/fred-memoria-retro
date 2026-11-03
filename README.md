# Fred Memoria Retro — sitio oficial

Sitio web estático, adaptable a iPhone y computadora y listo para publicar en GitHub Pages. Conserva las imágenes originales y presenta por separado los **dos avisos de privacidad proporcionados**.

## Estructura de archivos

- `index.html`: sitio principal, dificultades, galería, preguntas, soporte y sección con enlaces a ambos avisos.
- `privacidad.html`: **aviso de privacidad de la aplicación iOS** para Fred Memoria Retro.
- `privacidad-sitio.html`: **aviso de privacidad del sitio web** y comunicaciones de soporte.
- `styles.css`: estilos de la página principal.
- `assets/`: imágenes originales optimizadas y favicon.
- `.nojekyll`: configuración compatible con GitHub Pages.

**Contacto:** akibet.apple@gmail.com

## URLs de publicación

- Sitio: https://akibetapple-ai.github.io/fred-memoria-retro/
- Aviso aplicación iOS: https://akibetapple-ai.github.io/fred-memoria-retro/privacidad.html
- Aviso del sitio web: https://akibetapple-ai.github.io/fred-memoria-retro/privacidad-sitio.html

En App Store Connect, el campo **Privacy Policy URL** de la aplicación debe apuntar a la página `privacidad.html` (aviso de la aplicación), no a `privacidad-sitio.html`.

## Actualizar el repositorio GitHub existente

1. Descomprime el ZIP en tu computadora.
2. Ingresa a tu repositorio público `akibetapple-ai/fred-memoria-retro`.
3. Sube **el contenido extraído** de la carpeta, no el ZIP. `index.html`, `privacidad.html`, `privacidad-sitio.html` y `styles.css` deben quedar al mismo nivel, en la raíz; `assets/` debe mantenerse como carpeta.
4. Confirma los cambios con **Commit changes**.
5. GitHub Pages publicará la actualización desde `main` → `/ (root)`, si ya lo configuraste. Si tu navegador muestra la versión anterior, realiza una recarga forzada (Ctrl + F5).

**Importante:** El texto de ambos avisos se conservó del ZIP que proporcionaste, salvo por añadir un favicon al documento. Debes verificar que las declaraciones técnicas sobre la aplicación correspondan a la versión distribuida en App Store.
