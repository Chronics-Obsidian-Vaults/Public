---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/2
- source/monster/size/large
- source/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Plainscow"
---
# [Plainscow](Compendium/bestiary/beast/plainscow-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 59*  

Native to Dividing Plains is the hulking plainscow, an exceptionally sturdy beast of burden and used by the people of central Tal'Dorei for centuries. Though herds of wild plainscows still roam the prairies, domesticated plainscows are now used as mounts, pack animals, and sometimes even livestock. Plainscows are unusually empathetic for beasts, and often bond with a rider for life. Plainscows stand 6 feet tall, weigh about two tons, and live for 70 years. They can be bought in Westruun for 200 gp and have a carrying capacity of 1,500 pounds.

```statblock
"name": "Plainscow (TalDorei)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"modifier": !!int "-1"
"stats":
  - !!int "18"
  - !!int "8"
  - !!int "16"
  - !!int "2"
  - !!int "10"
  - !!int "6"
"speed": "40 ft."
"skillsaves":
  - "name": "[Insight](Rules/skills.md#Insight)"
    "desc": "+2"
"damage_resistances": "bludgeoning, piercing, slashing"
"senses": "passive Perception 10"
"languages": ""
"cr": "2"
"traits":
  - "desc": "If the plainscow moves at least 20 feet straight toward a creature and\
      \ then hits it with a hooves attack on the same turn, that target must succeed\
      \ on a DC 14 Strength saving throw or be knocked [prone](Rules/conditions.md#Prone).\
      \ If the target is [prone](Rules/conditions.md#Prone), the plainscow can make\
      \ another attack with its hooves as a bonus action."
    "name": "Trampling Charge"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) bludgeoning damage."
    "name": "Hooves"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Plainscow.png"
```
^statblock