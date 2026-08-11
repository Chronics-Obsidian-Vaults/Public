---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/ggr
- source/monster/cr/5
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mind Mage"
---
# [Mind Mage](Compendium/bestiary/humanoid/mind-mage-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 233*  

Dimir mind mages are among the most feared spellcasters in Ravnica, thanks in large part to the aura of mystery that shrouds them and their work. Their ability to read and alter memories commands respect from the other members of House Dimir and makes them useful in the full spectrum of the guild's activities. Many mind mages lead cells of their own.

```statblock
"name": "Mind Mage (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Compendium/spells/mage-armor.md)"
"hp": !!int "49"
"hit_dice": "11d8"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "20"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "8"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Arcana](Rules/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[Deception](Rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Insight](Rules/skills.md#Insight)"
    "desc": "+5"
  - "name": "[Persuasion](Rules/skills.md#Persuasion)"
    "desc": "+6"
"gear":
  - "[dagger](Compendium/items/dagger.md)"
"senses": "passive Perception 12"
"languages": "Common plus any four languages"
"cr": "5"
"traits":
  - "desc": "The mage's spellcasting ability is Intelligence (spell save DC 16). It\
      \ can innately cast the following spells, requiring no components:\n\n**At will:**\
      \ [encode thoughts](Compendium/spells/encode-thoughts-ggr.md) (see chapter 2),\
      \ [friends](Compendium/spells/friends.md)\n\n**3/day each:** [charm person](Compendium/spells/charm-person.md),\
      \ [detect thoughts](Compendium/spells/detect-thoughts.md), [mage armor](Compendium/spells/mage-armor.md),\
      \ [sleep](Compendium/spells/sleep.md), [suggestion](Compendium/spells/suggestion.md)\n\
      \n**1/day each:** [dominate person](Compendium/spells/dominate-person.md), [mass\
      \ suggestion](Compendium/spells/mass-suggestion.md), [modify memory](Compendium/spells/modify-memory.md)"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "The mage wears a [spies' murmur](Compendium/items/spies-murmur-ggr.md)\
      \ (see chapter 5)."
    "name": "Special Equipment"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "GGR"
"image": "Compendium/bestiary/humanoid/token/mind-mage-ggr.webp"
```
^statblock