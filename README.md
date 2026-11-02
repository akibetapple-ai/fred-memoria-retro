# Fred Memoria Retro — sitio oficial

Sitio estático, responsive, sin frameworks, sin fuentes externas y listo para publicarse en GitHub Pages.

## Archivos

- `index.html`: portada, instrucciones, dificultades, galería, preguntas frecuentes y soporte.
- `privacidad.html`: aviso de privacidad del sitio y las comunicaciones por correo.
- `styles.css`: diseño adaptable a computadora, tableta y móvil.
- `assets/`: imágenes originales optimizadas a WebP y favicon PNG.

**Contacto publicado:** akibet.apple@gmail.com

## Publicar gratis en GitHub Pages

1. Crea un repositorio público en GitHub, por ejemplo `fred-memoria-retro`. Se recomienda uno diferente de `fred-memoria-kids` para no reemplazar la página de Kids.
2. En la pestaña **Code** > **Add file** > **Upload files**, sube **el contenido de esta carpeta**, NO el ZIP. `index.html`, `privacidad.html`, `styles.css` y `assets/` deben aparecer directamente en la raíz del repositorio.
3. Guarda los archivos mediante **Commit changes**.
4. Ve a **Settings > Pages > Build and deployment**. Selecciona **Deploy from a branch**, rama `main`, carpeta `/ (root)` y **Save**.
5. Cuando termine la publicación, visita la dirección indicada por GitHub. Normalmente será `https://TU-USUARIO.github.io/fred-memoria-retro/`.
6. La política de privacidad estará en la misma dirección, agregando `privacidad.html`.

## Importante: alcance del aviso de privacidad

El aviso de `privacidad.html` describe el **sitio web estático** y las comunicaciones recibidas en el correo de soporte. **No se ha auditado el código de la aplicación iOS**. Antes de registrar esta URL en App Store Connect como política de la aplicación, revisa la compilación final para confirmar y documentar, según corresponda:

- Si se almacenan puntuaciones, nombres de jugador o preferencias localmente, en iCloud o en servidores.
- Si contiene analítica, publicidad, Game Center, compras, diagnósticos, crash reporting u otros SDKs.
- Qué datos recopila cada servicio, para qué se usan, su retención y si se comparten.
- Si necesita reglas específicas por edad o territorio.
- Que las declaraciones de privacidad en App Store Connect coincidan exactamente con la app.

Actualiza `privacidad.html` en función de esa revisión antes de usarlo como política definitiva de la aplicación. Esto evita afirmar algo que la app no cumple.

## Personalización

Para cambiar el correo electrónico, busca `akibet.apple@gmail.com` en `index.html` y `privacidad.html` y sustitúyelo en todas sus apariciones.

Todos los enlaces entre páginas son relativos para funcionar tanto bajo una ruta de GitHub Pages como en una página de dominio propio. No hay servicios de tracking ni scripts externos en este sitio.

## Derechos de las imágenes

El sitio utiliza las imágenes compartidas para el proyecto Fred Memoria Retro. Se conservaron su composición y diseño; únicamente se optimizaron y redimensionaron para carga web.
