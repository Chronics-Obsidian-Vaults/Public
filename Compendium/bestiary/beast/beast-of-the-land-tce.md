---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/tce
- source/monster/cr/
- source/monster/size/medium
- source/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Beast of the Land"
---
# [Beast of the Land](Compendium/bestiary/beast/beast-of-the-land-tce.md)
*Source: Tasha's Cauldron of Everything p. 61*  

```statblock
"name": "Beast of the Land (TCE)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac_class": "13 + PB (natural armor)"
"hp": "5 + five times your ranger level (the beast has a number of Hit Dice [d8s]\
  \ equal to your ranger level)"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "14"
  - !!int "15"
  - !!int "8"
  - !!int "14"
  - !!int "11"
"speed": "40 ft., climb 40 ft."
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 12"
"languages": "understands the languages you speak"
"traits":
  - "desc": "If the beast moves at least 20 feet straight toward a target and then\
      \ hits it with a maul attack on the same turn, the target takes an extra 1d6\
      \ slashing damage. If the target is a creature, it must succeed on a Strength\
      \ saving throw against your spell save DC or be knocked [prone](Rules/conditions.md#Prone)."
    "name": "Charge"
  - "desc": "You can add your proficiency bonus to any ability check or saving throw\
      \ that the beast makes."
    "name": "Primal Bond"
"actions":
  - "desc": "*Melee Weapon Attack:* your spell attack modifier to hit, reach 5 ft.,\
      \ one target. *Hit:* 1d8 + 2 + PB slashing damage."
    "name": "Maul"
"source":
  - "TCE"
"image": "Compendium/bestiary/beast/token/beast-of-the-land-tce.webp"
```
^statblock