---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mm
- source/monster/cr/1-4
- source/monster/environment/urban
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Acolyte"
---
# [Acolyte](Compendium/bestiary/humanoid/acolyte.md)
*Source: Monster Manual p. 342. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Acolytes are junior members of a clergy, usually answerable to a priest. They perform a variety of functions in a temple and are granted minor spellcasting power by their deities.

```statblock
"name": "Acolyte"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "10"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "14"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](Rules/skills.md#Medicine)"
    "desc": "+4"
  - "name": "[Religion](Rules/skills.md#Religion)"
    "desc": "+2"
"gear":
  - "[club](Compendium/items/club.md)"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "1/4"
"traits":
  - "desc": "The acolyte is a 1st-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 12, +4 to hit with spell attacks). The acolyte has the following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** [light](Compendium/spells/light.md),\
      \ [sacred flame](Compendium/spells/sacred-flame.md), [thaumaturgy](Compendium/spells/thaumaturgy.md)\n\
      \n**1st level (3 slots):** [bless](Compendium/spells/bless.md), [cure wounds](Compendium/spells/cure-wounds.md),\
      \ [sanctuary](Compendium/spells/sanctuary.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4)\
      \ bludgeoning damage."
    "name": "Club"
"source":
  - "MM"
"image": "Compendium/bestiary/humanoid/token/acolyte.webp"
```
^statblock

## Environment

urban