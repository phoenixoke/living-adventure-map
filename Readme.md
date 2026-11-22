# Living Adventure Map 1.4 beta 2

by Sinistral, co-authored by Claude

## DESCRIPTION

The adventure map comes alive.

The wind picks up and dies down, trees bend and lose their leaves, smoke drifts from chimneys and campfires and forges glow. Windmills turn with the wind. Birds cross the sky and settle on roofs, trees and lakes - until a hero rides too close. Wildlife can be spotted rarely, the water and the lava stir, clouds drift over it all, and the map can be heard as well as seen.

The guards of every creature bank come alive - from the game or from any mod: flyers circle the bank and perch on its roof, walkers patrol in front of it and look around, sea guards swim around and dive, floating eyes hover and drift - until the bank is cleared. Dwellings send out some of the creatures you could hire there. Devils do not walk - they vanish in flames and appear again somewhere else.

Towns grow a village in front of their walls as you build them: houses, the tavern, the marketplace, the blacksmith, the mage guild, a well, watchtowers, market stalls and gardens, placed around the map's own objects and never moved once they stand. Every village is there from the moment the game loads, even far from view. Rampart villages are elven, with their own houses and landmarks and a mage guild that rises to five levels. Villagers live in its houses, one in each: they stroll to the market, the well and the benches, stop for a word, visit their town and go home now and then. They bow when one of their lord's heroes passes, and they run home and bolt the door when an enemy hero comes near. Birds land on the roofs and the trees sway with the wind. Still a work in progress: Castle and Rampart only for now, and the town's dwellings and special buildings are not planned. Still shrines, wells and fountains give off a faint shimmer, and objects at sea stir the water around them.

A small compass shows where the wind blows - or lets you decide. Calm days leave the windmills standing still.

And somewhere, very rarely, something special happens.

Everything is read from the game's own graphics, so it fits the original art, WoG Graphic Fix, Third Upgrade Mod and JS's new objects and terrains alike.

## HOW TO USE

Install it from the Heroes Launcher Mod Browser, or unzip the release into `Heroes 3 ERA\Mods\` and enable the mod in the Mod Manager.

All switches and strengths are in `Mods\Living Adventure Map\Data\Living Adventure Map.ini`; each value shows its default and what it does. Change a value, then load a save or start a game: no restart needed (except to switch `[Main] Enabled` or `[Sound] Enabled` back on).

- **Wind compass:** left-click it for the wind window - tick "Let the game decide the wind" for changing weather, or untick it, drag the arrow to where the wind should blow and set its strength with the slider; OK keeps it (Cancel or Esc changes nothing). Right-click it to see what the wind does now. `[Compass] Clickable = 0` turns the clicks off.
- **Living Adventure Tweak:** System Options > Other Settings (below Script Message Disabling, once a game has started). Three columns: General (hide the compass, its corner and size, the leaf amount), Effects (trees, trees underground, leaves, birds, wildlife, smoke, windmills, windmills underground) and Creature Life (creature banks - the Dragon Utopia too -, dwellings, adventure objects), with Special Immersion below it (Town Building Immersion - the Castle and Rampart villages and their villagers). The compass icon at the top right opens the wind window. OK writes your changes into the ini.
- **Sound** follows the game's Sound Effects volume and its "Background Sounds" option.
- **Languages:** every text is in `Lang\living_adventure_map.json`; a Russian translation is in `Lang\ru\`. Choose the language with the Language button in System Options. To translate, copy the json into `Lang\<language code>\` and translate the texts (keep the `@name@` parts).
- **Each feature has its own switch:** `[Windmills]` (also `CalmStop` and `Underground`), `[Banks]`, `[Dwellings]`, `[Towns]` (also `Villagers`), `[Buildings] Training` and `Dragons`, `[Smoke] Chimneys` and `Glow`, `[Sites]`, `[Trees]` (also `Underground`: plants underground sway with the wind above ground).
- **Off by default:** the crackling fire and the leaf rustling sounds (`[Sound] Fire`, `Leaves`), and the experimental bending of volcano and geyser plumes (`[Smoke] Volcanic` - still being reworked, see the warning in the ini).

## COMPATIBILITY

- Made for ERA 3.9 with HD Mod, WoG, WoG Graphic Fix, Third Upgrade Mod (ResOunD / TUM Enchanted), JS - new objects and JS - new terrains. Works without WoG Graphic Fix, TUM or JS too.
- Creature banks and dwellings are recognised by their object type, so those added by other mods come alive too, without a list.
- The Living Adventure Tweak button uses ERA's System Options extension; without it the mod still works and is set in the ini.
- The creatures you see at a bank are its real guards, and at a dwelling the creatures you could hire there.
- Pure graphics and sound: no gameplay change. Savegames stay playable without the mod (the hero tracks and the villages are simply gone). Each village is kept in the savegame, so it looks the same after every load.
- Load order does not matter.
- The trees, smoke and windmills it moves are copied from what the game itself draws, so other graphic mods' art stays as it is.
- Performance: about 6 ms per frame on top of the game's own map drawing (measured on a huge, busy map at 1920x1080). The map is redrawn about 25 times a second for the animations, so the mod uses roughly a quarter of one CPU core. Lower `[Main] Fps` or `[Leaves] MaxParticles` in the ini on slow PCs.

## CREDITS

- Картонный лисъ - for valuable feedback.
