# Living Adventure Map 1.0

by Sinistral, co-authored by Claude

## DESCRIPTION

The adventure map comes alive.

The wind picks up and dies down, trees bend and lose their leaves, smoke drifts from chimneys and campfires. Birds cross the sky and settle on roofs, trees and lakes - until a hero rides too close. Wildlife can be spotted rarely, the water and the lava stir, clouds drift over it all, and the map can be heard as well as seen.

A small compass shows where the wind blows - or lets you decide.

And somewhere, very rarely, something special happens.

Everything is read from the game's own graphics, so it fits the original art, WoG Graphic Fix, Third Upgrade Mod and JS's new objects and terrains alike.

## HOW TO USE

Install it from the Heroes Launcher Mod Browser, or unzip the release into `Heroes 3 ERA\Mods\` and enable the mod in the Mod Manager.

All switches and strengths are in `Mods\Living Adventure Map\Data\Living Adventure Map.ini`; each value shows its default and what it does. Change a value, then load a save or start a game: no restart needed (except to switch `[Main] Enabled` or `[Sound] Enabled` back on).

- **Wind compass:** left-click it for the wind window - tick "Let the game decide the wind" for changing weather, or untick it, drag the arrow to where the wind should blow and set its strength with the slider; OK keeps it (Cancel or Esc changes nothing). Right-click it to see what the wind does now. `[Compass] Clickable = 0` turns the clicks off.
- **Off by default:** the crackling fire and the leaf rustling sounds (`[Sound] Fire`, `Leaves`), and the experimental bending of volcano and geyser plumes (`[Smoke] Volcanic` - still being reworked, see the warning in the ini).

## COMPATIBILITY

- Made for ERA 3.9 with HD Mod, WoG, WoG Graphic Fix, Third Upgrade Mod (ResOunD / TUM Enchanted), JS - new objects and JS - new terrains.
- Pure graphics and sound: no gameplay change. Savegames stay playable without the mod (the hero tracks are simply gone).
- Load order does not matter.
- Performance: about 1-4 ms per frame on a 1920x1080 screen. Lower `[Main] Fps` or `[Leaves] MaxParticles` in the ini on slow PCs.
