### Previous Requirements

This CFG's works with the eternalJK, client modification:
- https://github.com/eternalcodes/EternalJK

### Installation
You must place the files: master.cfg, sabering.cfg, jedimode.cfg, sithmode.cfg and racemode.cfg inside the game directory: `\Star Wars Jedi Knight Jedi Academy\GameData\base`. Once this is done, start the game and open the console on a server, you must type `exec master.cfg'.

After that, run the commands in the order that they appear in the 1-first.cfg file. This is only necessary to do the first time, then it will not be necessary.

### Controls
- F1 = Change name to Padawan
- F2 = Change name "yourName"
- F4 = Recharge master.cfg
- f5 = Load sabering.cfg
- f6 = Load jedimode.cfg
- f7 = Load sithmode.cfg
- f8 = Load racemode.cfg
- f10 = record
- f11 = stoprecord
- f12 = screenshot
- ctrl = Amtelemark (for racemode)
- alt = Amtele (for racemode)
- mouse4 = lowjump (for eternal sabering mode)
- mouse4 = flipkick (for eternal = jediSith mode)
- 7, 8 y 9 = Cambia entre distintos tipos de sable siendo el orden Single, Dobles y Dual en ese orden.
- H y J = Zoom in and out.

### Edition
You can always edit the files, you can open each cfg with your preferred code editor or use notepad if you want to change any value, for example f2 key in master.cfg to put a custom name.

### Some eternalJKA Documentation
- Eternal does not need more configurations to record the games.
```
bind f10 record;
bind f11 stoprecord;
```
- `cg_defaultModelRandom 0;` anti-bugmodel. Avoid client crash due to bug model error.
- `bind mouse4 lowjump;` exclusive command in eternal to do lowjump.
- `bind mouse4 flipkick;` exclusive command in eternal to do flipkick.
- `stylePlayer 0;` It is a very cool command that activates full brightness in the models.
- All commands inside `racemode.cfg` are designed to work in eternal or japro mod, they are special commands for strafe games.