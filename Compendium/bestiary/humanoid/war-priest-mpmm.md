---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/mpmm
- source/monster/cr/9
- source/monster/environment/desert
- source/monster/environment/urban
- source/monster/size/medium
- source/monster/type/humanoid/cleric
statblock: inline
statblock-link: "#^statblock"
aliases:
- War Priest
---
# [War Priest](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\humanoid/war-priest-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 254, Volo's Guide to Monsters p. 218*  

War priests worship deities of war, protection, and strategy. They plan tactics, lead soldiers into battle, confront enemy spellcasters, and tend to casualties. A war priest might command an army or serve as the right hand of a [warlord](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/warlord-mpmm.md) (appears in "this book") on the battlefield.

War priests typically adorn themselves with a symbol of their faith. You can roll on the War Priest Holy Symbols table below, or choose one that fits your campaign.

**War Priest Holy Symbols**

| dice: d8 | Holy Symbol |
|----------|-------------|
| 1 | Vial of iridescent liquid |
| 2 | Hilt of a broken sword |
| 3 | Piece of stained glass from a shrine |
| 4 | Clay figurine of a [ki-rin](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/celestial/ki-rin-mpmm.md) or another Celestial |
| 5 | [Torch](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/items/torch.md) carved so that a hand appears to be holding the flame |
| 6 | Circlet of woven reeds |
| 7 | Scrimshawed bone |
| 8 | Vessel such as a cup, a [jug](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/items/jug.md), an urn, or an amphora |
^war-priest-holy-symbols

```statblock
"name": "War Priest (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "cleric"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[plate](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/items/plate-armor.md)"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "constitution": !!int "6"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Intimidation](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Intimidation)"
    "desc": "+5"
  - "name": "[Religion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Religion)"
    "desc": "+4"
"senses": "passive Perception 13"
"languages": "any two languages"
"cr": "9"
"actions":
  - "desc": "The war priest makes two Maul attacks, and it uses Holy Fire."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) bludgeoning damage  plus *Hit:* 10 (3d6) radiant damage."
    "name": "Maul"
  - "desc": "The war priest targets one creature it can see within 60 feet of it.\
      \ The target must make a DC 15 Wisdom saving throw. On a failed save, the target\
      \ takes 12 (2d8 + 3) radiant damage, and it is [blinded](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Blinded)\
      \ until the start of the war priest's next turn. On a successful save, the target\
      \ takes half as much damage and isn't [blinded](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Blinded)."
    "name": "Holy Fire"
  - "desc": "The war priest casts one of the following spells, using Wisdom as the\
      \ spellcasting ability (spell save DC 15):\n\n**At will:** [light](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/light.md),\
      \ [spare the dying](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/spare-the-dying.md),\
      \ [thaumaturgy](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/thaumaturgy.md)\n\
      \n**1/day each:** [banishment](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/banishment.md),\
      \ [command](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/command.md),\
      \ [dispel magic](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/dispel-magic.md),\
      \ [flame strike](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/flame-strike.md),\
      \ [guardian of faith](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/guardian-of-faith.md),\
      \ [hold person](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/hold-person.md),\
      \ [lesser restoration](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/lesser-restoration.md),\
      \ [revivify](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/revivify.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The war priest or one creature of its choice within 60 feet of it regains\
      \ 12 (2d8 + 3) hit points."
    "name": "Healing Light (Recharge 4-6)"
"source":
  - "MPMM"
  - "VGM"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/token/war-priest-mpmm.webp"
```
^statblock

## Environment

desert, urban