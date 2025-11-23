---
name: Aneira
aliases:
tags:
  - character
  - playable
proficiency: 2
class: warlock
speed: 30
hp: 30
acbonus: 3
level: 3
hitdice: 8
player: Lele
race: Warforged
gender: Female
status: alive
age: 45
spellcasting: 3
modifier: 1
max-hp: 30
passperc: 11
---
# Aneira - Level 3 [[warforged-erlw|Warforged]] [[warlock-the-celestial-xge|Celestial]] [[warlock-ggr|Warlock]]



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

Aneira is a female warforged warlock and spy. Write your character's physical appearance, personality, mannerisms, and backstory here.

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
  - charisma
  - wisdom
```

### Skills

```skills
proficiencies:
  - intimidation
  - deception
  - sleight of hand
  - stealth
  - investigation
```

### Attacks
- **[[quarterstaff|Quarterstaff]]** melee, +3 to hit, 1d6+1 damage

---

### Proficiencies

### Languages
Common, Elvish

### Weapon Proficiencies
Simple

### Tool Proficiencies
[[thieves-tools|Thieves' Tools]]
[[playing-card-set|Playing Card Set]]

### Armour Proficiencies
Light

---



## Traits

### Damage Resistances
**Poison**

---

### Bonus Cantrips
At 1st level, you learn the light and sacred flame cantrips. They count as warlock cantrips for you, but they don't count against your number of cantrips known.

---

### Constructed Resilience
You were created to have remarkable fortitude, represented by the following benefits:
- You have advantage on saving throws against being poisoned, and you have resistance to poison damage.
- You don't need to eat, drink, or breathe.
- You are immune to disease.
- You don't need to sleep, and magic can't put you to sleep.

---

### Eldritch Invocation: Eldritch Sight
Cast detect magic at will.

---

### Eldritch Invocation: Mask of Many Faces
Cast disguise self at will.

---

### Healing Light
```consumable
label: ""
state_key: aneira_healing_light
uses: 4
reset_on:
  - event: long-rest
```

At 1st level, you gain the ability to channel celestial energy to heal wounds. You have a pool of d6s that you spend to fuel this healing. The number of dice in the pool equals 1 + your warlock level.

As a bonus action, you can heal one creature you can see within 60 feet of you, spending dice from the pool. The maximum number of dice you can spend at once equals your Charisma modifier (minimum of one die). Roll the dice you spend, add them together, and restore a number of hit points equal to the total.

Your pool regains all expended dice when you finish a long rest.

---

### Integrated Protection
Your body has built-in defensive layers, which can be enhanced with armour:
- You gain a +1 bonus to Armour Class.
- You can don only armour with which you have proficiency. To don armour, you must incorporate it into your body over the course of 1 hour, during which you remain in contact with the armour. To doff armour, you must spend 1 hour removing it. You can rest while donning or doffing armour in this way.
- While you live, your armour can't be removed from your body against your will.

---

### Pact Boon: Pact of the Tome
You have a spell book with 3 extra cantrips.

---

### Sentry's Rest
When you take a long rest, you must spend at least six hours in an inactive, motionless state, rather than sleeping. In this state, you appear inert, but it doesn't render you unconscious, and you can see and hear as normal.

---

### Specialized Design
You gain one skill proficiency and one tool proficiency of your choice.

---

### Spy

#### Criminal Contact
You have a reliable and trustworthy contact who acts as your liaison to a network of other criminals. You know how to get messages to and from your contact, even over great distances; specifically, you know the local messengers, corrupt caravan masters, and seedy sailors who can deliver messages for you.

---

## Spellbook

### Spell Slots
```consumable
items:
  - label: "Level 1"
    state_key: aneira_spell_1
    reset_on: long-rest
    uses: 4
```
```consumable
items:
  - label: "Level 2"
    state_key: aneira_spell_2
    reset_on: long-rest
    uses: 2
