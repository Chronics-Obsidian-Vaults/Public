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
- "Remnant Cultist"
---
# [Remnant Cultist](Compendium/bestiary/humanoid/remnant-cultist-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 139*  

> [!quote]  
> 
> Cycles within cycles, turning evermore. Do not think that the One-Who-Whispers is gone, and shall return again. That is an ignorant understanding of the Cycle of Inevitability. Instead understand that the Holy Susurrus ebbs and recedes like the tide. When the Tide of Whispers has withdrawn, the initiated are invested with a sacred charge: to prepare the world for the turning of that Tide, for the return of the Whispered One. When that sacred and holy day is upon us once more, the Ineffable Whispers will be heard not just by the sanctified, but by all thinking creatures, and woe, woe betide those who do not fall down in worship.

Empowered by the essentially never-dying essence of their lord, the Whispered One, those who remain under his sway and fulfill their part in his unknowable schemes are granted secret knowledge and powers that strip away the perceived fallacies of society and the world around them, baring the terrible truths that only aid to further indoctrinate the faithful.

All cultists of the Whispered One endure horrific rites of initiation that forever shackle them to the will of the cult leaders. Every cultist can feel the presence of their foul god just beyond the fabric of the physical world, and many claim to hear him speaking to them when the rest of the world is silent, urging them to prepare for his resurrection, either by secretly molding society to accept his return, or by concocting rituals that hasten his rebirth.

```statblock
"name": "Remnant Cultist (TalDorei)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "16 with [mage armor](Compendium/spells/mage-armor.md)"
"hp": !!int "4"
"hit_dice": "11d8 + 11"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "12"
  - !!int "18"
  - !!int "8"
  - !!int "8"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Deception](Rules/skills.md#Deception)"
    "desc": "+7"
  - "name": "[Stealth](Rules/skills.md#Stealth)"
    "desc": "+7"
"damage_resistances": "necrotic, psychic"
"senses": "passive Perception 9"
"languages": "Common, Infernal"
"cr": "7"
"traits":
  - "desc": "The remnant cultist is an 11th-level spellcaster. Its spellcasting ability\
      \ is Intelligence (spell save DC 16, +8 to hit with spell attacks). The cultist\
      \ has the following wizard spells prepared:\n\n**Cantrips (at will):** [chill\
      \ touch](Compendium/spells/chill-touch.md), [message](Compendium/spells/message.md),\
      \ [minor illusion](Compendium/spells/minor-illusion.md), [prestidigitation](Compendium/spells/prestidigitation.md),\
      \ [ray of frost](Compendium/spells/ray-of-frost.md)\n\n**1st level (4 slots):**\
      \ [detect magic](Compendium/spells/detect-magic.md), [mage armor](Compendium/spells/mage-armor.md),\
      \ [shield](Compendium/spells/shield.md), [tasha's hideous laughter](Compendium/spells/tashas-hideous-laughter.md)\n\
      \n**2nd level (3 slots):** [detect thoughts](Compendium/spells/detect-thoughts.md),\
      \ [suggestion](Compendium/spells/suggestion.md)\n\n**3rd level (3 slots):**\
      \ [counterspell](Compendium/spells/counterspell.md), [fear](Compendium/spells/fear.md),\
      \ [vampiric touch](Compendium/spells/vampiric-touch.md)\n\n**4th level (3 slots):**\
      \ [greater invisibility](Compendium/spells/greater-invisibility.md), [phantasmal\
      \ killer](Compendium/spells/phantasmal-killer.md)\n\n**5th level (2 slots):**\
      \ [dream](Compendium/spells/dream.md), [mislead](Compendium/spells/mislead.md)\n\
      \n**6th level (1 slots):** [circle of death](Compendium/spells/circle-of-death.md)"
    "name": "Spellcasting"
  - "desc": "Any attempt to form a mental link with the remnant cultist, scry the\
      \ cultist, or cast [speak with dead](Compendium/spells/speak-with-dead.md) on\
      \ a cultist instantly fails, and the creature that initiated the attempt takes\
      \ 6d6 psychic damage."
    "name": "Unknowable Secrets"
  - "desc": "The cultist has disadvantage on any attack roll made against a target\
      \ more than 30 feet away."
    "name": "One-Eyed"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft., range 20/60\
      \ ft., one target. *Hit:* 5 (1d4 + 3) piercing damage. Hit points lost to this\
      \ weapon's damage can be regained only through a short or long rest, rather\
      \ than by regeneration, magic, or any other means.\n\nOnce per turn, the cultist\
      \ may choose to wound its target. At the start of each of the wounded creature's\
      \ turns, it takes 1d4 necrotic damage for each time the cultist wounded it,\
      \ and it can then make a DC 15 Constitution saving throw, ending the effect\
      \ of all such wounds on itself on a success. Alternatively, the wounded creature,\
      \ or a creature within 5 feet of it, can use an action to make a DC 15 Wisdom\
      \ (Medicine) check, ending the effect of such wounds on it on a success."
    "name": "Dagger of Wounding"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Remnant_Cultist.png"
```
^statblock