---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/mpmm
- source/monster/cr/5
- source/monster/environment/coastal
- source/monster/environment/underwater
- source/monster/size/medium
- source/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kraken Priest
---
# [Kraken Priest](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\monstrosity/kraken-priest-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 167, Volo's Guide to Monsters p. 215*  

A kraken can seem godlike to folk who have faced its fury. Those who mistake its might for divine power and those who seek to appease the monster through veneration are sometimes rewarded with power, to serve thereafter as kraken priests.

Every kraken priest undergoes a change in appearance that reflects the kraken's influence, although each one differs in how their reverence is displayed. One kraken priest might have ink-black eyes and a suckered tentacle for a tongue, while another has a featureless face and a body covered in eyes and mouths that dribble seawater. These horrific manifestations intensify when the kraken possesses its minion to utter dire pronouncements.

```statblock
"name": "Kraken Priest (MPMM)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"modifier": !!int "0"
"stats":
  - !!int "12"
  - !!int "10"
  - !!int "16"
  - !!int "10"
  - !!int "15"
  - !!int "14"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Perception)"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": "any two languages"
"cr": "5"
"traits":
  - "desc": "The priest can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The priest makes two Thunderous Touch or Thunderbolt attacks."
    "name": "Multiattack"
  - "desc": "*Melee Spell Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 27 (5d10)\
      \ thunder damage."
    "name": "Thunderous Touch"
  - "desc": "*Ranged Spell Attack:* +5 to hit, range 60 ft., one target. *Hit:* 11\
      \ (2d10) lightning damage plus 11 (2d10) thunder damage, and the target is knocked\
      \ [prone](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Prone)."
    "name": "Thunderbolt"
  - "desc": "A kraken speaks through the priest with a thunderous voice audible within\
      \ 300 feet. Creatures of the priest's choice that can hear the kraken's words\
      \ (which are spoken in Abyssal, Infernal, or Primordial) must succeed on a DC\
      \ 14 Wisdom saving throw or be [frightened](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Frightened)\
      \ of the priest for 1 minute. A [frightened](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Frightened)\
      \ target can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success."
    "name": "Voice of the Kraken (Recharges after a Short or Long Rest)"
  - "desc": "The priest casts one of the following spells, requiring no material components\
      \ and using Wisdom as the spellcasting ability (spell save DC 13):\n\n**At will:**\
      \ [command](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/command.md),\
      \ [create or destroy water](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/create-or-destroy-water.md)\n\
      \n**3/day each:** [control water](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/control-water.md),\
      \ [darkness](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/darkness.md),\
      \ [water breathing](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/water-breathing.md),\
      \ [water walk](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/water-walk.md)\n\
      \n**1/day:** [Evard's black tentacles](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/evards-black-tentacles.md)"
    "name": "Spellcasting"
"source":
  - "MPMM"
  - "VGM"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/monstrosity/token/kraken-priest-mpmm.webp"
```
^statblock

## Environment

coastal, underwater