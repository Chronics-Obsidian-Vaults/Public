---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/tdcsr
- source/monster/cr/3
- source/monster/size/medium
- source/monster/type/humanoid/dwarf
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kraghammer Goat-Knight
---
# [Kraghammer Goat-Knight](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\humanoid/kraghammer-goat-knight-tdcsr.md)
*Source: Tal'Dorei Campaign Setting Reborn p. 246*  

The sheer cliff faces and winding mountainside roads of the "Cliffkeep Mountains" are nearly impossible to traverse by normal means with any speed. The Peakclimber Knights of "Kraghammer"—commonly known as the [goat-knights](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/kraghammer-goat-knight-tdcsr.md)—are the enforcers of peace and justice across the mountain range. They trust their [giant goat steeds](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/celestial/goat-knight-steed-tdcsr.md) to master the harsh mountain slopes, and many travelers lost within the "Cliffkeep Mountains" have been saved by a [goat-knight](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/kraghammer-goat-knight-tdcsr.md) who led them to safety along the more traversable mountain paths.

These knights serve the [All-Hammer](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/deities/exandria-the-all-hammer-tdcsr.md) and sometimes find themselves at odds while enforcing the laws of "Kraghammer" and upholding the edicts of their god.

## Mounted Combatant

Any spell the [goat-knight](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/kraghammer-goat-knight-tdcsr.md) casts with a range of self also targets the goat.

When a [Goat-Knight Steed](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/celestial/goat-knight-steed-tdcsr.md) drops to 0 hit points, it disappears, leaving behind no physical form. The [goat-knight](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/kraghammer-goat-knight-tdcsr.md) can also dismiss the steed at any time as an action, causing it to disappear. In either case, the same steed is summoned when the [goat-knight](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/kraghammer-goat-knight-tdcsr.md) casts [find steed](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/find-steed.md).

```statblock
"name": "Kraghammer Goat-Knight (TDCSR)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "[plate](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/items/plate-armor.md),\
  \ [shield](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/items/shield.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "-1"
"stats":
  - !!int "17"
  - !!int "8"
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "16"
"speed": "25 ft."
"saves":
  - "strength": !!int "5"
  - "dexterity": !!int "1"
  - "constitution": !!int "4"
  - "intelligence": !!int "2"
  - "wisdom": !!int "2"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Nature](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Nature)"
    "desc": "+2"
  - "name": "[Religion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Religion)"
    "desc": "+4"
"damage_resistances": "poison"
"condition_immunities": "disease"
"senses": "[darkvision](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 10"
"languages": "Common, Dwarvish"
"cr": "3"
"traits":
  - "desc": "The goat-knight is a 6th-level spellcaster. Its spellcasting ability\
      \ is Charisma (spell save DC 13, +5 to hit with spell attacks). It has the following\
      \ paladin spells prepared:\n\n**1st level (4 slots):** [bless](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/bless.md),\
      \ [cure wounds](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/cure-wounds.md),\
      \ [protection from evil and good](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/protection-from-evil-and-good.md),\
      \ [sanctuary](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/sanctuary.md),\
      \ [shield of faith](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/shield-of-faith.md)\n\
      \n**2nd level (2 slots):** [branding smite](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/branding-smite.md),\
      \ [find steed](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/find-steed.md)\
      \ ([Goat-Knight Steed](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/celestial/goat-knight-steed-tdcsr.md)\
      \ only), [lesser restoration](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/lesser-restoration.md),\
      \ [zone of truth](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/zone-of-truth.md)"
    "name": "Spellcasting"
  - "desc": "Whenever the goat-knight or a creature friendly to it within 10 feet\
      \ of it makes a saving throw, that creature gains a +2 bonus (included in the\
      \ goat-knight's saving throws above). The goat-knight must be conscious to grant\
      \ and gain this bonus."
    "name": "Aura of Protection"
  - "desc": "The goat-knight is immune to disease."
    "name": "Divine Health"
  - "desc": "The goat-knight has resistance to poison damage and advantage on saving\
      \ throws against poison."
    "name": "Dwarven Resilience"
"actions":
  - "desc": "The goat-knight makes two warhammer attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) bludgeoning damage, or 8 (1d10 + 3) bludgeoning damage if used with two\
      \ hands."
    "name": "Warhammer"
"source":
  - "TDCSR"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/token/kraghammer-goat-knight-tdcsr.webp"
```
^statblock