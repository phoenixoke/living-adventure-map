# Living Adventure Map - Changelog

The release notes of every version, newest first (the same notes as on the GitHub release pages).

## 1.4 beta 5

Town Building Immersion is in beta until every town type has its village.

### New
- **Necropolis villages:** Necropolis towns now grow a graveyard village as you build them, drawn to match the Necropolis town screen: graves, tombs and small crypts of cold grey stone take the place of houses, beside a stone tavern hall with blue stained-glass windows, a domed market shrine, a gothic arched portal for the silo, a blacksmith under red-lit iron arches, and a stepped stone mage guild that gains a level with every guild level.
- **Necropolis landmarks:** an obelisk with a green flame stands in front of the town from the start, a guard tower appears for each fort level and grows taller with the Citadel and the Castle, and the Veil of Darkness, Necromancy Amplifier and Skeleton Transformer bring a shrine wrapped in black mist, a red-lit spire and an altar of bones.
- **Necropolis grounds:** dead grey trees that stand still in the wind, thorn bushes, leaning tombstones and stone crosses, iron cemetery fences, bone piles, coffins, braziers and lanterns burning with green ghost-fire, a crow on its post, grey lilies, broken columns and freshly dug graves.
- **Necropolis roads:** the village road is laid from Necropolis's own pale sand path with the brown rubble beside it, so it carries on from the town without a seam.
- **Necropolis villagers:** hooded mourners in black and grey, skeletons without their sword, and zombies with nothing in their hands. They rise out of their graves and sink back into them when they go home, or when an enemy hero comes near. They walk up the town's own road to its door: the doorway of the village keep, the fort's door, and the gate once a Citadel stands.

- **Bigger villages:** every village building is about 25 % bigger with all its detail kept, and the decorations, the villagers and the creatures at creature banks, dwellings and the training ground grew with them. The village area is wider and deeper to make room.
- **Castle:** its village road is now laid from Castle's own dirt path and frays into the grass with a ragged, grainy edge, tufts of grass and a trampled border. New landmarks for Castle's own buildings: the Brotherhood of the Sword's guild house and the Lighthouse, beside a well from the start, a stable and market stalls. New decorations of its own.
- **Rampart:** the same blended road from Rampart's own path, and a lusher, greener valley like its town screen: dark firs, blue-green spruces, birches and green trees, more bushes and gardens, and mossy props of its own.
- **Tower:** new decorations of its own.
- **Smoking landmarks:** the Necropolis Cover of Darkness pours dense charcoal smoke that rises, levels off and spreads into a cover drifting with the wind, and with the Brimstone Clouds the two chimneys of an Inferno fort erupt every few seconds: a fireball, a maroon column lit from below, lightning and sparks (the sulphur vent of 1.4 beta 4 is gone - the smoke comes from the fort itself). The smoke is simulated (heat, wind and gusts, eddies, light and shadow) and drawn with the game's own smoke pixels. Ini [Towns] LandmarkSmoke.
### Note
- Villages in savegames from 1.4 beta 4 are made again once when the save is loaded, so they may look different.

## 1.4 beta 4

Town Building Immersion is in beta until every town type has its village.

### New
- **Inferno villages:** Inferno towns now grow a village of their own as you build them, drawn to match Inferno's own town screen: dark half-timbered houses of speckled maroon stone under horned charcoal roofs with glowing windows, a tavern, covered market stalls, three mercury troughs for the silo, a red-brick forge with a burning chimney, and a fire pagoda for a mage guild that gains a floor with every level.
- **Inferno landmarks:** a fire basin stands in front of the town from the start, a guard tower appears for each fort level, and the Brimstone Clouds, Castle Gate and Order of Fire bring a sulphur vent, a horned fire portal and a flame shrine.
- **Inferno grounds:** no green in an Inferno village - charred dead trees and lava-rock spires, thorn brambles and sulphur boulders, lava pools and ember pits, fire bowls, iron torch posts, spiked iron fences, coal carts and fire lilies. The charred trees stand still in the wind.
- **Inferno roads:** the village road is laid from Inferno's own cobbles with the dark rubble beside it, as on the town's own path, so it carries on from the town without a seam.
- **Inferno villagers:** townsfolk in dark red, charcoal and ember, imps, and gogs without the fireball in their hand. They walk up the town's own road to its door: the hall at the top of the stairs while the town has no fort, the keep's door once it has one.

