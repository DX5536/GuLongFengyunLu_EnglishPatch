# Gu Long Fengyun Lu (古龙风云录) - English Patch

    !! MACHINE-TRANSLATED FAN PATCH !!
    Text is machine translation with manual polish on high-visibility UI and dialogue.
    Quality is "playable"; some lines will read awkwardly or literally.

    !! PLEASE SUPPORT THE ORIGINAL GAME !!
    Gu Long Fengyun Lu (古龙风云录), developed by Heluo Studio (河洛互動),
    published by 心火游戏 (Steam: https://store.steampowered.com/app/2340650/)
    This patch contains no game files. You need your own copy of the game.

## What this patch changes

- All menus, UI, names, skills, items, quests and dialogue translated to English.
- English fonts (Aleo, Oregano, Ma Shan Zheng) and automatic text fitting.
- 58 loading-screen portraits with English text.
- 19 story and ending videos with English subtitles (if included in the repository).

## Install (about 2 minutes)

1. Buy and install the game on Steam, then run it once and close it.
2. Open the game folder: Steam > right-click the game > Manage > Browse local files
   (the folder that contains `GuLong.exe`).
3. Download this repository as a zip: on the GitHub page click the green **Code** button >
   **Download ZIP**. (Do not use the "Releases" page; everything is in the repository.)
4. Extract the zip anywhere. It creates a folder named `GuLongFengyunLu_EnglishPatch-main`.
5. Open that folder and copy everything inside it **into the game folder**, next to `GuLong.exe`:
   - `BepInEx/`
   - `winhttp.dll`
   - `doorstop_config.ini`
   - `.doorstop_version` (a hidden file; enable "Show hidden files" in Explorer if you do not see it)
   - `GuLong_Data/` (only if it is in the repository: the English videos)

   Choose "Replace" if asked. `README`, `LICENSE` and `NOTICE` are not needed in the game folder.
   After copying, `BepInEx` and `winhttp.dll` must sit beside `GuLong.exe`.
6. Start the game from Steam. The first launch takes a little longer.

No Python and no extra tools are needed.

## Uninstall / revert to Chinese

- Delete `BepInEx`, `winhttp.dll`, `doorstop_config.ini` and `.doorstop_version` from the game folder.
- If you installed the videos: Steam > Properties > Installed Files > Verify integrity of game files.

## Troubleshooting

- **Game shows Chinese:** the files were extracted into the wrong folder. `winhttp.dll` must sit next to `GuLong.exe`.
- **Antivirus removes `winhttp.dll`:** it is the BepInEx loader. Add an exception or restore it.
- **A text looks clipped or overlaps:** please open an issue with a screenshot (and the screen name).
- **Crashes after a game update:** the patch targets the Steam build at the time of release. Wait for a patch update.

## Font credits

Three open-source fonts from Google Fonts, all under the SIL Open Font License 1.1, are used by the patch:

- Aleo, by Alessio Laiso, for body text
    https://fonts.google.com/specimen/Aleo
- Oregano, by John Vargas Beltran, for display / menu titles
    https://fonts.google.com/specimen/Oregano
- Ma Shan Zheng, by the Ma Shan Zheng Project Authors, for battle effect text (banners, damage pop-ups)
    https://fonts.google.com/specimen/Ma+Shan+Zheng

License text: https://scripts.sil.org/OFL

## Tools used

- BepInEx (https://github.com/BepInEx/BepInEx), the plugin loader.
- XUnity.AutoTranslator and ResourceRedirector (https://github.com/bbepis/XUnity.AutoTranslator), which swap in the English text tables.
- Harmony (https://github.com/pardeike/Harmony) for runtime patching.
- UnityPy (https://github.com/K0lb3/UnityPy), used while preparing the patch (development only, not included).
- FFmpeg (https://ffmpeg.org), used to add subtitles to the videos (development only, not included).

## Credits and licenses

See `NOTICE.md` and `LICENSE`. Built with BepInEx and XUnity.AutoTranslator / ResourceRedirector.
Not affiliated with the developer or publisher.
