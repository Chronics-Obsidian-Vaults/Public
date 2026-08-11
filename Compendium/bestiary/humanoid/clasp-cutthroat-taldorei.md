---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/3
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Clasp Cutthroat"
---
# [Clasp Cutthroat](Compendium/bestiary/humanoid/clasp-cutthroat-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 131*  

For all its notoriety, the Clasp is largely a business empire run by smaller pocket families of 'spirelings' who oversee local illegal business and contracted work. Some Clasp are merely messengers, or thrive on intimidation. If conflict arises, and the problem can't be quelled, then the heavy hitters/assassins are brought in to 'clean up the mess.'

When the thieves and assassins of the Clasp need to 'acquire' additional funds or 'relieve' specific people of their possessions, their cutthroats are the first to be called. Clasp cutthroats can also represent any number of different rogues within the thieves' guilds of Tal'Dorei

```statblock
"name": "Clasp Cutthroat (TalDorei)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Lawful alignment"
"ac": !!int "14"
"ac_class": "[leather armor](Compendium/items/leather-armor.md)"
"hp": !!int "71"
"hit_dice": "8d8 + 8"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "12"
  - !!int "8"
  - !!int "14"
  - !!int "9"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
"skillsaves":
  - "name": "[Stealth](Rules/skills.md#Stealth)"
    "desc": "+7"
  - "name": "[Deception](Rules/skills.md#Deception)"
    "desc": "+3"
"gear":
  - "[dagger](Compendium/items/dagger.md)"
  - "[shortsword](Compendium/items/shortsword.md)"
"senses": "passive Perception 12"
"languages": "Common, Thieves' cant"
"cr": "3"
"traits":
  - "desc": "On each of its turns, the cutthroat can use a bonus action to take the\
      \ Dash, Disengage, or Hide action."
    "name": "Cunning Action"
  - "desc": "The cutthroat deals an extra 14 (4d6) damage when it hits a target with\
      \ a weapon attack and has advantage on the attack roll, or when the target is\
      \ within 5 feet of an ally of the cutthroat that isn't [incapacitated](Rules/conditions.md#Incapacitated)\
      \ and the cutthroat doesn't have disadvantage on the attack roll."
    "name": "Sneak Attack (1/Turn)"
"actions":
  - "desc": "The cutthroatmakes two shortsword or dagger attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6\
      \ + 3) piercing damage."
    "name": "Shortsword"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft., range 20/60\
      \ ft., one target. *Hit:* 5 (1d4 + 3) piercing damage."
    "name": "Dagger"
"reactions":
  - "desc": "When an attacker that the cutthroat can see\n\nhits it with an attack,\
      \ the cutthroat takes half damage instead."
    "name": "Uncanny Dodge"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Clasp_Cutthroat.png"
```
^statblock