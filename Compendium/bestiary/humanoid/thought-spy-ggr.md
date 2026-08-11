---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/ggr
- source/monster/cr/1
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Thought Spy"
---
# [Thought Spy](Compendium/bestiary/humanoid/thought-spy-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 233*  

Thought spies form the backbone of House Dimir's covert operations. They are trained in stealth and infiltration, tactics that they supplement with rigorously developed mental abilities. To ensure that no secrets slip through Dimir's fingers, they infiltrate rival guilds. In addition to traditional means of gathering intelligence, thought spies use their magic to spy on the thoughts of their targets.

```statblock
"name": "Thought Spy (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "[leather armor](Compendium/items/leather-armor.md)"
"hp": !!int "27"
"hit_dice": "6d8"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "10"
  - !!int "16"
  - !!int "13"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](Rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Insight](Rules/skills.md#Insight)"
    "desc": "+3"
  - "name": "[Investigation](Rules/skills.md#Investigation)"
    "desc": "+5"
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Sleight of Hand](Rules/skills.md#Sleight%20of%20Hand)"
    "desc": "+4"
  - "name": "[Stealth](Rules/skills.md#Stealth)"
    "desc": "+4"
"gear":
  - "[dagger](Compendium/items/dagger.md)"
  - "[rapier](Compendium/items/rapier.md)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 30 ft., passive Perception 13"
"languages": "Common plus any one language"
"cr": "1"
"traits":
  - "desc": "The thought spy's innate spellcasting ability is Intelligence (spell\
      \ save DC 13). The thought spy can innately cast the following spells, requiring\
      \ no components:\n\n**At will:** [charm person](Compendium/spells/charm-person.md),\
      \ [disguise self](Compendium/spells/disguise-self.md), [encode thoughts](Compendium/spells/encode-thoughts-ggr.md)\
      \ (see chapter 2)\n\n**1/day each:** [blur](Compendium/spells/blur.md), [detect\
      \ thoughts](Compendium/spells/detect-thoughts.md), [gaseous form](Compendium/spells/gaseous-form.md)"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "On each of its turns, the thought spy can use a bonus action to take\
      \ the [Dash](Rules/actions.md#Dash), [Disengage](Rules/actions.md#Disengage),\
      \ or [Hide](Rules/actions.md#Hide) action."
    "name": "Cunning Action"
"actions":
  - "desc": "The thought spy makes two melee attacks, or it makes three ranged attacks\
      \ with its daggers."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8\
      \ + 2) piercing damage."
    "name": "Rapier"
"source":
  - "GGR"
"image": "Compendium/bestiary/humanoid/token/thought-spy-ggr.webp"
```
^statblock