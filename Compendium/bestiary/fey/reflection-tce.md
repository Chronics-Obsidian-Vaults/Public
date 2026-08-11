---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/tce
- source/monster/cr/1-2
- source/monster/size/medium
- source/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Reflection"
---
# [Reflection](Compendium/bestiary/fey/reflection-tce.md)
*Source: Tasha's Cauldron of Everything p. 158*  

```statblock
"name": "Reflection (TCE)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "14"
  - !!int "13"
  - !!int "6"
  - !!int "10"
  - !!int "8"
"speed": "40 ft."
"skillsaves":
  - "name": "[Stealth](Rules/skills.md#Stealth)"
    "desc": "+4"
"damage_vulnerabilities": "bludgeoning"
"damage_resistances": "acid; cold; fire; lightning; thunder; piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](Rules/conditions.md#Exhaustion), [frightened](Rules/conditions.md#Frightened),\
  \ [grappled](Rules/conditions.md#Grappled), [paralyzed](Rules/conditions.md#Paralyzed),\
  \ [petrified](Rules/conditions.md#Petrified), [poisoned](Rules/conditions.md#Poisoned),\
  \ [prone](Rules/conditions.md#Prone), [restrained](Rules/conditions.md#Restrained)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 10"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "The reflection can move through a space as narrow as 1 inch wide without\
      \ squeezing."
    "name": "Amorphous"
  - "desc": "While in dim light or darkness, the reflection can take the [Hide](Rules/actions.md#Hide)\
      \ action as a bonus action. Its stealth bonus is also improved to +6."
    "name": "Shadow Stealth"
  - "desc": "While in sunlight, the reflection has disadvantage on attack rolls, ability\
      \ checks, and saving throws."
    "name": "Sunlight Weakness"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:* 9\
      \ (2d6 + 2) necrotic damage, and the target's Strength score is reduced by 1d4.\
      \ The target dies if this reduces its Strength to 0. Otherwise, the reduction\
      \ lasts until the target finishes a short or long rest.\n\nIf a non-evil humanoid\
      \ dies from this attack, a new reflection rises from the corpse 1d4 hours later."
    "name": "Strength Drain"
"source":
  - "TCE"
"image": "Compendium/bestiary/fey/token/reflection-tce.webp"
```
^statblock