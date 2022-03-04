### Previous Requirements

This CFG's works with the eternalJK, client modification:
- https://github.com/eternalcodes/EternalJK

### Installation
You must place the files: master.cfg, sabering.cfg, jedimode.cfg, sithmode.cfg and racemode.cfg inside the game directory: `\Star Wars Jedi Knight Jedi Academy\GameData\base`. Once this is done, start the game and open the console on a server, you must type `exec master.cfg'.

After that, run the commands in the order that they appear in the 1-first.cfg file. This is only necessary to do the first time, then it will not be necessary.

### Controls
- F1 = Change name to Padawan
- F2 = Change name "yourName1"
- F3 = Change name "yourName2"
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
- 7, 8 y 9 = Change saber: Single, double and staff.
- H y J = Zoom in and out.

### Base commands Documentation
- `com_maxfps` That modify your jump level: 142=very low, 200=low 125=medium 333=high
- `cl_timenudge` tn<-30 or tn>30 = hack. -1 for base server with proxy
- `cg_rendertotexturefx 0;` Disable push and pull effect
- `cg_fov` fov > 97 = hack
- `cg_thirdPersonRange` tpr > 80 = hack

### Ja+ commands Documentation
- `amdropsaber` drop saber
- `pluginDisable 13;` SP/MP-style for cartwheel move

### eternalJKA commands Documentation
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