### Fixed
- A village never lays its own road over a road of the map: it ends where it meets one and joins it (every town type).

### Note
- Villages in savegames from 1.4 beta 3 are made again once when the save is loaded, so they may look different.

## 1.4 beta 3

Town Building Immersion is in beta until every town type has its village.

### New
- **Tower villages:** Tower towns now grow a village of their own as you build them, drawn to match the Tower's own town screen: grey stone houses under mossy slate roofs, a classical tavern with fire braziers, a market hall on white columns, a clock-tower silo, a stone forge, and a mage guild that gains a floor with every level.
- **Tower landmarks:** a fountain stands in front of the town from the start, a guard tower appears for each fort level, and the Lookout Tower, Library, Wall of Knowledge and Artifact Merchants each bring their own small landmark to the village.
- **Tower roads:** the village road is laid from the Tower's own cobbles, so it carries on from the town's road without a seam.
- **Tower villagers:** townsfolk in the Tower's blues and whites, gremlins without their ball and chain, and mages without their staff.

### Fixed
- Village roads no longer disappear on snow (every town type).
- Villagers now follow the road to their town's door and back, instead of cutting straight over the grass (every town type). The Tower's door is where its gate opens between the two flags.

### Note
- Villages in savegames from 1.4 beta 2 are made again once when the save is loaded, so they may look different.

## 1.4 beta 2

Town Building Immersion is in beta until every town type has its village.

### New
- **Villagers:** every village house has someone living in it. Villagers stroll to the market, the well and the benches, stop for a word with each other, sit for a while and go home now and then, always to their own house.
- **They visit their town:** now and then a villager follows the road and the town's own road up to its door, goes in for a few seconds and comes back out.
- **They know their lord:** when a hero of the town's owner (or an ally) comes within 2 tiles, the villagers nearby stop and bow.
- **They fear strangers:** when an enemy hero comes within 3 tiles, everyone runs home and stays inside until he is gone, or until the town is his. Towns without an owner are wary of every hero.
- **Castle** villagers are peasants in different clothes. **Rampart** villagers are wood elves, elven peasants, centaurs and dwarves, none of them armed.
- New switches in `[Towns]`: `Villagers` (on/off) and `VillagerBow` (how they bow).

### Changed
- **Bigger village buildings:** houses, buildings and landmarks are 20 % bigger, and each village has more ground (wider and deeper), so a fully built town still gets all its houses.
- **Smaller creatures at banks and dwellings:** small creatures are drawn about a quarter smaller than before, so they fit the size of the map's buildings. Big creatures stay larger: every tier 6 and 7 creature, every two-hex creature (griffins, centaurs, wolf riders, pegasi, cerberi, basilisks, gorgons...), and the large dendroids, ogres, golems, minotaurs, elementals, demons, genies and trolls.

### Note
- Villages in savegames from 1.4 beta 1 are made again once when the save is loaded, so they may look different.

## 1.4 beta 1

Town Building Immersion is in beta until every town type has its village. Each new town type comes as the next beta. I should have done this on 1.3 where CASTLE Faction were developed.

### New
- **Rampart villages:** Rampart towns now grow an elven village as you build them: thatched houses among the trees, a mage guild pagoda that rises to five levels, the tavern, market stalls, a silo cart and a forest smithy. Landmarks include stone lanterns, a lookout tower for each fort level, a totem shrine, a granary and a dwarf mine, on a road of Rampart's own dirt.

### Fixed
- Towns with a horde building (Griffin Bastion, Miner's Guild, Dendroid Saplings) showed one house too few.
- Some Castle towns got one house too many from a scenery slot of the town screen.
- A Castle with the Brotherhood of the Sword lost its tavern.
- A town standing on special ground
- Houses no longer stand straight behind each other with only their roofs showing.
- The mage guild no longer spills over its spot, and benches and trees keep clear of it at every level.
- Villages are ready when the game loads

### Note
- Villages in savegames from 1.3 are made again once when the save is loaded, so they may look a little different.

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
