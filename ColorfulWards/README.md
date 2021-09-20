**Recommended to use with**
- [Configuration Manager](https://www.nexusmods.com/valheim/mods/740)﻿. Then press F1 for mod options.

# ColorfulWards

  * You can color the glow effect of any ward using RGB and HTML color codes!
  * Those without the mod installed will still see the default yellow glow.
  * **Wards will now only extend/cover its default radius (30m) on the vertical/Y axis.**
    * In the vanilla game, the range is infinite on the Y axis and the default radius on the XZ axis.

# Instructions

  1. Unzip `ColorfulLights.dll` to your `/Valheim/BepInEx/plugins/` folder.
  2. In-game, press F1 to bring up the ConfigurationManager and navigate to the ColorfulWards section.
     * Change the target color using the RGB sliders or using an HTML color code.
  3. Hover over any ward **that you are the owner of** and a prompt to change its color will appear.
  4. Hit `LeftShift + E` to change the color.

Looking for a chill server? Join us on [Comfy Valheim Discord](https://discord.gg/ameHJz5PFk)
Github: [https://github.com/redseiko/ComfyMods](https://github.com/redseiko/ComfyMods)


Looking for great Valheim servers to play on? Check out our community driven listing site at [https://valheimlist.org](https://valheimlist.org)


# Changelog

## 1.3.0

  * Updated for Hearth & Home.
  * Added `WardLastColoredBy` ZDO tag that is set to the last Player that modifies the Ward color.
  * Added an option to change the font-size for the text prompt on hover.

## 1.2.0

  * Fixed a memory-leak when caching PrivateArea/Wards.

## 1.1.0

  * Adding configuration setting to hide the 'change color' prompt over a ward.
  * Now saves the target color's **alpha** value to the ZDO and reads/uses this alpha value if present in the ZDO.
    * However, there isn't any apparent effect/use for color alpha for ward lights and particle systems.'

## 1.0.0

  * Initial release.