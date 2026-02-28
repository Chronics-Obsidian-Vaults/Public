---
name: Hix
aliases:
tags:
  - character
  - playable
proficiency: 2
class: blood hunter
speed: 30
hp: 17
acbonus: 2
level: 3
hitdice: 10
player: Maryp
race: Changeling
gender: Neutral
status: alive
age: 260
spellcasting: 1
modifier: 2
max-hp: 17
passperc: 11
ac: "12"
---


# Hix - Level 3 Changeling blood hunter



> [!column|no-i no-t]
>> [!div-m|no-title]
>> ![[Template_Player_Placeholder.png]]
>
>> [!div-m|no-title] Hix
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
state_key: template_health
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

Write your character's physical appearance, personality, mannerisms, and backstory here.

## Configure

| Field              | Value                                                                                                                                                                                                                                                               |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Name               | `INPUT[text:name]`|
| Player             | `INPUT[text:player]`|
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
  strength: 9
  dexterity: 14
  constitution: 14
  intelligence: 19
  wisdom: 12
  charisma: 10

proficiencies:
  - intelligence
  - wisdom
```

### Skills

```skills
proficiencies:
  - arcana
  - deception
  - history
  - insight
  - investigation
```

### Attacks
- **Dagger** melee, +3 to hit, 1d4+1 damage
- **Dagger (off-hand)** melee, +3 to hit, 1d4+0 damage

---

### Proficiencies

### Tool Proficiencies
List tool proficiencies here

### Languages
Common

### Weapon Proficiencies
Dagger, Dart, Sling, Quarterstaff

---



## Traits

### [[senses#Darkvision|Darkvision]]
**60 ft.**

---

### Damage Resistances
**Fire**

---

### Luck Points
```consumable
label: ""
state_key: template_luck_points
uses: 3
reset_on:
  - event: long-rest
```

You have inexplicable luck that seems to kick in at just the right moment.

**You have 3 luck points.** Whenever you make an attack roll, an ability check, or a saving throw, you can spend one luck point to roll an additional d20. You can choose to spend one of your luck points **after you roll the die, but before the outcome is determined**. You choose which of the d20s is used for the attack roll, ability check, or saving throw.

You can also spend one luck point when an **attack roll** is made against you. Roll a d20 and then choose whether the attack uses the attacker's roll or yours.

If more than one creature spends a luck point to influence the outcome of a roll, the points cancel each other out; no additional dice are rolled.

You regain your expended luck points when you finish a long rest.

---

### Arcane Recovery
```consumable
label: ""
state_key: template_arcane_recovery
uses: 1
reset_on:
  - event: short-rest
```

You have learned to regain some of your magical energy by studying your spell book. Once per day when you finish a **short rest**, you can choose expended spell slots to recover. The spell slots can have a combined level that is equal to or **less than half your wizard level** (rounded up), and none of the slots can be 6th level or higher.

For example, if you're a 4th-level wizard, you can recover up to two levels worth of spell slots. You can recover either a 2nd-level spell slot or two 1st-level spell slots.

---

## Spellbook

### Spell Slots

```consumable
items:
  - label: "Level 1"
    state_key: template_spells_1
    reset_on: long-rest
    uses: 4
  - label: "Level 2"
    state_key: template_spell_2
    reset_on: long-rest
    uses: 2
```

### Spells

> [!note]- Cantrips
> ##### Dancing Lights
> ```spell-components
> casting_time: 1 action
> range: 120 ft
> duration: Concentration, up to 1 minute
> components: V, S, M (a bit of phosphorus or wychwood, or a glowworm)
>```
>
> You create up to four torch-sized lights within range, making them appear as torches, lanterns, or glowing orbs that hover in the air for the duration. You can also combine the four lights into one glowing vaguely humanoid form of Medium size. Whichever form you choose, each light sheds dim light in a 10-foot radius.
>
> As a bonus action on your turn, you can move the lights up to 60 feet to a new spot within range. A light must be within 20 feet of another light created by this spell, and a light winks out if it exceeds the spell's range.


>[!note]- 1st Level
>
> ##### Spell Name
> ```spell-components
> casting_time: 1 action
> range: 60 ft
> duration: Instantaneous
> components: V, S
> ```


>[!note]- 2nd Level
>
> ##### Spell Name
> ```spell-components
> casting_time: 1 action
> range: Self
> duration: Instantaneous
> components: V, S
> ```


## Inventory

| Name | Quantity | Details |
| --- | --- | --- |
|  |  |  |
|  |  |  |

---

### Treasure

**Platinum Pieces**: 0
**Gold Pieces**: 0
**Silver Pieces**: 0
**Copper Pieces**: 0

### Equipped Items

**Worn Armour**:
**Worn Shield**:
**Main Hand**:
**Off Hand**:

### Magic Items

#### Magic Item Name
Description of magic item here.
