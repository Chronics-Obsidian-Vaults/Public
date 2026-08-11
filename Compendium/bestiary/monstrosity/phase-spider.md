---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/mm
- source/monster/cr/3
- source/monster/environment/desert
- source/monster/environment/forest
- source/monster/environment/grassland
- source/monster/environment/hill
- source/monster/environment/underdark
- source/monster/environment/urban
- source/monster/size/large
- source/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Phase Spider"
---
# [Phase Spider](Compendium/bestiary/monstrosity/phase-spider.md)
*Source: Monster Manual p. 334. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

A phase spider possesses the magical ability to phase in and out of the Ethereal Plane. It seems to appear out of nowhere and quickly vanishes after attacking. Its movement on the Ethereal Plane before coming back to the Material Plane makes it seem like it can teleport.

```statblock
"name": "Phase Spider"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "32"
"hit_dice": "5d10 + 5"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "15"
  - !!int "12"
  - !!int "6"
  - !!int "10"
  - !!int "6"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Stealth](Rules/skills.md#Stealth)"
    "desc": "+6"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 10"
"languages": ""
"cr": "3"
"traits":
  - "desc": "As a bonus action, the spider can magically shift from the Material Plane\
      \ to the Ethereal Plane, or vice versa."
    "name": "Ethereal Jaunt"
  - "desc": "The spider can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The spider ignores movement restrictions caused by webbing."
    "name": "Web Walker"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:* 7\
      \ (1d10 + 2) piercing damage, and the target must make a DC 11 Constitution\
      \ saving throw, taking 18 (4d8) poison damage on a failed save, or half as much\
      \ damage on a successful one. If the poison damage reduces the target to 0 hit\
      \ points, the target is stable but [poisoned](Rules/conditions.md#Poisoned)\
      \ for 1 hour, even after regaining hit points, and is [paralyzed](Rules/conditions.md#Paralyzed)\
      \ while [poisoned](Rules/conditions.md#Poisoned) in this way."
    "name": "Bite"
"source":
  - "MM"
"image": "Compendium/bestiary/monstrosity/token/phase-spider.webp"
```
^statblock

## Environment

underdark, grassland, forest, hill, urban, desert