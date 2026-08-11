---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/7
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ashari Stoneguard"
---
# [Ashari Stoneguard](Compendium/bestiary/humanoid/ashari-stoneguard-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 128*  

Though the tribes of the Ashari wardens are neutral and spurn the "petty political nonsense" that they consider outsiders to be focused on, it is still all too easy to run afoul of the Ashari. They consider the strange elemental rifts over which they are guardians to be of foremost importance, and it is very easy for strangers to take actions that unknowingly disrupt the delicate balance over which the Ashari carefully watch. Though they are generally friendly to travelers—particularly to travelers in need—they are guarded, and do not hesitate to act to eliminate threats to the elemental powers and their own way of life.

The earth ashari of Terrah are a stoic people, slow to change socially, and more likely to fight defensive battles and outlast enemies than wage offensive wars. The Terrah stoneguard are the perfect embodiment of this ideal; their druidic training has been augmented by ancient combat techniques, allowing them to hold fast against a tide of enemies. They craft arms and armor from the granite around them, and their magical stonecraft rivals that of the dwarves. It is said that in mythic times, when elemental armies poured into Exandria, that two legendary stoneguards protected all of Terrah against the elemental onslaught for ten days and ten nights, guarding each other while their partner rested.

Today, the order of stoneguards stands vigilant along key defensive points within the Cliffkeep Mountains, warding the Terrah tribe against the dwarves of Kraghammer. If the stoneguard were ever to falter in their vigil, they believe the dwarves would doubtlessly enter their ancestral lands and strip bare its natural beauty in search of wealth and fuel.

```statblock
"name": "Ashari Stoneguard (TalDorei)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Neutral"
"ac": !!int "15"
"ac_class": "[granite half plate](Compendium/items/half-plate-armor.md)"
"hp": !!int "92"
"hit_dice": "16d8 + 80"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "20"
  - !!int "10"
  - !!int "14"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "strength": !!int "8"
  - "constitution": !!int "9"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Intimidation](Rules/skills.md#Intimidation)"
    "desc": "+3"
  - "name": "[Athletics](Rules/skills.md#Athletics)"
    "desc": "+8"
"condition_immunities": "[petrified](Rules/conditions.md#Petrified)"
"senses": "tremorsense 30 ft., passive Perception 12"
"languages": "Common, Druidic, Primordial (Terran)"
"cr": "7"
"traits":
  - "desc": "The stoneguard a 3rd-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 14, +6 to hit with spell attacks). It has the following druid\
      \ spells prepared:\n\n**Cantrips (at will):** [druidcraft](Compendium/spells/druidcraft.md),\
      \ [resistance](Compendium/spells/resistance.md)\n\n**1st level (4 slots):**\
      \ [goodberry](Compendium/spells/goodberry.md), [speak with animals](Compendium/spells/speak-with-animals.md),\
      \ [thunderwave](Compendium/spells/thunderwave.md)\n\n**2nd level (2 slots):**\
      \ [hold person](Compendium/spells/hold-person.md), [spike growth](Compendium/spells/spike-growth.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "The stoneguard makes three granite maul attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) bludgeoning damage. If the attack hits, the stoneguard may also\
      \ immediately cast [thunderwave](Compendium/spells/thunderwave.md) as a bonus\
      \ action. This casting uses a spell slot, but no material components."
    "name": "Granite Maul"
"reactions":
  - "desc": "When a creature within 5 feet of the stoneguard attacks a target other\
      \ than the stoneguard, it can make a single attack roll against the attacker."
    "name": "Sentinel"
  - "desc": "When the stoneguard is attacked, it may gain resistance to bludgeoning,\
      \ piercing, and slashing damage from nonmagical attacks until the end of the\
      \ attacker's turn."
    "name": "Skin to Stone"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Ashari_Stoneguard.png"
```
^statblock