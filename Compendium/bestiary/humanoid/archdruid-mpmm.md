---
obsidianUIMode: preview
cssclasses: json5e-monster
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
- Archdruid
---
# [Archdruid](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\humanoid/archdruid-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 48, Volo's Guide to Monsters p. 210*  

Archdruids watch over the natural wonders of their domains. They seldom interact with folk away from their druid groves and shrines, unless there is a great threat to the natural order or to a nearby community. An archdruid typically has one or more pupils who are [druids](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/druid.md), and the archdruid's lair is usually guarded by loyal Beasts and Fey creatures.

When an archdruid uses their Change Shape action, you may choose the creature they turn into, abiding by the action's restrictions. Or you may roll on the Archdruid Favored Shapes table to determine the form the archdruid adopts.

**Archdruid Favored Shapes**

| dice: d8 | Favored Shape |
|----------|---------------|
| 1 | [Air elemental](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/elemental/air-elemental.md) |
| 2 | [Earth elemental](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/elemental/earth-elemental.md) |
| 3 | [Fire elemental](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/elemental/fire-elemental.md) |
| 4 | [Giant crocodile](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/beast/giant-crocodile.md) |
| 5 | [Mammoth](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/beast/mammoth.md) |
| 6 | [Flail snail](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/elemental/flail-snail-mpmm.md) |
| 7 | [Triceratops](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/beast/triceratops.md) |
| 8 | [Water elemental](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/elemental/water-elemental.md) |
^archdruid-favored-shapes

```statblock
"name": "Archdruid (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "druid"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[hide armor](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/items/hide-armor.md)"
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
  - "name": "[Medicine](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Medicine)"
    "desc": "+9"
  - "name": "[Nature](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Nature)"
    "desc": "+5"
  - "name": "[Perception](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Perception)"
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
      \ (6d6 + 5) fire damage, and the target is [blinded](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Blinded)\
      \ until the start of the druid's next turn."
    "name": "Wildfire"
  - "desc": "The archdruid casts one of the following spells, using Wisdom as the\
      \ spellcasting ability (spell save DC 17):\n\n**At will:** [beast sense](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/beast-sense.md),\
      \ [entangle](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/entangle.md),\
      \ [speak with animals](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/speak-with-animals.md)\n\
      \n**3/day each:** [animal messenger](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/animal-messenger.md),\
      \ [dominate beast](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/dominate-beast.md),\
      \ [faerie fire](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/faerie-fire.md),\
      \ [tree stride](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/tree-stride.md)\n\
      \n**1/day each:** [commune with nature](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/commune-with-nature.md)\
      \ (as an action), [mass cure wounds](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/mass-cure-wounds.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The archdruid magically transforms into a Beast or an Elemental with\
      \ a challenge rating of 6 or less and can remain in that form for up to 9 hours.\
      \ The archdruid can choose whether its equipment falls to the ground, melds\
      \ with its new form, or is worn by the new form. The archdruid reverts to its\
      \ true form if it dies or falls [unconscious](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Unconscious).\
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
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/token/archdruid-mpmm.webp"
```
^statblock

## Environment

forest, mountain, swamp, underwater