---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/mpmm
- source/monster/cr/5
- source/monster/environment/urban
- source/monster/size/medium
- source/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Enchanter Wizard
---
# [Enchanter Wizard](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\humanoid/enchanter-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 261, Volo's Guide to Monsters p. 213*  

Enchanters know how to magically influence minds. Benign enchanters use this magic to defuse violence and sow peace, while malevolent enchanters are some of the most evil of all spellcasters.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Enchanter Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/mage-armor.md)"
"hp": !!int "49"
"hit_dice": "11d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Arcana](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[History](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#History)"
    "desc": "+6"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "5"
"actions":
  - "desc": "The enchanter makes three Arcane Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +6 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 19 (3d10 + 3) psychic damage."
    "name": "Arcane Burst"
  - "desc": "The enchanter casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 14):\n\n**At will:** [friends](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/friends.md),\
      \ [mage hand](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/mage-hand.md),\
      \ [message](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/message.md)\n\
      \n**2/day each:** [charm person](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/charm-person.md),\
      \ [mage armor](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/mage-armor.md),\
      \ [hold person](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/hold-person.md),\
      \ [invisibility](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/invisibility.md),\
      \ [suggestion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/suggestion.md),\
      \ [tongues](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/tongues.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "When a visible creature within 30 feet of the enchanter makes an attack\
      \ roll against it, the enchanter forces the attacker to make a DC 14 Wisdom\
      \ saving throw. On a failed save, the attacker redirects the attack roll to\
      \ the creature closest to it, other than the enchanter or itself. If multiple\
      \ eligible creatures are closest, the attacker chooses which one to target."
    "name": "Instinctive Charm (Recharge 4-6)"
"source":
  - "MPMM"
  - "VGM"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/token/enchanter-wizard-mpmm.webp"
```
^statblock

## Environment

urban