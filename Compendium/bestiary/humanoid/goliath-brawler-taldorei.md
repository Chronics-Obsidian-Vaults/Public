---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/3
- source/monster/size/medium
- source/monster/type/humanoid/goliath
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Goliath Brawler"
---
# [Goliath Brawler](Compendium/bestiary/humanoid/goliath-brawler-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 134*  

> [!quote] A quote from Grogan the Bookie  
> 
> Well and damn me if I don't tell you the secret to real joy in this League, me lad: Find yoursel' a fight with one o' them goliaths what favor fisticuffs. Dead silent, like boulders brought to life—none of the roaring and grunting of other fighters. Quiet enough to hear the crunchin' when them fists the size o' hams slam into their opponent. Nothing gets a crowd cheering and bettin' quite like that does, I tell you!

After the fall of Kevdak and the Herd of Storms, the scattered groups of wandering outsiders took to a slightly less violent way of life, instead focusing on forgotten spirituality and survival in the wake of the Conclave's attack. However, some bands of roving warriors now grow either brash, or desperate, leading to savage attacks and raids on outlying camps and caravans.

Some prideful goliaths are so assured in their own strength that they refuse to use weapons. Most goliaths learn how to fist-fight from a young age, but goliath brawlers go so far as to eschew weapons even on the battlefield. Goliath brawlers loyal to the Rivermaw Tribe usually lead the charge on the battlefield, using their exceptional speed and brute strength to throw the enemy vanguard into chaos. 

Beyond the Dividing Plains, goliath brawlers can be found within criminal organizations as muscle, in underground fighting rings, and as personal bodyguards. In Emon, the most famous goliath brawlers have made a name for themselves within the Godsbrawl Ring, representing the Stormlord in the annual holy tournament.

```statblock
"name": "Goliath Brawler (TalDorei)"
"size": "Medium"
"type": "humanoid"
"subtype": "goliath"
"alignment": "Chaotic Neutral"
"ac": !!int "15"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "14"
  - !!int "15"
  - !!int "9"
  - !!int "16"
  - !!int "7"
"speed": "40 ft."
"skillsaves":
  - "name": "[Acrobatics](Rules/skills.md#Acrobatics)"
    "desc": "+4"
  - "name": "[Athletics](Rules/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Perception](Rules/skills.md#Perception)"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": "Common, Giant"
"cr": "3"
"traits":
  - "desc": "While the brawler is wearing no armor and not wielding a shield, its\
      \ AC equals 10 + its Dexterity modifier + its Wisdom modifier."
    "name": "Unarmored Defense"
"actions":
  - "desc": "The brawler makes three unarmed strikes."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) bludgeoning damage. If the target is a creature, the brawler can choose\
      \ one of the following additional effects:\n\n• *Bruise.* The target must succeed\
      \ on a DC 13 Constitution saving throw. On a failure, its speed is reduced by\
      \ 5 feet until it receives at least 1 point of magical healing. A DC 15 Wisdom\
      \ (Medicine) check performed as an action can also restore any lost speed.\n\
      \n• *Disarm.* The target must succeed on a DC 13 Strength saving throw or drop\
      \ one item it is holding. The brawler may choose which item is dropped, and\
      \ may choose to pick it up.\n\n•*Suplex.* The target must succeed on a DC 13\
      \ Strength saving throw or be knocked [prone](Rules/conditions.md#Prone)."
    "name": "Unarmed Strike"
"reactions":
  - "desc": "When the stormborn takes damage, it may reduce the damage by 8 (1d12\
      \ + 2). It cannot use this trait again until it completes a short or long rest."
    "name": "Endurance"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Goliath_Brawler.png"
```
^statblock