---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/efa
- source/monster/cr/
- source/monster/size/medium
- source/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Steel Defender"
---
# [Steel Defender](Compendium/bestiary/construct/steel-defender-efa.md)
*Source: Eberron: Forge of the Artificer p. 19*  

```statblock
"name": "Steel Defender (EFA)"
"size": "Medium"
"type": "construct"
"alignment": "Neutral"
"ac_class": "12 + your Intelligence modifier"
"hp": "5 + five times your Artificer level (the defender has a number of Hit Dice\
  \ [d8s] equal to your Artificer level)"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "4"
  - !!int "10"
  - !!int "6"
"speed": "40 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](Rules/conditions.md#Charmed), [exhaustion](Rules/conditions.md#Exhaustion),\
  \ [poisoned](Rules/conditions.md#Poisoned)"
"senses": "[Darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 10"
"languages": "understands the languages you know"
"traits":
  - "desc": "Add your <span title=\"Player's Handbook (2024)\">Proficiency Bonus</span>\
      \ to any ability check or saving throw the defender makes."
    "name": "Steel Bond"
"actions":
  - "desc": "*Melee Attack Roll:* Bonus equals your spell attack modifier, reach 5\
      \ ft. *Hit:* 1d8 + 2 plus your Intelligence modifier Force damage."
    "name": "Force-Empowered Rend"
  - "desc": "The defender, or one Construct or object it can see within 5 feet of\
      \ itself, regains a number of <span title=\"Player's Handbook (2024)\">Hit Points</span>\
      \ equal to 2d8 plus your Intelligence modifier."
    "name": "Repair (3/Day)"
"reactions":
  - "desc": "Trigger: A creature the defender can see within 5 feet of itself makes\
      \ an attack roll against a creature other than the defender. _Response:_ The\
      \ triggering creature makes the attack roll with <span title=\"Player's Handbook\
      \ (2024)\">Disadvantage</span>."
    "name": "Deflect Attack"
"source":
  - "EFA"
"image": "Compendium/bestiary/construct/token/steel-defender-efa.webp"
```
^statblock