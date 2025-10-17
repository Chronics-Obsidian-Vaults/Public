---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/mm
- source/monster/cr/2
- source/monster/environment/underdark
- source/monster/size/medium
- source/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- Nothic
---
# [Nothic](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\aberration/nothic.md)
*Source: Monster Manual p. 236, Explorer's Guide to Wildemount, Mythic Odysseys of Theros, The Book of Many Things. Available in the Basic Rules (2014)*  

A baleful eye peers out from the darkness, its gleam hinting at a weird intelligence and unnerving malevolence. Most times, a nothic is content to watch, weighing and assessing the creatures it encounters. When driven to violence, it uses its horrific gaze to rot the flesh from its enemies' bones.

## Cursed Arcanists

Rather than gaining the godlike supremacy they crave, some wizards who devote their lives to unearthing arcane secrets are reduced to creeping, tormented monsters by a dark curse left behind by Vecna, a powerful lich who, in some worlds, has transcended his undead existence to become a god of secrets. Nothics retain no awareness of their former selves, skulking amid the shadows and haunting places rich in magical knowledge, drawn by memories and impulses they can't quite understand.

## Dark Oracles

Nothics possess a strange magical insight that allows them to extract knowledge from other creatures. This grants them unique understanding of secret and forbidden lore, which they share for a price. A nothic covets magic items, greedily accepting such gifts from creatures that seek out its knowledge.

### Lurkers in Magical Places

Nothics are notorious for infiltrating arcane academies and other places rich in magical learning. They are driven by the vague knowledge that there exists a method to reverse their condition. This isn't a clear sense of purpose, but rather an obsessive tug at the end of the mind. Some nothics are clever enough to realize that this is merely part of the strange lesson for their folly, a false hope to drive them to seek out more arcane secrets.

```statblock
"name": "Nothic"
"size": "Medium"
"type": "aberration"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "16"
  - !!int "16"
  - !!int "13"
  - !!int "10"
  - !!int "8"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Insight](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Perception](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "[truesight](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/senses.md#Truesight)\
  \ 120 ft., passive Perception 12"
"languages": "Undercommon"
"cr": "2"
"traits":
  - "desc": "The nothic has advantage on Wisdom ([Perception](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Keen Sight"
"actions":
  - "desc": "The nothic makes two claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d6\
      \ + 3) slashing damage."
    "name": "Claw"
  - "desc": "The nothic targets one creature it can see within 30 feet of it. The\
      \ target must succeed on a DC 12 Constitution saving throw against this magic\
      \ or take 10 (3d6) necrotic damage."
    "name": "Rotting Gaze"
  - "desc": "The nothic targets one creature it can see within 30 feet of it. The\
      \ target must contest its Charisma ([Deception](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Deception))\
      \ check against the nothic's Wisdom ([Insight](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Insight))\
      \ check. If the nothic wins, it magically learns one fact or secret about the\
      \ target. The target automatically wins if it is immune to being [charmed](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Charmed)."
    "name": "Weird Insight"
"source":
  - "MM"
  - "EGW"
  - "MOT"
  - "BMT"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/aberration/token/nothic.webp"
```
^statblock

## Environment

underdark