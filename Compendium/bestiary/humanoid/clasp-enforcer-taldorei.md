---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/5
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Clasp Enforcer"
---
# [Clasp Enforcer](Compendium/bestiary/humanoid/clasp-enforcer-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 131*  

For all its notoriety, the Clasp is largely a business empire run by smaller pocket families of 'spirelings' who oversee local illegal business and contracted work. Some Clasp are merely messengers, or thrive on intimidation. If conflict arises, and the problem can't be quelled, then the heavy hitters/assassins are brought in to 'clean up the mess.'

The Clasp prefers to operate within the shadows, but sometimes targets of blackmail need a little "convincing." Whenever scare tactics and brute force are needed, the Clasp's musclebound enforcers make quite an impression.

```statblock
"name": "Clasp Enforcer (TalDorei)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Lawful alignment"
"ac": !!int "16"
"ac_class": "[half plate armor](Compendium/items/half-plate-armor.md)"
"hp": !!int "102"
"hit_dice": "12d8 + 48"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "8"
  - !!int "8"
  - !!int "11"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](Rules/skills.md#Athletics)"
    "desc": "+6"
  - "name": "[Intimidation](Rules/skills.md#Intimidation)"
    "desc": "+8"
"gear":
  - "[shortsword](Compendium/items/shortsword.md)"
"senses": "passive Perception 10"
"languages": "Common, Thieves' cant"
"cr": "5"
"traits":
  - "desc": "Whenever the enforcer hits with a melee attack, the target must make\
      \ a DC 15 Wisdom saving throw. On a failure, the target is [frightened](Rules/conditions.md#Frightened)\
      \ of the enforcer until the end of its next turn. The enforcer's allies have\
      \ advantage on attack rolls against creatures [frightened](Rules/conditions.md#Frightened)\
      \ in this way."
    "name": "Intimidating Presence"
  - "desc": "As a bonus action, the enforcer can regain 12 hit points."
    "name": "Second Wind (Recharges after a Short or Long Rest)"
"actions":
  - "desc": "The enforcer makes three warhammer attacks."
    "name": "Multiattack"
  - "desc": "Warhammer. Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:*\
      \ 8 (1d10 + 3) bludgeoning damage."
    "name": "Shortsword"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Clasp_Enforcer.png"
```
^statblock