---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/7
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ashari Firetamer"
---
# [Ashari Firetamer](Compendium/bestiary/humanoid/ashari-firetamer-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 128*  

Though the tribes of the Ashari wardens are neutral and spurn the "petty political nonsense" that they consider outsiders to be focused on, it is still all too easy to run afoul of the Ashari. They consider the strange elemental rifts over which they are guardians to be of foremost importance, and it is very easy for strangers to take actions that unknowingly disrupt the delicate balance over which the Ashari carefully watch. Though they are generally friendly to travelers—particularly to travelers in need—they are guarded, and do not hesitate to act to eliminate threats to the elemental powers and their own way of life.

Of all the ashari tribes, the fire ashari of Pyrah have suffered the greatest. Their people were all but destroyed when Thordak burst through the Rift of Flame in his cataclysmic return to Exandria. Yet despite their immense hardships, the fire ashari have given selflessly to the people of Tal'Dorei. Led by a half-orc ashari named Lorkathar, a group of firetamers keep watch over the volatile Scar of the Cinder King on the outskirts of Emon.

Firetamers are the elite elementalists of the Pyrah, using their attunement to the primordial forces of the world to not just create fire, not just command it, but tame it to their will. A firetamer of Pyrah is nothing like the manic pyromancers of Tal'Dorei; while the latter recklessly wields fire as a weapon, firetamers use their talent to protect others from fire's destructive power—or to use that same power to destroy those who threaten their people. Firetamers are almost always accompanied by a salamander, a fire elemental, or a small herd of magma or smoke mephits. While home in Pyrah, ashari firetamers use their power to control the Rift of Flame or to control the flames of the Cindergrove.

```statblock
"name": "Ashari Firetamer (TalDorei)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Good"
"ac": !!int "17"
"ac_class": "[red dragon scale mail](Compendium/items/red-dragon-scale-mail.md)"
"hp": !!int "92"
"hit_dice": "16d8 + 20"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "15"
  - !!int "14"
  - !!int "12"
  - !!int "18"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](Rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Nature](Rules/skills.md#Nature)"
    "desc": "+9"
"damage_resistances": "fire"
"gear":
  - "[scimitar](Compendium/items/scimitar.md)"
"senses": "passive Perception 14"
"languages": "Common, Druidic, Primordial (Ignan)"
"cr": "7"
"traits":
  - "desc": "The firetamer is a 9th-level spellcaster. Its spellcasting ability is\
      \ Wisdom (spell save DC 16, +8 to hit with spell attacks). It has the following\
      \ druid spells prepared:\n\n**Cantrips (at will):** [druidcraft](Compendium/spells/druidcraft.md),\
      \ [mending](Compendium/spells/mending.md), [produce flame](Compendium/spells/produce-flame.md)\n\
      \n**1st level (4 slots):** [cure wounds](Compendium/spells/cure-wounds.md),\
      \ [faerie fire](Compendium/spells/faerie-fire.md), [jump](Compendium/spells/jump.md),\
      \ [longstrider](Compendium/spells/longstrider.md)\n\n**2nd level (3 slots):**\
      \ [flame blade](Compendium/spells/flame-blade.md), [heat metal](Compendium/spells/heat-metal.md),\
      \ [lesser restoration](Compendium/spells/lesser-restoration.md)\n\n**3rd level\
      \ (3 slots):** [daylight](Compendium/spells/daylight.md), [dispel magic](Compendium/spells/dispel-magic.md),\
      \ [protection from energy](Compendium/spells/protection-from-energy.md)\n\n\
      **4th level (3 slots):** [blight](Compendium/spells/blight.md), [freedom of\
      \ movement](Compendium/spells/freedom-of-movement.md), [wall of fire](Compendium/spells/wall-of-fire.md)\n\
      \n**5th level (1 slots):** [conjure elemental](Compendium/spells/conjure-elemental.md)"
    "name": "Spellcasting"
  - "desc": "As a bonus action, the firetamer can transform into a [fire elemental](Compendium/bestiary/elemental/fire-elemental.md).\
      \ While in this form, the firetamer cannot cast spells, but can expend a spell\
      \ slot as a bonus action to regain 1d8 hit points per level of the spell slot\
      \ expended. When the firetamer is reduced to 0 hit points, falls [unconscious](Rules/conditions.md#Unconscious),\
      \ or dies in this form, it reverts to its humanoid form. It can remain in flameform\
      \ for up to 5 hours, and can enter flameform twice, regaining expended uses\
      \ after completing a short or long rest."
    "name": "Flameform."
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) slashing damage plus *Hit:* 14 (4d6) fire damage."
    "name": "Scimitar"
  - "desc": "The firetamer can cast [dominate monster](Compendium/spells/dominate-monster.md)\
      \ (DC 16) on a fire elemental or other fire elemental creature. If the elemental\
      \ has 150 or more hit points, it has advantage on the saving throw."
    "name": "Flamecharm (Recharges after a Short or Long Rest)"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Ashari_Firetamer.png"
```
^statblock