---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/9
- source/monster/size/large
- source/monster/type/humanoid/orc
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ravager Slaughter Lord"
---
# [Ravager Slaughter Lord](Compendium/bestiary/humanoid/ravager-slaughter-lord-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 137*  

Whether driven by resentment for being shunned by the fairer folk, or consumed by the burning fury that still drives them since the corruption of the Ruiner's blood in the Calamity, most orcs are a chaotic force of destruction. They are a threat to civilization, to be sure, but more a mindless force of nature than a coordinated menace.

However, with each generation, some orcs grow smarter: more organized, learning from their foes, and understanding the might in well-led numbers. This growing horde of calculating, ruthless murder is known as the Ravagers, and with each defeat, they learn. And grow stronger still.

Nearly every orc tribe of the Dividing Plains has joined the Ravagers, and most do so willingly. Orc warchiefs, hungry for recognition in the single burning eye of their god, turn to the Ravagers as a way to fight greater battles, kill stronger foes, and win bloodier spoils. The few war chiefs whose deeds live up to their ambitions soon find themselves leading an arm of the Ravagers—and honored by the title of Slaughter Lord. A Slaughter Lord craves combat like it craves food, and leads Ravager raids as often as possible, but is frequently forced to remain at its stronghold because of its strict regimen of alchemical treatments.

A small army of shamans and alchemists attend to the Slaughter Lords in order to artificially enhance their already-tremendous strength. The blessings and concoctions crafted by the orc-lords' lackeys grow their muscular forms to mountainous size, sharpen their tactical reasoning, and bestow upon them the divine protection of the One-Eyed Ruiner. While their unnatural size is a Slaughter Lord's most obvious martial advantage—it dual-wields weapons most humans could only wield with two hands—the Ruiner's blessings grant it tremendous divine magic. Rumors abound of brave warriors being slain or blinded by a single guttural utterance.

The people of the Dividing Plains do not know exactly how many Slaughter Lords command the Ravagers. Some reason that there are four major arms of the barbarian horde, and that each arm is commanded by one of these monsters. Inside the walls of the margrave of Westruun's keep, however, Margrave Zimmerset and his councilors worry over a graver matter: the Ravagers are too well-organized to be led by war-crazed, drug-addled orcs. Who, or what, is commanding the Slaughter Lords from the shadows?

```statblock
"name": "Ravager Slaughter Lord (TalDorei)"
"size": "Large"
"type": "humanoid"
"subtype": "orc"
"alignment": "Lawful Evil"
"ac": !!int "17"
"hp": !!int "152"
"hit_dice": "16d8 + 80"
"modifier": !!int "2"
"stats":
  - !!int "22"
  - !!int "14"
  - !!int "20"
  - !!int "12"
  - !!int "16"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "7"
  - "strength": !!int "10"
  - "constitution": !!int "9"
"skillsaves":
  - "name": "[Intimidation](Rules/skills.md#Intimidation)"
    "desc": "+11"
  - "name": "[Religion](Rules/skills.md#Religion)"
    "desc": "+5"
"gear":
  - "[spear](Compendium/items/spear.md)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 13"
"languages": "Common, Orc"
"cr": "9"
"traits":
  - "desc": "The Slaughter Lord has been showered with a cocktail of divine blessings,\
      \ and can call upon them at any time. Its innate spellcasting ability is Wisdom\
      \ (spell save DC 15). The Slaughter Lord can innately cast the following spells,\
      \ requiring no material components:\n\n**At will:** [thaumaturgy](Compendium/spells/thaumaturgy.md)\n\
      \n**3/day each:** [flame strike](Compendium/spells/flame-strike.md), [spirit\
      \ guardians](Compendium/spells/spirit-guardians.md)\n\n**1/day each:** [control\
      \ weather](Compendium/spells/control-weather.md), [divine word](Compendium/spells/divine-word.md),\
      \ [fire storm](Compendium/spells/fire-storm.md)"
    "name": "Blessings of the Ruiner"
  - "desc": "As a bonus action, the Slaughter Lord can move up to its speed toward\
      \ a hostile creature it can see."
    "name": "Aggressive"
  - "desc": "If the Ravager Slaughter Lord fails a saving throw, it can choose to\
      \ succeed instead."
    "name": "Legendary Resistance (2/Day)"
  - "desc": "While the Slaughter Lord is wearing no armor and not wielding a shield,\
      \ its AC equals 10 + its Dexterity modifier + its Constitution modifier."
    "name": "Unarmored Defense"
"actions":
  - "desc": "The Slaughter Lord makes four attacks with its greatswords or three attacks\
      \ with its spear."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d6 + 6) piercing damage plus 3 (1d6) fire damage."
    "name": "Dual Greatswords"
  - "desc": "*Melee  or Ranged Weapon Attack:* +10 to hit, range 20/60 ft., one target.\
      \ *Hit:* 13 (2d6 + 6) piercing damage plus 3 (1d6) fire damage, or 15 (2d8 +\
      \ 6) piercing damage plus 3 (1d6) fire damage if used with both hands to make\
      \ a melee attack."
    "name": "Spear"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the slaughter lord can expend a use to take one of the following actions.\
  \ The slaughter lord regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The Slaughter Lord makes a spear or greatsword attack."
    "name": "Attack"
  - "desc": "Slaughter Lord moves up to half its speed."
    "name": "Move"
  - "desc": "The Slaughter Lord casts an innate spell."
    "name": "Cast a Spell (Costs 3 Actions)"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Ravager_Slaughter_Lord.png"
```
^statblock