---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/10
- source/monster/size/large
- source/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cyclops Stormcaller"
---
# [Cyclops Stormcaller](Compendium/bestiary/giant/cyclops-stormcaller-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 132*  

When a cyclops is born beneath a raging storm, the child is sometimes born different. Smaller than the rest, sickly and weak. Most of these stormborn cyclopes are relentlessly bullied and beaten for their tiny stature, and most die before adulthood. Those who survive do so because of the magic the Stormlord has bestowed upon them intentionally or otherwise. As cyclopes are a simple-minded and magically-inert people, the power of a stormcaller awes and terrifies them. They believe that a stormcaller is nothing short of a god.

As of late, a cabal of stormcallers have gathered in the Daggerbay Mountains at a time-lost elven temple called the Skyneedle; in elven, ira' fallai, in cyclops, "Tall Zappo- Zappo." There they conduct strange rituals beseeching an entity called the Eye of the Storm, and with every ritual, their power seems to grow.

## Notorious Stormcallers

Efficient raiders and powerful leaders, stormcallers are dangerous enough on their own that several legends of them are told and retold along caravan routes and by any forced to venture too closely to cyclops territory. Some of them are:

### The Eye of the Storm

More legend than rumor, the Eye of the Storm is said to be a truly ancient cyclops stormcaller, the first of their kind. It is said that she gave over her only eye for the power of the storm, and now anywhere a storm brews, she can watch the devastation as though the center of that storm were her very own eye.

### Oluk Wagonsbane

A raider infamous for ambushing caravans and stealing their wealth, Oluk commands a force of other cyclops. His warriors are fanatical in their devotion to him, revering his power and deeds. Each of his followers bears the distinctive scar from a lightning strike, and they proudly show off their scars.

### Elikka of Stormpeak

Hidden away in some mountain range, Elikka is an oddity among her people: a historian. It is said that her lair holds documents and other treatises on the origins of the cyclops folk, and that she helps new stormcallers come into their power in exchange for keeping her updated on what goes on in their tribes and bands.

```statblock
"name": "Cyclops Stormcaller (TalDorei)"
"size": "Large"
"type": "giant"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "[chain mail](Compendium/items/chain-mail.md), [ring of protection](Compendium/items/ring-of-protection.md),\
  \ [cloak of protection](Compendium/items/cloak-of-protection.md)"
"hp": !!int "119"
"hit_dice": "12d10 + 48"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "18"
  - !!int "15"
  - !!int "8"
  - !!int "20"
"speed": "30 ft., fly 60 ft. (storm only)"
"saves":
  - "strength": !!int "4"
  - "dexterity": !!int "1"
  - "constitution": !!int "5"
  - "wisdom": !!int "4"
  - "charisma": !!int "10"
  - "intelligence": !!int "0"
"skillsaves":
  - "name": "[Arcana](Rules/skills.md#Arcana)"
    "desc": "+6"
"senses": "passive Perception 9"
"languages": "Common, Elvish, Giant"
"cr": "10"
"traits":
  - "desc": "The cyclops's innate spellcasting ability is Charisma (spell save DC\
      \ 17). The cyclops can innately cast the following spells, requiring no material\
      \ components:\n\n**At will:** [ray of frost](Compendium/spells/ray-of-frost.md)\
      \ (3d8), [water walk](Compendium/spells/water-walk.md)\n\n**3/day each:** [ice\
      \ storm](Compendium/spells/ice-storm.md), [sleet storm](Compendium/spells/sleet-storm.md),\
      \ [wind wall](Compendium/spells/wind-wall.md)\n\n**1/day each:** [control weather](Compendium/spells/control-weather.md),\
      \ [storm of vengeance](Compendium/spells/storm-of-vengeance.md)"
    "name": "Innate Spellcasting"
  - "desc": "The cyclops has disadvantage on any attack roll against a target more\
      \ than 30 ft. away."
    "name": "Poor Depth Perception"
  - "desc": "While within 1 mile of a storm, the cyclops gains a fly speed of 60 feet."
    "name": "Storm Wings"
  - "desc": "The cyclops has advantage on Constitution saving throws made to maintain\
      \ concentration on a spell, and cannot lose concentration because of turbulent\
      \ weather."
    "name": "Supernatural Focus"
"actions":
  - "desc": "The cyclops makes two ice claws attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (3d6 + 3) slashing damage plus 3 (1d6) cold damage."
    "name": "Ice Claws"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Cyclops_Stormcaller.png"
```
^statblock