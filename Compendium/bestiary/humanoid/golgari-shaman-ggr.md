---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/ggr
- source/monster/cr/5
- source/monster/size/medium
- source/monster/type/humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- Golgari Shaman
---
# [Golgari Shaman](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\humanoid/golgari-shaman-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 236*  

Golgari shamans are the spiritual leaders of the Golgari Swarm. They teach the guild's beliefs about the cycles of nature, using their necromantic magic to show how life sprouts from death.

Golgari shamans paint their faces so they appear to have extra eyes on their cheeks and chins. They sometimes use magical moodmark paint (described in chapter 5) to allow them to communicate by means of these marks. They wear clothing adorned with beetle carapaces, spiderwebs, or shelf fungus.

## Golgari Lairs

Members of the Golgari Swarm have an intimate connection to their territory. When at least six Golgari defend their territory together, they can call on the environment to aid them. The group must include Jarad Vod Savo or at least one Golgari shaman, kraul death priest, undercity medusa, or Devkarin lich. When determining the difficulty of such an encounter, consider the lair to be one additional creature of challenge rating 1.

```statblock
"name": "Golgari Shaman (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "[hide armor](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/items/hide-armor.md)"
"hp": !!int "88"
"hit_dice": "16d8 + 16"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "15"
  - !!int "12"
  - !!int "12"
  - !!int "17"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Arcana](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[Insight](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Nature](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Nature)"
    "desc": "+4"
  - "name": "[Religion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Religion)"
    "desc": "+4"
"senses": "[darkvision](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 13"
"languages": "Common, Elvish"
"cr": "5"
"traits":
  - "desc": "The shaman is an 8th-level Golgari spellcaster. Its spellcasting ability\
      \ is Wisdom (spell save DC 14, +6 to hit with spell attacks). The shaman has\
      \ the following druid spells prepared:\n\n**Cantrips (at will):** [poison spray](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/poison-spray.md),\
      \ [shillelagh](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/shillelagh.md),\
      \ [thorn whip](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/thorn-whip.md)\n\
      \n**1st level (4 slots):** [cure wounds](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/cure-wounds.md),\
      \ [entangle](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/entangle.md),\
      \ [ray of sickness](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/ray-of-sickness.md)\n\
      \n**2nd level (3 slots):** [pass without trace](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/pass-without-trace.md),\
      \ [ray of enfeeblement](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/ray-of-enfeeblement.md),\
      \ [spike growth](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/spike-growth.md)\n\
      \n**3rd level (3 slots):** [animate dead](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/animate-dead.md),\
      \ [dispel magic](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/dispel-magic.md),\
      \ [plant growth](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/plant-growth.md)\n\
      \n**4th level (2 slots):** [blight](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/blight.md),\
      \ [giant insect](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/giant-insect.md)"
    "name": "Spellcasting"
  - "desc": "The shaman has advantage on saving throws against being [charmed](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Charmed),\
      \ and magic can't put it to sleep."
    "name": "Fey Ancestry"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) bludgeoning damage, or 6 (1d8 + 2) bludgeoning damage if used with two\
      \ hands."
    "name": "Quarterstaff"
  - "desc": "*Melee Spell Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 9 (2d8)\
      \ necrotic damage, and the target must make a DC 14 Constitution saving throw,\
      \ taking 18 (4d8) poison damage on a failed save, or half as much damage on\
      \ a successful one."
    "name": "Fungal Rot"
"reactions":
  - "desc": "When a creature within 30 feet of the shaman drops to 0 hit points, the\
      \ shaman gains 5 (1d10) temporary hit points."
    "name": "Feed on Death"
"source":
  - "GGR"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/token/golgari-shaman-ggr.webp"
```
^statblock