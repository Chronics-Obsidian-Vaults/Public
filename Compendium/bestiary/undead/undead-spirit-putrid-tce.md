---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/tce
- source/monster/cr/
- source/monster/size/medium
- source/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Undead Spirit (Putrid)"
---
# [Undead Spirit (Putrid)](Compendium/bestiary/undead/undead-spirit-putrid-tce.md)
*Source: Tasha's Cauldron of Everything p. 114*  

```statblock
"name": "Undead Spirit (Putrid) (TCE)"
"size": "Medium"
"type": "undead"
"alignment": "Unaligned"
"ac_class": "11 + the level of the spell (natural armor)"
"hp": "30 + 10 for each spell level above 3rd"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "15"
  - !!int "4"
  - !!int "10"
  - !!int "9"
"speed": "30 ft."
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](Rules/conditions.md#Exhaustion), [frightened](Rules/conditions.md#Frightened),\
  \ [paralyzed](Rules/conditions.md#Paralyzed), [poisoned](Rules/conditions.md#Poisoned)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 10"
"languages": "understands the languages you speak"
"traits":
  - "desc": "Any creature, other than you, that starts its turn within 5 feet of the\
      \ spirit must succeed on a Constitution saving throw against your spell save\
      \ DC or be [poisoned](Rules/conditions.md#Poisoned) until the start of its next\
      \ turn."
    "name": "Festering Aura"
"actions":
  - "desc": "The spirit makes a number of attacks equal to half this spell's level\
      \ (rounded down)."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* your spell attack modifier to hit, reach 5 ft.,\
      \ one target. *Hit:* 1d6 + 3 + the spell's level slashing damage. If the target\
      \ is [poisoned](Rules/conditions.md#Poisoned), it must succeed on a Constitution\
      \ saving throw against your spell save DC or be [paralyzed](Rules/conditions.md#Paralyzed)\
      \ until the end of its next turn."
    "name": "Rotting Claw"
"source":
  - "TCE"
```
^statblock