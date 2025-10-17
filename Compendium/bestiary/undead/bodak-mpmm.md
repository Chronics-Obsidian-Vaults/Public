---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/mpmm
- source/monster/cr/6
- source/monster/environment/swamp
- source/monster/environment/underdark
- source/monster/environment/urban
- source/monster/size/medium
- source/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bodak
---
# [Bodak](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\undead/bodak-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 64, Volo's Guide to Monsters p. 127*  

A bodak is the undying remains of someone who revered Orcus. Devoid of life and soul, it exists only to cause death.

A worshiper of Orcus can take ritual vows while carving the demon lord's symbol on their chest over the heart. Orcus's power flays body, mind, and soul, leaving behind a sentient husk that consumes life energy near it. Most bodaks come into being in this way, then are unleashed to spread death in Orcus's name.

Bodaks are extensions of Orcus's will outside the Abyss, serving the demon prince's aims and other minions. Orcus can recall anything a bodak sees or hears. If he so chooses, he can speak through a bodak to address his enemies and followers directly.

A bodak retains vague impressions of its past life. It seeks out its former allies and enemies alike to destroy them, as its warped soul seeks to erase anything connected to its former life. Minions of Orcus are the one exception to this compulsion; a bodak recognizes them as kindred souls and spares them from its wrath. Anyone who knew the individual before its transformation into a bodak can recognize mannerisms or other subtle clues to its original identity.

```statblock
"name": "Bodak (MPMM)"
"size": "Medium"
"type": "undead"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"modifier": !!int "3"
"stats":
  - !!int "15"
  - !!int "16"
  - !!int "15"
  - !!int "7"
  - !!int "12"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "cold; fire; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Charmed),\
  \ [frightened](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Frightened),\
  \ [poisoned](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Poisoned)"
"senses": "[darkvision](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/senses.md#Darkvision)\
  \ 120 ft., passive Perception 14"
"languages": "Abyssal, the languages it knew in life"
"cr": "6"
"traits":
  - "desc": "When a creature that can see the bodak's eyes starts its turn within\
      \ 30 feet of the bodak, the bodak can force it to make a DC 13 Constitution\
      \ saving throw if the bodak isn't [incapacitated](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Incapacitated)\
      \ and can see the creature. If the saving throw fails by 5 or more, the creature\
      \ is reduced to 0 hit points unless it is immune to the [frightened](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Frightened)\
      \ condition. Otherwise, a creature takes 16 (3d10) psychic damage on a failed\
      \ save.\n\nUnless [surprised](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Surprised),\
      \ a creature can avert its eyes to avoid the saving throw at the start of its\
      \ turn. If the creature does so, it has disadvantage on attack rolls against\
      \ the bodak until the start of its next turn. If the creature looks at the bodak\
      \ in the meantime, that creature must immediately make the saving throw."
    "name": "Death Gaze"
  - "desc": "The bodak takes 5 radiant damage when it starts its turn in sunlight.\
      \ While in sunlight, it has disadvantage on attack rolls and ability checks."
    "name": "Sunlight Hypersensitivity"
  - "desc": "The bodak doesn't require air, food, drink, or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 4 (1d4\
      \ + 2) bludgeoning damage plus 9 (2d8) necrotic damage."
    "name": "Fist"
  - "desc": "One creature that the bodak can see within 60 feet of it must make a\
      \ DC 13 Constitution saving throw, taking 22 (4d10) necrotic damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Withering Gaze"
"bonus_actions":
  - "desc": "The bodak activates or deactivates this deathly aura. While active, the\
      \ aura deals 5 necrotic damage to any creature that ends its turn within 30\
      \ feet of the bodak. Undead and Fiends ignore this effect."
    "name": "Aura of Annihilation"
"source":
  - "MPMM"
  - "VGM"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/undead/token/bodak-mpmm.webp"
```
^statblock

## Environment

swamp, underdark, urban