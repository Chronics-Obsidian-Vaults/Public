---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/efa
- source/monster/cr/4
- source/monster/size/small-or-medium
- source/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Emerald Claw Commander"
---
# [Emerald Claw Commander](Compendium/bestiary/humanoid/emerald-claw-commander-efa.md)
*Source: Eberron: Forge of the Artificer p. 90*  

Emerald Claw commanders lead large groups of soldiers, inspiring the fanatical devotion of Humanoids and Undead alike.

```statblock
"name": "Emerald Claw Commander (EFA)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Lawful Evil"
"ac": !!int "20"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "11"
  - !!int "15"
  - !!int "15"
  - !!int "12"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Athletics](Rules/skills.md#Athletics)"
    "desc": "+6"
  - "name": "[Intimidation](Rules/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+3"
"gear":
  - "flail"
  - "five javelins"
  - "plate armor"
  - "shield"
"senses": "passive Perception 13"
"languages": "Common, Dwarvish"
"cr": "4"
"traits":
  - "desc": "While in a 30-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from the commander, the commander and its allies have <span title=\"\
      Player's Handbook (2024)\">Advantage</span> on attack rolls and saving throws,\
      \ provided the commander doesn't have the Incapacitated condition."
    "name": "Aura of Authority"
"actions":
  - "desc": "The commander makes two attacks, using Flail or Javelin in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 8 (1d8 + 4) Bludgeoning damage—\
      plus 7 (2d6) Necrotic damage if the commander is Bloodied—and the target has\
      \ <span title=\"Player's Handbook (2024)\">Disadvantage</span> on its next attack\
      \ roll before the start of the commander's next turn."
    "name": "Flail"
  - "desc": "*Melee  or Ranged Attack Roll:* +6, reach 5 ft. or range 30/120 ft. *Hit:*\
      \ 7 (1d6 + 4) Piercing damage—plus 7 (2d6) Necrotic damage if the commander\
      \ is Bloodied."
    "name": "Javelin"
"source":
  - "EFA"
"image": "Compendium/bestiary/humanoid/token/emerald-claw-commander-efa.webp"
```
^statblock