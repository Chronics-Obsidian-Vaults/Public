---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mpmm
- source/monster/cr/1-4
- source/monster/environment/urban
- source/monster/size/medium
- source/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Apprentice Wizard"
---
# [Apprentice Wizard](Compendium/bestiary/humanoid/apprentice-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 259, Volo's Guide to Monsters p. 209*  

Apprentices are novice arcane spellcasters who serve more experienced wizards or attend school. They perform menial work like cooking or cleaning in exchange for education in the ways of magic.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Apprentice Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "10"
"ac_class": "13 with [mage armor](Compendium/spells/mage-armor.md)"
"hp": !!int "13"
"hit_dice": "3d8"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](Rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[History](Rules/skills.md#History)"
    "desc": "+4"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "1/4"
"actions":
  - "desc": "*Melee  or Ranged Spell Attack:* +4 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 7 (1d10 + 2) force damage."
    "name": "Arcane Burst"
  - "desc": "The apprentice casts one of the following spells, using Intelligence\
      \ as the spellcasting ability (spell save DC 12)\n\n**At will:** [mage hand](Compendium/spells/mage-hand.md),\
      \ [prestidigitation](Compendium/spells/prestidigitation.md)\n\n**1/day each:**\
      \ [burning hands](Compendium/spells/burning-hands.md), [disguise self](Compendium/spells/disguise-self.md),\
      \ [mage armor](Compendium/spells/mage-armor.md)"
    "name": "Spellcasting"
"source":
  - "MPMM"
  - "VGM"
"image": "Compendium/bestiary/humanoid/token/apprentice-wizard-mpmm.webp"
```
^statblock

## Environment

urban