## TestingKatagoNetworks
This is a database comparing the strength of different KataGo networks and unofficial networks. You can get the networks in [Network_Library](https://github.com/foxrainowo/TestingKatagoNetworks/releases/tag/Network_Library) and view the [Latest_Test_Result](https://github.com/foxrainowo/TestingKatagoNetworks/releases/latest).

### Elo Estimation Tool
Download [summarize_elo.py](https://github.com/foxrainowo/TestingKatagoNetworks/blob/main/summarize_elo.py) and run a command. Thanks to [@lightvector](https://github.com/lightvector) for developing this script, and I have made some improvements to it.

**Normal Usage:**

	py summarize_elo.py "path" -standard {number} -prior {number} -create {v/p/t} -color -first-advantage -recursive
 
**For Instructions:**

	py summarize_elo.py -h
 
### How to contribute
I would collect *Game Records(SGFs)* and *Networks(bin.gz)* from public channels or You can send it to me.

**Standard requirements:**
- Only 19×19 board.
- Fixed playouts (50+).
- More than 1000 games with each opponent.

