---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/4
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ashari Waverider"
---
# [Ashari Waverider](Compendium/bestiary/humanoid/ashari-waverider-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 129*  

Though the tribes of the Ashari wardens are neutral and spurn the "petty political nonsense" that they consider outsiders to be focused on, it is still all too easy to run afoul of the Ashari. They consider the strange elemental rifts over which they are guardians to be of foremost importance, and it is very easy for strangers to take actions that unknowingly disrupt the delicate balance over which the Ashari carefully watch. Though they are generally friendly to travelers—particularly to travelers in need—they are guarded, and do not hesitate to act to eliminate threats to the elemental powers and their own way of life.

The waveriders of Vesrah know firsthand the dangers of the open ocean, and dedicate their lives to protecting seafarers from storms, pirates, and sea monsters. Though they are not warriors, they are accomplished healers and aquatic empaths, using their powers to seek out and rescue survivors of marine disasters, sometimes returning critically wounded survivors to Vesrah itself. The isolationist water ashari condemn this practice, fearing that the refugees threaten their way of life. The waveriders take their peers' scorn in stride, for they would rather be righteous than popular.

A waverider turns to violence only as a last resort, and prefer to fight in fishform than with their fishing harpoon, using hit-and-run tactics as a shark or their octopus form's natural camouflage to harry opponents. When patrolling the open seas, waveriders skim across the water on personal waveboards with folding sails, similar in function to the skysails of the Zephrah.

```statblock
"name": "Ashari Waverider (TalDorei)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Good"
"ac": !!int "14"
"ac_class": "[hide armor of cold resistance](Compendium/items/armor-of-cold-resistance.md)"
"hp": !!int "77"
"hit_dice": "14d8 + 14"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "16"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Nature](Rules/skills.md#Nature)"
    "desc": "+3"
  - "name": "[Athletics](Rules/skills.md#Athletics)"
    "desc": "+8"
"damage_resistances": "cold"
"senses": "passive Perception 13"
"languages": "Common, Druidic, Primordial (Aquan)"
"cr": "4"
"traits":
  - "desc": "The waverider is a 7th-level spellcaster. Its spellcasting ability is\
      \ Wisdom (spell save DC 14, +6 to hit with spell attacks). It has the following\
      \ druid spells prepared:\n\n**Cantrips (at will):** [druidcraft](Compendium/spells/druidcraft.md),\
      \ [poison spray](Compendium/spells/poison-spray.md), [resistance](Compendium/spells/resistance.md)\n\
      \n**1st level (4 slots):** [create or destroy water](Compendium/spells/create-or-destroy-water.md),\
      \ [cure wounds](Compendium/spells/cure-wounds.md), [healing word](Compendium/spells/healing-word.md)\n\
      \n**2nd level (3 slots):** [animal messenger](Compendium/spells/animal-messenger.md),\
      \ [enhance ability](Compendium/spells/enhance-ability.md), [lesser restoration](Compendium/spells/lesser-restoration.md)\n\
      \n**3rd level (3 slots):** [conjure animals](Compendium/spells/conjure-animals.md)\
      \ (aquatic beasts only), [water breathing](Compendium/spells/water-breathing.md),\
      \ [water walk](Compendium/spells/water-walk.md)\n\n**4th level (1 slots):**\
      \ [control water](Compendium/spells/control-water.md)"
    "name": "Spellcasting"
  - "desc": "As a bonus action, the waverider can transform into a [hunter shark](Compendium/bestiary/beast/hunter-shark.md)\
      \ or [giant octopus](Compendium/bestiary/beast/giant-octopus.md). While in this\
      \ form, the waverider cannot cast spells, but can expend a spell slot as a bonus\
      \ action to regain 1d8 hit points per level of the spell slot expended. When\
      \ the waverider is reduced to 0 hit points, falls [unconscious](Rules/conditions.md#Unconscious),\
      \ or dies in this form, it reverts to its humanoid form. It can remain in fishform\
      \ for up to 3 hours, and can enter fishform twice, regaining expended uses after\
      \ completing a short or long rest."
    "name": "Fishform"
  - "desc": "Whenever the waverider casts a spell of 1st level or higher that affects\
      \ a nonhostile creature, that creature regains 3 hit points (in addition to\
      \ any healing the spell may provide)."
    "name": "Healing Tides"
  - "desc": "The waverider can speak with and understand aquatic plants and animals."
    "name": "Marine Empathy"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. range 20/60\
      \ ft., one target. *Hit:* 5 (1d6 + 2) piercing damage. Attacks with this weapon\
      \ while underwater are not made with disadvantage."
    "name": "Harpoon"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Ashari_Waverider.png"
```
^statblock