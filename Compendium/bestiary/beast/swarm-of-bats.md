---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mm
- source/monster/cr/1-4
- source/monster/environment/hill
- source/monster/environment/mountain
- source/monster/environment/underdark
- source/monster/environment/urban
- source/monster/size/medium
- source/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Swarm of Bats"
---
# [Swarm of Bats](Compendium/bestiary/beast/swarm-of-bats.md)
*Source: Monster Manual p. 337. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

> [!note] The Nature of Swarms
> 
> The swarms presented here aren't ordinary or benign assemblies of little creatures. They form as a result of some sinister or unwholesome influence. A vampire can summon swarms of bats and rats from the darkest corners of the night, while the very presence of a mummy lord can cause scarab beetles to boil up from the sand-filled depths of its tomb. A hag might have the power to turn swarms of ravens against her enemies, while a [yuan-ti abomination](Compendium/bestiary/monstrosity/yuan-ti-abomination.md) might have [swarms of poisonous snakes](Compendium/bestiary/beast/swarm-of-poisonous-snakes.md) slithering in its wake. Even druids can't charm these swarms, and their aggressiveness is borderline unnatural.
^the-nature-of-swarms

```statblock
"name": "Swarm of Bats"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "2"
"stats":
  - !!int "5"
  - !!int "15"
  - !!int "10"
  - !!int "2"
  - !!int "12"
  - !!int "4"
"speed": "0 ft., fly 30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](Rules/conditions.md#Charmed), [frightened](Rules/conditions.md#Frightened),\
  \ [grappled](Rules/conditions.md#Grappled), [paralyzed](Rules/conditions.md#Paralyzed),\
  \ [petrified](Rules/conditions.md#Petrified), [prone](Rules/conditions.md#Prone),\
  \ [restrained](Rules/conditions.md#Restrained), [stunned](Rules/conditions.md#Stunned)"
"senses": "[blindsight](Rules/senses.md#Blindsight) 60 ft., passive Perception 11"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The swarm can't use its blindsight while [deafened](Rules/conditions.md#Deafened)."
    "name": "Echolocation"
  - "desc": "The swarm has advantage on Wisdom ([Perception](Rules/skills.md#Perception))\
      \ checks that rely on hearing."
    "name": "Keen Hearing"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny bat. The swarm\
      \ can't regain hit points or gain temporary hit points."
    "name": "Swarm"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 0 ft., one creature in the swarm's\
      \ space. *Hit:* 5 (2d4) piercing damage, or 2 (1d4) piercing damage if the swarm\
      \ has half of its hit points or fewer."
    "name": "Bites"
"source":
  - "MM"
"image": "Compendium/bestiary/beast/token/swarm-of-bats.webp"
```
^statblock

## Environment

underdark, mountain, hill, urban