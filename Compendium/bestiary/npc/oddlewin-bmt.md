---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/bmt
- source/monster/cr/2
- source/monster/size/small
- source/monster/type/fey/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Oddlewin"
---
# [Oddlewin](Compendium/bestiary/npc/oddlewin-bmt.md)
*Source: The Book of Many Things p. 111*  

Oddlewin is a nilbog, a goblin possessed by a trickster spirit.

```statblock
"name": "Oddlewin (BMT)"
"size": "Small"
"type": "fey"
"subtype": "goblinoid"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"ac_class": "[leather armor](Compendium/items/leather-armor.md)"
"hp": !!int "21"
"hit_dice": "6d6"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "16"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[Performance](Rules/skills.md#Performance)"
    "desc": "+4"
  - "name": "[Stealth](Rules/skills.md#Stealth)"
    "desc": "+6"
"condition_immunities": "[charmed](Rules/conditions.md#Charmed)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 13"
"languages": "Common, Goblin, Sylvan"
"cr": "2"
"traits":
  - "desc": "Oddlewin can cast the [Augury](Compendium/spells/augury.md) spell as\
      \ a ritual, using cards as the material component."
    "name": "Fortune Teller"
  - "desc": "Any creature that attempts to damage Oddlewin must first succeed on a\
      \ DC 12 Charisma saving throw or have the [charmed](Rules/conditions.md#Charmed)\
      \ condition until the end of the creature's next turn. The creature must use\
      \ its action praising Oddlewin.\n\nOddlewin can't regain hit points, including\
      \ through magical healing, except through his Reversal of Fortune reaction."
    "name": "Nilbogism"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) bludgeoning damage."
    "name": "Fool's Scepter"
  - "desc": "Oddlewin conjures magical cards that slash at the air in a 5-foot cube\
      \ within 60 feet of Oddlewin until the start of Oddlewin's next turn. A creature\
      \ that starts its turn in the cube or that enters that area for the first time\
      \ on a turn takes 10 (4d4) slashing damage."
    "name": "Cloud of Cards"
  - "desc": "Oddlewin casts one of the following spells, using Charisma as the spellcasting\
      \ ability (spell save DC 12):\n\n**At will:** [Mage Hand](Compendium/spells/mage-hand.md),\
      \ [Tasha's Hideous Laughter](Compendium/spells/tashas-hideous-laughter.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Oddlewin takes the [Disengage](Rules/actions.md#Disengage) or [Hide](Rules/actions.md#Hide)\
      \ action."
    "name": "Nimble Escape"
"reactions":
  - "desc": "In response to another creature dealing damage to Oddlewin, Oddlewin\
      \ reduces the damage to 0 and regains 9 (2d8) hit points."
    "name": "Reversal of Fortune"
"source":
  - "BMT"
"image": "Compendium/bestiary/npc/token/oddlewin-bmt.webp"
```
^statblock