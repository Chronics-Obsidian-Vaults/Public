---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/vgm
- source/monster/cr/6
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Booyahg Slave of the Great Old One"
---
# [Booyahg Slave of the Great Old One](Compendium/bestiary/humanoid/booyahg-slave-of-the-great-old-one-vgm.md)
*Source: Volo's Guide to Monsters p. 42*  

This goblin warlock serves a patron who can extract payment in flesh if the goblin doesn't do as promised. Often this patron is a coven of hags serving as the tribe's boss, a fiend that has made its way into the world, or an undying lord such as a lich or a vampire. (For more information on undying lord patrons, see the "Sword Coast Adventurer's Guide").

## Booyahgs

Spellcasters of any sort among the goblins are rare. Goblins typically lack the intelligence and patience needed to learn and practice wizardry, and they fare poorly even when given access to the necessary training and knowledge. Sorcerers are less prevalent among them than in many other races, and Khurgorbaeyag seems to dislike sharing his divine power with his followers. And although many goblins would readily offer anything to have the abilities of a warlock, the patrons that grant such power know a goblin is unlikely to be able to uphold its end of any bargain.

Even when a goblin is born with the ability to become a spellcaster, the knowledge and talent necessary to carry on the tradition rarely persists for more than a couple of generations. Because they have so little experience with magic, goblins make no distinction between its forms. To them all magic is "booyahg," and the word is part of the name they give to any of its practitioners.

A goblin with access to booyahg becomes a member of the lashers and can often rise to the role of boss.

```statblock
"name": "Booyahg Slave of the Great Old One (VGM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Compendium/spells/mage-armor.md)"
"hp": !!int "91"
"hit_dice": "14d8 + 28"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "15"
  - !!int "12"
  - !!int "12"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "4"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Arcana](Rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[History](Rules/skills.md#History)"
    "desc": "+4"
"damage_resistances": "psychic"
"gear":
  - "[dagger](Compendium/items/dagger.md)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., [darkvision](Rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 11"
"languages": "any two languages, telepathy 30 ft., Goblin"
"cr": "6"
"traits":
  - "desc": "The goblin is a 14th-level spellcaster. Its spellcasting ability is Charisma\
      \ (spell save DC 15, +7 to hit with spell attacks). It regains its expended\
      \ spell slots when it finishes a short or long rest. It knows the following\
      \ warlock spells:\n\n**Cantrips (at will):** [chill touch](Compendium/spells/chill-touch.md),\
      \ [eldritch blast](Compendium/spells/eldritch-blast.md), [guidance](Compendium/spells/guidance.md),\
      \ [mage hand](Compendium/spells/mage-hand.md), [minor illusion](Compendium/spells/minor-illusion.md),\
      \ [prestidigitation](Compendium/spells/prestidigitation.md), [shocking grasp](Compendium/spells/shocking-grasp.md)\n\
      \n**1st-5th level (3 slots):** [armor of Agathys](Compendium/spells/armor-of-agathys.md),\
      \ [arms of Hadar](Compendium/spells/arms-of-hadar.md), [crown of madness](Compendium/spells/crown-of-madness.md),\
      \ [clairvoyance](Compendium/spells/clairvoyance.md), [contact other plane](Compendium/spells/contact-other-plane.md),\
      \ [detect thoughts](Compendium/spells/detect-thoughts.md), [dimension door](Compendium/spells/dimension-door.md),\
      \ [dissonant whispers](Compendium/spells/dissonant-whispers.md), [dominate beast](Compendium/spells/dominate-beast.md),\
      \ [telekinesis](Compendium/spells/telekinesis.md), [vampiric touch](Compendium/spells/vampiric-touch.md)"
    "name": "Spellcasting"
  - "desc": "The goblin's innate spellcasting ability is Charisma. It can innately\
      \ cast the following spells (spell save DC 15), requiring no material components:\n\
      \n**At will:** [detect magic](Compendium/spells/detect-magic.md), [jump](Compendium/spells/jump.md),\
      \ [levitate](Compendium/spells/levitate.md), [mage armor](Compendium/spells/mage-armor.md)\
      \ (self only), [speak with dead](Compendium/spells/speak-with-dead.md)\n\n**1/day\
      \ each:** [arcane gate](Compendium/spells/arcane-gate.md), [true seeing](Compendium/spells/true-seeing.md)"
    "name": "Innate Spellcasting"
  - "desc": "At the start of each of the goblin's turns, each creature of its choice\
      \ within 5 feet of it must succeed on a DC 15 Wisdom saving throw or take 10\
      \ (3d6) psychic damage, provided that the goblin isn't [incapacitated](Rules/conditions.md#Incapacitated)."
    "name": "Whispering Aura"
  - "desc": "The goblin"
    "name": "Nimble Escape"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "VGM"
"image": "Compendium/bestiary/humanoid/token/booyahg-slave-of-the-great-old-one-vgm.webp"
```
^statblock