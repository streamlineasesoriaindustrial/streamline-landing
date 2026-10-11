# Streamline Asesoría Industrial · Landing page

Página única en HTML, sin dependencias ni proceso de compilación.

## Archivos

- `index.html`: la página completa (estilos y calculadora incluidos).
- `assets/`: logo, ícono de pestaña y la imagen que se ve al compartir el enlace.
- `.nojekyll`: le indica a GitHub Pages que sirva los archivos tal cual.

## Datos a reemplazar antes de publicar

Abrí `index.html` y usá buscar y reemplazar (Ctrl+H en el editor de GitHub):

| Buscar | Reemplazar por |
| --- | --- |
| `5493510000000` (aparece 5 veces) | Tu WhatsApp en formato internacional, sin signos. Ej.: `5493515551234` |
| `+54 9 351 000-0000` | El mismo número, como querés que se vea en pantalla |
| `contacto@streamline.com.ar` | Tu correo real |
| `TU-USUARIO` (en `og:image`) | Tu usuario de GitHub |

Si el repositorio no se llama `streamline-landing`, cambiá también ese nombre en la línea de `og:image`.

## Publicar en GitHub Pages

1. En GitHub: **New repository**. Nombre: `streamline-landing`. Público.
2. Dentro del repositorio: **Add file → Upload files**. Arrastrá el contenido de esta carpeta (`index.html`, `.nojekyll` y la carpeta `assets`) y hacé **Commit changes**.
3. **Settings → Pages**. En *Source* elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y **Save**.
4. En uno o dos minutos la página queda en `https://TU-USUARIO.github.io/streamline-landing/`.

## Dominio propio (opcional)

1. Registrá el dominio (por ejemplo, en NIC Argentina si es `.com.ar`).
2. En **Settings → Pages → Custom domain** escribí el dominio y guardá. GitHub te indica los registros DNS que tenés que cargar en tu proveedor.
3. Cuando el dominio esté verificado, activá **Enforce HTTPS**.
4. Actualizá la línea `og:image` con la dirección nueva.

## Revisión final

- Los botones de WhatsApp abren el chat con tu número.
- El correo y el teléfono son los reales.
- La página se ve bien en el celular.
- Pegá el enlace en un chat de WhatsApp y comprobá que aparece el logo.
