# Third-party notices

This patch bundles or depends on several open-source projects. The MIT
License in `LICENSE` covers the original code and translations in this
repository; the components listed below retain their own licenses.

## Bundled runtime dependencies

### BepInEx 5 (Mono / Unity)
- License: LGPL-2.1-only
- Upstream: https://github.com/BepInEx/BepInEx
- Files: `BepInEx/core/*.dll`, `winhttp.dll`, `doorstop_config.ini`,
  `.doorstop_version`

### XUnity.AutoTranslator and XUnity.ResourceRedirector
- License: MIT
- Upstream: https://github.com/bbepis/XUnity.AutoTranslator
- Files: `BepInEx/plugins/XUnity.AutoTranslator/*`,
  `BepInEx/plugins/XUnity.ResourceRedirector/*`

### Harmony / MonoMod (bundled with BepInEx)
- License: MIT
- Upstream: https://github.com/pardeike/Harmony

## Project plugin

`BepInEx/plugins/GuLongFonts` (font replacement, text fitting and loading
screen swap) is original code covered by `LICENSE`.

## Fonts

All three fonts are from Google Fonts and distributed under the SIL
Open Font License 1.1. Full license text:
https://scripts.sil.org/OFL

- Aleo, by Alessio Laiso: https://fonts.google.com/specimen/Aleo
- Oregano, by John Vargas Beltran: https://fonts.google.com/specimen/Oregano
- Ma Shan Zheng, by the Ma Shan Zheng Project Authors: https://fonts.google.com/specimen/Ma+Shan+Zheng

They are packed inside `BepInEx/plugins/GuLongFonts/gulongfonts.bundle`.

## Development-only tooling (used to make the patch, not bundled)

- UnityPy -- MIT -- https://github.com/K0lb3/UnityPy
- FFmpeg -- LGPL/GPL (build dependent) -- https://ffmpeg.org

## Game

*Gu Long Fengyun Lu* (古龙风云录) is © its developer (Heluo Studio, 河洛互動)
and publisher (心火游戏) and is NOT covered by any license in this repository.
No game code, assets or fonts are distributed here. The English text tables,
loading-screen images and subtitled videos in this patch are derived works
made for use with a legitimate copy of the game; you must own the game to
use this patch.

    https://store.steampowered.com/app/2340650/
