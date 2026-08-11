---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/ai
- source/monster/cr/2
- source/monster/size/medium
- source/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Phoenix Anvil"
---
# [Phoenix Anvil](Compendium/bestiary/npc/phoenix-anvil-ai.md)
*Source: Acquisitions Incorporated p. 206*  

The "B" Team hoards person, Phoenix Anvil is a servant of Waukeen and a soft-spoken sort. Really soft. Like, he talks so infrequently that even he might not recognize his own voice. Phoenix comes from the streets, where he grew up a fighter until a job sweeping the steps of a small temple of Waukeen showed him a new path. His hunger for coin as an adventurer is thus guided by his knowledge of what it is to do without.

More of an object individual than a people person, Phoenix is obsessively dedicated to the franchise's assets and accounts. Thankfully, he includes his fellow members among those assets, making him fiercely loyal. However, Oak Truestrike is the only team member he's ever really warmed to, which doesn't do either of them any good.

```statblock
"name": "Phoenix Anvil (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"ac_class": "[chain mail](Compendium/items/chain-mail.md), [shield](Compendium/items/shield.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "10"
  - !!int "12"
  - !!int "13"
  - !!int "16"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](Rules/skills.md#Athletics)"
    "desc": "+4"
  - "name": "[Performance](Rules/skills.md#Performance)"
    "desc": "+3"
  - "name": "[Persuasion](Rules/skills.md#Persuasion)"
    "desc": "+3"
  - "name": "[Religion](Rules/skills.md#Religion)"
    "desc": "+3"
"gear":
  - "[warhammer](Compendium/items/warhammer.md)"
"senses": "passive Perception 13"
"languages": "Common, Elvish"
"cr": "2"
"traits":
  - "desc": "Phoenix is a 4th-level spellcaster. His spellcasting ability is Wisdom\
      \ (spell save DC 13, +5 to hit with spell attacks). He has the following cleric\
      \ spells prepared:\n\n**Cantrips (at will):** [guidance](Compendium/spells/guidance.md),\
      \ [light](Compendium/spells/light.md), [mending](Compendium/spells/mending.md),\
      \ [sacred flame](Compendium/spells/sacred-flame.md)\n\n**1st level (4 slots):**\
      \ [bane](Compendium/spells/bane.md), [cure wounds](Compendium/spells/cure-wounds.md),\
      \ [guiding bolt](Compendium/spells/guiding-bolt.md)\n\n**2nd level (3 slots):**\
      \ [hold person](Compendium/spells/hold-person.md), [spiritual weapon](Compendium/spells/spiritual-weapon.md)"
    "name": "Spellcasting"
  - "desc": "As a bonus action, Phoenix causes his shield to flare with divine light.\
      \ Each creature of his choice within 30 feet of him must succeed on a DC 13\
      \ Wisdom saving throw or be [blinded](Rules/conditions.md#Blinded) for 1 minute.\
      \ A creature can repeat the save at the end of each of its turns, ending the\
      \ effect on itself with a success."
    "name": "Divine Display (1/Day)"
"actions":
  - "desc": "Phoenix makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8\
      \ + 2) bludgeoning damage, and the target must succeed on a DC 12 Strength saving\
      \ throw or be pushed 5 feet."
    "name": "Warhammer"
"source":
  - "AI"
"image": "Compendium/bestiary/npc/token/phoenix-anvil-ai.webp"
```
^statblock