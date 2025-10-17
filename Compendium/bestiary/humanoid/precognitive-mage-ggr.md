---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/ggr
- source/monster/cr/3
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Precognitive Mage
---
# [Precognitive Mage](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\humanoid/precognitive-mage-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 228*  

Precognitive mages, a rarity among Azorius spellcasters, are capable of capturing glimpses of the future. They are typically employed to anticipate the actions of wanted criminals, thus aiding in their capture.

```statblock
"name": "Precognitive Mage (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Neutral"
"ac": !!int "11"
"ac_class": "14 with [mage armor](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/mage-armor.md)"
"hp": !!int "63"
"hit_dice": "14d8"
"modifier": !!int "1"
"stats":
  - !!int "9"
  - !!int "13"
  - !!int "10"
  - !!int "18"
  - !!int "13"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Perception](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Perception)"
    "desc": "+3"
"senses": "[truesight](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/senses.md#Truesight)\
  \ 120 ft., passive Perception 13"
"languages": "Common plus any one language"
"cr": "3"
"traits":
  - "desc": "The mage's innate spellcasting ability is Intelligence (spell save DC\
      \ 14). It can cast the following spells, requiring no material components:\n\
      \n**3/day:** [detect thoughts](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/detect-thoughts.md),\
      \ [mage armor](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/mage-armor.md)\n\
      \n**1/day each:** [clairvoyance](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/clairvoyance.md),\
      \ [locate object](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/locate-object.md)"
    "name": "Innate Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +1 to hit, reach 5 ft., one target. *Hit:* 2 (1d6\
      \ - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two\
      \ hands."
    "name": "Quarterstaff"
  - "desc": "The mage targets one creature within 120 feet of it that it can see.\
      \ The target takes 18 (4d8) psychic damage, and it must succeed on a DC 14 Intelligence\
      \ saving throw or be [stunned](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Stunned)\
      \ until the end of its next turn."
    "name": "Glimpse the Temporal Flood (Recharge 5-6)"
"reactions":
  - "desc": "When the mage or a creature it can see makes an attack roll, a saving\
      \ throw, or an ability check, the mage can cause the roll to be made with advantage\
      \ or disadvantage."
    "name": "Precognitive Insight (3/Day)"
"source":
  - "GGR"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/token/precognitive-mage-ggr.webp"
```
^statblock