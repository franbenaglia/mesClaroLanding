# MesClaro — sitio web

Página de presentación y política de privacidad de [MesClaro](https://github.com/franbenaglia/mesclaro), un planificador de gastos mensuales para Android, privado y sin conexión.

Publicado con GitHub Pages en <https://mesclaro.fab-apps.com/> (dominio propio, archivo `CNAME`).

| Página | Español | English |
| --- | --- | --- |
| Presentación | `index.html` | `en/index.html` |
| Política de privacidad | `privacy.html` | `en/privacy.html` |

La dirección de la política de privacidad es <https://mesclaro.fab-apps.com/privacy.html>.

## Estructura

- `assets/style.css`: estilos de todas las páginas, con tema claro y oscuro.
- `assets/`: iconos, gráfico de funciones comprimido y capturas de pantalla.
- `mesclaro-app-icon-512.png` y `mesclaro-feature-graphic-1024x500.png`: originales para la ficha de Google Play.
- `.nojekyll`: indica a GitHub Pages que sirva los archivos tal cual.

Es un sitio estático: no usa scripts, fuentes externas, cookies ni analíticas.

## Publicar

En GitHub: Settings → Pages → Source «Deploy from a branch», rama `main`, carpeta `/ (root)`.

## Descarga de la app

El código de la app está en un repositorio privado, así que el APK se publica en los **Releases de este repositorio**, que es público.

- El archivo adjunto se llama siempre `MesClaro.apk`. Por eso el botón de descarga usa la dirección fija `https://github.com/franbenaglia/mesClaroLanding/releases/latest/download/MesClaro.apk`, que apunta sola a la última versión.
- Cada release lleva la etiqueta `v<versión>` (por ejemplo `v0.1.0`) y adjunta también `MesClaro.apk.sha256`.
- Los pasos para publicar una versión nueva están en `CLAUDE.md` del repositorio de la app.

Si algún día la app se publica en Google Play, agregar un segundo botón con `https://play.google.com/store/apps/details?id=com.fabapps.mesclaro`.

## Si cambia la política de privacidad

Actualizar las dos versiones (`privacy.html` y `en/privacy.html`) y la fecha de «Última actualización». El texto debe coincidir con lo que la app hace de verdad y con la pantalla de privacidad dentro de la app.

## Contacto

feedback@fab-apps.com