```

### Spells

> [!note]- Cantrips
> ##### [[light|Light]]
> ```spell-components
> casting_time: 1 action
> range: Touch
> duration: 1 hour
> components: V, M (a firefly or phosphorecent moss)
> ```
>
> ##### [[sacred-flame|Sacred Flame]]
> ```spell-components
> casting_time: 1 action
> range: 60 ft
> duration: Instantaneous
> components: V, S
> ```
>
> ##### [[booming-blade-tce|Booming Blade]]
> ```spell-components
> casting_time: 1 action
> range: 5 feet
> duration: On hit
> components: V, M (a weapon)
> ```
>
> ##### [[eldritch-blast|Eldritch Blast]]
> ```spell-components
> casting_time: 1 action
> range: 120 ft
> duration: Instantaneous
> components: V, S
> ```
>
> ##### [[green-flame-blade-tce|Green-Flame Blade]]
> ```spell-components
> casting_time: 1 action
> range: 5 feet
> duration: On hit
> components: V, M (a weapon)
> ```
>
> ##### [[guidance|Guidance]]
> ```spell-components
> casting_time: 1 action
> range: Touch
> duration: Concentration, up to 1 minute
> components: V, S
> ```
>
> ##### [[shillelagh|Shillelagh]]
> ```spell-components
> casting_time: 1 bonus action
> range: Touch
> duration: 1 minute
> components: V, S, M (mistletoe, a shamrock leaf, and a club or quarterstaff)
> ```


>[!note]- 1st Level
>
> ##### [[cure-wounds|Cure Wounds]]
> ```spell-components
> casting_time: 1 action
> range: Touch
> duration: Instantaneous
> components: V, S
> ```
>
> ##### [[detect-magic|Detect Magic]]
> ```spell-components
> casting_time: 1 action (ritual)
> range: Self
> duration: Concentration, up to 10 minutes
> components: V, S
> ```
>
> ##### [[disguise-self|Disguise Self]]
> ```spell-components
> casting_time: 1 action
> range: Self
> duration: 1 hour
> components: V, S
> ```
>
> ##### [[hellish-rebuke|Hellish Rebuke]]
> ```spell-components
> casting_time: 1 reaction, which you take in response to being damaged by a creature within 60 feet of you that you can see
> range: 60 ft
> duration: Instantaneous
> components: V, S
> ```
>
> ##### [[hex|Hex]]
> ```spell-components
> casting_time: 1 bonus action
> range: 90 ft
> duration: Concentration
> components: V, S, M (the petrified ey of a newt)
> ```


>[!note]- 2nd Level
>
> ##### [[misty-step|Misty Step]]
> ```spell-components
> casting_time: 1 bonus action
> range: Self
> duration: Instantaneous
> components: V
> ```


## Inventory

|Name|Qty.|Details|
|---|---|---|
|Pouch|1|5 sp, 1 lb.|
|Clothes, common|1|5 sp, 3 lb.|
|Crystal|1|10 gp, 1 lb.|
|Knife, Small|1||
|Book|1|25 gp, 5 lb.|
|Jeweller's Tools|1||
|Ink pen|1|2 cp, —|
|Bag of Sand|1||
|Parchment|10|1 sp, —|
|Backpack|1|2 gp, 5 lb.|
|Crowbar|1|2 gp, 5 lb.|
|Ink|1|10 gp, —|

---

### Treasure

**Platinum Pieces**: 20
**Gold Pieces**: 15
**Silver Pieces**: 0
**Copper Pieces**: 0

### Equipped Items

**Worn Armour**: [[leather-armor|Leather Armor]]
**Worn Shield**:
**Main Hand**: [[quarterstaff|Quarterstaff]]
**Off Hand**:

### Magic Items

#### Immovable Rod
This flat iron rod has a button on one end. You can use an action to press the button, which causes the rod to become magically fixed in place. Until you or another creature uses an action to push the button again, the rod doesn't move, even if it is defying gravity. The rod can hold up to 8,000 pounds of weight. More weight causes the rod to deactivate and fall. A creature can use an action to make a DC 30 Strength check, moving the fixed rod up to 10 feet on a success.
