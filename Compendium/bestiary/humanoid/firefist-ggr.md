---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/ggr
- source/monster/cr/7
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Firefist"
---
# [Firefist](Compendium/bestiary/humanoid/firefist-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 231*  

Boros firefists combine potent magic with peerless fighting ability, inspiring all who serve alongside them. They often act as the point of contact between the Boros Legion and the angelic leaders.

```statblock
"name": "Firefist (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "[plate armor](Compendium/items/plate-armor.md)"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "constitution": !!int "5"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Intimidation](Rules/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Religion](Rules/skills.md#Religion)"
    "desc": "+3"
"gear":
  - "[greatsword](Compendium/items/greatsword.md)"
"senses": "passive Perception 13"
"languages": "any one language (usually Common)"
"cr": "7"
"traits":
  - "desc": "The firefist is a 9th-level Boros spellcaster. Its spellcasting ability\
      \ is Wisdom (spell save DC 14, +6 to hit with spell attacks). It has the following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** [fire bolt](Compendium/spells/fire-bolt.md),\
      \ [light](Compendium/spells/light.md), [sacred flame](Compendium/spells/sacred-flame.md),\
      \ [spare the dying](Compendium/spells/spare-the-dying.md)\n\n**1st level (4\
      \ slots):** [guiding bolt](Compendium/spells/guiding-bolt.md), [healing word](Compendium/spells/healing-word.md),\
      \ [heroism](Compendium/spells/heroism.md), [shield of faith](Compendium/spells/shield-of-faith.md)\n\
      \n**2nd level (3 slots):** [lesser restoration](Compendium/spells/lesser-restoration.md),\
      \ [scorching ray](Compendium/spells/scorching-ray.md)\n\n**3rd level (3 slots):**\
      \ [blinding smite](Compendium/spells/blinding-smite.md), [crusader's mantle](Compendium/spells/crusaders-mantle.md),\
      \ [revivify](Compendium/spells/revivify.md)\n\n**4th level (3 slots):** [banishment](Compendium/spells/banishment.md),\
      \ [wall of fire](Compendium/spells/wall-of-fire.md)\n\n**5th level (1 slots):**\
      \ [flame strike](Compendium/spells/flame-strike.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "The firefist makes two greatsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) slashing damage."
    "name": "Greatsword"
"reactions":
  - "desc": "When the firefist or one creature it can see within 30 feet of it makes\
      \ an attack roll, the firefist grants a +10 bonus to that roll."
    "name": "Guided Attack (Recharges after a Short or Long Rest)"
"source":
  - "GGR"
"image": "Compendium/bestiary/humanoid/token/firefist-ggr.webp"
```
^statblock