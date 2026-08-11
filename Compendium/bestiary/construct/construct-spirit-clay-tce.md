---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/tce
- source/monster/cr/
- source/monster/size/medium
- source/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Construct Spirit (Clay)"
---
# [Construct Spirit (Clay)](Compendium/bestiary/construct/construct-spirit-clay-tce.md)
*Source: Tasha's Cauldron of Everything p. 111*  

```statblock
"name": "Construct Spirit (Clay) (TCE)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac_class": "13 + the level of the spell (natural armor)"
"hp": "40 + 15 for each spell level above 4th"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "18"
  - !!int "14"
  - !!int "11"
  - !!int "5"
"speed": "30 ft."
"damage_resistances": "poison"
"condition_immunities": "[charmed](Rules/conditions.md#Charmed), [exhaustion](Rules/conditions.md#Exhaustion),\
  \ [frightened](Rules/conditions.md#Frightened), [incapacitated](Rules/conditions.md#Incapacitated),\
  \ [paralyzed](Rules/conditions.md#Paralyzed), [petrified](Rules/conditions.md#Petrified),\
  \ [poisoned](Rules/conditions.md#Poisoned)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 10"
"languages": "understands the languages you speak"
"actions":
  - "desc": "The construct makes a number of attacks equal to half this spell's level\
      \ (rounded down)."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* your spell attack modifier to hit, reach 5 ft.,\
      \ one target. *Hit:* 1d8 + 4 + the spell's level bludgeoning damage."
    "name": "Slam"
"reactions":
  - "desc": "When the construct takes damage, it makes a slam attack against a random\
      \ creature within 5 feet of it. If no creature is within reach, the construct\
      \ moves up to half its speed toward an enemy it can see, without provoking opportunity\
      \ attacks."
    "name": "Berserk Lashing"
"source":
  - "TCE"
```
^statblock