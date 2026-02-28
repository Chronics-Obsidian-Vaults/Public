---
name: Aneira
aliases:
tags:
  - character
  - playable
  - source/monster/cr/1
  - source/monster/size/medium
  - source/monster/type/humanoid
cssclasses: json5e-monster
statblock: inline
statblock-link: "#^statblock"
proficiency: 2
class: warlock
speed: 30
hp: 30
ac: "13"
acbonus: 3
level: 3
hitdice: 8
player: Lele
race: Warforged
gender: Unknown
status: alive
age: 45
spellcasting: 3
modifier: 1
max-hp: 30
passperc: 9
alignment: Chaotic Good
background: Spy
subrace: Warforged (CHA)
---
# Aneira - Level 3 Warforged [[warlock-the-celestial-xge|The Celestial]] [[warlock|Warlock]]

```statblock
"name": "Aneira"
"size": "Medium"
"type": "humanoid"
"alignment": "Chaotic Good"
"ac": !!int "13"
"hp": !!int "30"
"hit_dice": "3d8"
"modifier": !!int "1"
"stats":
  - !!int "12"
  - !!int "13"
  - !!int "16"
  - !!int "10"
  - !!int "8"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "name": "Wisdom"
    "desc": "+1"
  - "name": "Charisma"
    "desc": "+5"
"skillsaves":
  - "name": "Deception"
    "desc": "+5"
  - "name": "Intimidation"
    "desc": "+5"
  - "name": "Investigation"
    "desc": "+2"
  - "name": "Sleight Of Hand"
    "desc": "+3"
  - "name": "Stealth"
    "desc": "+3"
"damage_resistances": "poison"
"senses": "passive Perception 9"
"languages": "Common, Elvish"
"cr": "1"
"traits":
  - "desc": "Resistant to Poison damage."
    "name": "Damage Resistances"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 1d4+1 piercing"
    "name": "Dagger"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 1d6+1 piercing"
    "name": "Shortbow"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 1d6+1 bludgeoning"
    "name": "Quarterstaff"
"source":
  - "DMV Import"
```
^statblock



