---
name: Axel
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
class: sorcerer
speed: 30
hp: 14
ac: "14"
acbonus: 4
level: 3
hitdice: 6
player: Axel
race: Tiefling
gender: Female
status: alive
age: 35
spellcasting: 3
modifier: 1
max-hp: 14
passperc: 11
alignment: Chaotic Neutral
background: Guild Artisan
---
# Axel - Level 3 [[tiefling|Tiefling]] [[sorcerer-draconic-bloodline|Draconic Bloodline]] [[sorcerer|Sorcerer]]

```statblock
"name": "Axel"
"size": "Medium"
"type": "humanoid"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"hp": !!int "14"
"hit_dice": "3d6"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "8"
  - !!int "15"
  - !!int "13"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "name": "Constitution"
    "desc": "+1"
  - "name": "Charisma"
    "desc": "+5"
"skillsaves":
  - "name": "Arcana"
    "desc": "+4"
  - "name": "Deception"
    "desc": "+5"
  - "name": "Insight"
    "desc": "+3"
  - "name": "Persuasion"
    "desc": "+5"
"damage_resistances": "fire"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Draconic, Elvish, Infernal"
"cr": "1"
"traits":
  - "desc": "The character has darkvision out to 60 feet."
    "name": "Darkvision"
  - "desc": "Resistant to Fire damage."
    "name": "Damage Resistances"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 1d4+1 piercing"
    "name": "Dagger"
"source":
  - "DMV Import"
```
^statblock



> [!column|no-i no-t]
>> [!div-m|no-title]
>> ![[Template_Player_Placeholder.png]]
>
>> [!div-m|no-title] Axel
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
state_key: axel_health
health: '{{frontmatter.hp}}'
reset_on: long-rest
hitdice:
  dice: 6
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

Axel is a female tiefling sorcerer and guild artisan. Write your character's physical appearance, personality, mannerisms, and backstory here.

## Characteristics

### Physical
**Height**: 5"3' | **Weight**: 130 | **Eyes**: Amber | **Hair**: Chestnut with Blue Highlights | **Skin**: Peach

### Personality
**Traits**: Erratic, Hot-Headed
**Ideals**: Nihilist
**Bonds**: Adoptive Family
**Flaws**: Way too emotionally invested

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
  strength: 10
  dexterity: 12
  constitution: 8
  intelligence: 15
  wisdom: 13
  charisma: 17

proficiencies:
  - con
  - cha
```

### Saving Throws
**Proficiencies**: Con, Cha

### Skills

```skills
proficiencies:
  - insight
  - deception
  - persuasion
  - arcana
```

### Attacks
- **[[dagger|Dagger]]** melee, +3 to hit, 1d4+1 piercing

---

### Proficiencies

### Languages
Common, Draconic, Elvish, Infernal

### Weapon Proficiencies
Crossbow, light, Dagger, Dart, Quarterstaff, Sling

### Tool Proficiencies
Weaver's Tools

### Armour Proficiencies
*None*

---


## Traits

### Damage Resistances
**Fire**

---

### Darkvision: 60 ft.
Damage Resistances: fire

---

### Draconic Resilience. +1 HP/level, unarmored AC 13 + DEX modifier.


---

### Equipment. You possess a letter of introduction from your guild. Enter this manually as a custom item.


---

### Guild Membership. As an established and respected member of a guild, you can rely on certain benefits that membership provides, Your fellow guild members will provide you with lodging and food if necessary, and pay for your funeral if needed. In some cities and towns, a guildhall offers a central place to meet other members of your profession, which can be a good place to meet potential patrons, allies, or hirelings.


---

### Guilds often wield tremendous political power. If you are accused of a crime, your guild will support you if a good case can be made for your innocence or the crime is justifiable. You can also gain access to powerful political figures through the guild, if you are a member in good standing. Such connections might require the donation of money or magic items to the guild's coffers. You must pay dues of 5 gp per month to the guild. If you miss payments, you must make up back dues to remain in the guild's good graces. .


---

### Hellish Resistance. Resistance to fire damage.


---

### Infernal Legacy. You know thaumaturgy and can cast Hellish Rebuke once per day. CHA is the spellcasting ability.

```consumable
label: ""
state_key: axel_infernal_legacy._you_know_thaumaturgy_and_can_cast_hellish_rebuke_once_per_day._cha_is_the_spellcasting_ability.
uses: 1
reset_on: new-day
```

---

### Sorcery Points. You have 3 sorcery points (use 3 times/long rest).

```consumable
label: ""
state_key: axel_sorcery_points
uses: 3
reset_on:
  - event: long-rest
```

---

### Subtle Spell. Spend 1 sorcery pt. to cast a spell without somatic or verbal components.


---

## Spellbook

### Spell Slots
```consumable
items:
  - label: "Level 1"
    state_key: axel_spells_1
    reset_on: long-rest
    uses: 4
  - label: "Level 2"
    state_key: axel_spells_2
    reset_on: long-rest
    uses: 2
```

### Spells

*Spell data not available from DMV export. Please add spells manually or re-run with --orcpub-url parameter.*

## Inventory

| Name | Quantity | Details |
| ---- | -------- | ------- |
| [[pouch|Pouch]] | 1 |  |
| [[potion-of-healing|Potion Of Healing]] | 3 |  |
| Knife Small | 1 |  |
| [[waterskin|Waterskin]] | 1 |  |
| [[bedroll|Bedroll]] | 1 |  |
| [[rations-1-day|Rations 1 Day ]] | 10 |  |
| Rope Hempen | 1 |  |
| [[tinderbox|Tinderbox]] | 1 |  |
| Clothes Traveler S | 1 |  |
| [[mess-kit|Mess Kit]] | 1 |  |
| [[backpack|Backpack]] | 1 |  |
| [[weavers-tools|Weavers Tools]] | 1 |  |
| [[torch|Torch]] | 10 |  |
| [[component-pouch|Component Pouch]] | 1 |  |
| [[dagger|Dagger]] | 1 |  |
| [[ersatz-eye-xge|Ersatz Eye]] | 1 |  |

---

### Treasure

**Platinum Pieces**: 0
**Gold Pieces**: 58
**Silver Pieces**: 8
**Copper Pieces**: 0

### Equipped Items

**Worn Armour**:
**Worn Shield**:
**Main Hand**: [[dagger|Dagger]]
**Off Hand**:

### Magic Items

#### [[ersatz-eye-xge|Ersatz Eye]]
*Add magic item description here*
