---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mpmm
- source/monster/cr/4
- source/monster/environment/arctic
- source/monster/environment/forest
- source/monster/environment/mountain
- source/monster/environment/swamp
- source/monster/environment/urban
- source/monster/size/medium
- source/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Warlock of the Archfey"
---
# [Warlock of the Archfey](Compendium/bestiary/humanoid/warlock-of-the-archfey-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 255, Volo's Guide to Monsters p. 219*  

Warlocks of the Archfey gain their powers through magical pacts forged with lords of the Feywild. These warlocks commonly associate with lesser Fey creatures such as [boggles](Compendium/bestiary/fey/boggle-mpmm.md), [quicklings](Compendium/bestiary/fey/quickling-mpmm.md), and [redcaps](Compendium/bestiary/fey/redcap-mpmm.md) (all appear in "this book") or even [satyrs](Compendium/bestiary/fey/satyr.md) and [sprites](Compendium/bestiary/fey/sprite.md).

## Warlocks

Warlocks gain arcane might through magical pacts with mysterious entities. While some use their abilities to serve the sources of their power, others use them to undermine or even destroy these entities.

```statblock
"name": "Warlock of the Archfey (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "16 with [mage armor](Compendium/spells/mage-armor.md)"
"hp": !!int "67"
"hit_dice": "15d8"
"modifier": !!int "3"
"stats":
  - !!int "9"
  - !!int "16"
  - !!int "11"
  - !!int "11"
  - !!int "12"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "3"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Arcana](Rules/skills.md#Arcana)"
    "desc": "+2"
  - "name": "[Deception](Rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Nature](Rules/skills.md#Nature)"
    "desc": "+2"
  - "name": "[Persuasion](Rules/skills.md#Persuasion)"
    "desc": "+6"
"condition_immunities": "[charmed](Rules/conditions.md#Charmed)"
"gear":
  - "[rapier](Compendium/items/rapier.md)"
"senses": "passive Perception 11"
"languages": "any two languages (usually Sylvan)"
"cr": "4"
"actions":
  - "desc": "The warlock makes two Rapier attacks, or it uses Bewildering Word twice."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) piercing damage plus 7 (2d6) force damage."
    "name": "Rapier"
  - "desc": "The warlock utters a magical bewilderment, targeting one creature it\
      \ can see within 60 feet of it. The target must succeed on a DC 14 Wisdom saving\
      \ throw or take 9 (2d8) psychic damage and have disadvantage on attack rolls\
      \ until the end of the warlock's next turn."
    "name": "Bewildering Word"
  - "desc": "The warlock casts one of the following spells, using Charisma as the\
      \ spellcasting ability (spell save DC 14): \n\n**At will:** [dancing lights](Compendium/spells/dancing-lights.md),\
      \ [disguise self](Compendium/spells/disguise-self.md), [mage armor](Compendium/spells/mage-armor.md)\
      \ (self only), [mage hand](Compendium/spells/mage-hand.md), [minor illusion](Compendium/spells/minor-illusion.md),\
      \ [prestidigitation](Compendium/spells/prestidigitation.md), [speak with animals](Compendium/spells/speak-with-animals.md)\n\
      \n**1/day each:** [charm person](Compendium/spells/charm-person.md), [dimension\
      \ door](Compendium/spells/dimension-door.md), [hold monster](Compendium/spells/hold-monster.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "In response to taking damage, the warlock turns [invisible](Rules/conditions.md#Invisible)\
      \ and teleports, along with any equipment it is wearing or carrying, up to 60\
      \ feet to an unoccupied space it can see. It remains [invisible](Rules/conditions.md#Invisible)\
      \ until the start of its next turn or until it attacks, makes a damage roll,\
      \ or casts a spell."
    "name": "Misty Escape (Recharges after a Short or Long Rest)"
"source":
  - "MPMM"
  - "VGM"
"image": "Compendium/bestiary/humanoid/token/warlock-of-the-archfey-mpmm.webp"
```
^statblock

## Environment

arctic, forest, mountain, swamp, urban