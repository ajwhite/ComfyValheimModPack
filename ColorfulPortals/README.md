**Recommended to use with**
- [Configuration Manager](https://www.nexusmods.com/valheim/mods/740)﻿. Then press F1 for mod options.

# ColorfulPortals

  * You can color the activation glow effect of any portal using RGB and HTML color codes!
  * Those without the mod will still see the vanilla yellow/red glow effect.
  * ***Stone portals*** prefabs are fixed to work (though cannot be built and requires serverside mod to connect).

# Manual Installation Instructions

  1. Unzip `ColorfulPortals.dll` to your `/Valheim/BepInEx/plugins/` folder.
  2. In-game, press F1 to bring up the ConfigurationManager and navigate to the ColorfulPortals section.
     * Change the target color using the RGB sliders or using an HTML color code.
  3. Hover over any portal ***that you are the owner of*** and a prompt to change its color will appear.
  4. Hit `LeftShift + E` to change the color.


## Links

Github: [https://github.com/redseiko/ComfyMods](https://github.com/redseiko/ComfyMods)

Looking for a chill server? Join us on [Comfy Valheim Discord](https://discord.gg/ameHJz5PFk)

Looking for great Valheim servers to play on? Check out our community driven listing site at [https://valheimlist.org](https://valheimlist.org)


# Changelog

## 1.4.0

  * Added an option to change the font-size for the text prompt on hover.

## 1.3.0

  * Updated for Hearth & Home.
  * Added `PortalLastColoredBy` ZDO property that is set whenever a player changes the portals color.

## 1.2.0

  * Fixed a memory-leak when caching TeleportWorld/Portals.

## 1.1.0

  * Adding configuration setting to hide the 'change color' prompt over a ward.
  * Now saves the target color's **alpha** value to the ZDO and reads/uses this alpha value if present in the ZDO.

## 1.0.0

  * Initial release.