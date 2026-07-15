# NPM
```My first small console game on C++```

My first project made in the first year of learning programming and C++. It is some sort of attempt to remake PacMan in console, that went away half a way into developing tiled sandbox.
All code was changing during learning process and done without knowledge how to do such things in the right way, so the game is very buggy, laggy and messy. 

No futher updates is planned so far.
<img width="630" height="675" alt="VsDebugConsole_RQj0uSwtOT" src="https://github.com/user-attachments/assets/1ee6988e-6cdd-4f69-9567-02291df049e3" />


## Micro-setup Guide
- require C++ 23 on the latest version
- change console in windows settings to the old Windows 10 version (if using Windows 11)
- use "Lucida Console" font in console (right click on console bar -> options)
- also using bigger font size is advised


## Control
- WASD - movement
- Space - pause
- e - command line (during pause)


## Game Mechanics
- 15000 score - Win
- fruits and tokens grant score
- white pills give ability to kill enemies and make them run away from the player
- Crism (red one) just pursuit you
- Phantom (purple) pursuit you and can walk through walls
- Moss (green) pursuit you
- some of enemies changes during night
- and more...


## Commands
- show_(pos/params) - show special data about the state of the game
- set - set value for specific parameter of the game (speed, tokens, fruits... etc)
- active_mode - change mode of enemy movement
- active - change specific state of a game or disable enemies
- place - replace player or enemy in set position
- spawn - create one item or line of tiles
- replace - replace specific tiles (or all tiles) by another tile

- mod_(create/gamelife) - activate specific section of commands
- mod_create_obj - add new tile into the game that you can spawn later in the game
- mod_create_edit - change specific parameter of tile, like collision or cost
- mod_gamelife_active - activate game of life simulation
- mod_gamelife_speed - change simulation speed of GoF
- mod_gamelife_(zero/one) - set *zero* and *one* objects for simulation (plate and token by default)
- mod_gamelife_(birth/life) - set birth and life rule for cell simulation

~while writing down into command line, templates showing up. (you can press *Enter* while typing to copy template into line)
~also spaces and brackets are unnecessary while typing command
<img width="1221" height="693" alt="VsDebugConsole_BlREVpTICI" src="https://github.com/user-attachments/assets/75785911-2b5f-4b19-815c-d757fb908752" />
