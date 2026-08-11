---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/tce
- source/monster/cr/
- source/monster/size/large
- source/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Celestial Spirit (Avenger)"
---
# [Celestial Spirit (Avenger)](Compendium/bestiary/celestial/celestial-spirit-avenger-tce.md)
*Source: Tasha's Cauldron of Everything p. 110*  

```statblock
"name": "Celestial Spirit (Avenger) (TCE)"
"size": "Large"
"type": "celestial"
"alignment": "Unaligned"
"ac_class": "11 + the level of the spell (natural armor)"
"hp": "40 + 10 for each spell level above 5th"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "16"
  - !!int "10"
  - !!int "14"
  - !!int "16"
"speed": "30 ft., fly 40 ft."
"damage_resistances": "radiant"
"condition_immunities": "[charmed](Rules/conditions.md#Charmed), [frightened](Rules/conditions.md#Frightened)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 12"
"languages": "Celestial, understands the languages you speak"
"actions":
  - "desc": "The celestial makes a number of attacks equal to half this spell's level\
      \ (rounded down)."
    "name": "Multiattack"
  - "desc": "*Ranged Weapon Attack:* your spell attack modifier to hit, range 150/600\
      \ ft., one target. *Hit:* 2d6 + 2 + the spell's level radiant damage."
    "name": "Radiant Bow"
  - "desc": "The celestial touches another creature. The target magically regains\
      \ hit points equal to 2d8 + the spell's level."
    "name": "Healing Touch (1/Day)"
"source":
  - "TCE"
```
^statblock