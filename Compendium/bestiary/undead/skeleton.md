---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/mm
- source/monster/cr/1-4
- source/monster/environment/urban
- source/monster/size/medium
- source/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Skeleton
---
# [Skeleton](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\undead/skeleton.md)
*Source: Monster Manual p. 272, Tasha's Cauldron of Everything, The Book of Many Things. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Skeletons arise when animated by dark magic. They heed the summons of spellcasters who call them from their stony tombs and ancient battlefields, or rise of their own accord in places saturated with death and loss, awakened by stirrings of necromantic energy or the presence of corrupting evil.

## Animated Dead

Whatever sinister force awakens a skeleton infuses its bones with a dark vitality, adhering joint to joint and reassembling dismantled limbs. This energy motivates a skeleton to move and think in a rudimentary fashion, though only as a pale imitation of the way it behaved in life. An animated skeleton retains no connection to its past, although resurrecting a skeleton restores it body and soul, banishing the hateful undead spirit that empowers it.

While most skeletons are the animated remains of dead humans and other humanoids, skeletal undead can be created from the bones of other creatures besides humanoids, giving rise to a host of terrifying and unique forms.

## Obedient Servants

Skeletons raised by spell are bound to the will of their creator. They follow orders to the letter, never questioning the tasks their masters give them, regardless of the consequences. Because of their literal interpretation of commands and unwavering obedience, skeletons adapt poorly to changing circumstances. They can't read, speak, emote, or communicate in any way except to nod, shake their heads, or point. Still, skeletons are able to accomplish a variety of relatively complex tasks.

A skeleton can fight with weapons and wear armor, can load and fire a catapult or trebuchet, scale a siege ladder, form a shield wall, or dump boiling oil. However, it must receive careful instructions explaining how such tasks are accomplished.

Although they lack the intellect they possessed in life, skeletons aren't mindless. Rather than break its limbs attempting to batter its way through an iron door, a skeleton tries the handle first. If that doesn't work, it searches for another way through or around the obstacle.

## Habitual Behaviors

Independent skeletons temporarily or permanently free of a master's control sometimes pantomime actions from their past lives, their bones echoing the rote behaviors of their former living selves. The skeleton of a miner might lift a pick and start chipping away at stone walls. The skeleton of a guard might strike up a post at a random doorway. The skeleton of a dragon might lie down on a pile of treasure, while the skeleton of a horse crops grass it can't eat. Left alone in a ballroom, the skeletons of nobles might continue an eternally unfinished dance.

When skeletons encounter living creatures, the necromantic energy that drives them compels them to kill unless they are commanded by their masters to refrain from doing so. They attack without mercy and fight until destroyed, for skeletons possess little sense of self and even less sense of self-preservation.

## Undead Nature

A skeleton doesn't require air, food, drink, or sleep.

```statblock
"name": "Skeleton"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "armor scraps"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "15"
  - !!int "6"
  - !!int "8"
  - !!int "5"
"speed": "30 ft."
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Exhaustion),\
  \ [poisoned](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Poisoned)"
"senses": "[darkvision](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 9"
"languages": "understands all languages it spoke in life but can't speak"
"cr": "1/4"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 80/320 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) piercing damage."
    "name": "Shortbow"
"source":
  - "MM"
  - "TCE"
  - "BMT"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/undead/token/skeleton.webp"
```
^statblock

## Environment

urban