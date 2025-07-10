# Bedrockless Bedrock Wither Cage (Shuffling Cage)
<img alt="area_render_23.png" src="images/area_render_23.png?raw=1">

**Authors:** *Scorpio*

**Endorsed by:** *Scorpio*

**Tags:** *Untested, Bedrockless Cage*

**Original post:** [View on Discord](https://discord.com/channels/913065809096638494/1392541242201608214)

A bedrock-less wither cage made long ago.
## Versions
- 1.17+ (not sure)
## Design Specifications
- Uses a chunk reload detector to block the main head's eyesight to its target to prevent the 1/1000 chance of main head shooting blue skulls
- The side head black skulls are prevented by shuffling the side head skull blocker
  1. When the wither is attempting to break blocks, the blockers will be pulled backwards with sticky pistons. 
  2. After the block breaking attack, new blockers from the top will be 0-ticked into place to detonate potential wither skulls that spawned in the previous tick. Because the initial velocity of the wither skulls is very low, the skulls will not have a chance to escape before the new blocker arrived.

## Other Images
<img src="images/7de80c4ff3d270e087cf161998f26a18.png?raw=1" height="300px">

## Resources
- [CG008_Bedrockless_Bedrock_Cage_Prepared.litematic](attachments/CG008_Bedrockless_Bedrock_Cage_Prepared.litematic): MC 1.18.2, Size 6x13x3 blocks
- [CG008_Bedrockless_Bedrock_Cage.litematic](attachments/CG008_Bedrockless_Bedrock_Cage.litematic): MC 1.18.2, Size 6x12x3 blocks
