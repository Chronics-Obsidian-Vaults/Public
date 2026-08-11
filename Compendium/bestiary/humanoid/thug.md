---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mm
- source/monster/cr/1-2
- source/monster/environment/urban
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Thug"
---
# [Thug](Compendium/bestiary/humanoid/thug.md)
*Source: Monster Manual p. 350. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Thugs are ruthless enforcers skilled at intimidation and violence. They work for money and have few scruples.

```statblock
"name": "Thug"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Good alignment"
"ac": !!int "11"
"ac_class": "[leather armor](Compendium/items/leather-armor.md)"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "11"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Intimidation](Rules/skills.md#Intimidation)"
    "desc": "+2"
"gear":
  - "[heavy crossbow](Compendium/items/heavy-crossbow.md)"
  - "[mace](Compendium/items/mace.md)"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "1/2"
"traits":
  - "desc": "The thug has advantage on an attack roll against a creature if at least\
      \ one of the thug's allies is within 5 feet of the creature and the ally isn't\
      \ [incapacitated](Rules/conditions.md#Incapacitated)."
    "name": "Pack Tactics"
"actions":
  - "desc": "The thug makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:* 5\
      \ (1d6 + 2) bludgeoning damage."
    "name": "Mace"
  - "desc": "*Ranged Weapon Attack:* +2 to hit, range 100/400 ft., one target. *Hit:*\
      \ 5 (1d10) piercing damage."
    "name": "Heavy Crossbow"
"source":
  - "MM"
"image": "Compendium/bestiary/humanoid/token/thug.webp"
```
^statblock

## Environment

urban