---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/5
- source/monster/size/large
- source/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cinderslag Elemental"
---
# [Cinderslag Elemental](Compendium/bestiary/elemental/cinderslag-elemental-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 130*  

> [!quote] A quote from Master Smith Drunneq Bronzegrip  
> 
> Furthermore, don't you believe that nonsense about rare metals, already refined, found in the remains of a cinderslag. That's so much old smelters' tales! You go seeking a cinderslag, and ye'll get yourself murdered and set on fire, and if ye're very lucky, t'will happen in that order!

Cinderslag elementals are pure manifestations of the hatred and furor of the deceased Cinder King, Thordak. Even in death, Thordak's fires manage to ravage Emon, as places scorched by his corrupting flames are transformed into vitriolic pits of slag and ash, spawning these mindless engines of destruction. Most notably, Thordak's Crater in Emon's Cloudtop District is a spawning pit of cinderslag elementals, though they cannot—or at least, do not—leave the crater. Beyond Thordak's Crater, the Scar of the Cinder King is a breeding ground for more of these mindless elementals, as are the ruins of Serpent's Head in the Cliffkeep Mountains, and the Ashen Gorge in the Stormcrest Mountains.

A cinderslag's molten gaze is a weapon of incredible power, capable of melting steel and stone with a single glance. If an elemental's gaze were focused on buildings over the course of a few hours, or if several elementals worked in unison, entire cities could be leveled in a tide of molten stone. Fortunately for the people of Emon, Thordak's elemental spawn are mindless and incapable of unified action—but what if someone were able to bend them to their will?

```statblock
"name": "Cinderslag Elemental (TalDorei)"
"size": "Large"
"type": "elemental"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "107"
"hit_dice": "12d10 + 36"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "12"
  - !!int "20"
  - !!int "1"
  - !!int "10"
  - !!int "3"
"speed": "20 ft., burrow 40 ft."
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "fire, poison"
"condition_immunities": "[exhaustion](Rules/conditions.md#Exhaustion), [grappled](Rules/conditions.md#Grappled),\
  \ [paralyzed](Rules/conditions.md#Paralyzed), [petrified](Rules/conditions.md#Petrified),\
  \ [poisoned](Rules/conditions.md#Poisoned), [prone](Rules/conditions.md#Prone),\
  \ [restrained](Rules/conditions.md#Restrained), [unconscious](Rules/conditions.md#Unconscious)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 10"
"languages": ""
"cr": "5"
"traits":
  - "desc": "The elemental can move through a space as narrow as 1 inch wide without\
      \ squeezing. A creature that touches the elemental or hits it with a melee attack\
      \ while within 5 feet of it takes 5 (1d10) fire damage. In addition, the elemental\
      \ can enter a hostile creature's space and stop there. The first time it enters\
      \ a creature's space on a turn, that creature takes 5 (1d10) fire damage and\
      \ must make a DC 14 Strength saving throw, becoming [restrained](Rules/conditions.md#Restrained)\
      \ on a failure. When the begins its turn while [restrained](Rules/conditions.md#Restrained)\
      \ in this way, it takes 5 (1d10) fire damage."
    "name": "Molten Form"
  - "desc": "For every 5 feet that elemental moves in water, or for every gallon of\
      \ water splashed on it, it takes 1 cold damage."
    "name": "Water Susceptibility"
"actions":
  - "desc": "The elemental makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (3d6 + 2) bludgeoning damage plus 5 (1d10) fire damage. If the target is a\
      \ creature or a flammable object, it ignites. Until a creature takes an action\
      \ to douse the fire, the target takes 5 (1d10) fire damage at the start of each\
      \ of its turns."
    "name": "Slam"
  - "desc": "*Ranged Spell Attack:* +8 to hit, range 30 ft., one target. *Hit:* 21\
      \ (6d6) fire damage and the target must makze a DC 14 Constitution saving throw.\
      \ On a failure, one nonmagical item the target is carrying instantly melts or\
      \ burns to cinders."
    "name": "Molten Gaze"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Cinderslag_Elemental.png"
```
^statblock