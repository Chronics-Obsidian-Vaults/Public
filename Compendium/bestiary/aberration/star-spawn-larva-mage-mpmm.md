---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/mpmm
- source/monster/cr/16
- source/monster/environment/mountain
- source/monster/size/medium
- source/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- Star Spawn Larva Mage
---
# [Star Spawn Larva Mage](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\aberration/star-spawn-larva-mage-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 228, Mordenkainen's Tome of Foes p. 235, The Book of Many Things*  

A larva mage is a nightmarish combination of a mortal body and otherworldly substance. When a powerful cultist of a wormlike entity such as Kyuss or Kezef—usually a warlock or other spellcaster—contacts the comet-borne emissary of an Elder Evil, the emissary can merge with a mortal consciousness to create a larva mage. None of the original cultist's personality survives the transformation; what emerges is wholly alien.

## Star Spawn

> [!quote] A quote from Mordenkainen  
> 
> Stars don't spawn these creatures.
> 
> Such beautiful lights shouldn't be blamed for such balefulness.

The Material Plane represents only one small part of the multiverse. Beyond the best-known planes of existence lie realms alien to mortal life. Some are so hostile that even a moment's contact is enough to break a mortal's mind. Yet beings do exist that are native to these realms: entities that are ever hungering, searching, warring, and sometimes dreaming. These Elder Evils are far older than most of the mortal peoples and always inimical to such creatures' minds.

However much they might desire to enter and dominate the Material Plane, the Elder Evils are unable or unwilling to leave their realms. Some are imprisoned in their dimensions by external forces, some are inextricably bound to their home realities, and others simply can't find any way out.

The creatures known as star spawn are the heralds, servants, and soldiers of the Elder Evils, capable of taking on forms that can journey to the Material Plane. They arrive most often in the wake of a comet—or perhaps this phenomenon merely signals that star spawn are in the vicinity and available for communication. When the signs are right, cultists gather together, read aloud their blasphemous texts, and conduct the mind-searing rituals that guide star spawn into the world.

### Elder Evil Blessings

Disciples of certain Elder Evils can bestow supernatural gifts on those who serve that cult, including star spawn. The following powers are unique to specific cults; typically a creature has only one.

- Cult of Atropus, the World Born Dead  
- Cult of Borem, of the Lake of Boiling Mud  
- Cult of Haask, the Voice of Hargut  
- Cult of Tharizdun, the Chained God  
- Cult of Tyranthraxus, the Flamed One  

```statblock
"name": "Star Spawn Larva Mage (MPMM)"
"size": "Medium"
"type": "aberration"
"alignment": "Typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "168"
"hit_dice": "16d8 + 96"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "12"
  - !!int "23"
  - !!int "18"
  - !!int "12"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "6"
  - "wisdom": !!int "6"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Perception](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Perception)"
    "desc": "+6"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Charmed),\
  \ [frightened](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Frightened),\
  \ [paralyzed](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Paralyzed),\
  \ [petrified](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Petrified),\
  \ [poisoned](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Poisoned),\
  \ [restrained](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Restrained)"
"senses": "[darkvision](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 16"
"languages": "Deep Speech"
"cr": "16"
"traits":
  - "desc": "When the mage is reduced to 0 hit points, it breaks apart into a [swarm\
      \ of insects](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/beast/swarm-of-insects.md)\
      \ in the same space. Unless the swarm is destroyed, the mage reforms from it\
      \ 24 hours later."
    "name": "Return to Worms"
"actions":
  - "desc": "The mage makes three Slam or Eldritch Bolt attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:* 7\
      \ (1d8 + 3) bludgeoning damage, and the target must succeed on a DC 19 Constitution\
      \ saving throw or be [poisoned](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Poisoned)\
      \ until the end of its next turn."
    "name": "Slam"
  - "desc": "*Ranged Spell Attack:* +8 to hit, range 60 ft., one target. *Hit:* 19\
      \ (3d10 + 3) force damage."
    "name": "Eldritch Bolt"
  - "desc": "Each creature other than a star spawn within 10 feet of the mage must\
      \ succeed on a DC 19 Dexterity saving throw or take 22 (5d8) necrotic damage\
      \ and be [blinded](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Blinded)\
      \ and [restrained](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Restrained)\
      \ by masses of swarming worms. The affected creature takes 22 (5d8) necrotic\
      \ damage at the start of each of the mage's turns. The creature can repeat the\
      \ saving throw at the end of each of its turns, ending the effect on itself\
      \ on a success."
    "name": "Plague of Worms (Recharge 6)"
  - "desc": "The mage casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 16):\n\n**At\
      \ will:** [mage hand](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/mage-hand.md),\
      \ [message](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/message.md),\
      \ [minor illusion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/minor-illusion.md)\n\
      \n**1/day:** [dominate monster](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/dominate-monster.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "When a creature within 20 feet of the mage fails a saving throw, the\
      \ mage gains 10 temporary hit points."
    "name": "Feed on Weakness"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the star spawn larva mage can expend a use to take one of the following\
  \ actions. The star spawn larva mage regains all expended uses at the start of each\
  \ of its turns."
"legendary_actions":
  - "desc": "The mage makes one Slam attack."
    "name": "Slam"
  - "desc": "The mage makes one Eldritch Bolt attack."
    "name": "Eldritch Bolt (Costs 2 Actions)"
  - "desc": "Each creature [restrained](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Restrained)\
      \ by the mage's Plague of Worms takes 13 (3d8) necrotic damage, and the mage\
      \ gains 6 temporary hit points."
    "name": "Feed (Costs 3 Actions)"
"source":
  - "MPMM"
  - "MTF"
  - "BMT"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/aberration/token/star-spawn-larva-mage-mpmm.webp"
```
^statblock

## Environment

mountain