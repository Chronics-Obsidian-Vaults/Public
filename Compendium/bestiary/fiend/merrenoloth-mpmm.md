---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mpmm
- source/monster/cr/3
- source/monster/environment/coastal
- source/monster/size/medium
- source/monster/type/fiend/yugoloth
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Merrenoloth"
---
# [Merrenoloth](Compendium/bestiary/fiend/merrenoloth-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 180, Mordenkainen's Tome of Foes p. 250*  

The grim captains of the ferries on the River Styx, merrenoloths can navigate safely through the worst storms and always stay on course. Wielding fiery oars, merrenoloths strike fear into anyone who forcefully boards their vessels.

```statblock
"name": "Merrenoloth (MPMM)"
"size": "Medium"
"type": "fiend"
"subtype": "yugoloth"
"alignment": "Typically  Neutral Evil"
"ac": !!int "13"
"hp": !!int "40"
"hit_dice": "9d8"
"modifier": !!int "3"
"stats":
  - !!int "8"
  - !!int "17"
  - !!int "10"
  - !!int "17"
  - !!int "14"
  - !!int "11"
"speed": "30 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "5"
  - "intelligence": !!int "5"
"skillsaves":
  - "name": "[History](Rules/skills.md#History)"
    "desc": "+5"
  - "name": "[Nature](Rules/skills.md#Nature)"
    "desc": "+5"
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Survival](Rules/skills.md#Survival)"
    "desc": "+4"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "[poisoned](Rules/conditions.md#Poisoned)"
"senses": "[blindsight](Rules/senses.md#Blindsight) 60 ft., [darkvision](Rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 14"
"languages": "Abyssal, Infernal, telepathy 60 ft."
"cr": "3"
"traits":
  - "desc": "The merrenoloth has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The merrenoloth makes one Oar attack and uses Fear Gaze."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 8 (2d4\
      \ + 3) fire damage."
    "name": "Oar"
  - "desc": "The merrenoloth targets one creature it can see within 60 feet of it.\
      \ The target must succeed on a DC 13 Wisdom saving throw or become [frightened](Rules/conditions.md#Frightened)\
      \ of the merrenoloth for 1 minute. The [frightened](Rules/conditions.md#Frightened)\
      \ target can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success."
    "name": "Fear Gaze"
  - "desc": "The merrenoloth casts one of the following spells, requiring no material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 13):\n\n**At will:** [charm person](Compendium/spells/charm-person.md),\
      \ [darkness](Compendium/spells/darkness.md), [detect magic](Compendium/spells/detect-magic.md),\
      \ [dispel magic](Compendium/spells/dispel-magic.md), [gust of wind](Compendium/spells/gust-of-wind.md)\n\
      \n**3/day:** [control water](Compendium/spells/control-water.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The merrenoloth teleports, along with any equipment it is wearing or\
      \ carrying, up to 60 feet to an unoccupied space it can see."
    "name": "Teleport"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties) while captaining a vessel,\
      \ the merrenoloth can take one of the following lair actions; it can't take\
      \ the same lair action two rounds in a row:\n\n- **Gale.** The air within 60\
      \ feet of the vessel is filled with wind. Until initiative count 20 on the next\
      \ round, that area is difficult terrain, and when a Medium or smaller creature\
      \ flies into that area or starts its turn flying there, it must succeed on a\
      \ DC 13 Strength saving throw or be knocked [prone](Rules/conditions.md#Prone).\
      \  \n- **Propel.** A strong wind propels the vessel, increasing its speed by\
      \ 30 feet until initiative count 20 on the next round.  \n- **Repair.** The\
      \ vessel regains 22 (4d10) hit points.  "
    "name": ""
"regional_effects":
  - "desc": "A merrenoloth imbues its vessel with magic that creates one or more of\
      \ the following effects:\n\n- **Unerring.** The vessel always stays on course\
      \ to the destination the merrenoloth names.  \n- **Unsinkable.** The vessel\
      \ doesn't sink even if its hull is breached.  \n\nIf the merrenoloth dies, these\
      \ effects fade over the course of 1d6 hours."
    "name": ""
"source":
  - "MPMM"
  - "MTF"
"image": "Compendium/bestiary/fiend/token/merrenoloth-mpmm.webp"
```
^statblock

## Environment

coastal