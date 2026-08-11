---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mpmm
- source/monster/cr/12
- source/monster/environment/coastal
- source/monster/environment/desert
- source/monster/environment/forest
- source/monster/environment/grassland
- source/monster/environment/mountain
- source/monster/environment/urban
- source/monster/size/medium
- source/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Eidolon"
---
# [Eidolon](Compendium/bestiary/undead/eidolon-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 114, Mordenkainen's Tome of Foes p. 194*  

To protect sites they deem holy, gods often rely on eidolons, ghostly spirits bound to safeguard a sacred place. Forged from the souls of those with unwavering devotion, eidolons stalk temples and vaults to ensure that no enemy defiles, damages, or plunders these sites. If an enemy sets foot inside a warded location, the [eidolon](Compendium/bestiary/undead/eidolon-mpmm.md) plunges into a [statue](Compendium/bestiary/construct/sacred-statue-mpmm.md) specially prepared to house its soul; it then animates this effigy and uses the statue to drive out the intruders.

```statblock
"name": "Eidolon (MPMM)"
"size": "Medium"
"type": "undead"
"alignment": "Any alignment"
"ac": !!int "9"
"hp": !!int "63"
"hit_dice": "18d8 - 18"
"modifier": !!int "-1"
"stats":
  - !!int "7"
  - !!int "8"
  - !!int "9"
  - !!int "14"
  - !!int "19"
  - !!int "16"
"speed": "0 ft., fly 40 ft. (hover)"
"saves":
  - "wisdom": !!int "8"
"skillsaves":
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+8"
"damage_resistances": "acid; fire; lightning; thunder; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[charmed](Rules/conditions.md#Charmed), [exhaustion](Rules/conditions.md#Exhaustion),\
  \ [frightened](Rules/conditions.md#Frightened), [grappled](Rules/conditions.md#Grappled),\
  \ [paralyzed](Rules/conditions.md#Paralyzed), [petrified](Rules/conditions.md#Petrified),\
  \ [poisoned](Rules/conditions.md#Poisoned), [prone](Rules/conditions.md#Prone),\
  \ [restrained](Rules/conditions.md#Restrained)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 18"
"languages": "the languages it knew in life"
"cr": "12"
"traits":
  - "desc": "The eidolon can move through other creatures and objects as if they were\
      \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
      \ an object other than a [sacred statue](Compendium/bestiary/construct/sacred-statue-mpmm.md)."
    "name": "Incorporeal Movement"
  - "desc": "When the eidolon moves into a space occupied by a [sacred statue](Compendium/bestiary/construct/sacred-statue-mpmm.md),\
      \ the eidolon can disappear, causing the statue to become a creature under the\
      \ eidolon's control. The eidolon uses the [sacred statue's stat block](Compendium/bestiary/construct/sacred-statue-mpmm.md)\
      \ in place of its own."
    "name": "Sacred Animation (Recharge 5-6)"
  - "desc": "The eidolon has advantage on saving throws against any effect that turns\
      \ Undead."
    "name": "Turn Resistance"
  - "desc": "The eidolon doesn't require air, food, drink, or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "Each creature within 60 feet of the eidolon that can see it must succeed\
      \ on a DC 15 Wisdom saving throw or be [frightened](Rules/conditions.md#Frightened)\
      \ of it for 1 minute. While [frightened](Rules/conditions.md#Frightened) in\
      \ this way, the creature must take the [Dash](Rules/actions.md#Dash) action\
      \ and move away from the eidolon by the safest available route at the start\
      \ of each of its turns, unless there is nowhere for it to move, in which case\
      \ the creature also becomes [stunned](Rules/conditions.md#Stunned) until it\
      \ can move again. A [frightened](Rules/conditions.md#Frightened) target can\
      \ repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success. If a target's saving throw is successful or the effect\
      \ ends for it, the target is immune to any eidolon's Divine Dread for the next\
      \ 24 hours."
    "name": "Divine Dread"
"source":
  - "MPMM"
  - "MTF"
"image": "Compendium/bestiary/undead/token/eidolon-mpmm.webp"
```
^statblock

## Environment

coastal, desert, forest, grassland, mountain, urban