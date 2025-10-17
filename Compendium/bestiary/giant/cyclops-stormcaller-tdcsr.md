---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/tdcsr
- source/monster/cr/10
- source/monster/environment/mountain
- source/monster/size/large
- source/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Cyclops Stormcaller
---
# [Cyclops Stormcaller](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\giant/cyclops-stormcaller-tdcsr.md)
*Source: Tal'Dorei Campaign Setting Reborn p. 235*  

When [cyclopes](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/giant/cyclops.md) are born beneath a raging storm, they sometimes grow up different—smaller than the rest, sickly and weak. Most of these stormborn [cyclopes](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/giant/cyclops.md) are relentlessly bullied and beaten for their tiny stature, and many die before adulthood. Those who survive do so because of the magic the [Stormlord](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/deities/exandria-the-stormlord-tdcsr.md) has bestowed upon them—intentionally or otherwise. As [cyclopes](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/giant/cyclops.md) are generally unfamiliar with magic, the power of a stormcaller awes and terrifies them, and many see stormcallers as nothing short of the manifestation of a god.

## Storm Worship

Their fellow [cyclopes](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/giant/cyclops.md) may assume that the might of a stormcaller is akin to godliness, but many stormcallers hunger for greater power. A cabal of stormcallers regularly gathers in the "Daggerbay Mountains" at an ancient elven temple called the Skyneedle (in Elvish, ira'fallai; in Giant, "Tall Zappo-Zappo"). There, they conduct strange rituals to commune with an entity they call the Eye of the Storm—and with every ritual, their power grows.

However, the Eye of the Storm is no avatar of the [Stormlord](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/deities/exandria-the-stormlord-tdcsr.md), but a vengeful [storm giant](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/giant/storm-giant.md) named Eyvindr, who's posing as a demigod and intent on raising an army to exact retribution on the "Council of Seven Scepters". He'll have to risk revealing himself to the stormcallers eventually—but not until he believes that his control over his cyclops devotees is absolute.

```statblock
"name": "Cyclops Stormcaller (TDCSR)"
"size": "Large"
"type": "giant"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "[chain mail](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/items/chain-mail.md),\
  \ [cloak of protection](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/items/cloak-of-protection.md),\
  \ [ring of protection](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/items/ring-of-protection.md)"
"hp": !!int "114"
"hit_dice": "12d10 + 48"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "18"
  - !!int "15"
  - !!int "8"
  - !!int "20"
"speed": "30 ft., fly 60 ft. (stormy conditions only)"
"saves":
  - "strength": !!int "5"
  - "dexterity": !!int "2"
  - "constitution": !!int "6"
  - "intelligence": !!int "4"
  - "wisdom": !!int "5"
  - "charisma": !!int "11"
"skillsaves":
  - "name": "[Arcana](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Arcana)"
    "desc": "+6"
"senses": "passive Perception 9"
"languages": "Common, Elvish, Giant"
"cr": "10"
"traits":
  - "desc": "The cyclops's innate spellcasting ability is Charisma (spell save DC\
      \ 17, +9 to hit with spell attacks). The cyclops can innately cast the following\
      \ spells, requiring no material components:\n\n**At will:** [ray of frost](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/ray-of-frost.md)\
      \ (3d8), [water walk](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/water-walk.md)\n\
      \n**3/day each:** [ice storm](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/ice-storm.md),\
      \ [sleet storm](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/sleet-storm.md),\
      \ [wind wall](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/wind-wall.md)\n\
      \n**1/day each:** [control weather](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/control-weather.md),\
      \ [storm of vengeance](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/storm-of-vengeance.md)"
    "name": "Innate Spellcasting"
  - "desc": "The cyclops has disadvantage on any attack roll against a target more\
      \ than 30 feet away."
    "name": "One-Eyed"
  - "desc": "While outdoors in stormy conditions, the cyclops has a flying speed of\
      \ 60 feet."
    "name": "Storm Wings"
  - "desc": "The cyclops has advantage on Constitution saving throws made to maintain\
      \ [concentration](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Concentration)\
      \ on spells, and cannot lose [concentration](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Concentration)\
      \ because of turbulent weather."
    "name": "Supernatural Focus"
"actions":
  - "desc": "The cyclops makes two ice claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (3d6 + 3) slashing damage plus 3 (1d6) cold damage."
    "name": "Ice Claw"
"source":
  - "TDCSR"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/giant/token/cyclops-stormcaller-tdcsr.webp"
```
^statblock

## Environment

mountain