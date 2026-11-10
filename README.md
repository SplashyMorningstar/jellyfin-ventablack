# VantaBlack for Jellyfin

An AMOLED black and monochrome theme for Jellyfin Web, with blur and animations disabled to keep the interface lightweight.

## Installation

In Jellyfin, go to **Dashboard → General → Custom CSS** and paste this line at the top:

```css
@import url("https://cdn.jsdelivr.net/gh/SplashyMorningstar/jellyfin-ventablack@1.0.8/ventablack.css");
```

Save and reload Jellyfin. If the theme does not appear, try a hard refresh (`Ctrl+F5`). The link points to a fixed version so the CDN does not serve a stale copy of the CSS.

If `@import` does not work in your client, it may not support remote CSS imports or may not have access to the internet/CDN. In that case, copy the contents of [`ventablack.css`](ventablack.css) directly into the Custom CSS field. Some native TV apps ignore custom CSS entirely.
