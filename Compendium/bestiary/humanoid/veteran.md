---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mm
- source/monster/cr/3
- source/monster/environment/arctic
- source/monster/environment/coastal
- source/monster/environment/forest
- source/monster/environment/grassland
- source/monster/environment/hill
- source/monster/environment/mountain
- source/monster/environment/underdark
- source/monster/environment/urban
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Veteran"
---
# [Veteran](Compendium/bestiary/humanoid/veteran.md)
*Source: Monster Manual p. 350. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Veterans are professional fighters that take up arms for pay or to protect something they believe in or value. Their ranks include soldiers retired from long service and warriors who never served anyone but themselves.

```statblock
"name": "Veteran"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "[splint armor](Compendium/items/splint-armor.md)"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "13"
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](Rules/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+2"
"gear":
  - "[heavy crossbow](Compendium/items/heavy-crossbow.md)"
  - "[longsword](Compendium/items/longsword.md)"
  - "[shortsword](Compendium/items/shortsword.md)"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "3"
"actions":
  - "desc": "The veteran makes two longsword attacks. If it has a shortsword drawn,\
      \ it can also make a shortsword attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
    "name": "Longsword"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6\
      \ + 3) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +3 to hit, range 100/400 ft., one target. *Hit:*\
      \ 6 (1d10 + 1) piercing damage."
    "name": "Heavy Crossbow"
"source":
  - "MM"
"image": "Compendium/bestiary/humanoid/token/veteran.webp"
```
^statblock

## Environment

coastal, mountain, grassland, hill, arctic, urban, forest, underdark