---
name: Axel O'Brien
aliases:
tags:
  - character
  - playable
proficiency: 2
class: sorcerer
speed: 30
hp: 14
acbonus: 4
level: 3
hitdice: 6
player: Axel
race: Tiefling
gender: Non-binary
status: alive
age: 35
spellcasting: 3
modifier: 1
max-hp: 14
passperc: 11
---
# Axel O'Brien - Level 3 [[tiefling|Tiefling]] [[sorcerer-draconic-bloodline|Draconic Bloodline]] [[sorcerer-ggr|Sorcerer]]



> [!column|no-i no-t]
>> [!div-m|no-title]
>> ![[Axel.png]]
>
>> [!div-m|no-title] Axel O'Brien
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

Axel is a non-binary tiefling sorcerer and guild artisan (weaver). Write your character's physical appearance, personality, mannerisms, and backstory here.

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
  strength: 10
  dexterity: 12
  constitution: 8
  intelligence: 15
  wisdom: 13
  charisma: 17

proficiencies:
  - constitution
  - charisma
```

### Skills

```skills
proficiencies:
  - arcana
  - deception
  - insight
  - persuasion
```

### Attacks
- **[[dagger|Dagger]]** melee, +3 to hit, 1d4+1 piercing damage
- **[[dagger|Dagger]] (off-hand)** melee, +3 to hit, 1d4+0 piercing damage

---

### Proficiencies

### Tool Proficiencies
**[[weavers-tools|Weaver's Tools]]**

### Languages
Common, Draconic, Infernal

### Weapon Proficiencies
Dagger, Dart, Sling, Quarterstaff, Crossbow, light

---



## Traits

### [[senses#Darkvision|Darkvision]]
**60 ft.**

---

### Damage Resistances
**Fire**

---

### Flexible Casting
You can convert sorcery points into spell slots.

| Level | Point cost |
| --- | --- |
| 1st | 2 |
| 2nd | 3 |
| 3rd | 5 |
| 4th | 6 |
| 5th | 7 |

You can also convert spell slots into sorcery points equal to the slot's level.

---

### Puppeteer

```healthpoints
state_key: axel_puppet_health
health: '{{divide (multiply frontmatter.max-hp 3) 2}}'
```

You manipulate a puppet resembling your image. The puppet can be controlled with Mage Hand and acts as an [[arcane-focus|Arcane Focus]] while being controlled. While handling the puppet, you can forgo the 1 minute duration of Mage Hand.

While in combat, the puppet has three halves of your total hit points. The puppet cannot be healed, magically restored or regenerate health on a short or long rest. To heal the puppet, [[weavers-tools|Weaver's Tools]] and sewing materials are required.

When its hit points fall to 0, the puppet is damaged and cannot be used as an arcane focus.
You can stitch it back together in 1d4 hours and with the appropriate materials. Magically mending the puppet at 0 HP can prevent it from breaking, but it but will still be inoperable as an arcane focus for the duration of the encounter. 

If enough damage is dealt as to be considered as an instant death, the puppet is permanently destroyed and a new one must be made. Making a new puppet will take 1d10 + 3 hours and the appropriate materials.

---

### Sorcery Points
```consumable
label: ""
state_key: "{{frontmatter.name}}_arcane_recovery"
uses: 3
reset_on:
  - event: long-rest
```

---

### [[distant-spell|Distant Spell]]
Spend 1 sorcery pt. double the range of a spell with range 5 ft. or greater or make the range of a touch spell 30 ft.

---

### [[subtle-spell|Subtle Spell]]
Spend 1 sorcery pt. to cast a spell without somatic or verbal components.

---

### [[tiefling-infernal-legacy-scag|Tiefling (Infernal Legacy)]]
```consumable
label: ""
state_key: "{{frontmatter.name}}_infernal_legacy"
uses: 1
reset_on: new-day
```
You know thaumaturgy and can cast Hellish Rebuke once per day. CHA is the spellcasting ability.

---

### Draconic Resilience
+1 HP/level, unarmoured AC 13 + DEX modifier.

---

### Hellish Resistance
Resistance to fire damage.

---

### [[guild-artisan|Guild Artisan]]

#### Equipment
You possess a letter of introduction from your guild. Enter this manually as a custom item.

#### Guild Membership
As an established and respected member of a guild, you can rely on certain benefits that membership provides, Your fellow guild members will provide you with lodging and food if necessary, and pay for your funeral if needed. In some cities and towns, a guildhall offers a central place to meet other members of your profession, which can be a good place to meet potential patrons, allies, or hirelings.

Guilds often wield tremendous political power. If you are accused of a crime, your guild will support you if a good case can be made for your innocence or the crime is justifiable. You can also gain access to powerful political figures through the guild, if you are a member in good standing. Such connections might require the donation of money or magic items to the guild's coffers. You must pay dues of 5 gp per month to the guild. If you miss payments, you must make up back dues to remain in the guild's good graces.

---

## Spellbook

### Spell Slots

```consumable
items:
  - label: "Level 1"
    state_key: '{frontmatter.name}_spells_1'
    reset_on: long-rest
    uses: 4
  - label: "Level 2"
    state_key: axel_spell_2
    reset_on: long-rest
    uses: 2
