---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mm
- source/monster/cr/10
- source/monster/environment/desert
- source/monster/environment/forest
- source/monster/size/large
- source/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Guardian Naga"
---
# [Guardian Naga](Compendium/bestiary/monstrosity/guardian-naga.md)
*Source: Monster Manual p. 234. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Wise and good, the beautiful guardian nagas protect sacred places and items of magical power from falling into evil hands. In their hidden redoubts, they research spells and hatch convoluted plots to thwart the evil designs of their enemies.

A guardian naga doesn't seek out violence, warning off intruders rather than attacking. Only if its foes persist does the naga attack, accosting enemies with its spells and poisonous spittle.

## Nagas

Nagas are intelligent serpents that inhabit the ruins of the past, amassing arcane treasures and knowledge.

The first nagas were created as immortal guardians by a humanoid race long lost to history. When this race died out, the nagas deemed themselves the rightful inheritors of their masters' treasures and magical lore. Industrious and driven, nagas occasionally venture out from their lairs to track down magic items or rare spellbooks.

Nagas never feel the ravages of time or succumb to sickness. Even if it is struck down, a naga's immortal spirit reforms in a new body in a matter of days, ready to continue its eternal work.

### Benevolent Dictators and Brutal Tyrants

A naga rules its domain with absolute authority. Whether it rules with compassion or by terrorizing its subjects, the naga believes itself the master of all other creatures that inhabit its domain.

### Rivalry

Nagas have a long-standing enmity with the yuan-ti, with each race seeing itself as the epitome of serpentine evolution. Though cooperation between them is rare, nagas and yuan-ti sometimes set aside their differences to work toward common objectives. However, yuan-ti always chafe under a naga's authority.

### Immortal Nature

A naga doesn't require air, food, drink, or sleep.

```statblock
"name": "Guardian Naga"
"size": "Large"
"type": "monstrosity"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "127"
"hit_dice": "15d10 + 45"
"modifier": !!int "4"
"stats":
  - !!int "19"
  - !!int "18"
  - !!int "16"
  - !!int "16"
  - !!int "19"
  - !!int "18"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "8"
  - "constitution": !!int "7"
  - "intelligence": !!int "7"
  - "wisdom": !!int "8"
  - "charisma": !!int "8"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Rules/conditions.md#Charmed), [poisoned](Rules/conditions.md#Poisoned)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 14"
"languages": "Celestial, Common"
"cr": "10"
"traits":
  - "desc": "The naga is an 11th-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 16, +8 to hit with spell attacks), and it needs only verbal\
      \ components to cast its spells. It has the following cleric spells prepared:\n\
      \n**Cantrips (at will):** [mending](Compendium/spells/mending.md), [sacred flame](Compendium/spells/sacred-flame.md),\
      \ [thaumaturgy](Compendium/spells/thaumaturgy.md)\n\n**1st level (4 slots):**\
      \ [command](Compendium/spells/command.md), [cure wounds](Compendium/spells/cure-wounds.md),\
      \ [shield of faith](Compendium/spells/shield-of-faith.md)\n\n**2nd level (3\
      \ slots):** [calm emotions](Compendium/spells/calm-emotions.md), [hold person](Compendium/spells/hold-person.md)\n\
      \n**3rd level (3 slots):** [bestow curse](Compendium/spells/bestow-curse.md),\
      \ [clairvoyance](Compendium/spells/clairvoyance.md)\n\n**4th level (3 slots):**\
      \ [banishment](Compendium/spells/banishment.md), [freedom of movement](Compendium/spells/freedom-of-movement.md)\n\
      \n**5th level (2 slots):** [flame strike](Compendium/spells/flame-strike.md),\
      \ [geas](Compendium/spells/geas.md)\n\n**6th level (1 slots):** [true seeing](Compendium/spells/true-seeing.md)"
    "name": "Spellcasting"
  - "desc": "If it dies, the naga returns to life in 1d6 days and regains all its\
      \ hit points. Only a [wish](Compendium/spells/wish.md) spell can prevent this\
      \ trait from functioning."
    "name": "Rejuvenation"
"actions":
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one creature. *Hit:*\
      \ 8 (1d8 + 4) piercing damage, and the target must make a DC 15 Constitution\
      \ saving throw, taking 45 (10d8) poison damage on a failed save, or half as\
      \ much damage on a successful one."
    "name": "Bite"
  - "desc": "*Ranged Weapon Attack:* +8 to hit, range 15/30 ft., one creature. *Hit:*\
      \ The target must make a DC 15 Constitution saving throw, taking 45 (10d8) poison\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Spit Poison"
"source":
  - "MM"
"image": "Compendium/bestiary/monstrosity/token/guardian-naga.webp"
```
^statblock

## Environment

forest, desert