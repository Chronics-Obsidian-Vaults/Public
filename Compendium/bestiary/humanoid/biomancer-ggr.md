---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- source/compendium/src/5e/ggr
- source/monster/cr/10
- source/monster/size/medium
- source/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Biomancer
---
# [Biomancer](Campaigns\Chronics of the Times Before\Public\Compendium\bestiary\humanoid/biomancer-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 256*  

Nearly all the innovation and advancement in Simic bioengineering comes from the work of biomancers. Specialists in hybridizing and altering creatures through a mixture of science and magic, they have spawned countless hybrids and krasis in search of the perfect union between nature and civilization.

```statblock
"name": "Biomancer (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Good"
"ac": !!int "17"
"ac_class": "[splint armor](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/items/splint-armor.md)"
"hp": !!int "110"
"hit_dice": "17d8 + 34"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "14"
  - !!int "20"
  - !!int "14"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "9"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Arcana](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Arcana)"
    "desc": "+9"
  - "name": "[Nature](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Nature)"
    "desc": "+9"
"senses": "passive Perception 12"
"languages": "Common plus any one language"
"cr": "10"
"traits":
  - "desc": "The biomancer is a 16th-level Simic spellcaster. Its spellcasting ability\
      \ is Intelligence (spell save DC 17, +9 to hit with spell attacks). The biomancer\
      \ has the following wizard spells prepared:\n\n**Cantrips (at will):** [acid\
      \ splash](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/acid-splash.md),\
      \ [light](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/light.md),\
      \ [mending](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/mending.md),\
      \ [poison spray](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/poison-spray.md),\
      \ [shocking grasp](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/shocking-grasp.md)\n\
      \n**1st level (4 slots):** [detect magic](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/detect-magic.md),\
      \ [grease](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/grease.md),\
      \ [shield](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/shield.md)\n\
      \n**2nd level (3 slots):** [alter self](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/alter-self.md),\
      \ [darkvision](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/darkvision.md),\
      \ [enlarge/reduce](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/enlarge-reduce.md),\
      \ [hold person](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/hold-person.md)\n\
      \n**3rd level (3 slots):** [counterspell](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/counterspell.md),\
      \ [dispel magic](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/dispel-magic.md),\
      \ [haste](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/haste.md),\
      \ [protection from energy](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/protection-from-energy.md)\n\
      \n**4th level (3 slots):** [confusion](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/confusion.md),\
      \ [conjure minor elementals](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/conjure-minor-elementals.md),\
      \ [polymorph](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/polymorph.md)\n\
      \n**5th level (2 slots):** [cone of cold](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/cone-of-cold.md),\
      \ [creation](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/creation.md),\
      \ [hold monster](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/hold-monster.md)\n\
      \n**6th level (1 slots):** [move earth](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/move-earth.md),\
      \ [wall of ice](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/wall-of-ice.md)\n\
      \n**7th level (1 slots):** [prismatic spray](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/prismatic-spray.md)\n\
      \n**8th level (1 slots):** [control weather](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/control-weather.md)"
    "name": "Spellcasting"
  - "desc": "The biomancer magically emanates life-giving energy within 30 feet of\
      \ itself. Any ally of the biomancer that starts its turn there regains 5 (1d10)\
      \ hit points."
    "name": "Bolstering Presence"
  - "desc": "The biomancer has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) slashing damage."
    "name": "Scimitar"
"source":
  - "GGR"
"image": "/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/bestiary/humanoid/token/biomancer-ggr.webp"
```
^statblock