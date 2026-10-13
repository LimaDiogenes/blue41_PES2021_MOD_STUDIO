<p align="center"><img src="assets/icon.png" width="96" alt="blue41 PES2021 Mod Studio icon"></p>

# blue41 PES2021 Mod Studio — v0.1.0 Early Access

> **Early Access:** this is the first public version. It works, but bugs are expected and some pages are still placeholders. Every change the app makes is backed up and can be undone (see "Change log" below). Found a bug or have an idea? Write to [blue41management@gmail.com](mailto:blue41management@gmail.com)

Website: <https://limadiogenes.github.io/blue41_PES2021_MOD_STUDIO/>

## Requirements
- Windows 10 or 11 (64-bit)
- eFootball PES 2021 with Sider 7 (works with patches that use Sider, e.g. SP Football Life)

## Getting started
- Unzip the folder anywhere. No installer: settings and backups stay inside this folder.
- Run `blue41.ModStudio.exe`.
- Home: the app finds your game, Sider and save folders. If one is missing, click "Choose…" and pick it.
- First start: you can install the blue41 modules you want (you can also do it later).
- Changes to Sider (modules, settings, chants) are loaded when the game starts: restart the game to see them.

## Sider
- Settings: every sider.ini option explained in plain words, with switches, key pickers, font list and colour picker.
- Modules / Content roots: switch Lua modules and livecpk folders on or off and change their order.
- Text: see the whole sider.ini with a before/after comparison of your changes.
- Nothing is written until you save. Leaving a page with unsaved changes asks you first.

## blue41 modules (sidebar)

### Chants
*Your own crowd chants for any team that has chant tracks in the game*
- Included sets: click "+ Liverpool FC" or "+ SC Corinthians" to add them in one click.
- "+ Add team": pick a team, then drop MP3 or WAV files (or a folder) on it, or use "Add songs…".
- Songs are converted in the background and matched to the game's chant loudness. A different song plays each time.
- On a team's page: play/stop a song, rename it, switch it off, replace or remove it. "Retry" if a file failed.
- Switch a whole team off with its toggle (songs are kept). "Remove team" sends its songs to the Recycle Bin.
- Home / away volume: set it on the Chants page, or in game in the Sider overlay (ChantRotator_blue41): [2]/[3] home, [4]/[5] away.
- If the page shows a "Fix it" button, click it once (it installs the chant module).

### No Injuries
*No in-match injuries, also in Become a Legend*
- Install it from its page (or on first start).
- It is ON every time the game starts.
- In game: Sider overlay -> NoInjuries_blue41 -> [2] switches it off / on (applies from the next kick-off).

### BAL Captain (experimental)
*Keep the captain you choose in Become a Legend*
- Install it from its page.
- In the app: pick your team and player, then "Keep as captain" (with the game closed it also changes your save).
- In game, once per session, in the Become a Legend menus: Sider overlay -> BALCaptain_blue41 -> press [6] (it looks for your team; may take a few seconds).
- Then [2]/[3] choose a player and [4] makes him captain. [5] stops keeping the captain.
- **Known bug:** after you play a match in Become a Legend the captain may be reset. Just open the overlay and press [4] again to set your player back.

## Change log (bottom of the sidebar)
- Every change the app made to your game, Sider or saves is listed here.
- "Undo" puts the files back exactly as they were.

## Sider overlay tip
- Open the overlay with Sider's overlay key (Space by default) and press [1] to switch between modules.

## Support the project
- The studio is free and made by one independent developer.
- Patreon: <https://www.patreon.com/blue41Studio>
- Buy Me a Coffee: <https://buymeacoffee.com/blue41studio>

## Contact
- [blue41management@gmail.com](mailto:blue41management@gmail.com)

## License
Freeware, all rights reserved - see [LICENSE.txt](LICENSE.txt). Please share the website link instead of re-uploading the app.
Not affiliated with or endorsed by KONAMI. eFootball and PES are trademarks of KONAMI. The app ships no game files.
Sider is a separate tool by its own author.
