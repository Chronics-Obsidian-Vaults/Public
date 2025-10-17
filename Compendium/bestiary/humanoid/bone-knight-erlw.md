---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/erlw
- source/monster/cr/5
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bone Knight
---
# [Bone Knight](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\humanoid/bone-knight-erlw.md)
*Source: Eberron: Rising from the Last War p. 316*  

Bone knights are the champions of the Order of the Emerald Claw. Clad in distinctive bonecraft armor—heavy armor adorned with the bones of fallen enemies—these fearsome warriors command squads of undead soldiers as they pursue the sinister goals of Lady Illmarrow.

## Karrnathi Patriots

Early in the Last War, Karrnath turned to the necromancers of the Blood of Vol to bolster the nation's army with undead forces. The skeletons and zombies created by the necromancers were mindless creatures that required guidance. The first bone knights were appointed to provide this control.

Devoted paladins of the Blood of Vol were fused into suits of bonecraft armor, whose magic focused their divine gifts, allowing them to command units of mindless undead. Bonecraft armor can't be removed without killing the knight who wears it, and when donning it, each bone knight understood that their former life was over.

## The Fall of the Emerald Claw

During the Last War, many bone knights took service with the Order of the Emerald Claw, helping that name strike fear into the enemies of Karrnath. In the last decade, King Kaius III of Karrnath has done much to ensure a peaceful end to the Last War. Under the terms of the Treaty of Thronehold, Kaius sealed most of Karrnath's undead in deep vaults, and the Order of the Emerald Claw was disbanded. A few bone knights remained in service to the crown, but most were cast aside—still bound to their bonecraft armor and still convinced of Karrnathi supremacy. These bone knights felt that Kaius had betrayed both them and their nation, leading their once-proud order to find a new purpose in the service of Lady Illmarrow.

```statblock
"name": "Bone Knight (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Good alignment"
"ac": !!int "20"
"ac_class": "bonecraft armor"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "5"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Athletics](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Deception](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Intimidation](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Intimidation)"
    "desc": "+6"
"damage_resistances": "necrotic, poison"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "5"
"traits":
  - "desc": "The knight is an 8th-level spellcaster. Its spellcasting ability is Charisma\
      \ (spell save DC 14, +6 to hit with spell attacks). It has the following paladin\
      \ spells prepared:\n\n**1st level (4 slots):** [command](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/command.md),\
      \ [compelled duel](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/compelled-duel.md),\
      \ [hellish rebuke](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/hellish-rebuke.md),\
      \ [wrathful smite](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/wrathful-smite.md)\n\
      \n**2nd level (3 slots):** [branding smite](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/branding-smite.md),\
      \ [crown of madness](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/crown-of-madness.md),\
      \ [darkness](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/darkness.md),\
      \ [find steed](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/find-steed.md),\
      \ [magic weapon](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/magic-weapon.md)"
    "name": "Spellcasting"
  - "desc": "As a bonus action, the knight can target one skeleton or zombie it can\
      \ see within 30 feet of it. The target must make a DC 14 Wisdom saving throw.\
      \ On a failed save, the target must obey the knight's commands until the knight\
      \ dies or until the knight releases it as a bonus action. The knight can command\
      \ up to twelve undead at a time this way."
    "name": "Commander of Bones"
  - "desc": "While within 60 feet of the knight, any undead ally of the knight has\
      \ advantage on saving throws against any effect that turns undead."
    "name": "Master of the Pallid Banner"
"actions":
  - "desc": "The knight attacks twice with one of its weapons."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage."
    "name": "Greatsword"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 150/600 ft., one target. *Hit:*\
      \ 5 (1d8 + 1) piercing damage."
    "name": "Longbow"
"source":
  - "ERLW"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/token/bone-knight-erlw.webp"
```
^statblock