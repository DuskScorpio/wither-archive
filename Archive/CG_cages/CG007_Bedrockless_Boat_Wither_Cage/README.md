# Bedrockless Boat Wither Cage
<img alt="Image_59607992550936.png" src="images/Image_59607992550936.png?raw=1" height="300px">

**Authors:** *Scorpio, booty*

**Endorsed by:** *Scorpio*

**Tags:** *Tested & Functional, Recommended, Bedrockless Cage*

**Original post:** [View on Discord](https://discord.com/channels/913065809096638494/1392400293077061763)

A simple wither cage without any redstone made by @bigbooty17 and Scorpio. 
### Credits
- Chunk reload detector and chunk loading explanation by @savva4424.
### Versions
- 1.16+
### Video Links
- [Showcase](https://youtu.be/Cf1lBWqwzIo)
### Design Specifications
-  Mechanics
  - This works because on reload, the passenger is momentarily centered on the boat’s exact position instead of being shifted to the front. That causes it to briefly touch the tripwire for a tick before snapping to its proper spot.
- Entity processing order
  - Minecraft loads entities within the same sub-chunk from bottom to top. We need the wither to load before the boat, so it can see the chicken before the boat loads and shifts the chicken’s position. To make that happen, we place the wither’s feet in the sub-chunk directly below the boat. This way, the wither is always loaded first.
  - This gives us an reliable wither cage that’s much more resilient to atypical reloading than ones that rely on redstone.
## Notes
- When setting up this cage, you can also place the boat in the adjacent chunk first, and after the wither is summoned in, and then push the boat into the same chunk as the wither. This also ensure the wither is always processed before the boat, instead of relying on sub chunks
- It doesn’t have to be a chest boat, just a regular boat with two passengers works, since each one gets offset from the boat’s center. Refer to [this design](https://discord.com/channels/913065809096638494/1391992148739625140) for reference

## Resources
- [CG007_ChestboatWitherCage.url](https://www.mediafire.com/folder/9mgkxdfyk78ls/Chestboat+Wither+Cage): Mediafire link
- [Simple chunkloading detector](https://www.youtube.com/watch?v=Ho_aJ1Lw0Zw): by [Savva](https://www.youtube.com/@savva4424)
- [Chunkloading rant pt3 “ticking disorder”](https://www.youtube.com/watch?v=FrQoGXeSezE): by [Savva](https://www.youtube.com/@savva4424)
- [SIMPLE Bedrockless Wither Cage with NO Redstone in Minecraft](https://youtu.be/Cf1lBWqwzIo): by [Scorpio](https://www.youtube.com/@Scorpio03)
