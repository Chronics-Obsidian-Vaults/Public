---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/12
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Remnant Chosen"
---
# [Remnant Chosen](Compendium/bestiary/humanoid/remnant-chosen-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 139*  

> [!quote]  
> 
> Cycles within cycles, turning evermore. Do not think that the One-Who-Whispers is gone, and shall return again. That is an ignorant understanding of the Cycle of Inevitability. Instead understand that the Holy Susurrus ebbs and recedes like the tide. When the Tide of Whispers has withdrawn, the initiated are invested with a sacred charge: to prepare the world for the turning of that Tide, for the return of the Whispered One. When that sacred and holy day is upon us once more, the Ineffable Whispers will be heard not just by the sanctified, but by all thinking creatures, and woe, woe betide those who do not fall down in worship.

Empowered by the essentially never-dying essence of their lord, the Whispered One, those who remain under his sway and fulfill their part in his unknowable schemes are granted secret knowledge and powers that strip away the perceived fallacies of society and the world around them, baring the terrible truths that only aid to further indoctrinate the faithful.

All followers of the Whispered One are zealous followers of their god-to-be. Every cultist spends hours in silent meditation, hoping to hear their long-dead master whisper a commandment from beyond the veil. For most, this meditation is fruitless.

But some do hear the whispers. In the silence of their meditation, the spectral voice of the Whispered One worms its way into their emptied minds, filling their heads with words of power. Fragments of the Whispered One's ancient arcane might boils within their blood, granting them spells unseen since the Age of Arcanum.

```statblock
"name": "Remnant Chosen (TalDorei)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Compendium/spells/mage-armor.md)"
"hp": !!int "116"
"hit_dice": "18d8 + 36"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "14"
  - !!int "15"
  - !!int "16"
  - !!int "20"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "6"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Arcana](Rules/skills.md#Arcana)"
    "desc": "+11"
  - "name": "[Deception](Rules/skills.md#Deception)"
    "desc": "+9"
"damage_resistances": "damage from spells"
"damage_immunities": "necrotic"
"senses": "[truesight](Rules/senses.md#Truesight) 60 ft., passive Perception 13"
"languages": "Common, Infernal, Abyssal"
"cr": "12"
"traits":
  - "desc": "The Chosen is an 18th-level spellcaster. Its spellcasting ability is\
      \ Charisma (spell save DC 17, +9 to hit with spell attacks). The Chosen has\
      \ the following sorcerer spells prepared:\n\n**Cantrips (at will):** [chill\
      \ touch](Compendium/spells/chill-touch.md), [dancing lights](Compendium/spells/dancing-lights.md),\
      \ [mage hand](Compendium/spells/mage-hand.md), [message](Compendium/spells/message.md),\
      \ [shocking grasp](Compendium/spells/shocking-grasp.md)\n\n**1st level (4 slots):**\
      \ [charm person](Compendium/spells/charm-person.md), [expeditious retreat](Compendium/spells/expeditious-retreat.md),\
      \ [mage armor](Compendium/spells/mage-armor.md)*, [shield](Compendium/spells/shield.md)\n\
      \n**2nd level (3 slots):** [blindness/deafness](Compendium/spells/blindness-deafness.md),\
      \ [darkness](Compendium/spells/darkness.md), [detect thoughts](Compendium/spells/detect-thoughts.md)\n\
      \n**3rd level (3 slots):** [counterspell](Compendium/spells/counterspell.md),\
      \ [fly](Compendium/spells/fly.md), [hypnotic pattern](Compendium/spells/hypnotic-pattern.md)\n\
      \n**4th level (3 slots):** [confusion](Compendium/spells/confusion.md), [greater\
      \ invisibility](Compendium/spells/greater-invisibility.md)*\n\n**5th level (3\
      \ slots):** [dominate person](Compendium/spells/dominate-person.md), [scrying](Compendium/spells/scrying.md),\
      \ [seeming](Compendium/spells/seeming.md)\n\n**6th level (1 slots):** [eyebite](Compendium/spells/eyebite.md)\n\
      \n**7th level (1 slots):** [finger of death](Compendium/spells/finger-of-death.md)\n\
      \n**8th level (1 slots):** [power word stun](Compendium/spells/power-word-stun.md)\n\
      \n**9th level (1 slots):** [power word kill](Compendium/spells/power-word-kill.md)\n\
      \n**The Chosen typically casts these spells on itself before combat.*"
    "name": "Spellcasting"
  - "desc": "As a bonus action, the Chosen may select a creature or object affected\
      \ by an illusion spell of 4th level or lower. One illusion of the Chosen's choice\
      \ affecting that creature is instantly dispelled."
    "name": "All-Seeing Eye"
  - "desc": "The Chosen has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Spell Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 37 (5d6\
      \ + 20) force damage. If this damage reduces the target to 0 hit points, it\
      \ is [disintegrated](Compendium/spells/disintegrate.md)."
    "name": "Withered Hand"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Remnant_Chosen.png"
```
^statblock