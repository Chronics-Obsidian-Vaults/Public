---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/bmt
- source/monster/cr/18
- source/monster/size/medium
- source/monster/type/monstrosity/druid
- source/monster/type/monstrosity/medusa
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Euryale"
---
# [Euryale](Compendium/bestiary/npc/euryale-bmt.md)
*Source: The Book of Many Things p. 189*  

When she retired from adventuring, Euryale relocated to Cair Ophidian, a small hideaway in the Outlands detailed later in chapter 22. There, Euryale embraced the quiet life of a gardener, and she spends her time tending to the plants she's cultivated around her home. However, should Asteria call for her aid, Euryale would venture across the multiverse without hesitation, battling tooth and nail to protect her sister.

Euryale has the petrifying gaze and venomous snaky hair of other medusas. But as an ancient and powerful druid, Euryale often adopts the form of a hulking serpent when threatened. She has attained precise control over her petrifying gaze, rendering her immune to its effects and allowing her to use it while not in her medusa guise. Despite her alarming appearance in serpent form, Euryale remains a healer and caretaker at heart.

```statblock
"name": "Euryale (BMT)"
"size": "Medium"
"type": "monstrosity"
"subtype": "druid, medusa"
"alignment": "Neutral Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "297"
"hit_dice": "35d8 + 140"
"modifier": !!int "3"
"stats":
  - !!int "21"
  - !!int "16"
  - !!int "18"
  - !!int "12"
  - !!int "20"
  - !!int "15"
"speed": "30 ft., 50 ft. in serpent form"
"saves":
  - "dexterity": !!int "9"
  - "constitution": !!int "10"
  - "intelligence": !!int "7"
  - "wisdom": !!int "11"
"skillsaves":
  - "name": "[Animal Handling](Rules/skills.md#Animal%20Handling)"
    "desc": "+11"
  - "name": "[Insight](Rules/skills.md#Insight)"
    "desc": "+17"
  - "name": "[Medicine](Rules/skills.md#Medicine)"
    "desc": "+11"
  - "name": "[Nature](Rules/skills.md#Nature)"
    "desc": "+13"
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+11"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Rules/conditions.md#Charmed), [frightened](Rules/conditions.md#Frightened),\
  \ [petrified](Rules/conditions.md#Petrified), [poisoned](Rules/conditions.md#Poisoned)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 21"
"languages": "Common, Druidic"
"cr": "18"
"traits":
  - "desc": "If Euryale fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Euryale carries one half of a pair of [Sending Stones](Compendium/items/sending-stones.md);\
      \ the other half of the pair is held by Asteria."
    "name": "Special Equipment"
"actions":
  - "desc": "Euryale makes three attacks. If she is in serpent form, only one of these\
      \ attacks can be Constrict."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 15 ft., one Large or smaller\
      \ creature. *Hit:* 16 (2d10 + 5) bludgeoning damage, and the target has the\
      \ [grappled](Rules/conditions.md#Grappled) condition (escape DC 19). Until this\
      \ grapple ends, the target takes 11 (2d10) bludgeoning damage at the start of\
      \ each of its turns, and Euryale can't constrict another target."
    "name": "Constrict (Serpent Form Only)"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:* 12\
      \ (2d6 + 5) piercing damage, and the target must succeed on a DC 18 Constitution\
      \ saving throw or have the [poisoned](Rules/conditions.md#Poisoned) condition\
      \ until the start of Euryale's next turn."
    "name": "Snake Bite"
  - "desc": "*Ranged Spell Attack:* +11 to hit, range 120 ft., one target. *Hit:*\
      \ 18 (4d8) acid damage."
    "name": "Verdant Bolt (Medusa Form Only)"
  - "desc": "Euryale casts one of the following spells, requiring no material components\
      \ and using Wisdom as the spellcasting ability (spell save DC 19):\n\n**At will:**\
      \ [Druidcraft](Compendium/spells/druidcraft.md), [Pass without Trace](Compendium/spells/pass-without-trace.md)\n\
      \n**2/day each:** [Goodberry](Compendium/spells/goodberry.md), [Lesser Restoration](Compendium/spells/lesser-restoration.md),\
      \ [Locate Creature](Compendium/spells/locate-creature.md), [Move Earth](Compendium/spells/move-earth.md),\
      \ [Transport via Plants](Compendium/spells/transport-via-plants.md)"
    "name": "Spellcasting (Medusa Form Only)"
"bonus_actions":
  - "desc": "Euryale changes shape into her Huge serpent form or back into her Medium\
      \ medusa form. Euryale's game statistics are the same in each form except where\
      \ noted in this stat block. Any equipment she is wearing or carrying isn't transformed.\
      \ Euryale reverts to her medusa form if she dies."
    "name": "Change Shape"
  - "desc": "Euryale unleashes petrifying magic from her eyes in a 30-foot cone. Each\
      \ creature in that area must make a DC 18 Constitution saving throw if it doesn't\
      \ have the [blinded](Rules/conditions.md#Blinded) condition. If the saving throw\
      \ fails by 5 or more, the creature has the [petrified](Rules/conditions.md#Petrified)\
      \ condition. Otherwise, on a failed save, the creature takes 14 (4d6) force\
      \ damage, begins to turn to stone, and has the [restrained](Rules/conditions.md#Restrained)\
      \ condition. The [restrained](Rules/conditions.md#Restrained) creature must\
      \ repeat the saving throw at the end of its next turn. On a failed save, it\
      \ has the [petrified](Rules/conditions.md#Petrified) condition, and on a successful\
      \ save, the effect ends on it, The petrification lasts until the creature is\
      \ freed by the [Greater Restoration](Compendium/spells/greater-restoration.md)\
      \ spell or other magic A creature can use its reaction, if available, to shut\
      \ its eyes to avoid the saving throw. If the creature does so, it has the [blinded](Rules/conditions.md#Blinded)\
      \ condition until the end of its next turn."
    "name": "Petrifying Gaze (Recharge 4-6)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Euryale can expend a use to take one of the following actions. Euryale regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Euryale moves up to her speed."
    "name": "Move"
  - "desc": "Euryale makes one Snake Bite attack. If the target has the [poisoned](Rules/conditions.md#Poisoned)\
      \ condition, the attack deals an extra 16 (3d10) poison damage."
    "name": "Venomous Strike (Costs 2 Actions)"
"source":
  - "BMT"
"image": "Compendium/bestiary/npc/token/euryale-bmt.webp"
```
^statblock