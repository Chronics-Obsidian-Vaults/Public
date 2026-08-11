---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/3
- source/monster/size/medium
- source/monster/type/humanoid/dwarf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Kraghammer Goat-Knight"
---
# [Kraghammer Goat-Knight](Compendium/bestiary/humanoid/kraghammer-goat-knight-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 133*  

The sheer cliff faces and winding winding mountainside roads of the Cliffkeep Mountains are nearly impossible to traverse by normal means with any speed. However, the Peakclimber Knights of Kraghammer—commonly known as the goat-knights—are enforcers of peace and justice across the mountain range, and their giant goat steeds can easily traverse the harsh mountain slopes and climb nearly vertical slopes at their full pace. These knights are in service to the Allhammer, and often find themselves at odds with enforcing the laws of Kraghammer and upholding the edicts of their god.

Travelers lost within the mountains are sometimes saved by a traveling goat-knight, who is able to lead them through dangerous-but-traversable mountain roads.

```statblock
"name": "Kraghammer Goat-Knight (TalDorei)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Neutral Good"
"ac": !!int "20"
"ac_class": "[plate armor](Compendium/items/plate-armor.md)"
"hp": !!int "4"
"hit_dice": "8d8 + 16"
"modifier": !!int "-1"
"stats":
  - !!int "16"
  - !!int "8"
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "14"
"speed": "25 ft. 40 ft. when mounted"
"saves":
  - "dexterity": !!int "1"
  - "strength": !!int "5"
  - "constitution": !!int "4"
  - "intelligence": !!int "2"
  - "wisdom": !!int "2"
  - "charisma": !!int "4"
"skillsaves":
  - "name": "[Nature](Rules/skills.md#Nature)"
    "desc": "+3"
  - "name": "[Religion](Rules/skills.md#Religion)"
    "desc": "+6"
"damage_resistances": "poison"
"condition_immunities": "diseases"
"gear":
  - "[warhammer](Compendium/items/warhammer.md)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 12"
"languages": "Common, Dwarvish"
"cr": "3"
"traits":
  - "desc": "The goat-knight is a 6th-level spellcaster. Its spellcasting ability\
      \ is Charisma (spell save DC 16, +8 to hit with spell attacks). The goat-knight\
      \ has the following paladin spells prepared:\n\n**1st level (4 slots):** [bless](Compendium/spells/bless.md),\
      \ [cure wounds](Compendium/spells/cure-wounds.md), [protection from evil and\
      \ good](Compendium/spells/protection-from-evil-and-good.md), [sanctuary](Compendium/spells/sanctuary.md),\
      \ [shield of faith](Compendium/spells/shield-of-faith.md)\n\n**2nd level (2\
      \ slots):** [branding smite](Compendium/spells/branding-smite.md), [lesser restoration](Compendium/spells/lesser-restoration.md),\
      \ [locate object](Compendium/spells/locate-object.md), [zone of truth](Compendium/spells/zone-of-truth.md)"
    "name": "Spellcasting"
  - "desc": "Whenever the goat-knight or a friendly creature within 10 feet of it\
      \ makes a saving throw, the creature gains a +2 bonus (included above). The\
      \ knight must be conscious to grant this bonus."
    "name": "Aura of Protection"
  - "desc": "The goat-knight has advantage on saving throws against poison."
    "name": "Dwarven Resilience"
"actions":
  - "desc": "The goat-knight makes two warhammer attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) bludgeoning damage, or 8 (1d10 + 3) bludgeoning damage if used with two\
      \ hands."
    "name": "Warhammer"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Kraghammer_Goat-Knight.png"
```
^statblock