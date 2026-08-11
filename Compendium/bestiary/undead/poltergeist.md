---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mm
- source/monster/cr/2
- source/monster/environment/underdark
- source/monster/environment/urban
- source/monster/size/medium
- source/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Poltergeist"
---
# [Poltergeist](Compendium/bestiary/undead/poltergeist.md)
*Source: Monster Manual p. 279*  

A poltergeist is the confused, invisible spirit of an individual with no sense of how he or she died. A poltergeist expresses its rage by hurling creatures and objects using the power of its shattered psyche.

```statblock
"name": "Poltergeist"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "2"
"stats":
  - !!int "1"
  - !!int "14"
  - !!int "11"
  - !!int "10"
  - !!int "10"
  - !!int "11"
"speed": "0 ft., fly 50 ft. (hover)"
"damage_resistances": "acid; cold; fire; lightning; thunder; bludgeoning, piercing,\
  \ slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](Rules/conditions.md#Charmed), [exhaustion](Rules/conditions.md#Exhaustion),\
  \ [grappled](Rules/conditions.md#Grappled), [paralyzed](Rules/conditions.md#Paralyzed),\
  \ [petrified](Rules/conditions.md#Petrified), [poisoned](Rules/conditions.md#Poisoned),\
  \ [prone](Rules/conditions.md#Prone), [restrained](Rules/conditions.md#Restrained),\
  \ [unconscious](Rules/conditions.md#Unconscious)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 10"
"languages": "understands all languages it knew in life but can't speak"
"cr": "2"
"traits":
  - "desc": "The poltergeist can move through other creatures and objects as if they\
      \ were difficult terrain. It takes 5 (1d10) force damage if it ends its turn\
      \ inside an object."
    "name": "Incorporeal Movement"
  - "desc": "While in sunlight, the poltergeist has disadvantage on attack rolls,\
      \ as well as on Wisdom ([Perception](Rules/skills.md#Perception)) checks that\
      \ rely on sight."
    "name": "Sunlight Sensitivity"
  - "desc": "The poltergeist is [invisible](Rules/conditions.md#Invisible)."
    "name": "Invisibility"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:* 10\
      \ (3d6) force damage."
    "name": "Forceful Slam"
  - "desc": "The poltergeist targets a creature or unattended object within 30 feet\
      \ of it. A creature must be Medium or smaller to be affected by this magic,\
      \ and an object can weigh up to 150 pounds.\n\nIf the target is a creature,\
      \ the poltergeist makes a Charisma check contested by the target's Strength\
      \ check. If the poltergeist wins the contest, the poltergeist hurls the target\
      \ up to 30 feet in any direction, including upward. If the target then comes\
      \ into contact with a hard surface or heavy object, the target takes 1d6 damage\
      \ per 10 feet moved.\n\nIf the target is an object that isn't being worn or\
      \ carried, the poltergeist hurls it up to 30 feet in any direction. The poltergeist\
      \ can use the object as a ranged weapon, attacking one creature along the object's\
      \ path (+4 to hit) and dealing 5 (2d4) bludgeoning damage on a hit."
    "name": "Telekinetic Thrust"
"source":
  - "MM"
"image": "Compendium/bestiary/undead/token/poltergeist.webp"
```
^statblock

## Environment

underdark, urban