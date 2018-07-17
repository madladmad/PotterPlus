# Changelog

Changes are organized here for record-keeping purposes. Changes are organized from top to bottom by order of most to least recent.

There is a relatively up-to-date and accurate roadmap and list of upcoming changes in the document [here](https://github.com/grisstyl/BetterPotter/blob/master/README.md).

There is a list of current, known issues [here](https://github.com/grisstyl/BetterPotter/issues).

This is not an absolute record of *every* change that happens, just ones that are user-facing or significant under the hood. Click [here](https://github.com/grisstyl/BetterPotter/commits/master) for the absolute list.

### 7/17/18

* Buffed Verdimillious and followed Vermillious
* Buffed Vermillious
* Buffed Multa Basorium

### 7/16/18

* Nerfed Everte Statum
* Re-worked Furnunculus with new icon, effects, levels
* Re-balanced Incendio with new levels
* Fixed slowness on a bunch of spells
* Added slowness to Scribblifors
* Added slowness to Flintifors
* Added more depth to the leveling of Homenum Revelio

### 5/16/18

* Added Basic Blaze Box and Deflagration Deluxe

### 5/13/18

* Overhauled Salvio Hexia with new levels and stats.
* Nerfed Expulso and spread it out across more levels.

### 5/12/18

* Buffed Homenum Revelio across multiple levels
* Buffed Percutios and split it into more levels
* Updated Carpe Retractum with new level and balance
* Re-worked Immobulus leveling
* Re-worked Rictusempra leveling
* Re-worked Herbifors leveling
* Re-worked Herbifors leveling
* Re-worked Waddiwasi leveling
* Re-worked Epoximise leveling
* Re-worked Lumos Maxima leveling
* Fixed progression on Flagrate
* Re-worked Vermillious leveling
* Re-worked Ascendio
* Overhauled spell and wand looks
* Fixed broken potion effects
* Added Godric Gryffindor's Sword
* Added more levels to Aguamenti
* Added Peruvian Instant Darkness Powder

### 5/11/18

* Added back Firebolt and Nimbus brooms
* Buffed and added leveling to Scribblifors and Flintifors
* Converted all upgrade messages to new multi-line format
* Re-worked Bubblehead Charm with leveling and nerf
* Added Ignis Disceditus leveling
* Added Bewitched Snowball leveling
* Fixed Lumos leveling

### 5/10/18

* Nerfed Arania Exumai
* Changed `flagrate|2` to be more visible
* PVP restricted spells that should be PVP restricted
* Fix Conductor's Wand inheritance
* Added Trick Wands
* Added Overgrown Bowtruckle

### 5/9/18

* Added Key and Skeleton Key items
* Added spawners for Erklings, Bowtruckles, and Centaurs
* Added AC drops to some Magic Mobs
* Re-worked Flagellos
* Re-worked Alohomora and Aberto
* Added Portable Swamps
* Converted to use custom currency system
* Removed all custom messages in preparation for overhaul
* Revamped Aparecium
* Added Ashwinder spawners
* Restructured spawner automata
* Added Erumpent spawners
* Buffed Erumpent

### 5/6/18

* Converted all spells spells that used long-form class references to use short-hands. (ex. `AtomEffect` -> `Atom` or `CustomProjectileAction` -> `CustomProjectile`)

### 5/5/18

* Converted all `PotionEffectAction` spells to not use aggregate format
* Re-balanced and nerfed Protego
* Overhauled `frigusignatus`, the Flame-Freezing Charm particles and buffed it
* Fixed Crucio particles from Magic update
* Nerfed and overhauled Avada Kedavra
* Buffed and fixed Gillyweed messages
* Fixed Expelliarmus colors
* Fixed passthrough for Expelliarmus and made `hit_entity` apply on hitting anything
* Changed Atmos and Meteolojinx Recanto messages to be less verbose
* Re-worked Lumos, Lumos Maxima, and Lumos Solem
* Added spawner automata

### 5/4/18

* Removed `not_canon` folder
* Moved Avis and Lapifors to action system and used new `undo_entity` effects
* Updated Periculum colors to be lore-accurate, added EffectRing to periculum|3
* Fixed base wands starting with Vermillious due to classes

### 5/3/18

* Added license.md
* Shifted material lists from `materials.yml` to use `/materials/`
* Re-organized the `/wands/` folder to negate the need for a `wands.yml` file
* Disabled a bunch of wands that are unnecessary for this configuration and created a list of those to overhaul (`/wands/to_redo.yml`)