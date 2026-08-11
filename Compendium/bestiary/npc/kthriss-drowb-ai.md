---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/ai
- source/monster/cr/3
- source/monster/size/medium
- source/monster/type/humanoid/drow-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "K'thriss Drow'b"
---
# [K'thriss Drow'b](Compendium/bestiary/npc/kthriss-drowb-ai.md)
*Source: Acquisitions Incorporated p. 202*  

> [!quote]  
> 
> All things are divided into meat and mouths-but even a mouth is just meat.

The drow warlock K'thriss Drow'b cuts a dashing figure as the worldly representative of the Ur-a ravenous, inscrutable, and largely indifferent elder entity from beyond reality. Tapped into this dark power, the "C" Team's hoards person sees all existence as a puzzle to unlock, and he is obsessed by the essential lack of meaning and purpose in the structures of so-called "reality." Still, all things considered, he is most often polite and affable. Because after a long adventuring career, he understands that he can't afford to make more enemies.

Given his blue skin tone, rumors suggest that K'thriss is of mixed heritage, but no one knows for sure. As a young and doubting adherent of Lolth, he stumbled upon fragments of a relic known as the Black Altar, exposing him to their infinite truths and shocking the drow's hair jet-black. His matching "beard" is actually a slow-growing colony of inert spores that K'thriss believes makes him look distinguished. Possessed of alarming and asymmetric crystalline eyes, he often wears a blindfold to spare others his visage, seeing through the eyes of his familiar while he does.

Tentacles play a big part in K'thriss's spellcasting, whether wrenching him through the sky when he uses magic to fly, or manifesting in dark, suckered form when he casts spells such as thorn whip. And when enemies hear K'thriss whisper the deep truths of the Ur-typically something about how on a geologic time scale, everyone's desires are meaningless-they remember it.

K'thriss's familiar, Ligotti, is a semi-sapient remnant of a tentacle attack, spawned by the warlock's intercessor patron god. Though entirely alien to the material plane (and often appearing in the form of a staff), Ligotti uses the stat block of a poisonous snake with these changes:

- It has an Intelligence score of 12 (+2).  
- It has telepathy out to a range of 30 feet.  

```statblock
"name": "K'thriss Drow'b (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "Drow elf"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"ac_class": "[studded leather](Compendium/items/studded-leather-armor.md)"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "11"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "strength": !!int "0"
  - "dexterity": !!int "3"
  - "constitution": !!int "2"
  - "intelligence": !!int "3"
  - "wisdom": !!int "3"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Arcana](Rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[Insight](Rules/skills.md#Insight)"
    "desc": "+2"
  - "name": "[Investigation](Rules/skills.md#Investigation)"
    "desc": "+4"
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Religion](Rules/skills.md#Religion)"
    "desc": "+4"
"gear":
  - "[sickle](Compendium/items/sickle.md)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 120 ft., passive Perception 12"
"languages": "Celestial, Common, Elvish, Undercommon; can read all writing"
"cr": "3"
"traits":
  - "desc": "K'thriss is a 5th-level spellcaster. His spellcasting ability is Charisma\
      \ (spell save DC 14, +6 to hit with spell attacks). He regains his expended\
      \ spell slots when he finishes a short or long rest, and knows the following\
      \ warlock spells:\n\n**Cantrips (at will):** [chill touch](Compendium/spells/chill-touch.md),\
      \ [eldritch blast](Compendium/spells/eldritch-blast.md), [mending](Compendium/spells/mending.md),\
      \ [prestidigitation](Compendium/spells/prestidigitation.md), [thorn whip](Compendium/spells/thorn-whip.md),\
      \ [vicious mockery](Compendium/spells/vicious-mockery.md)\n\n**1st-3rd level\
      \ (2 slots):** [dissonant whispers](Compendium/spells/dissonant-whispers.md),\
      \ [fly](Compendium/spells/fly.md), [hex](Compendium/spells/hex.md), [misty step](Compendium/spells/misty-step.md),\
      \ [sending](Compendium/spells/sending.md), [shatter](Compendium/spells/shatter.md)"
    "name": "Spellcasting"
  - "desc": "K'thriss's innate spellcasting ability is Charisma (spell save DC 14).\
      \ He can innately cast the following spells, requiring no material components:\n\
      \n**At will:** [dancing lights](Compendium/spells/dancing-lights.md), [disguise\
      \ self](Compendium/spells/disguise-self.md)\n\n**1/day each:** [darkness](Compendium/spells/darkness.md),\
      \ [faerie fire](Compendium/spells/faerie-fire.md)"
    "name": "Innate Spellcasting"
  - "desc": "K'thriss wears a [robe of stars](Compendium/items/robe-of-stars.md) (accounted\
      \ for in his statistics). The robe allows him to cast the following spells:\
      \ 6/day: [magic missile](Compendium/spells/magic-missile.md) (7 missiles)"
    "name": "Special Equipment"
  - "desc": "K'thriss can telepathically speak to any creature he can see within 30\
      \ feet of him, provided the creature can understand at least one language."
    "name": "Awakened Mind"
  - "desc": "K'thriss has advantage on saving throws against being [charmed](Rules/conditions.md#Charmed),\
      \ and magic can't put him to sleep. Sunlight Sensitivity. While in sunlight,\
      \ K'thriss has disadvantage on attack rolls, as well as on Wisdom ([Perception](Rules/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Fey Ancestry"
"actions":
  - "desc": "K'thriss makes two attacks with his sickle."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4\
      \ + 2) slashing damage."
    "name": "Sickle"
"source":
  - "AI"
"image": "Compendium/bestiary/npc/token/kthriss-drowb-ai.webp"
```
^statblock