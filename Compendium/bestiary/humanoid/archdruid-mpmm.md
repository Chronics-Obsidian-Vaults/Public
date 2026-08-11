---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mpmm
- source/monster/cr/12
- source/monster/environment/forest
- source/monster/environment/mountain
- source/monster/environment/swamp
- source/monster/environment/underwater
- source/monster/size/medium
- source/monster/type/humanoid/druid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Archdruid"
---
# [Archdruid](Compendium/bestiary/humanoid/archdruid-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 48, Volo's Guide to Monsters p. 210*  

Archdruids watch over the natural wonders of their domains. They seldom interact with folk away from their druid groves and shrines, unless there is a great threat to the natural order or to a nearby community. An archdruid typically has one or more pupils who are [druids](Compendium/bestiary/humanoid/druid.md), and the archdruid's lair is usually guarded by loyal Beasts and Fey creatures.

When an archdruid uses their Change Shape action, you may choose the creature they turn into, abiding by the action's restrictions. Or you may roll on the Archdruid Favored Shapes table to determine the form the archdruid adopts.

**Archdruid Favored Shapes**

| dice: d8 | Favored Shape |
|----------|---------------|
| 1 | [Air elemental](Compendium/bestiary/elemental/air-elemental.md) |
| 2 | [Earth elemental](Compendium/bestiary/elemental/earth-elemental.md) |
| 3 | [Fire elemental](Compendium/bestiary/elemental/fire-elemental.md) |
| 4 | [Giant crocodile](Compendium/bestiary/beast/giant-crocodile.md) |
| 5 | [Mammoth](Compendium/bestiary/beast/mammoth.md) |
| 6 | [Flail snail](Compendium/bestiary/elemental/flail-snail-mpmm.md) |
| 7 | [Triceratops](Compendium/bestiary/beast/triceratops.md) |
| 8 | [Water elemental](Compendium/bestiary/elemental/water-elemental.md) |
^archdruid-favored-shapes

```statblock
"name": "Archdruid (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "druid"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[hide armor](Compendium/items/hide-armor.md)"
"hp": !!int "154"
"hit_dice": "28d8 + 28"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "14"
  - !!int "12"
  - !!int "12"
  - !!int "20"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "[Medicine](Rules/skills.md#Medicine)"
    "desc": "+9"
  - "name": "[Nature](Rules/skills.md#Nature)"
    "desc": "+5"
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+9"
"senses": "passive Perception 19"
"languages": "Druidic plus any two languages"
"cr": "12"
"actions":
  - "desc": "The archdruid makes three Staff or Wildfire attacks. It can replace one\
      \ attack with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) bludgeoning damage plus 21 (6d6) poison damage."
    "name": "Staff"
  - "desc": "*Ranged Spell Attack:* +9 to hit, range 120 ft., one target. *Hit:* 26\
      \ (6d6 + 5) fire damage, and the target is [blinded](Rules/conditions.md#Blinded)\
      \ until the start of the druid's next turn."
    "name": "Wildfire"
  - "desc": "The archdruid casts one of the following spells, using Wisdom as the\
      \ spellcasting ability (spell save DC 17):\n\n**At will:** [beast sense](Compendium/spells/beast-sense.md),\
      \ [entangle](Compendium/spells/entangle.md), [speak with animals](Compendium/spells/speak-with-animals.md)\n\
      \n**3/day each:** [animal messenger](Compendium/spells/animal-messenger.md),\
      \ [dominate beast](Compendium/spells/dominate-beast.md), [faerie fire](Compendium/spells/faerie-fire.md),\
      \ [tree stride](Compendium/spells/tree-stride.md)\n\n**1/day each:** [commune\
      \ with nature](Compendium/spells/commune-with-nature.md) (as an action), [mass\
      \ cure wounds](Compendium/spells/mass-cure-wounds.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The archdruid magically transforms into a Beast or an Elemental with\
      \ a challenge rating of 6 or less and can remain in that form for up to 9 hours.\
      \ The archdruid can choose whether its equipment falls to the ground, melds\
      \ with its new form, or is worn by the new form. The archdruid reverts to its\
      \ true form if it dies or falls [unconscious](Rules/conditions.md#Unconscious).\
      \ The archdruid can revert to its true form using a bonus action.\n\nWhile in\
      \ a new form, the archdruid's stat block is replaced by the stat block of that\
      \ form, except the archdruid keeps its current hit points, its hit point maximum,\
      \ this bonus action, its languages and ability to speak, and its Spellcasting\
      \ action.\n\nThe new form's attacks count as magical for the purpose of overcoming\
      \ resistances and immunity to nonmagical attacks."
    "name": "Change Shape (2/Day)"
"source":
  - "MPMM"
  - "VGM"
"image": "Compendium/bestiary/humanoid/token/archdruid-mpmm.webp"
```
^statblock

## Environment

forest, mountain, swamp, underwater