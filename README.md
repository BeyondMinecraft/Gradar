# Gradar
The Minecraft mod 'Gradar', a-k-a "Gregory's Radar". It imitates functionality from its predecessor, "RadarBro".

## Modules.
This comes in three primary modules: the Core, IFFS (Identify-Friend-Foe-System), and WPTS (Way-Point Tracking System).
All are primarily client-sided modules, with some optional server-side capabilities (or, TBD).

### GradarCore.
This core module is what draws the radar overlay, depending upon configured options for what will be shown. Settings to
be chosen will be whether to draw general items, boss mobs, hostile mobs, neutral mobs, passive mobs, other players, et
cetera.

### GradarIFFS.
This is the player's client-side registry of friend-or-foe status; the data you set for player-names is never sent to
any server -- it is *your* state of play.

### GradarWPTS.
This is the player's client-side registry of way-points to be tracked, allowing easier recall of various coordinates. A
future enhancement might allow "shared" way-points, for teams, collaborative, or even "public" way-point data.
