Set the health of player-placed items in the game to a configurable (default: 100,000,000) health value. Reduces monster attacks on player objects. Recommended mod for dedicated servers so that players passing by your building doesn't mean mobs tear your building down.

**Recommended to use with**

- [Configuration Manager](https://www.nexusmods.com/valheim/mods/740)﻿. Then press F1 and look for the Get Off My Lawn Mod and change the health value.
- [Building Health Display](https://www.nexusmods.com/valheim/mods/793)﻿ so you can see that you've set the health of things.


**Usage Notes**

- Health will be set when you place the item or when you use the repair hammer on it. You can only change the health of building pieces that you own or are permitted on.
- You can activate a ward to set the health value of all building pieces within range to the configured value.
- You can use this mod to ignore stability. Copy a very large number into the health value such as 99999999999999. When you place objects if you're using the building health display mod you'll see that your building's health is now a large negative number. This has "glitched" the item so it will no longer check for stability. *Warning:*stability in the game helps keep buildings smaller to reduce lag. When you cheat stability you can create larger buildings, but this means more lag. Keep an eye on your instances with F2 if this is a concern for you. (Why this works: Stability ticks down HP over time. With high enough health it just takes such a long time to tick down(years) it doesn't matter.)
- Great for boats. There are often "lag" issues with the game that cause boats to take more damage than they're supposed to. Just set your boat to high health. You can also set the value to low (like 10) and it will give your boat the normal health again. This allows you to destroy your boat, pick up the materials, and carry them to another place.
- All items placed with the hammer have their health changed. If you're using a mod that spawns things with the hammer such as ore please keep in mind the ore will likely have high health. Simply disable GOML in the configuration manager if you're trying to place normal health ore veins for example.
- Disabling the mod does not change the health of previously placed/repaired pieces. If you want to lower the health again you'll need to set the health value to low in GOML and repair the piece or activate a ward and everything in the ward radius will be set to that health.

## Links

  * Source code available at:
    * [Github](https://github.com/redseiko/ComfyMods/tree/main/EulersRuler)
  * Looking for a chill Valheim server?
    * Join us on: [Comfy Valheim Discord](https://discord.gg/ameHJz5PFk)
  * Looking for a great Valheim server to play on?
    * Check out our community driven listing site at: [valheimlist.org](https://valheimlist.org/)

## Changelog

### 1.0.1

  * Added null-checks for Piece and Piece.ZNetView references in the ward-interaction method.

### 1.0.0

  * Updated for Hearth & Home.