> [!column|no-i no-t]
>> [!div-m|no-title]
>> ![[Template_Player_Placeholder.png]]
>
>> [!div-m|no-title] Aneira
>> ~~~meta-bind
>> INPUT[select(
>> option(1, ℹ️General),
>> option(2, 🧙Description),
>> option(3, ⚙️Configure),
>> class(tabbed)
>> )]
>> ~~~
>>>[!tabbed-box-maxh480|10]
>>> >[!div-m|no-title]
>>> > ![[#General|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#Description|no-h clean]]
>>>
>>> >[!div-m|no-title]
>>> > ![[#Configure|no-h clean]]
>>>

> [!NOTE|no-title]
>```meta-bind
>INPUT[select(
>option(1, 📜Abilities and Proficiencies),
>option(2, 💪Traits),
>option(3, 📖Spellbook),
>option(4, 🎒Inventory),
>class(tabbed)
>)]
>```
>>[!tabbed-box-maxh480|10]
>> >[!div-m|no-title]
>> > ![[#Abilities|no-h-clean]]
>>
>> >[!div-m|no-title]
>> >![[#Traits|no-h-clean]]
>>
>> >[!div-m|no-title]
>> > ![[#Spellbook]]
>>
>> >[!div-m|no-title]
>> > ![[#Inventory]]

## General


```badges
items:
  - label: Level
    value: '{{frontmatter.level}}'
  - label: Initiative
    value: '+{{frontmatter.modifier}}'
  - label: Spell Save
    value: '{{add 8 frontmatter.proficiency frontmatter.spellcasting}}'
  - label: AC
    value: '{{add 10 frontmatter.acbonus}}'
  - label: Passive Perception
    value: "{{ frontmatter.passperc }}"
  - label: Speed
    value: "{{frontmatter.speed}}"
```
<br>

```healthpoints
state_key: aneira_health
health: '{{frontmatter.hp}}'
reset_on: long-rest
hitdice:
  dice: 8
  value: 3
```
<br>

```event-btns
items:
  - name: Short Rest
    value: short-rest
  - name: Long Rest
    value: long-rest
  - name: Level Up
    value: level-up
  - name: New Day
    value: new-day
```

## Description

Aneira is a yes warforged warlock and spy. Write your character's physical appearance, personality, mannerisms, and backstory here.

## Characteristics

### Physical
**Height**: 4"5' | **Weight**: 400 lb | **Eyes**: Hollow | **Skin**: Metal

### Personality
**Traits**: Unamused by life

## Configure

| Field              | Value                                                                                                                                                                                                                                                               |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Name               | `INPUT[text:name]`|
| Player             | `INPUT[text:player]`|
| Race               | `INPUT[text:race]`|
| Class              | `INPUT[suggester(option(artificer), option(barbarian), option(bard), option(blood hunter), option(cleric), option(druid), option(fighter), option(monk), option(paladin), option(ranger), option(rouge), option(sorcerer), option(warlock), option(wizard)):class]` |
| Level              | `INPUT[number:level]`|
| Gender             | `INPUT[text:gender]`|
| Age                | `INPUT[text:age]`|
| Speed              | `INPUT[number:speed]`|
| Current HP         | `INPUT[number:hp]`|
| Max HP             | `INPUT[number:max-hp]`|
| Hit Dice           | `INPUT[number:hitdice]`|
| AC Bonus           | `INPUT[number:acbonus]`|
| Proficiency Bonus  | `INPUT[number:proficiency]`|
| Spellcasting Bonus | `INPUT[number:spellcasting]`|
| Status             | `INPUT[suggester(option(alive), option(deceased), option(unknown)):status]`|
| Modifier           | `INPUT[number:modifier]`|



---

## Abilities

```ability
abilities:
  strength: 12
  dexterity: 13
  constitution: 16
  intelligence: 10
  wisdom: 8
  charisma: 16

proficiencies:
  - wis
  - cha
```

### Saving Throws
**Proficiencies**: Wis, Cha

### Skills

```skills
proficiencies:
  - sleight of hand
  - investigation
  - intimidation
  - stealth
  - deception
```

### Attacks
- **[[dagger|Dagger]]** melee, +3 to hit, 1d4+1 piercing
- **[[shortbow|Shortbow]]** melee, +3 to hit, 1d6+1 piercing
- **[[quarterstaff|Quarterstaff]]** melee, +3 to hit, 1d6+1 bludgeoning

---

### Proficiencies

### Languages
Common, Elvish

### Weapon Proficiencies
Simple

### Tool Proficiencies
[[playing-card-set|Playing Card Set]]
Thieves' Tools

### Armour Proficiencies
Light

---


## Traits

### Damage Resistances
**Poison**

---

### Damage Resistances: poison


---

### Constructed Resilience
You were created to have remarkable fortitude, represented by the following benefits:
   • You have advantage on saving throws against being poisoned, and you have resistance to poison damage.
   • You don't need to eat, drink, or breathe.
   • You are immune to disease.
   • You don't need to sleep, and magic can't put you to sleep.

---

### Criminal Contact. You have a reliable and trustworthy contact who acts as your liaison to a network of other criminals. You know how to get messages to and from your contact, even over great distances; specifically, you know the local messengers, corrupt caravan masters, and seedy sailors who can deliver messages for you. .


---

### Eldritch Invocation: Eldritch Sight. Cast detect magic at will.


---

### Eldritch Invocation: Mask of Many Faces. Cast disguise self at will.


---

### Healing Light. At 1st level, you gain the ability to channel celestial energy to heal wounds. You have a pool of d6s that you spend to fuel this healing. The number of dice in the pool equals 1 + your warlock level.

```consumable
label: ""
state_key: aneira_healing_light
uses: 4
reset_on:
  - event: long-rest
```

---

### As a bonus action, you can heal one creature you can see within 60 feet of you, spending dice from the pool. The maximum number of dice you can spend at once equals your Charisma modifier (minimum of one die). Roll the dice you spend, add them together, and restore a number of hit points equal to the total.


---

### Your pool regains all expended dice when you finish a long rest.


---

### Integrated Protection
Your body has built-in defensive layers, which can be enhanced with armor:
   • You gain a +1 bonus to Armor Class. Enter this manually as a custom item that grants +1 AC.
   • You can don only armor with which you have proficiency. To don armor, you must incorporate it into your body over the course of 1 hour, during which you remain in contact with the armor. To doff armor, you must spend 1 hour removing it. You can rest while donning or doffing armor in this way.
   • While you live, your armor can't be removed from your body against your will.

---

### Pact Boon: Pact of the Tome. You have a spellbook with 3 extra cantrips.


---

### Sentry's Rest. When you take a long rest, you must spend at least six hours in an inactive, motionless state, rather than sleeping. In this state, you appear inert, but it doesn't render you unconscious, and you can see and hear as normal.


---

### Specialized Design. You gain one skill proficiency and one tool proficiency of your choice. Enter the tool proficiency manually.


---

## Spellbook

### Spell Slots
```consumable
items:
  - label: "Pact Magic (Level 2)"
    state_key: aneira_pact_slots
    reset_on: short-rest
    uses: 2
```

### Spells

> [!note]- Cantrips
> ##### [[eldritch-blast|Eldritch Blast]]
> ```spell-components
> casting_time: 1 Action
> range: 120 feet
> duration: Instantaneous
> components: V, S
> ```
>
> A beam of crackling energy streaks toward a creature within range. Make a ranged spell attack against the target. On a hit, the target takes `1d10` force damage.
> 
> The spell creates more than one beam when you reach higher levels: two beams at 5th level, three beams at 11th level, and four beams at 17th level. You can direct the beams at the same target or at different ones. Make a separate attack roll for each beam.

> ##### [[mage-hand|Mage Hand]]
> ```spell-components
> casting_time: 1 Action
> range: 30 feet
> duration: 1 minute
> components: V, S
> ```
>
> A spectral, floating hand appears at a point you choose within range. The hand lasts for the duration or until you dismiss it as an action. The hand vanishes if it is ever more than 30 feet away from you or if you cast this spell again.
> 
> You can use your action to control the hand. You can use the hand to manipulate an object, open an unlocked door or container, stow or retrieve an item from an open container, or pour the contents out of a vial. You can move the hand up to 30 feet each time you use it.
> 
> The hand can't attack, activate magic items, or carry more than 10 pounds.

> ##### [[minor-illusion|Minor Illusion]]
> ```spell-components
> casting_time: 1 Action
> range: 30 feet
> duration: 1 minute
> components: S, M (a bit of fleece)
> ```
>
> You create a sound or an image of an object within range that lasts for the duration. The illusion also ends if you dismiss it as an action or cast this spell again.
> 
> If you create a sound, its volume can range from a whisper to a scream. It can be your voice, someone else's voice, a lion's roar, a beating of drums, or any other sound you choose. The sound continues unabated throughout the duration, or you can make discrete sounds at different times before the spell ends.
> 
> If you create an image of an object—such as a chair, muddy footprints, or a small chest—it must be no larger than a 5-foot cube. The image can't create sound, light, smell, or any other sensory effect. Physical interaction with the image reveals it to be an illusion, because things can pass through it.
> 
> If a creature uses its action to examine the sound or image, the creature can determine that it is an illusion with a successful Intelligence ([Investigation](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/skills.md#Investigation)) check against your spell save DC. If a creature discerns the illusion for what it is, the illusion becomes faint to the creature.

> ##### [[prestidigitation|Prestidigitation]]
> ```spell-components
> casting_time: 1 Action
> range: 10 feet
> duration: 1 hour
> components: V, S
> ```
>
> This spell is a minor magical trick that novice spellcasters use for practice. You create one of the following magical effects within range:
> 
> - You create an instantaneous, harmless sensory effect, such as a shower of sparks, a puff of wind, faint musical notes, or an odd odor.  
> - You instantaneously light or snuff out a candle, a torch, or a small campfire.  
> - You instantaneously clean or soil an object no larger than 1 cubic foot.  
> - You chill, warm, or flavor up to 1 cubic foot of nonliving material for 1 hour.  
> - You make a color, a small mark, or a symbol appear on an object or a surface for 1 hour.  
> - You create a nonmagical trinket or an illusory image that can fit in your hand and that lasts until the end of your next turn.  
> 
> If you cast this spell multiple times, you can have up to three of its non-instantaneous effects active at a time, and you can dismiss such an effect as an action.


> [!note]- 1st-Level Spells
> ##### [[armor-of-agathys|Armor of Agathys]]
> ```spell-components
> casting_time: 1 Action
> range: Self
> duration: 1 hour
> components: V, S, M (a cup of water)
> ```
>
> A protective magical force surrounds you, manifesting as a spectral frost that covers you and your gear. You gain 5 temporary hit points for the duration. If a creature hits you with a melee attack while you have these hit points, the creature takes 5 cold damage.
> 
> **At Higher Levels.** When you cast this spell using a spell slot of 2nd level or higher, both the temporary hit points and the cold damage increase by 5 for each slot level above 1st.

> ##### [[hellish-rebuke|Hellish Rebuke]]
> ```spell-components
> casting_time: 1 Reaction
> range: 60 feet
> duration: Instantaneous
> components: V, S
> ```
>
> You point your finger, and the creature that damaged you is momentarily surrounded by hellish flames. The creature must make a Dexterity saving throw. It takes `2d10` fire damage on a failed save, or half as much damage on a successful one.
> 
> **At Higher Levels.** When you cast this spell using a spell slot of 2nd level or higher, the damage increases by `1d10` for each slot level above 1st.

> ##### [[hex|Hex]]
> ```spell-components
> casting_time: 1 Bonus Action
> range: 90 feet
> duration: Concentration, up to 1 hour
> components: V, S, M (the petrified eye of a newt)
> ```
>
> You place a curse on a creature that you can see within range. Until the spell ends, you deal an extra `1d6` necrotic damage to the target whenever you hit it with an attack. Also, choose one ability when you cast the spell. The target has disadvantage on ability checks made with the chosen ability.
> 
> If the target drops to 0 hit points before this spell ends, you can use a bonus action on a subsequent turn of yours to curse a new creature.
> 
> A [remove curse](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Compendium/spells/remove-curse.md) cast on the target ends this spell early.
> 
> **At Higher Levels.** When you cast this spell using a spell slot of 3rd or 4th level, you can maintain your [concentration](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Concentration) on the spell for up to 8 hours. When you use a spell slot of 5th level or higher, you can maintain your [concentration](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Concentration) on the spell for up to 24 hours.


> [!note]- 2nd-Level Spells
> ##### [[invisibility|Invisibility]]
> ```spell-components
> casting_time: 1 Action
> range: Touch
> duration: Concentration, up to 1 hour
> components: V, S, M (an eyelash encased in gum arabic)
> ```
>
> A creature you touch becomes [invisible](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Invisible) until the spell ends. Anything the target is wearing or carrying is [invisible](/Campaigns/Chronics%20of%20the%20Times%20Before/Public/Rules/conditions.md#Invisible) as long as it is on the target's person. The spell ends for a target that attacks or casts a spell.
> 
> **At Higher Levels.** When you cast this spell using a spell slot of 3rd level or higher, you can target one additional creature for each slot level above 2nd.



## Inventory

| Name | Quantity | Details |
| ---- | -------- | ------- |
| [[pouch|Pouch]] | 1 |  |
| Clothes Common | 1 |  |
| [[crystal|Crystal]] | 1 |  |
| Knife Small | 1 |  |
| [[book|Book]] | 1 |  |
| [[jewelers-tools|Jewelers Tools]] | 1 |  |
| [[ink-pen|Ink Pen]] | 1 |  |
| Bag Of Sand | 1 |  |
| [[parchment-one-sheet|Parchment]] | 10 |  |
| [[backpack|Backpack]] | 1 |  |
| [[crowbar|Crowbar]] | 1 |  |
| [[aerenal-trinket-erlw|Ink]] | 1 |  |
| [[dagger|Dagger]] | 2 |  |
| [[quarterstaff|Quarterstaff]] | 1 |  |
| [[shortbow|Shortbow]] | 1 |  |
| [[immovable-rod|Immovable Rod]] | 1 |  |
| Leather 1 | 1 |  |

---

### Treasure

**Platinum Pieces**: 20
**Gold Pieces**: 15
**Silver Pieces**: 0
**Copper Pieces**: 0

### Equipped Items

**Worn Armour**: Leather 1
**Worn Shield**:
**Main Hand**: [[dagger|Dagger]]
**Off Hand**: [[quarterstaff|Quarterstaff]]

### Magic Items

#### [[immovable-rod|Immovable Rod]]
*Add magic item description here*
