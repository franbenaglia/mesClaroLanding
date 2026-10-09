# MesClaro — sitio web

Página de presentación y política de privacidad de [MesClaro](https://github.com/franbenaglia/mesclaro), un planificador de gastos mensuales para Android, privado y sin conexión.

Publicado con GitHub Pages en <https://franbenaglia.github.io/mesClaroLanding/>.

| Página | Español | English |
| --- | --- | --- |
| Presentación | `index.html` | `en/index.html` |
| Política de privacidad | `privacy.html` | `en/privacy.html` |

La dirección de la política de privacidad para la ficha de Google Play es <https://franbenaglia.github.io/mesClaroLanding/privacy.html>.

## Estructura

- `assets/style.css`: estilos de todas las páginas, con tema claro y oscuro.
- `assets/`: iconos, gráfico de funciones comprimido y capturas de pantalla.
- `mesclaro-app-icon-512.png` y `mesclaro-feature-graphic-1024x500.png`: originales para la ficha de Google Play.
- `.nojekyll`: indica a GitHub Pages que sirva los archivos tal cual.

Es un sitio estático: no usa scripts, fuentes externas, cookies ni analíticas.

## Publicar

En GitHub: Settings → Pages → Source «Deploy from a branch», rama `main`, carpeta `/ (root)`.

## Al publicar la app en Google Play

En `index.html` y `en/index.html`, reemplazar el botón «Próximamente en Google Play» por un enlace a `https://play.google.com/store/apps/details?id=com.fabapps.mesclaro`.

## Si cambia la política de privacidad

Actualizar las dos versiones (`privacy.html` y `en/privacy.html`) y la fecha de «Última actualización». El texto debe coincidir con lo que la app hace de verdad y con la pantalla de privacidad dentro de la app.

## Contacto

feedback@fab-apps.com
