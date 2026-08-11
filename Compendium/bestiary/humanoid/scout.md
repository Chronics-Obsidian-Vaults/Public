---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mm
- source/monster/cr/1-2
- source/monster/environment/arctic
- source/monster/environment/coastal
- source/monster/environment/desert
- source/monster/environment/forest
- source/monster/environment/grassland
- source/monster/environment/hill
- source/monster/environment/mountain
- source/monster/environment/swamp
- source/monster/environment/underdark
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Scout"
---
# [Scout](Compendium/bestiary/humanoid/scout.md)
*Source: Monster Manual p. 349. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Scouts are skilled hunters and trackers who offer their services for a fee. Most hunt wild game, but a few work as bounty hunters, serve as guides, or provide military reconnaissance.

```statblock
"name": "Scout"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[leather armor](Compendium/items/leather-armor.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "11"
  - !!int "13"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Nature](Rules/skills.md#Nature)"
    "desc": "+4"
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](Rules/skills.md#Stealth)"
    "desc": "+6"
  - "name": "[Survival](Rules/skills.md#Survival)"
    "desc": "+5"
"gear":
  - "[longbow](Compendium/items/longbow.md)"
  - "[shortsword](Compendium/items/shortsword.md)"
"senses": "passive Perception 15"
"languages": "any one language (usually Common)"
"cr": "1/2"
"traits":
  - "desc": "The scout has advantage on Wisdom ([Perception](Rules/skills.md#Perception))\
      \ checks that rely on hearing or sight."
    "name": "Keen Hearing and Sight"
"actions":
  - "desc": "The scout makes two melee attacks or two ranged attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, ranged 150/600 ft., one target. *Hit:*\
      \ 6 (1d8 + 2) piercing damage."
    "name": "Longbow"
"source":
  - "MM"
"image": "Compendium/bestiary/humanoid/token/scout.webp"
```
^statblock

## Environment

coastal, mountain, grassland, hill, arctic, forest, swamp, underdark, desert