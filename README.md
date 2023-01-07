# age2de-ui

Changes the Age2 DE HUD.

like_age3
* Minimap bottom left
* Command bar bottom right
* Resources bar bottom left

like_sc2
* Minimap bottom left
* Command bar bottom right
* Resources bar top right

## How to develop

* Do changes in age2de-ui\xxx\xxx.json
* Copy file to ```C:\Users\user\Games\Age of Empires 2 DE\playerID\mods\local\LocalUIMod\widgetui```
* Open the corresponding X:\Steam\steamapps\common\AoE2DE\widgetui\xxx.json
* The game reloads the UI, when you save this file.

## Troubleshooting

* Moving the command buttons to the right of the building queue introduces a weird glitch, where further changes to the UI may randomly crash the game, when you cancel objects from the building queue.   
For like_age3 it works, for like_sc2 it does not.
Logs don't help a bit. The only error message is something like
```Exception type 0xc0000005 occurred at 00007ff63a563bab```.

* If the game crashes instantly after reloading the UI, there is an obvious error like syntax error etc.
