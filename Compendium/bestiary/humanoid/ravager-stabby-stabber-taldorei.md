---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- source/compendium/src/5e/taldorei
- source/monster/cr/2
- source/monster/size/small
- source/monster/type/humanoid/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ravager Stabby-Stabber"
---
# [Ravager Stabby-Stabber](Compendium/bestiary/humanoid/ravager-stabby-stabber-taldorei.md)
*Source: Tal'Dorei Campaign Setting p. 137*  

Whether driven by resentment for being shunned by the fairer folk, or consumed by the burning fury that still drives them since the corruption of the Ruiner's blood in the Calamity, most orcs are a chaotic force of destruction. They are a threat to civilization, to be sure, but more a mindless force of nature than a coordinated menace.

However, with each generation, some orcs grow smarter: more organized, learning from their foes, and understanding the might in well-led numbers. This growing horde of calculating, ruthless murder is known as the Ravagers, and with each defeat, they learn. And grow stronger still.

Tales of the bloodthirsty Ravagers have spread from Kymal across Tal'Dorei. Most adventurers and mercenaries take up arms against the Ravager after hearing stories of muscle-bound orcs terrorizing the free people of the Dividing Plains. They are prepared for single combat with great foes. They are not prepared for the Ravagers' most terrifying weapon: the stabby-stabbers. Fresh-faced warriors from Emon laugh at the name when they first hear it in Kymal's taverns, but veteran mercenaries close their eyes and hastily bury their face in their tankards.

Goblins only join the Ravagers as slaves; spoils from orcish raids of goblin nests. Those that show exceptional skill are brought before their Slaughter Lord and forced to drink a terrible brew the orcs call skullfire. The concoction burns what little reason the goblins had away, turning them into perfectly obedient, flesh-hungry monsters. In battle, stabby-stabbers swarm like rats, eviscerating fleeing innocents and warriors alike in seconds.

```statblock
"name": "Ravager Stabby-Stabber (TalDorei)"
"size": "Small"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "[studded leather armor](Compendium/items/studded-leather-armor.md)"
"hp": !!int "36"
"hit_dice": "8d6 + 8"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "12"
  - !!int "10"
  - !!int "8"
  - !!int "7"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "1"
"condition_immunities": "[charmed](Rules/conditions.md#Charmed)"
"gear":
  - "[dagger](Compendium/items/dagger.md)"
  - "[shortsword](Compendium/items/shortsword.md)"
"senses": "[darkvision](Rules/senses.md#Darkvision) 60 ft., passive Perception 9"
"languages": "Common, Goblin"
"cr": "2"
"traits":
  - "desc": "The Ravager Stabby-Stabber can take the [Disengage](Rules/actions.md#Disengage)\
      \ or [Hide](Rules/actions.md#Hide) action as a bonus action on each of its turns."
    "name": "Nimble Escape"
  - "desc": "When the goblin hits with a melee attack, it may attack again. It can\
      \ continue making additional attacks until it does not hit. The goblin cannot\
      \ move between attacks made with this trait."
    "name": "Stabby Frenzy"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6\
      \ + 3) piercing damage."
    "name": "Shortsword"
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft., range 20/60\
      \ ft., one target. *Hit:* 5 (1d4 + 3) piercing damage."
    "name": "Dagger"
"source":
  - "TalDorei"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/TalDorei/Ravager_Stabby-Stabber.png"
```
^statblock