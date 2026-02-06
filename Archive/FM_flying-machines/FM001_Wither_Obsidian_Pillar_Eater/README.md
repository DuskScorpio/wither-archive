# Wither Obsidian Pillar Eater
<img alt="FM001_5wide1.18_render.png" src="images/FM001_5wide1.18_render.png?raw=1">

**Authors:** *Vitamin_C*

**Endorsed by:** *Scorpio*

**Tags:** *Untested*

**Original post:** [View on Discord](https://discord.com/channels/913065809096638494/1392573103007334452)

The world's very first pillar eater that uses Withers instead of players/bots to mine obsidian. Usable in any difficulty. The snow golem at the top is targeted by the Wither's main head, and the iron golem behind the wall is targeted by the side heads.
### Credits
- DF_M: For making the prototype and helping me with debugging
- Youmiel: For dragging me back to a bigger hell just when I thought I escaped (1.18 sucks, man)
And for providing a 1.18 testing server and helping with pathfinding debugging. 
- Scorpio : For helping with withers and stuff
- Menggui233: For directionality testing and robustness testing (mostly still done by myself)
- FAS server: For 1.17 CMP
- Wither Archive, Nub Tech and OSTC lab: For helping with lots of technical details
### Video Links
- [Showcase](https://www.bilibili.com/video/BV1FL4y1u7dy/)
- [User Guide](https://www.bilibili.com/video/BV1FL4y1u7dy?p=2)
### Files
- [World Download and Schematics](https://wwd.lanzouf.com/b02ow52wd) (Password: 82j3)
### Design Specifications
- Due to a bug that makes tall entities un-pushable at subchunk borders (Video demonstration by @Fallen_Breath#1215: https://www.bilibili.com/video/BV1Gv411t7sb?p=4), the machine needs to 0-tick a stone slab into the Withers before pushing them down. Moving the withers by pistons on x/z axis is not possible due to this bug, a pathfinding related solution is used instead. The machine simply moves the snow golem at the top to attract Withers. 
- A TNT duper is used to damage the Withers. The TNTs explode in waterlogged slabs, and they are primed by the duper as well.
- The engine for the duper is a 22 gt/10 gt engine, because Withers destroy blocks once every 20 gt, and if you damage them twice in less than 12 gt, they get angry and start shooting blue skulls randomly.
- Before pushing down the wall that protects the iron golem, the golem is pushed down, and the withers stop firing for a while, allowing the wall to safely descend.
- The Wither gets bored if it doesn't fire any skull for least 170 gt, and start firing blue skulls, but the machine works much faster than that.
## Considerations
- This machine still has a very small chance of breaking, so it is recommended to make backups before starting the machine.
- There's a small chance of black skulls bypassing the wall, if you are building multiple pillar eaters, be sure to consider that.
## Notes
- Check video link for user guide and more info. DM for questions. Recommended to make backups before starting the machine.
- Mojang changed Wither pathfinding in 1.18, so be sure to check the versions before using the machine.

## Other Images
<img src="images/2022-03-08_17.png?raw=1" height="300px">

## Resources
- [FM001_5wide1.16.litematic](attachments/FM001_5wide1.16.litematic): MC 1.16.5, Size 7x23x33 blocks
- [FM001_5wide1.18.litematic](attachments/FM001_5wide1.18.litematic): MC 1.16.5, Size 7x23x33 blocks
- [FM001_7wide1.16.litematic](attachments/FM001_7wide1.16.litematic): MC 1.16.5, Size 9x23x35 blocks
- [FM001_Pillar_Eaters.zip](attachments/FM001_Pillar_Eaters.zip): discord
- [FM001_9wide1.18.litematic](attachments/FM001_9wide1.18.litematic): MC 1.16.5, Size 9x23x37 blocks
- [FM001_7wide1.18.litematic](attachments/FM001_7wide1.18.litematic): MC 1.16.5, Size 9x23x35 blocks
- [FM001_9wide1.16.litematic](attachments/FM001_9wide1.16.litematic): MC 1.16.5, Size 9x23x37 blocks
- [FM001_11wide1.16.litematic](attachments/FM001_11wide1.16.litematic): MC 1.16.5, Size 11x23x39 blocks
- [FM001_11wide1.18.litematic](attachments/FM001_11wide1.18.litematic): MC 1.16.5, Size 11x23x39 blocks
