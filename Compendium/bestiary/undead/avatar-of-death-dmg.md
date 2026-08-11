---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/dmg
- source/monster/cr/
- source/monster/size/medium
- source/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Avatar of Death"
---
# [Avatar of Death](Compendium/bestiary/undead/avatar-of-death-dmg.md)
*Source: Dungeon Master's Guide p. 164. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Summoned by the "Skull" card from the [Deck of Many Things](Compendium/items/deck-of-many-things.md).

```statblock
"name": "Avatar of Death (DMG)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "20"
"hp": "half the hit point maximum of its summoner"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "16"
  - !!int "16"
  - !!int "16"
  - !!int "16"
  - !!int "16"
"speed": "60 ft., fly 60 ft. (hover)"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](Rules/conditions.md#Charmed), [frightened](Rules/conditions.md#Frightened),\
  \ [paralyzed](Rules/conditions.md#Paralyzed), [petrified](Rules/conditions.md#Petrified),\
  \ [poisoned](Rules/conditions.md#Poisoned), [unconscious](Rules/conditions.md#Unconscious)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., [truesight](Rules/senses.md#Truesight)\
  \ 60 ft., passive Perception 13"
"languages": "all languages known to its summoner"
"traits":
  - "desc": "The avatar can move through other creatures and objects as if they were\
      \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
      \ an object."
    "name": "Incorporeal Movement"
  - "desc": "The avatar is immune to features that turn undead."
    "name": "Turn Immunity"
"actions":
  - "desc": "The avatar sweeps its spectral scythe through a creature within 5 feet\
      \ of it, dealing 7 (1d8 + 3) slashing damage plus 4 (1d8) necrotic damage."
    "name": "Reaping Scythe"
"source":
  - "DMG"
"image": "Compendium/bestiary/undead/token/avatar-of-death-dmg.webp"
```
^statblock