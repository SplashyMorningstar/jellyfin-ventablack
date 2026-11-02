# VantaBlack para Jellyfin

Tema negro y monocromático para Jellyfin Web, sin blur ni animaciones para mantener la interfaz ligera.

## Instalar

En Jellyfin, ve a **Panel de control → General → CSS personalizado** y pega:

```css
@import url("https://raw.githubusercontent.com/SplashyMorningstar/jellyfin-ventablack/main/ventablack.css");
```

Guarda y recarga Jellyfin. Si no aparece, prueba una recarga forzada (`Ctrl+F5`).

> Requiere que el navegador/cliente pueda acceder a GitHub. Algunas apps nativas no aplican CSS personalizado.
