---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/mpmm
- source/monster/cr/18
- source/monster/environment/underdark
- source/monster/size/huge
- source/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Sibriex
---
# [Sibriex](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\fiend/sibriex-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 217, Mordenkainen's Tome of Foes p. 137*  

Thought to be as old as the Abyss itself, sibriexes haunt remote parts of that plane, where they use their vile abilities to create new horrors and they seek ancient lore. Rivulets of blood and bile cascade from a sibriex's body, polluting the surrounding landscape.

Sibriexes have spent eons amassing knowledge from across the planes, hoarding it for when it might be useful. Such are their incredible intellects and stores of information that many seek them out, including demon lords. Some sibriexes act as advisors and oracles, manipulating demons into serving their ends, while others parcel out lore only when doing so advances their plans.

Sibriexes can channel the power of the Abyss to create new demons from other creatures. Some demons petition sibriexes for physical gifts, for sibriexes can graft on new body parts to give the demons greater strength, vision, or stamina. Sibriexes never give aid freely, though; they demand a service or a treasure in return for the flesh-shaping they provide.

```statblock
"name": "Sibriex (MPMM)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "150"
"hit_dice": "12d12 + 72"
"modifier": !!int "-4"
"stats":
  - !!int "10"
  - !!int "3"
  - !!int "23"
  - !!int "25"
  - !!int "24"
  - !!int "25"
"speed": "0 ft., fly 20 ft. (hover)"
"saves":
  - "intelligence": !!int "13"
  - "charisma": !!int "13"
"skillsaves":
  - "name": "[Arcana](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Arcana)"
    "desc": "+13"
  - "name": "[History](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#History)"
    "desc": "+13"
  - "name": "[Perception](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Perception)"
    "desc": "+13"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Poisoned)"
"senses": "[truesight](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/senses.md#Truesight)\
  \ 120 ft., passive Perception 23"
"languages": "all, telepathy 120 ft."
"cr": "18"
"traits":
  - "desc": "The sibriex emits an aura of corruption 30 feet in every direction. Vegetation\
      \ withers in the aura, and the ground in the aura is difficult terrain for other\
      \ creatures. Any creature that starts its turn in the aura must succeed on a\
      \ DC 20 Constitution saving throw or take 14 (4d6) poison damage. A creature\
      \ that succeeds on the save is immune to this sibriex's Contamination for 24\
      \ hours."
    "name": "Contamination"
  - "desc": "If the sibriex fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The sibriex has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The sibriex makes three Chain attacks, and it uses Squirt Bile."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 15 ft., one target. *Hit:* 20\
      \ (2d12 + 7) force damage."
    "name": "Chain"
  - "desc": "The sibriex targets one creature it can see within 120 feet of it. The\
      \ target must succeed on a DC 20 Dexterity saving throw or take 31 (9d6) acid\
      \ damage."
    "name": "Squirt Bile"
  - "desc": "The sibriex targets up to three creatures it can see within 120 feet\
      \ of it. Each target must make a DC 20 Constitution saving throw. On a successful\
      \ save, a creature becomes immune to this sibriex's Warp Creature. On a failed\
      \ save, the target is [poisoned](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Poisoned),\
      \ which causes it to also gain 1 level of [exhaustion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Exhaustion).\
      \ While [poisoned](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Poisoned)\
      \ in this way, the target must repeat the saving throw at the start of each\
      \ of its turns. Three successful saves against the poison end it, and ending\
      \ the poison removes any levels of [exhaustion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Exhaustion)\
      \ caused by it. Each failed save causes the target to gain another level of\
      \ [exhaustion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Exhaustion).\
      \ Once the target reaches 6 levels of [exhaustion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Exhaustion),\
      \ it dies and instantly transforms into a living [manes](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/fiend/manes.md)\
      \ under the sibriex's control. The transformation of the body can be undone\
      \ only by a [wish](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/wish.md)\
      \ spell."
    "name": "Warp Creature"
  - "desc": "The sibriex casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 21):\n\
      \n**At will:** [command](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/command.md),\
      \ [dispel magic](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/dispel-magic.md),\
      \ [hold monster](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/hold-monster.md)\n\
      \n**1/day:** [feeblemind](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/feeblemind.md)"
    "name": "Spellcasting"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the sibriex can expend a use to take one of the following actions. The sibriex\
  \ regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The sibriex uses Spellcasting."
    "name": "Cast a Spell"
  - "desc": "The sibriex uses Squirt Bile."
    "name": "Spray Bile"
  - "desc": "The sibriex uses Warp Creature."
    "name": "Warp (Costs 2 Actions)"
"source":
  - "MPMM"
  - "MTF"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/fiend/token/sibriex-mpmm.webp"
```
^statblock

## Environment

underdark