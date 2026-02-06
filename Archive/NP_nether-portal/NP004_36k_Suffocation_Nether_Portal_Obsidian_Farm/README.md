# 36k Suffocation Nether Portal Obsidian Farm
<img alt="area_render_2_.png" src="images/area_render_2_.png?raw=1" height="300px">

**Authors:** *soullessjump*

**Endorsed by:** *Scorpio*

**Tags:** *Tested & Functional, Recommended, Entity Generate*

**Original post:** [View on Discord](https://discord.com/channels/913065809096638494/1396705975595040869)

A nether portal obsidian farm using suffocation instead of TNT duping to harm the withers
## Credits
- booty, Scorpio: Wither cage based on savva's reload detector
- magplum: Nether based collection and obsidian recycling system
- WMC: Original design of a 6-wither cage which inspired this diagonal dual wither setup
- team109, applestruck: Clock from their wither cage design
## Versions
- 1.21+
## Rates
- Obsidian: 36k/h
## Lag info
- Test environment: CPU i7-11370H with Lithium
- Idle: 1.0mspt
- Active: 2.1mspt
## Files
- Schematics:
- Overworld side: https://cdn.discordapp.com/attachments/1385857890086289540/1395965007270772786/36k_Dupeless_Obi_v1.1.litematic?
- Nether side: https://cdn.discordapp.com/attachments/1385857890086289540/1396692698290983044/36k_suffocation_nether.litematic?
- Images: https://cdn.discordapp.com/attachments/1385857890086289540/1396020116147404870/area_render_2_.png?
## Positives
- Uses no duping and is fully playerless
- Uses a dispenser-less and mob-less method of harming the withers, which avoids item consumption by dispensers as well as dealing with unreliable mob AI
- Automatically recycles obsidian from the nether to generate new portals (uses Magplum's design)
- Farm can be started and stopped entirely in the overworld
## Negatives
- Requires subchunk alignment for wither cage
- Not unload proof. If the chunks are reloaded while the wither harming mechanism is left running, the design has a small chance of breaking (~10%).
## Design specifications
- Uses a piston to repeatedly push a block into the wither to momentarily suffocate it. This is done through aligning the wither's hitbox to partially clip into the blocks behind it with an extended piston based cage setup.
## Instructions
### Notes
1. Don't reload the chunks while the wither harming mechanism is running as this has a small chance (~10%) of breaking the design. This can easily be mitigated by making sure the clock is turned off before leaving the farm.
2. When starting the farm, there is a very small chance (~5%) that the portal creation cycle would be in perfect sync with the wither harming mechanism which would prevent the farm from running. This can be resolved by simply reigniting your side portal, throwing an item through it and pressing the button on the dispenser to break the portal.
### Build
1. Use the blue wool to ensure your schematic is subchunk aligned (refer to figure 1 and 2) and the OW portal's y coords is as close as possible to the y coords of your nether side portal. Your main portal (the one broken by your withers) should also be coordinate aligned to and face the same direction as the nether side portal
2. Test your portal generation to ensure it gets created in the correct place. If this isn't the case, then flood the floor of any caves you find your portal generated in and deactivate that portal. You may have to do this a few times before your portal generates in the farm.
3. Once you've confirmed your portal generates correctly, you can summon the withers with the placement and steps shown in figure 3. Ensure your chickens and iron golem are at full health, your chickens are **fully grown** and no other mobs are in the vicinity when summoning your wither.
4. If you see the main head firing no skulls, you have done everything correctly. Simply use a bucket to collect your water and make sure to break the iron trapdoor to enable the piston to harm the wither.
### How to use
- Starting the farm
  1. If you are starting it for the first time, go to the nether side portal and prefill the dropper underneath the glass pillar with 64 dummy items. Feel free to add more dummy items if you feel you need more time to start the farm. Place a minecart on the sloped rail to start the clock. You should see items being fired through the portal at 1 second intervals if everything is setup correctly.
  2. In the OW, flip the switch to start the pistons that'll hurt your withers. Activate your side portal if it isn't already and throw any dummy item in there. Quickly press the button on the dispenser to deactivate your portal and the farm should be started.
- Stopping the farm
  1. Press the button on the dispenser to pick up the placed water and reignite your side portal.
  2. Flip the switch to turn off the wither hurting mechanism.

## Resources
- [NP004_36k_suffocation_nether.litematic](attachments/NP004_36k_suffocation_nether.litematic): MC 1.21.4, Size 6x9x4 blocks
- [NP004_36k_Dupeless_Obi_v1.1.litematic](attachments/NP004_36k_Dupeless_Obi_v1.1.litematic): MC 1.21.5, Size 16x24x27 blocks

## Comments

### Scorpio (7/21/2025)
## Figures
- *Figure 1.* https://cdn.discordapp.com/attachments/1385857890086289540/1396010578807361567/2025-07-19_02.05.33.png?ex=687c87aa&is=687b362a&hm=4c5c7274ef70acaca0f63bf3896cf76171993718eaaa56deb205d57837527749&

**Other attachments:**
- [2025-07-19_02.05.33.png](comments_attachments/1396010578807361567-2025-07-19_02.05.33.png): discord


### Scorpio (7/21/2025)
- *Figure 2.* https://cdn.discordapp.com/attachments/1385857890086289540/1396022246258245642/2025-07-19_02.53.29.png?ex=687c9288&is=687b4108&hm=b44b576fb89af073fbeae483ed22d7144958893bc3effb8e5197a086253d9aaf&

**Other attachments:**
- [2025-07-19_02.53.29.png](comments_attachments/1396022246258245642-2025-07-19_02.53.29.png): discord


### Scorpio (7/21/2025)
- *Figure 3.* https://cdn.discordapp.com/attachments/1385857890086289540/1386015624454738051/wither_summoning.mp4?ex=687bc3a3&is=687a7223&hm=07d2a0807d563eb33a3a533fbb95964de7c8540e18ae388a1f54d0854ea26e1f&

**Other attachments:**
- [wither_summoning.mp4](comments_attachments/1386015624454738051-wither_summoning.mp4): discord

