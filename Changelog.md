# Living Adventure Map - Changelog

The release notes of every version, newest first (the same notes as on the GitHub release pages).

## 1.3

### New
- **Town Building Immersion** (work in progress): towns grow a village in front of their walls as you build them - houses (more with every hall level and building), the tavern, marketplace, blacksmith and mage guild, a well, a watchtower for each fort level, market stalls, variety of building of size and style, gardens and trees. The village keeps clear of the map's objects, roads and water, becoming invisible when hero stand. Each village is kept in the savegame. Birds land on its roofs and its trees sway with the wind. Castle only for now; the town's dwellings and special buildings are not planned. Switch: `[Towns] Enabled`, or "Town Building Immersion" in the new Special Immersion section of the Living Adventure Tweak window.
- **Trees underground** (off by default): plants on the underground level sway with the wind above ground, like the underground windmills. `[Trees] Underground`, or "Trees underground" in the tweak window.

### Changed
- **Smoother sway:** gusts ease in and out, and the quick flutter is slower, so trees no longer flick back and forth.

### Fixed
- The Living Adventure Tweak button was missing from System Options in every game after the first one of a session.
- The Antichrist (Third Upgrade Mod) never came out of banks and dwellings.
- Patched wrong Devils animation
- Patched wrong Minotaur animation
- Commanders no longer appear among the guards of creature banks and dwellings (they flew around them).
- Bank and dwelling creatures standing behind a tall object, such as the Marletto Tower, are now hidden by it instead of being drawn over it.

## 1.2.1

### Changed
- The mod has no volume settings of its own any more: all its sounds follow the game's Sound Effects volume. The wind stays as loud as in 1.2. (`[Sound] Volume` and `[Sound] Wind` are gone.)

### New
- "Leaf amount" in the Living Adventure Tweak window: how many leaves, needles and snow the wind takes off the trees. Top bar = as before, half-way = about half, bottom = about a tenth (`[Leaves] Rate`).

## 1.2

### New
- Living Adventure Tweak in System Options > Other Settings
- Creature banks come alive
- Every text can be translated (ERA's Lang json files). Russian translation included.

### Changed
- Windmills stand still in a calm wind, then start turning again as the wind picks up.
- The mod's sounds follow the game's Sound Effects volume and the "Background Sounds" option. The wind is louder and gets louder as it grows stronger.

### Fixed
- Trees no longer look worse.
- The wind window's checkbox and the compass make the game's click sound.
- Circling hawks and vultures no longer fly back and forth before they settle into a circle.

## 1.1

### New
- Windmills turn with the wind: faster in a strong wind, slowly in a calm, the other way when the wind turns. The sails move smoothly.
- Dragon Utopias: dragons of the kind guarding the utopia fly around it, rest on its walls, roofs and arches, and go back in. A cleared utopia stays quiet. Works with any mod's utopia.
- Marletto Tower: swordsmen come out to train and go back in after a while, or at once when a hero comes near. With Third Upgrade Mod, one of them is a Sword Master.
- Colourful birds on roofs: pigeons, doves, magpies, storks, gulls and sparrows. Crows and ravens keep to trees and the ground.
- Buildings with a chimney or a fire in their picture smoke, and their fires glow. Lighthouse and lantern lamps glow too.
- Still magic sites shimmer faintly, magic patches get motes or haze, and objects in the sea ripple the water. Objects with their own animation are left alone.

### Changed
- The wind window uses the game's own checkbox and button frames. The strength bar has a gold border, and its fill follows the rounded end.

### Fixed
- Birds land on roofs again (birds that had flown off blocked new flocks).
- Buildings no longer cut off figures standing in front of them.
- Without WoG Graphic Fix, the war machine factory smokes from its own pipe.

New ini switches, all on by default: `[Windmills]`, `[Buildings] Training` and `Dragons`, `[Smoke] Chimneys` and `Glow`, `[Sites]`. Graphics only: no gameplay change, saves unaffected.

## 1.0

- First public release: wind and weather with the wind compass and wind window, swaying plants and falling leaves, life on every ground type, birds that land and fly off, wildlife, flamingos, smoke, hero tracks and sound.
