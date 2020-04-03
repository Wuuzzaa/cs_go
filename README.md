# Counter-Strike: Global Offensive

## What it does:
Enables you to train nades efficiently on any map without workshopmaps.

mostly taken from this tutorial:

https://cs.ingame.de/counter-strike-global-offensive/tipps-tricks/grenade-trajectory/

## Features
- godmode
- removes bots
- infinite ammo
- infinite nades
- give ak
- enable grenade trajectory
- enable grenade preview
- show weapon impacts
- rethrow grenade
- noclip
- no waiting times for warumup and freezetime
- 60000$ and buy anytime anywhere
- place a standing t_bot by pressing f9


## How to use:
save both files in:

\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg

or (depending on your pc)

\Steam\userdata\00000000\730\local\cfg where “00000000” is your steam ID.

run both scripts in the console with:

exec xyz  
xyz is the filename without .cfg


run in this order (because nades_server restarts the server and you lose the items at this moment):

exec nades_server

exec nades_util

## Warning:
Binds the x button to noclip, f8 button to rethrow the last nade and f9 to place a standing bot. You can adjust the buttons in nades_util.cfg.


