---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/ggr
- source/monster/cr/21
- source/monster/size/gargantuan
- source/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Isperia"
---
# [Isperia](Compendium/bestiary/npc/isperia-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 227*  

Isperia is the current guildmaster of the Azorius Senate. As a sphinx, she is aloof and values solitude above all. However, she has been forced to give up her privacy to deal with the increased crime and chaos on Ravnica.

Isperia is devoted to her guild's belief that law is the ultimate bulwark against chaos, and it is her steady hand that guides the Azorius through these uncertain times. As guildmaster, Isperia serves as the supreme judge, a role that takes advantage of her encyclopedic knowledge of Ravnica's labyrinthine legal system.

If an encounter turns violent, Isperia refrains from using lethal force if possible, preferring to subdue a wrongdoing so that the legal system can mete out justice.

```statblock
"name": "Isperia (GGR)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "261"
"hit_dice": "18d20 + 72"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "18"
  - !!int "23"
  - !!int "26"
  - !!int "20"
"speed": "40 ft., fly 60 ft."
"saves":
  - "dexterity": !!int "9"
  - "constitution": !!int "11"
  - "intelligence": !!int "13"
  - "wisdom": !!int "15"
"skillsaves":
  - "name": "[Arcana](Rules/skills.md#Arcana)"
    "desc": "+13"
  - "name": "[History](Rules/skills.md#History)"
    "desc": "+13"
  - "name": "[Insight](Rules/skills.md#Insight)"
    "desc": "+15"
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+15"
"damage_immunities": "psychic; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](Rules/conditions.md#Charmed), [frightened](Rules/conditions.md#Frightened)"
"senses": "[truesight](Rules/senses.md#Truesight) 120 ft., passive Perception 25"
"languages": "Common, Sphinx"
"cr": "21"
"traits":
  - "desc": "Isperia is a 15th-level Azorius spellcaster. Her spellcasting ability\
      \ is Wisdom (spell save DC 23, +14 to hit with spell attacks). Isperia has the\
      \ following cleric spells prepared:\n\n**Cantrips (at will):** [guidance](Compendium/spells/guidance.md),\
      \ [light](Compendium/spells/light.md), [resistance](Compendium/spells/resistance.md),\
      \ [sacred flame](Compendium/spells/sacred-flame.md), [thaumaturgy](Compendium/spells/thaumaturgy.md)\n\
      \n**1st level (4 slots):** [command](Compendium/spells/command.md), [detect\
      \ evil and good](Compendium/spells/detect-evil-and-good.md), [ensnaring strike](Compendium/spells/ensnaring-strike.md),\
      \ [sanctuary](Compendium/spells/sanctuary.md), [shield of faith](Compendium/spells/shield-of-faith.md)\n\
      \n**2nd level (3 slots):** [arcane lock](Compendium/spells/arcane-lock.md),\
      \ [augury](Compendium/spells/augury.md), [calm emotions](Compendium/spells/calm-emotions.md),\
      \ [hold person](Compendium/spells/hold-person.md), [silence](Compendium/spells/silence.md),\
      \ [zone of truth](Compendium/spells/zone-of-truth.md)\n\n**3rd level (3 slots):**\
      \ [bestow curse](Compendium/spells/bestow-curse.md), [clairvoyance](Compendium/spells/clairvoyance.md),\
      \ [counterspell](Compendium/spells/counterspell.md), [dispel magic](Compendium/spells/dispel-magic.md),\
      \ [tongues](Compendium/spells/tongues.md)\n\n**4th level (3 slots):** [divination](Compendium/spells/divination.md),\
      \ [locate creature](Compendium/spells/locate-creature.md)\n\n**5th level (2\
      \ slots):** [dispel evil and good](Compendium/spells/dispel-evil-and-good.md),\
      \ [scrying](Compendium/spells/scrying.md)\n\n**6th level (1 slots):** [word\
      \ of recall](Compendium/spells/word-of-recall.md)\n\n**7th level (1 slots):**\
      \ [divine word](Compendium/spells/divine-word.md)\n\n**8th level (1 slots):**\
      \ [antimagic field](Compendium/spells/antimagic-field.md)"
    "name": "Spellcasting"
  - "desc": "Isperia's innate spellcasting ability is Wisdom (spell save DC 23). Isperia\
      \ can innately cast [imprisonment](Compendium/spells/imprisonment.md) twice\
      \ per day, requiring no material components.\n"
    "name": "Innate Spellcasting"
  - "desc": "Isperia is immune to any effect that would sense her emotions or read\
      \ her thoughts, as well as any divination spell that she refuses. Wisdom ([Insight](Rules/skills.md#Insight))\
      \ checks made to ascertain her intentions or sincerity have disadvantage."
    "name": "Inscrutable"
  - "desc": "If Isperia fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Isperia has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Isperia makes two claw attacks. She can cast a spell with a casting time\
      \ of 1 action in place of one claw attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:* 21\
      \ (3d10 + 5) slashing damage. If the target is a creature, it must succeed on\
      \ a DC 23 Wisdom saving throw or take 14 (4d6) psychic damage after each attack\
      \ it makes against Isperia before the start of her next turn."
    "name": "Claw"
  - "desc": "Isperia chooses up to three creatures she can see within 90 feet of her.\
      \ Each target must succeed on a DC 23 Intelligence saving throw or Isperia chooses\
      \ an action for that target: [Attack](Rules/actions.md#Attack), [Cast a Spell](Rules/actions.md#Cast%20a%20Spell),\
      \ [Dash](Rules/actions.md#Dash), [Disengage](Rules/actions.md#Disengage), [Dodge](Rules/actions.md#Dodge),\
      \ [Help](Rules/actions.md#Help), [Hide](Rules/actions.md#Hide), [Ready](Rules/actions.md#Ready),\
      \ [Search](Rules/actions.md#Search), or [Use an Object](Rules/actions.md#Use%20an%20Object).\
      \ The affected target can't take that action for 1 minute. At the end of each\
      \ of the target's turns, it can end the effect on itself with a successful DC\
      \ 23 Intelligence saving throw. A target that succeeds on the saving throw becomes\
      \ immune to Isperia's Supreme Legal Authority for 24 hours."
    "name": "Supreme Legal Authority"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Isperia can expend a use to take one of the following actions. Isperia regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Isperia makes one claw attack."
    "name": "Claw Attack"
  - "desc": "Isperia casts a spell of 3rd level or lower from her list of prepared\
      \ spells, using a spell slot as normal."
    "name": "Cast a Spell (Costs 2 Actions)"
  - "desc": "Isperia uses Supreme Legal Authority."
    "name": "Supreme Legal Authority (Costs 3 Actions)"
"source":
  - "GGR"
"image": "Compendium/bestiary/npc/token/isperia-ggr.webp"
```
^statblock