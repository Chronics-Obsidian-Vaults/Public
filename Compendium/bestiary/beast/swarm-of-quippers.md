---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mm
- source/monster/cr/1
- source/monster/environment/underwater
- source/monster/size/medium
- source/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Swarm of Quippers"
---
# [Swarm of Quippers](Compendium/bestiary/beast/swarm-of-quippers.md)
*Source: Monster Manual p. 338. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

> [!note] The Nature of Swarms
> 
> The swarms presented here aren't ordinary or benign assemblies of little creatures. They form as a result of some sinister or unwholesome influence. A vampire can summon swarms of bats and rats from the darkest corners of the night, while the very presence of a mummy lord can cause scarab beetles to boil up from the sand-filled depths of its tomb. A hag might have the power to turn swarms of ravens against her enemies, while a [yuan-ti abomination](Compendium/bestiary/monstrosity/yuan-ti-abomination.md) might have [swarms of poisonous snakes](Compendium/bestiary/beast/swarm-of-poisonous-snakes.md) slithering in its wake. Even druids can't charm these swarms, and their aggressiveness is borderline unnatural.
^the-nature-of-swarms

```statblock
"name": "Swarm of Quippers"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "28"
"hit_dice": "8d8 - 8"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "16"
  - !!int "9"
  - !!int "1"
  - !!int "7"
  - !!int "2"
"speed": "0 ft., swim 40 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](Rules/conditions.md#Charmed), [frightened](Rules/conditions.md#Frightened),\
  \ [grappled](Rules/conditions.md#Grappled), [paralyzed](Rules/conditions.md#Paralyzed),\
  \ [petrified](Rules/conditions.md#Petrified), [prone](Rules/conditions.md#Prone),\
  \ [restrained](Rules/conditions.md#Restrained), [stunned](Rules/conditions.md#Stunned)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 8"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The swarm has advantage on melee attack rolls against any creature that\
      \ doesn't have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny quipper. The swarm\
      \ can't regain hit points or gain temporary hit points."
    "name": "Swarm"
  - "desc": "The swarm can breathe only underwater."
    "name": "Water Breathing"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 0 ft., one creature in the swarm's\
      \ space. *Hit:* 14 (4d6) piercing damage, or 7 (2d6) piercing damage if the\
      \ swarm has half of its hit points or fewer."
    "name": "Bites"
"source":
  - "MM"
"image": "Compendium/bestiary/beast/token/swarm-of-quippers.webp"
```
^statblock

## Environment

underwater