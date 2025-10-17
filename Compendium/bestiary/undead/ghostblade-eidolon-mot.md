---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/mot
- source/monster/cr/5
- source/monster/size/medium
- source/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ghostblade Eidolon
---
# [Ghostblade Eidolon](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\undead/ghostblade-eidolon-mot.md)
*Source: Mythic Odysseys of Theros p. 222*  

When a mortal soul traumatically sacrifices its identity in order to escape the Underworld as a Returned, its identity manifests as a spirit-like eidolon. While eidolons possess many of the skills and details related to their past lives, they're disconnected from those experiences, choosing to wander the world or brood in haunts they're drawn to in death. They care nothing for morbid reunions with their lost bodies or Returned remnants.

Of the various types of eidolons, ghostblade eidolons typically arise from fallen warriors and believe they're endlessly embroiled in great battles.

```statblock
"name": "Ghostblade Eidolon (MOT)"
"size": "Medium"
"type": "undead"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "55"
"hit_dice": "10d8 + 10"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "15"
  - !!int "12"
  - !!int "13"
  - !!int "12"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Acrobatics](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Acrobatics)"
    "desc": "+5"
  - "name": "[Athletics](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Athletics)"
    "desc": "+6"
  - "name": "[Perception](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Perception)"
    "desc": "+4"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Charmed),\
  \ [exhaustion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Exhaustion),\
  \ [frightened](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Frightened),\
  \ [grappled](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Grappled),\
  \ [paralyzed](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Paralyzed),\
  \ [petrified](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Petrified),\
  \ [poisoned](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Poisoned),\
  \ [restrained](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Restrained)"
"senses": "passive Perception 14"
"languages": "the languages it knew in life"
"cr": "5"
"traits":
  - "desc": "Attack rolls against the eidolon are made with disadvantage unless the\
      \ eidolon is [incapacitated](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Incapacitated)."
    "name": "Blurred Form"
  - "desc": "The eidolon can move through other creatures and objects as if they were\
      \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
      \ an object."
    "name": "Incorporeal Movement"
  - "desc": "The eidolon has advantage on saving throws against any effect that turns\
      \ undead."
    "name": "Turn Resistance"
"actions":
  - "desc": "The eidolon makes two ghostblade attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8\
      \ + 3) slashing damage plus 11 (2d10) force damage."
    "name": "Ghostblade"
"source":
  - "MOT"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/undead/token/ghostblade-eidolon-mot.webp"
```
^statblock