# VantaBlack para Jellyfin

Tema negro y monocromático para Jellyfin Web, sin blur ni animaciones para mantener la interfaz ligera.

## Instalar

En Jellyfin, ve a **Panel de control → General → CSS personalizado** y pega esta línea como primera línea:

```css
@import url("https://cdn.jsdelivr.net/gh/SplashyMorningstar/jellyfin-ventablack@a110cd8d80ab8bf0b455b66314fee521a8a66857/ventablack.css");
```

Guarda y recarga Jellyfin. Si no aparece, prueba una recarga forzada (`Ctrl+F5`). El enlace queda fijado a una versión para evitar que el CDN mezcle el CSS nuevo con una copia antigua; al publicar otra versión hay que actualizar este enlace.

Si `@import` no carga en tu cliente, puede que la app no permita importar CSS remoto o no tenga acceso a Internet/CDN. En ese caso, copia el contenido de [`ventablack.css`](ventablack.css) directamente en el campo CSS personalizado. Algunas apps nativas de TV ignoran el CSS personalizado por completo.
