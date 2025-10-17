---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/mpmm
- source/monster/cr/9
- source/monster/environment/urban
- source/monster/size/medium
- source/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Abjurer Wizard
---
# [Abjurer Wizard](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\humanoid/abjurer-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 260, Volo's Guide to Monsters p. 209*  

Abjurers specialize in creating protective magical wards. Monarchs, nobles, and other wealthy individuals commonly hire abjurers to provide protection.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Abjurer Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/mage-armor.md)"
"hp": !!int "104"
"hit_dice": "16d8 + 32"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "14"
  - !!int "18"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "8"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Arcana](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[History](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#History)"
    "desc": "+8"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "9"
"actions":
  - "desc": "The abjurer makes three Arcane Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +6 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 20 (3d10 + 4) force damage."
    "name": "Arcane Burst"
  - "desc": "Each creature in a 20-foot cube originating from the abjurer must make\
      \ a DC 16 Constitution saving throw. On a failed save, a creature takes 36 (8d8)\
      \ force damage and is pushed up to 10 feet away from the abjurer. On a successful\
      \ save, a creature takes half as much damage and isn't pushed."
    "name": "Force Blast"
  - "desc": "The abjurer casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 16):\n\n**At will:** [dancing lights](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/dancing-lights.md),\
      \ [mage hand](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/mage-hand.md),\
      \ [message](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/message.md),\
      \ [prestidigitation](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/prestidigitation.md)\n\
      \n**2/day each:** [dispel magic](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/dispel-magic.md),\
      \ [lightning bolt](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/lightning-bolt.md),\
      \ [mage armor](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/mage-armor.md)\n\
      \n**1/day each:** [arcane lock](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/arcane-lock.md),\
      \ [banishment](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/banishment.md),\
      \ [globe of invulnerability](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/globe-of-invulnerability.md),\
      \ [invisibility](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/invisibility.md),\
      \ [wall of force](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/wall-of-force.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "When the abjurer or a creature it can see within 30 feet of it takes\
      \ damage, the abjurer magically creates a protective barrier around itself or\
      \ the other creature. The barrier reduces the damage to the protected creature\
      \ by 26 (4d10 + 4), to a minimum of 0, and then vanishes."
    "name": "Arcane Ward (Recharge 4-6)"
"source":
  - "MPMM"
  - "VGM"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/token/abjurer-wizard-mpmm.webp"
```
^statblock

## Environment

urban