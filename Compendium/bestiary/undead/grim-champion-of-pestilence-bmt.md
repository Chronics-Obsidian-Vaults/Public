---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/bmt
- source/monster/cr/15
- source/monster/size/medium
- source/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Grim Champion of Pestilence
---
# [Grim Champion of Pestilence](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\undead/grim-champion-of-pestilence-bmt.md)
*Source: The Book of Many Things p. 163*  

Aleron was once a tiefling adventurer, but unlike so many victims of the Deck of Many Things, he never drew the Skull card. Instead, when one of his allies drew the card and faced the avatar of death, Aleron came to his ally's aid. A second avatar of death appeared, and Aleron was slain; soon after, his Undead corpse crawled from Withered Vineyard, tainted with plague. Aleron resents his fellow Undead in the Grim Harrow, considering himself better than all of them and unjustly condemned to the Gardens of Decay for an act of altruism.

Though the weakest of the Harrow's three leaders, the Grim Champion of Pestilence is nonetheless a fearsome entity of sickness and blight. A swarm of insects surrounds him in a mockery of a halo, and debilitating plagues flow from his fingertips. Aleron rides a warhorse skeleton with flies buzzing in its gaping eye sockets.

## The Grim Champions

The Grim Harrow is led by three powerful entities with the title of grim champion. Each champion embodies a terrible facet of death. Jyn Corvis, Grim Champion of Desolation, is the oldest and most powerful of the three and embodies all-consuming nothingness. She led the Grim Harrow to the Gardens of Delight long ago and is the nominal leader of all the Undead in the demiplane. The other two champions—Wynemar Brack, Grim Champion of Bloodshed, and Aleron, Grim Champion of Pestilence—rival Jyn for power and together can oppose her. The fact that the three champions rarely agree on anything is a major check on the group's power. Instead of the Grim Harrow acting as a unified force, each of the three champions usually pursues their own interests, seldom cooperating or sharing intelligence or resources.

```statblock
"name": "Grim Champion of Pestilence (BMT)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "17 with [mage armor](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/mage-armor.md)"
"hp": !!int "120"
"hit_dice": "16d8 + 48"
"modifier": !!int "4"
"stats":
  - !!int "10"
  - !!int "18"
  - !!int "16"
  - !!int "17"
  - !!int "15"
  - !!int "21"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "9"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Arcana](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[Perception](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Stealth)"
    "desc": "+9"
"damage_resistances": "cold; necrotic; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "poison"
"condition_immunities": "[blinded](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Blinded),\
  \ [charmed](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Charmed),\
  \ [deafened](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Deafened),\
  \ [exhaustion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Exhaustion),\
  \ [frightened](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Frightened),\
  \ [poisoned](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Poisoned),\
  \ [stunned](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Stunned),\
  \ [unconscious](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Unconscious)"
"senses": "[darkvision](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 17"
"languages": "Common, Infernal"
"cr": "15"
"traits":
  - "desc": "The champion is surrounded by an aura of deadly magic that takes the\
      \ form of a host of glowing white insects. Each creature that starts its turn\
      \ within 10 feet of the champion must succeed on a DC 18 Constitution saving\
      \ throw or have the [incapacitated](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Incapacitated)\
      \ condition until the start of its next turn, as the insects ravage its body."
    "name": "Halo of Pestilence"
  - "desc": "If the champion fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "The champion makes two Blight Staff attacks, two Plague Bolt attacks,\
      \ or one of each."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 8 (1d8\
      \ + 4) bludgeoning damage plus 21 (6d6) necrotic damage."
    "name": "Blight Staff"
  - "desc": "*Ranged Spell Attack:* +10 to hit, range 120 ft., one target. *Hit:*\
      \ 23 (4d8 + 5) poison damage, and the target has the [poisoned](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Poisoned)\
      \ condition until the start of the champion's next turn."
    "name": "Plague Bolt"
  - "desc": "The champion casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 18):\n\
      \n**At will:** [Detect Magic](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/detect-magic.md),\
      \ [Mage Armor](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/mage-armor.md)\
      \ (self only)\n\n**2/day each:** [Blight](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/blight.md),\
      \ [Blindness/Deafness](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/blindness-deafness.md)\n\
      \n**1/day each:** [Cloudkill](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/cloudkill.md),\
      \ [Contagion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/contagion.md)"
    "name": "Spellcasting"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the grim champion of pestilence can expend a use to take one of the following\
  \ actions. The grim champion of pestilence regains all expended uses at the start\
  \ of each of its turns."
"legendary_actions":
  - "desc": "The champion makes one Blight Staff or Plague Bolt attack."
    "name": "Attack"
  - "desc": "The champion moves up to its speed or commands its mount to move up to\
      \ its speed. This movement doesn't provoke opportunity attacks."
    "name": "Furious Pursuit"
  - "desc": "The champion uses Spellcasting."
    "name": "Cast a Spell (Costs 2 Actions)"
"source":
  - "BMT"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/undead/token/grim-champion-of-pestilence-bmt.webp"
```
^statblock