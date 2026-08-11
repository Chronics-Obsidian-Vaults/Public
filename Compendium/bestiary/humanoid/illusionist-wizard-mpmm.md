---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mpmm
- source/monster/cr/3
- source/monster/environment/urban
- source/monster/size/medium
- source/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Illusionist Wizard"
---
# [Illusionist Wizard](Compendium/bestiary/humanoid/illusionist-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 263, Volo's Guide to Monsters p. 214*  

Illusionists twist light, sound, and even thought to create illusory effects. Some illusionists are delightful entertainers, while others are devilish tricksters.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Illusionist Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Compendium/spells/mage-armor.md)"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "13"
  - !!int "16"
  - !!int "11"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "[Arcana](Rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[History](Rules/skills.md#History)"
    "desc": "+5"
"senses": "passive Perception 10"
"languages": "any four languages"
"cr": "3"
"actions":
  - "desc": "The illusionist makes two Arcane Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +5 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 14 (2d10 + 3) psychic damage."
    "name": "Arcane Burst"
  - "desc": "The illusionist casts one of the following spells, using Intelligence\
      \ as the spellcasting ability (spell save DC 13):\n\n**At will:** [dancing lights](Compendium/spells/dancing-lights.md),\
      \ [mage hand](Compendium/spells/mage-hand.md), [minor illusion](Compendium/spells/minor-illusion.md)\n\
      \n**2/day each:** [disguise self](Compendium/spells/disguise-self.md), [invisibility](Compendium/spells/invisibility.md),\
      \ [mage armor](Compendium/spells/mage-armor.md), [major image](Compendium/spells/major-image.md),\
      \ [phantasmal force](Compendium/spells/phantasmal-force.md), [phantom steed](Compendium/spells/phantom-steed.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The illusionist projects an illusion that makes the illusionist appear\
      \ to be standing in a place a few inches from its actual location, causing any\
      \ creature to have disadvantage on attack rolls against the illusionist. The\
      \ effect lasts for 1 minute, and it ends early if the illusionist takes damage,\
      \ if it is [incapacitated](Rules/conditions.md#Incapacitated), or if its speed\
      \ becomes 0."
    "name": "Displacement (Recharge 5-6)"
"source":
  - "MPMM"
  - "VGM"
"image": "Compendium/bestiary/humanoid/token/illusionist-wizard-mpmm.webp"
```
^statblock

## Environment

urban