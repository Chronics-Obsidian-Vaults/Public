---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/ai
- source/monster/cr/2
- source/monster/size/medium
- source/monster/type/humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Oak Truestrike"
---
# [Oak Truestrike](Compendium/bestiary/npc/oak-truestrike-ai.md)
*Source: Acquisitions Incorporated p. 205*  

Oak Truestrike is the "B" Team's decisionist-and, depending on who you talk to, a reincarnated demigod. (It's a long story.) Those who know him acknowledge his confidence, his arrogance, and his odd ability to engage with others by somehow saying exactly what each listener wants to hear. Whether this is some subtle magical ability or simply grifter's charm, he makes good use of it either way.

Oak becomes a radically different person with each of his reincarnations, flipping between neutral good and neutral evil. His memories of past lives have been fractured by his many deaths, but he spends each new life accounting for the previous life in a karmic-ledger kind of way. His current incarnation embraces the good side. Mostly. Except for that occasional toxic bitterness. Oh, and the misanthropy. Actually, if you end up hating this guy, it's probably not your fault.

```statblock
"name": "Oak Truestrike (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Good or Neutral Evil"
"ac": !!int "15"
"ac_class": "[studded leather](Compendium/items/studded-leather-armor.md)"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "16"
  - !!int "14"
  - !!int "10"
  - !!int "13"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Nature](Rules/skills.md#Nature)"
    "desc": "+4"
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Performance](Rules/skills.md#Performance)"
    "desc": "+2"
  - "name": "[Stealth](Rules/skills.md#Stealth)"
    "desc": "+5"
  - "name": "[Survival](Rules/skills.md#Survival)"
    "desc": "+3"
"gear":
  - "[hand crossbow](Compendium/items/hand-crossbow.md)"
"senses": "passive Perception 13"
"languages": "Common"
"cr": "2"
"traits":
  - "desc": "Oak has advantage on saving throws against being [charmed](Rules/conditions.md#Charmed),\
      \ and magic can't put him to sleep."
    "name": "Fey Ancestry"
  - "desc": "Oak has advantage on Wisdom ([Perception](Rules/skills.md#Perception))\
      \ checks that rely on hearing or sight."
    "name": "Keen Hearing and Sight"
"actions":
  - "desc": "Oak makes three attacks with his hooked daggers or his hand crossbow."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4\
      \ + 3) piercing damage."
    "name": "Hooked Dagger"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 30/120 ft., one target. *Hit:*\
      \ 6 (1d6 + 3) piercing damage."
    "name": "Hand Crossbow"
"reactions":
  - "desc": "When Oak takes damage from a melee weapon attack, he can make a hooked\
      \ dagger attack."
    "name": "Return the Favor (3/Day)"
"source":
  - "AI"
"image": "Compendium/bestiary/npc/token/oak-truestrike-ai.webp"
```
^statblock