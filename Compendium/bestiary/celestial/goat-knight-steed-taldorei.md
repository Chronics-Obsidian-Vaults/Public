---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/1-2
- source/monster/size/large
- source/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Goat-Knight Steed"
---
# [Goat-Knight Steed](Compendium/bestiary/celestial/goat-knight-steed-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 135*  

The sheer cliff faces and winding winding mountainside roads of the Cliffkeep Mountains are nearly impossible to traverse by normal means with any speed. However, the Peakclimber Knights of Kraghammer—commonly known as the goat-knights—are enforcers of peace and justice across the mountain range, and their giant goat steeds can easily traverse the harsh mountain slopes and climb nearly vertical slopes at their full pace. These knights are in service to the Allhammer, and often find themselves at odds with enforcing the laws of Kraghammer and upholding the edicts of their god.

Travelers lost within the mountains are sometimes saved by a traveling goat-knight, who is able to lead them through dangerous-but-traversable mountain roads.

```statblock
"name": "Goat-Knight Steed (TalDorei)"
"size": "Large"
"type": "celestial"
"alignment": "Unaligned"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "4"
"hit_dice": "3d10 + 3"
"modifier": !!int "0"
"stats":
  - !!int "17"
  - !!int "11"
  - !!int "12"
  - !!int "6"
  - !!int "12"
  - !!int "6"
"speed": "40 ft."
"senses": "passive Perception 11"
"languages": "Dwarvish (comprehends, but can't speak)"
"cr": "1/2"
"traits":
  - "desc": "If the goat-knight steed moves at least 20 feet straight toward a target\
      \ and then hits it with a ram attack on the same turn, the target takes a extra\
      \ 5 (2d4) bludgeoning damage. If the target is a creature, it must succeed on\
      \ a DC 13 Strength saving throw or be knocked [prone](Rules/conditions.md#Prone)."
    "name": "Charge"
  - "desc": "The Goat-Knight Steed has advantage on Strength and Dexterity saving\
      \ throws made against effects that would knock it [prone](Rules/conditions.md#Prone)."
    "name": "Sure-Footed"
  - "desc": "Any spell with a range of Self cast by a [goatknight rider](Compendium/bestiary/humanoid/kraghammer-goat-knight-taldorei.md)\
      \ who is mounted on a goat-knight steed also targets the goat-knight steed."
    "name": "Rider and Steed"
  - "desc": "When the goat-knight steed drops to 0 hit points it disappears, leaving\
      \ behind no physical form. A goat knight can also dismiss his steed at any point\
      \ as an action, causing it to disappear. In either case, the same steed is summoned\
      \ when the goat-knight casts [find steed](Compendium/spells/find-steed.md)."
    "name": "Divine Provenance"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 8 (2d4\
      \ + 3) bludgeoning damage."
    "name": "Ram"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Goat-Knight_Steed.png"
```
^statblock