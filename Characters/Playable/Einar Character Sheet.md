---
name: Einar
aliases:
tags:
  - character
  - playable
proficiency: 2
class: barbarian
speed: 30
hp: 25
acbonus: 3
level: 3
hitdice: 12
player: Beli
race: Shifter
gender: Male
status: alive
age: 24
spellcasting: 0
modifier: 2
max-hp: 25
passperc: 13
---
# Einar - Level 3 [[shifter-wildhunt-erlw|Shifter (Wildhunt)]] [[barbarian-path-of-the-zealot-xge|Path of the Zealot]] [[Barbarian]]



> [!column|no-i no-t]
>> [!div-m|no-title]
>> ![[Template_Player_Placeholder.png]]
>
>> [!div-m|no-title] Einar
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
>option(3, 🎒Inventory),
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
state_key: einar_health
health: '{{frontmatter.hp}}'
reset_on: long-rest
hitdice:
  dice: 12
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

Einar is a male shifter (wildhunt) barbarian and recovered cultist. Write your character's physical appearance, personality, mannerisms, and backstory here.

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
  strength: 15
  dexterity: 15
  constitution: 13
  intelligence: 8
  wisdom: 12
  charisma: 12

proficiencies:
  - strength
  - constitution
```

### Skills

```skills
proficiencies:
  - animal handling
  - deception
  - perception
  - religion
  - survival
```

### Attacks
- [[javelin|Javelin]] melee, +4 to hit, 1d6+2 piercing damage
- [[whip|Whip]] melee, [[item-properties#Reach|Reach]], +4 to hit, 1d4+2 slashing damage
- **[[dagger|Dagger]]** melee, +3 to hit, 1d4+1 piercing damage
- **[[dagger|Dagger]] (off-hand)** melee, +3 to hit, 1d4+0 piercing damage

---

### Proficiencies

### Languages
Common, Infernal

### Weapon Proficiencies
Simple, Martial

---



## Traits

### Damage Resistances
None

---

### [[senses#Darkvision|Darkvision]]
**60 ft.**

---

### [[barbarian#Rage (Level 1)|Rage]]
```consumable
label: ""
state_key: einar-rage
uses: 3
reset_on:
  - event: long-rest
```

Advantage on Strength checks and saves; melee damage bonus +2; resistance to bludgeoning, piercing, and slashing damage (lasts 1 minute, use 3 times/long rest).

---

### [[barbarian#Danger Sense (Level 2)|Danger Sense]]
Advantage on DEX saves against effects you can see.

---

### [[barbarian#Reckless Attack (Level 2)|Reckless Attack]]
Advantage on attacks using Strength, attacks against you have advantage as well.

---

### [[barbarian-path-of-the-zealot-xge#Divine Fury (Level 3)|Divine Fury]]
Starting when you choose this path at 3rd level, you can channel divine fury into your weapon strikes. While you're raging, the first creature you hit on each of your turns with a weapon attack takes extra damage equal to 1d6 + half your barbarian level. The extra damage is necrotic or radiant; you choose the type of damage when you gain this feature.

---

### [[barbarian-path-of-the-zealot-xge#Warrior of the Gods (Level 3)|Warrior of the Gods]]
At 3rd level, your soul is marked for endless battle. If a spell, such as [[raise-dead|Raise Dead]], has the sole effect of restoring you to life (but not undeath), the caster doesn't need material components to cast the spell on you.

---

### [[shifter-mpmm#Shifting|Shifting]]
As a bonus action, you can assume a more bestial appearance. This transformation lasts for 1 minute, until you die, or until you revert to your normal appearance as a bonus action. When you shift, you gain temporary hit points equal to your level + your Constitution modifier (minimum of 1 temporary hit point). You also gain additional benefits that depend on your shifter subrace, described below. Once you shift, you can't do so again until you finish a short or long rest.

While shifted, you have advantage on Wisdom checks, and no creature within 30 feet of you can make an attack roll with advantage against you, unless you're incapacitated.

---

### Recovered Cultist
Your time worshipping in secrecy and shadow at the altar of malevolent forces has left you with insight and keen awareness to those who still operate in such ways. You can often spot hidden signs, messages, and signals left in populated places. If actively seeking signs of a cult or dark following, you have an easier time locating and decoding the signs or social interactions that signify cult activity, gaining advantage on any ability checks to discover such details.

---

## Inventory

| **Name**                            | **Quantity** | **Details** |
| ----------------------------------- | ------------ | ----------- |
| [[explorers-pack\|Explorer's Pack]] | 1            |             |
| [[common-clothes\|Common Clothes]]  | 1            | 5 sp        |
| [[holy-symbol\|Holy Symbol]]        | 1            |             |
| Vestments                           | 1            |             |
|                                     |              |             |

---

### Treasure

**Platinum Pieces**: 0
**Gold Pieces**: 35
**Silver Pieces**: 0
**Copper Pieces**: 0

### Equipped Items

**Worn Armour**:
**Worn Shield**:
**Main Hand**: [[Whip]]
**Off Hand**:

### Magic Items

#### [[Patrick's Shiftweave]]
When a suit of shiftweave is created, up to five different outfits can be embedded into the cloth. While wearing the clothing, you can speak its command word as a bonus action to transform your outfit into your choice of one of the other designs contained within it. Regardless of its appearance, the outfit can't be anything but clothing. Although it can duplicate the look of other magical clothing, it doesn't gain their magical properties.

This particular Shiftweave was found in [[Patrick]]'s room before he was gone missing.
