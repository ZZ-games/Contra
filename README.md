# Contra (NES) player for ZZ Games

Files:
- index.html: the player (keyboard controls, click-to-play screen, fullscreen)
- jsnes.min.js: the NES emulator (jsnes, Apache-2.0 license, see jsnes-LICENSE)
- contra.nes: add your ROM here with exactly this name

## Deploy on GitHub Pages
1. Create a repo on github.com/ZZ-games, e.g. `Contra`.
2. Upload these files to the root of the repo (Add file > Upload files).
3. Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After a minute it's live at https://zz-games.github.io/Contra/

If contra.nes is missing, the page asks the player to pick a .nes file instead.

## Embed in ZZ Games
```html
<iframe src="https://zz-games.github.io/Contra/" width="768" height="720"
        style="border:0" allow="fullscreen; autoplay" allowfullscreen></iframe>
```

## Controls
| Action | Keys |
|---|---|
| Move | Arrows / WASD |
| Fire | J or Z |
| Jump | K or X |
| Start | Enter |
| Select | Shift |
| Pause | P |
| Fullscreen | F |

Players click the game once to give it keyboard focus (this also turns on sound).
