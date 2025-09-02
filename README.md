# age2de-ui

Personalized Age of Empires 2 Definitive Edition mods

## How to use

- Go to `C:\Users\<user>\Games\Age of Empires 2 DE\<steam user id>\mods`
- Do `git clone git@github.com:Ch4nKyy/age2de-ui.git local`
- Start the game. In-game, only enable 1 UI mod. Restart the game.

## How to reload assets

- To reload panels in-game, e.g. the map panel, open
  `X:\Steam\steamapps\common\AoE2DE\widgetui\mappanel.json` and save the file.
- Textures cannot be reloaded ingame
- To reload palette.json, click Restart in an active game.

## Published mods I use

- 2416_No Intro
- 14335_Improved Extended Tooltips
- 14786\_[GreatestTech] Larger Onager Projectiles
- 17227\_[KoBHV] Villager Highlighter
- 18308_Green Flashing Age Up Button Icon
- 21423_Short walls All in One
- 2553_No more plants
- 3259_Better Civ Emblems
- 20846_Anne_HK - Building Foundation Label (with Player Color)
- 22781_Anne_HK - Selected Small Trees with Grid Shadow
- 23167_Anne_HK - Monk Pointer (Attack and Carry Relic Only)
- 37614_Anne_HK - Bigger and Eye-catching Relic
- 50126_Anne_HK - Boar Pointer
- 58889_Anne_HK - New Fish Border
- 4015_Barbarian 2.18
- 409484_Legacy ES Maps

## Troubleshooting

- If the game crashes instantly after reloading the UI, there is an obvious error like syntax error
  etc.
- There is a really annoying bug. The game crashes, when you remove something from a building queue
  by clicking on it, while no UI element is behind the building queue buttons that consumes the
  click event. Some UI elements consume clicks, some don't. A workaround for that is positioning the
  blankbottompanel behind the queue panel.
- The resource panel has a weird bug. Its click event eating area doesn't change when changing the
  panels size. Also, when adding a y offset to its position, the area suddenly extends extremely far
  below the actual panel. Because of that, in the UI SC2 Modded version I move the panel to the
  left, so the buggy area is hidden behind the minimap.
