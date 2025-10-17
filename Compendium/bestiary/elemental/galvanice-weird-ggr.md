---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/ggr
- source/monster/cr/1
- source/monster/size/medium
- source/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- Galvanice Weird
---
# [Galvanice Weird](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\elemental/galvanice-weird-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 209*  

Galvanice weirds seem to be the epitome of weird technology. Indeed, they serve willingly, with cheerful stupidity, as guardians and laborers in Izzet workshops. They combine a rigid body of elemental ice with a core of lightning that animates them. If a galvanice weird is destroyed, the ice shatters and lightning crackles outward in a dangerous explosion. Still, most Izzet researchers find that their usefulness outweighs this risk.

## Izzet Weirds

Weirds are the products of Izzet League experiments intended to combine two opposing elemental types in the hope of creating elementals that were more stable than the norm and easier to control. As commonly happens with Izzet experiments, the outcome was the exact opposite. Weirds are even wilder and more unpredictable than elementals of either of their component elements. Nevertheless, they can make potent guardian creatures and can be urged into fighting on behalf of their creators.

### Elemental Nature

An Izzet weird doesn't require air, food, drink, or sleep.

```statblock
"name": "Galvanice Weird (GGR)"
"size": "Medium"
"type": "elemental"
"alignment": "Chaotic Neutral"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "22"
"hit_dice": "3d8 + 9"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "10"
  - !!int "17"
  - !!int "3"
  - !!int "10"
  - !!int "5"
"speed": "30 ft."
"damage_resistances": "cold; lightning; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Exhaustion),\
  \ [grappled](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Grappled),\
  \ [paralyzed](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Paralyzed),\
  \ [petrified](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Petrified),\
  \ [poisoned](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Poisoned),\
  \ [prone](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Prone),\
  \ [restrained](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Restrained),\
  \ [unconscious](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Unconscious)"
"senses": "[darkvision](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 10"
"languages": ""
"cr": "1"
"traits":
  - "desc": "When the galvanice weird dies, it explodes in a burst of ice and lightning.\
      \ Each creature within 10 feet of the exploding weird must make a DC 13 Dexterity\
      \ saving throw, taking 7 (2d6) lightning damage on a failed save, or half as\
      \ much damage on a successful one."
    "name": "Death Burst"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) bludgeoning damage plus 5 (2d4) lightning damage. If the target is a\
      \ creature, it must succeed on a DC 13 Constitution saving throw or lose the\
      \ ability to use reactions until the start of the weird's next turn."
    "name": "Slam"
"source":
  - "GGR"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/elemental/token/galvanice-weird-ggr.webp"
```
^statblock