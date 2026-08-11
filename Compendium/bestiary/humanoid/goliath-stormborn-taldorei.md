---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/4
- source/monster/size/medium
- source/monster/type/humanoid/goliath
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Goliath Stormborn"
---
# [Goliath Stormborn](Compendium/bestiary/humanoid/goliath-stormborn-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 133*  

After the fall of Kevdak and the Herd of Storms, the scattered groups of wandering outsiders took to a slightly less violent way of life, instead focusing on forgotten spirituality and survival in the wake of the Conclave's attack. However, some bands of roving warriors now grow either brash, or desperate, leading to savage attacks and raids on outlying camps and caravans.

Countless goliath legends tell of heroes born beneath a raging storm. These stormborn grow to become peerless warriors, blessed with preternatural skill with a blade and the uncanny ability to command lightning itself. As warriors destined to become mythic heroes, stormborn fight with reckless abandon and are often distressingly prideful. Little do they know that destiny is a fickle thing, and that the songs of defeated stormborn (or worse, tyrannical ones) are rarely sung by the bards.

Though the fearsome Herd of Storms was broken at Westruun during the Chroma Crisis, most of the goliaths that made up the herd still roam across the Dividing Plains. Many joined with the Rivermaw Tribe, a vast, nomadic community of goliaths, humans, and other free folk of the plains. What few stormborn remain are now part of the Rivermaw. The next generation of storm children, those who lived through the reign of Kevdak and Umbrasyl, have just entered adulthood. They are ready to forge new legends.

```statblock
"name": "Goliath Stormborn (TalDorei)"
"size": "Medium"
"type": "humanoid"
"subtype": "goliath"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"ac_class": "[hide armor](Compendium/items/hide-armor.md)"
"hp": !!int "85"
"hit_dice": "12d8 + 48"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "18"
  - !!int "9"
  - !!int "11"
  - !!int "9"
"speed": "30 ft."
"saves":
  - "constitution": !!int "6"
"skillsaves":
  - "name": "[Athletics](Rules/skills.md#Athletics)"
    "desc": "+6"
  - "name": "[Intimidation](Rules/skills.md#Intimidation)"
    "desc": "+3"
"damage_resistances": "lightning"
"gear":
  - "[greataxe](Compendium/items/greataxe.md)"
"senses": "passive Perception 10"
"languages": "Common, Giant"
"cr": "4"
"traits":
  - "desc": "The stormborn's innate spellcasting ability is Charisma (spell save DC\
      \ 9). The stormborn can innately cast the following spells, requiring no material\
      \ components:\n\n**3/day:** [lightning bolt](Compendium/spells/lightning-bolt.md)\n\
      \n**1/day:** [call lightning](Compendium/spells/call-lightning.md)"
    "name": "Innate Spellcasting"
  - "desc": "At the start of its turn, the stormborn can gain advantage on all melee\
      \ weapon attack rolls it makes during that turn, but attack rolls against it\
      \ have advantage until the start of its next turn."
    "name": "Reckless"
"actions":
  - "desc": "The stormborn makes two greataxe attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (1d12 + 4) slashing damage plus 7 (2d6) lightning damage. Miss: 3 (1d6) lightning\
      \ damage."
    "name": "Greataxe"
"reactions":
  - "desc": "When the stormborn takes damage, it may reduce the damage by 10 (1d12\
      \ + 4). It cannot use this trait again until it completes a short or long rest."
    "name": "Endurance"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Goliath_Stormborn.png"
```
^statblock