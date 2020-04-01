# Counter-Strike: Global Offensive

## What it does:
Enables you to train nades efficiently on any map without workshopmaps.

mostly taken from this tutorial:

https://cs.ingame.de/counter-strike-global-offensive/tipps-tricks/grenade-trajectory/

## How to use:
save both files in:

C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg


run both scripts in the console with:

exec xyz  
xyz is the filename without .cfg


run in this order (because nades_server restarts the server and you lose the items at this moment):

exec nades_server

exec nades_util

## Warning:
Binds the x button to noclip and f8 button to rethrow the last nade. You can adjust the buttons in nades_util.cfg.


