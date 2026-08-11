---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/efa
- source/monster/cr/3
- source/monster/size/small
- source/monster/type/humanoid/halfling
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ghallanda Troubleshooter"
---
# [Ghallanda Troubleshooter](Compendium/bestiary/humanoid/ghallanda-troubleshooter-efa.md)
*Source: Eberron: Forge of the Artificer p. 80*  

The inns of House Ghallanda are meant to be places of safe refuge and quiet rest, so the house employs troubleshooters (mostly halflings) to protect the safety and serenity of its guests.

```statblock
"name": "Ghallanda Troubleshooter (EFA)"
"size": "Small"
"type": "humanoid"
"subtype": "halfling"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "78"
"hit_dice": "12d6 + 36"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "17"
  - !!int "13"
  - !!int "14"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "5"
  - "wisdom": !!int "4"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Insight](Rules/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](Rules/skills.md#Stealth)"
    "desc": "+5"
"condition_immunities": "[frightened](Rules/conditions.md#Frightened)"
"gear":
  - "six daggers"
  - "leather armor"
"senses": "passive Perception 14"
"languages": "Common, Halfling"
"cr": "3"
"traits":
  - "desc": "The troubleshooter can move through the space of any creature that is\
      \ of a larger size, but it can't stop there."
    "name": "Hustle"
"actions":
  - "desc": "The troubleshooter makes two Poisoned Dagger attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +5, reach 5 ft. or range 20/60 ft. *Hit:*\
      \ 5 (1d4 + 3) Piercing damage, and the target has the Poisoned condition until\
      \ the start of the troubleshooter's next turn."
    "name": "Poisoned Dagger"
  - "desc": "The troubleshooter casts one of the following spells, requiring no Material\
      \ components and using Charisma as the spellcasting ability (spell save DC 13):\n\
      \n**1/day each:** Sleep, Unseen Servant"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The troubleshooter takes the Disengage or Hide action."
    "name": "Nimble Escape"
"source":
  - "EFA"
"image": "Compendium/bestiary/humanoid/token/ghallanda-troubleshooter-efa.webp"
```
^statblock