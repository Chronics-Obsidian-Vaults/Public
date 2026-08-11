---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/5
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ashari Skydancer"
---
# [Ashari Skydancer](Compendium/bestiary/humanoid/ashari-skydancer-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 129*  

Though the tribes of the Ashari wardens are neutral and spurn the "petty political nonsense" that they consider outsiders to be focused on, it is still all too easy to run afoul of the Ashari. They consider the strange elemental rifts over which they are guardians to be of foremost importance, and it is very easy for strangers to take actions that unknowingly disrupt the delicate balance over which the Ashari carefully watch. Though they are generally friendly to travelers—particularly to travelers in need—they are guarded, and do not hesitate to act to eliminate threats to the elemental powers and their own way of life.

Zephrah's location in the Summit Peaks has shielded the Ashari from countless hardships; few infringe upon their isolated home, and this safety has bred a certain recklessness within the Zephrah people. Though they guard their elemental rift as closely as the rest of their kin, their lack of stoicism and restraint often earns them the scorn of the Terrah, the only other Ashari tribe in Tal'Dorei.

Air Ashari children learn to fly before they learn to walk, accompanying their parents through the snow-fattened clouds on Ashari-craft skysails (see pg. 45). While all in Zephrah love the sensation of flight, few hone their skills as rigorously as the skydancers. These graceful masters of the wind are at once artists, performers, and warriors; they are beloved heroes of their people, both defending them in times of danger and bringing them happiness in times of peace.

```statblock
"name": "Ashari Skydancer (TalDorei)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"hp": !!int "63"
"hit_dice": "14d8"
"modifier": !!int "4"
"stats":
  - !!int "10"
  - !!int "18"
  - !!int "10"
  - !!int "12"
  - !!int "16"
  - !!int "11"
"speed": "30 ft., fly 60 ft. with [skysail](Compendium/items/skysail-taldorei.md)"
"saves":
  - "dexterity": !!int "7"
"skillsaves":
  - "name": "[Acrobatics](Rules/skills.md#Acrobatics)"
    "desc": "+7"
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+6"
"senses": "passive Perception 16"
"languages": "Common, Druidic, Primordial (Auran)"
"cr": "5"
"traits":
  - "desc": "The skydancer a 3rd-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 14, +6 to hit with spell attacks). It has the following druid\
      \ spells prepared:\n\n**Cantrips (at will):** [guidance](Compendium/spells/guidance.md),\
      \ [shillelagh](Compendium/spells/shillelagh.md)\n\n**1st level (4 slots):**\
      \ [entangle](Compendium/spells/entangle.md), [fog cloud](Compendium/spells/fog-cloud.md),\
      \ [jump](Compendium/spells/jump.md)\n\n**2nd level (2 slots):** [gust of wind](Compendium/spells/gust-of-wind.md),\
      \ [skywrite](Compendium/spells/skywrite-xge.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "The skydancer makes two skysail staff attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6\
      \ + 4) bludgeoning damage. If the skydancer makes this attack while *flying*,\
      \ the target must make a DC 14 Dexterity saving throw, taking 21 (6d6) lightning\
      \ damage on a failure or half as much damage on a success."
    "name": "Skysail Staff"
"reactions":
  - "desc": "When the skydancer takes falling damage, it may reduce the damage by\
      \ half."
    "name": "Slow Fall"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Ashari_Skydancer.png"
```
^statblock