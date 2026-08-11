---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/efa
- source/monster/cr/2
- source/monster/size/small-or-medium
- source/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Emerald Claw Knight"
---
# [Emerald Claw Knight](Compendium/bestiary/humanoid/emerald-claw-knight-efa.md)
*Source: Eberron: Forge of the Artificer p. 90*  

Knights of the Emerald Claw command squads of Humanoid or Undead soldiers. As they draw nearer to death, the chill of the grave suff uses their weapon attacks.

```statblock
"name": "Emerald Claw Knight (EFA)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Lawful Evil"
"ac": !!int "18"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "0"
"stats":
  - !!int "17"
  - !!int "11"
  - !!int "14"
  - !!int "13"
  - !!int "10"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "[Athletics](Rules/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+2"
"gear":
  - "chain mail"
  - "flail"
  - "five javelins"
  - "shield"
"senses": "passive Perception 12"
"languages": "Common, Dwarvish"
"cr": "2"
"actions":
  - "desc": "The knight makes two attacks, using Flail or Javelin in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Bludgeoning damage—\
      plus 4 (1d8) Necrotic damage if the knight is Bloodied—and the target has <span\
      \ title=\"Player's Handbook (2024)\">Disadvantage</span> on its next attack\
      \ roll before the start of the knight's next turn."
    "name": "Flail"
  - "desc": "*Melee  or Ranged Attack Roll:* +5, reach 5 ft. or range 30/120 ft. *Hit:*\
      \ 6 (1d6 + 3) Piercing damage—plus 4 (1d8) Necrotic damage if the knight is\
      \ Bloodied."
    "name": "Javelin"
"source":
  - "EFA"
"image": "Compendium/bestiary/humanoid/token/emerald-claw-knight-efa.webp"
```
^statblock