```

### Spells

> [!note]- Cantrips
> ##### [[dancing-lights|Dancing Lights]]
> ```spell-components
> casting_time: 1 action
> range: 120 ft
> duration: Concentration, up to 1 minute
> components: V, S, M (a bit of phosphorus or wychwood, or a glowworm)
>```
>
> ##### [[mage-hand|Mage Hand]]
> ```spell-components
> casting_time: 1 action
> range: 30 ft
> duration: 1 minute
> components: V, S
> ```
>
> ##### [[mending|Mending]]
> ```spell-components
> casting_time: 1 minute
> range: Touch
> duration: Instantaneous
> components: V, S, M (two loadstones)
> ```
>
> ##### [[ray-of-frost|Ray of Frost]]
> ```spell-components
> casting_time: 1 action
> range: 60 ft
> duration: Instantaneous
> components: V, S
> ```
> 
> ##### [[thaumaturgy|Thaumaturgy]]
> ```spell-components
> casting_time: 1 action
> range: 60 ft
> duration: Instantaneous
> components: V, S
> ```

>[!note]- 1st Level
>
> ##### [[detect-magic|Detect Magic]]
> ```spell-components
> casting_time: 1 action (ritual)
> range: Self
> duration: Concentration, up to 10 minutes
> components: V, S
> ```
>
> ##### [[false-life|False Life]]
> ```spell-components
> casting_time: 1 action
> range: 60 ft
> duration: 1 hour
> components: V, S, M (a small amount of alcohol)
> ```
>
> ##### [[chaos-bolt-xge|Chaos Bolt]]
> ```spell-components
> casting_time: 1 action
> range: 120 ft
> duration: Instantaneous
> components: V, S
> ```

>[!note]- 2nd Level
> 
> ##### [[detect-thoughts|Detect Thoughts]]
> ```spell-components
> casting_time: 1 action
> range: Self
> duration: Concentration, up to 1 minute
> components: V, S, M (A copper piece)
> ```


## Inventory

| Name                                           | Quantity | Details            |
| ---------------------------------------------- | -------- | ------------------ |
| [[pouch\|Pouch]]                               | 1        | 5 sp, 1 lb.        |
| [[potion-of-healing\|Potion of Healing]]       | 3        | 50 gp, 1/2 lb.     |
| Knife, Small                                   | 1        |                    |
| [[waterskin\|Waterskin]]                       | 1        | 2 sp, 5 lb. (full) |
| [[bedroll\|Bedroll]]                           | 1        | 1 gp, 7 lb.        |
| [[rations-1-day\|Rations (1 day)]]             | 10       | 5 sp, 2 lb.        |
| [[hempen-rope-50-feet\|Hempen Rope (50 feet)]] | 1        | 1 gp, 10 lb.       |
| [[tinderbox\|Tinderbox]]                       | 1        | 5 sp, 1 lb.        |
| Clothes, traveller's                           | 1        | 2 gp, 4 lb.        |
| [[mess-kit\|Mess Kit]]                         | 1        | 2 sp, 1 lb.        |
| [[backpack\|Backpack]]                         | 1        | 2 gp, 5 lb.        |
| [[weavers-tools\|Weaver's Tools]]              | 1        |                    |
| [[torch\|Torch]]                               | 10       | 1 cp, 1 lb.        |
| [[component-pouch\|Component Pouch]]           | 1        | 25 gp, 2 lb.       |

---

### Treasure

**Platinum Pieces**: 0
**Gold Pieces**: 58
**Silver Pieces**: 8
**Copper Pieces**: 0

### Equipped Items

**Worn Armour**:
**Worn Shield**:
**Main Hand**: [[Dagger]]
**Off Hand**: [[Dagger]] (off-hand)

### Magic Items

#### [[ersatz-eye-xge|Ersatz Eye]]
This artificial eye replaces a real one that was lost or removed. While the ersatz eye is embedded in your eye socket, it can't be removed by anyone other than you, and you can see through the tiny orb as though it were a normal eye.