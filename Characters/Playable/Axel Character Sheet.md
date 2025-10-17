---
name: Axel
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
---
# Axel - Level 3 [[tiefling|Tiefling]] [[sorcerer-ggr|Sorcerer]]

```badges
items:
  - label: Level
    value: '{{frontmatter.level}}'
  - label: Initiative
    value: '+{{modifier abilities.dexterity}}'
  - label: Spell Save
    value: '{{add 8 frontmatter.proficiency (modifier frontmatter.spellcasting)}}'
  - label: AC
    value: '{{add 10 frontmatter.acbonus}}'
  - label: Passive Perception
    value: "{{ add 10 (modifier abilities.wisdom) frontmatter.proficiency }}"
  - label: Speed
    value: "{{frontmatter.speed}}"
```


```healthpoints
state_key: axel_health
health: '{{frontmatter.hp}}'
hitdice:
  dice: 6
  value: 3
```


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

## Skills

```skills
proficiencies:
  - arcana
  - deception
  - insight
  - persuasion
```


### Attacks
- **[[dagger|Dagger]]** melee, +3 to hit, 1d4+1 damage
- **[[dagger|Dagger]] (off-hand)** melee, +3 to hit, 1d4+0 damage


### Equipped Items

**Worn Armour**: 
**Worn Shield**:
**Main Hand**: [[Dagger]]
**Off Hand**: [[Dagger]] (off-hand)


### Spell Slots

```consumable
items:
  - label: "Level 1"
    state_key: '{frontmatter.name}_spells_1'
    uses: 4
  - label: "Level 2"
    state_key: axel_spell_2
    uses: 2
```

### Spells

#### Cantrips

##### [[dancing-lights|Dancing Lights]]
```spell-components
casting_time: 1 action
range: 120 ft
duration: Concentration, up to 1 minute
components: V, S, M (a bit of phosphorus or wychwood, or a glowworm)
```

##### [[mage-hand|Mage Hand]]
```spell-components
casting_time: 1 action
range: 30 ft
duration: 1 minute
components: V, S
```

##### [[mending|Mending]]
```spell-components
casting_time: 1 minute
range: Touch
duration: Instantaneous
components: V, S, M (two loadstones)
```

##### [[ray-of-frost|Ray of Frost]]
```spell-components
casting_time: 1 action
range: 60 ft
duration: Instantaneous
components: V, S
```

##### [[thaumaturgy|Thaumaturgy]]
```spell-components
casting_time: 1 action
range: 60 ft
duration: Instantaneous
components: V, S
```

#### 1st Level

##### [[detect-magic|Detect Magic]]
```spell-components
casting_time: 1 action (ritual)
range: Self
duration: Concentration, up to 10 minutes
components: V, S
```

##### [[false-life|False Life]]
```spell-components
casting_time: 1 action
range: 60 ft
duration: 1 hour
components: V, S, M (a small amount of alcohol)
```

##### [[hellish-rebuke|Hellish Rebuke]]
```spell-components
casting_time: 1 reaction, which you take in response to being damaged by a creature within 60 feet of you that you can see
range: 60 ft
duration: Instantaneous
components: V, S
```

##### [[chaos-bolt-xge|Chaos Bolt]]
```spell-components
casting_time: 1 action
range: 120 ft
duration: Instantaneous
components: V, S
```

#### 2nd Level

##### [[detect-thoughts|Detect Thoughts]]
```spell-components
casting_time: 1 action
range: Self
duration: Concentration, up to 1 minute
components: V, S, M (A copper piece)
```

---

## Proficiencies

### Tool Proficiencies
**[[weavers-tools|Weaver's Tools]]**

### Languages

Common, Draconic, Infernal

### Weapon Proficiencies
Dagger, Dart, Sling, Quarterstaff, Crossbow, light


## Features

### Damage Resistances
**Fire**


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

### Puppeteer
```healthpoints
state_key: axel_puppet_health
health: '{{divide (multiply frontmatter.hp 3) 2}}'
```

You manipulate a sock puppet. The puppet can be controlled with Mage Hand and acts as an arcane focus while being controlled.

While in combat the puppet has 3/2 your total hit points. When hit points fall to 0, the puppet is damaged and cannot be controlled. You can stitch it back together 1d4 hours. Magically mending the puppet can stabilize it but will still be inoperable as an arcane focus until the next short rest. If enough damage is dealt as to count as an instant death, the puppet is permanently destroyed and a new one must be made. Making a new puppet will take 1d10 + 3 hours and the appropriate materials.


### Sorcery Points
```consumable
label: ""
state_key: "{{frontmatter.name}}_arcane_recovery"
uses: 3
resets_on:
  - event: long-rest
```

### [[distant-spell|Distant Spell]]
Spend 1 sorcery pt. double the range of a spell with range 5 ft. or greater or make the range of a touch spell 30 ft.

### [[subtle-spell|Subtle Spell]]
Spend 1 sorcery pt. to cast a spell without somatic or verbal components.

### [[tiefling-infernal-legacy-scag|Tiefling (Infernal Legacy)]]
```consumable
label: ""
state_key: "{{frontmatter.name}}_infernal_legacy"
uses: 1
resets-on: new-day
```
You know thaumaturgy and can cast Hellish Rebuke once per day. CHA is the spellcasting ability.

### Draconic Resilience
+1 HP/level, unarmored AC 13 + DEX modifier.

### Hellish Resistance
Resistance to fire damage.


## Magic Items

#### [[ersatz-eye-xge|Ersatz Eye]]

This artificial eye replaces a real one that was lost or removed. While the ersatz eye is embedded in your eye socket, it can't be removed by anyone other than you, and you can see through the tiny orb as though it were a normal eye.

## [[guild-artisan|Guild Artisan]]

### Equipment
You possess a letter of introduction from your guild. Enter this manually as a custom item.

### Guild Membership

As an established and respected member of a guild, you can rely on certain benefits that membership provides, Your fellow guild members will provide you with lodging and food if necessary, and pay for your funeral if needed. In some cities and towns, a guildhall offers a central place to meet other members of your profession, which can be a good place to meet potential patrons, allies, or hirelings.

Guilds often wield tremendous political power. If you are accused of a crime, your guild will support you if a good case can be made for your innocence or the crime is justifiable. You can also gain access to powerful political figures through the guild, if you are a member in good standing. Such connections might require the donation of money or magic items to the guild's coffers. You must pay dues of 5 gp per month to the guild. If you miss payments, you must make up back dues to remain in the guild's good graces.

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
| Clothes, traveler’s                            | 1        | 2 gp, 4 lb.        |
| [[mess-kit\|Mess Kit]]                         | 1        | 2 sp, 1 lb.        |
| [[backpack\|Backpack]]                         | 1        | 2 gp, 5 lb.        |
| [[weavers-tools\|Weaver's Tools]]              | 1        |                    |
| [[torch\|Torch]]                               | 10       | 1 cp, 1 lb.        |
| [[component-pouch\|Component Pouch]]           | 1        | 25 gp, 2 lb.       |

### Treasure

**Platinum Pieces**: 0
**Gold Pieces**: 58
**Silver Pieces**: 8
**Copper Pieces**: 0
