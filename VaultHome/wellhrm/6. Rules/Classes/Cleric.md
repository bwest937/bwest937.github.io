---
classname: Cleric
ancestries:
  - "[[Humans]]"
  - "[[Dwarves]]"
dg-publish: "true"
cssclasses:
  - wideTable
---

## `=this.file.name`

 >[!info] `=this.classname` ![[SW Cleric.png]]
**Prime Abilities:** Wisdom
**Hit Dice:** 1d6
**Armour:** Any
**Weapons:** Blunt weapons only. No missile weapons other than slings.
**Alignment**: Lawful
**Ancestries:** `=this.ancestries`
**Tags:** #caster

  
### Description

Clerics are adventurers sworn to the service of a deity. *For now, all Clerics will be devoted to [[Gael]].* They are trained for battle and channel the power of their deity.

  
### Combat
 
Clerics can use all types of armor, but tradition forbids them from using weapons that have a sharp, cutting edge or stabbing point. They can hold the line like a fighter, but also provide support via their divine magic.
  

### Save Bonus
  
Clerics have a +2 bonus on all saving throws against being *paralyzed*  or *poisoned*.



### Divine Magic

**Divine Casting:** Clerics know all the spells on the basic Cleric spell lists, but may find others on scrolls or other forms. They do not use spellbooks, but do need to spend some time every day in prayer and contemplation or they will be unable to access divine magic the next day. If they manage to upset their deity or their own conception of their deity, they may lose access to some of their divine magic ([MD] and/or Spell Level) for a time until the relationship is repaired.


**Holy Symbol:** Clerics start with a holy symbol. If lost somehow, a local priest can probably help them out for a small donation or favor. The holy symbol can be worn around the neck, but must be held in one hand while Turning Undead.

**Learning New Spells:** When a Cleric increases their Spell Level, they gain access to the entire basic spell list for that level. They can also learn spells from divine scrolls.

**Using Magic Items:** Clerics can use items that may only be used by divine spell casters (e.g. some magic staves).

#### Divine Scrolls
Clerics can use scrolls of divine spells, and instantly recognize any scrolls of their current Spell Level. Higher level spells need to be identified by a [[Magic User]] or another [[Cleric]] of sufficient level before they can be learned. ^c353f9

![[Learn Spell From Scroll or Book|clean]]


### Turning Undead
 

Lawful Clerics have the ability to "turn" the undead, causing the foul creatures to flee or even destroying them outright. The Cleric's Holy Symbol must be held in one hand when Turning.

#### Procedure

When a Lawful Cleric attempts a turning, the player should roll 2d10 and consult the table for the result.

- If the number on the dice is equal to or greater than the number shown on the table, 2d6 creatures of the targeted type are turned and depart, not returning for 3d6 rounds.
- If the table indicates **"T"**, 2d6 undead creatures of the targeted type are automatically turned and depart for 3d6 rounds.
- If the table indicates **"D"**, 2d6 of the undead creatures are automatically destroyed and crumble to dust.


| Monster CL | Example  | Cleric  1 | Cleric 2 | Cleric 3 | Cleric 4 |
|:----------:| :--------: |:---------:|:--------:|:--------:|:--------:|
|     1      | Skeleton |    10     |    7     |    4     |    **T**     |
|     2      | Zombie   |    13     |    10    |    7     |    4     |
|     3      | Ghoul    |    16     |    13    |    10    |    7     |
|     4      | Shadow   |    19     |    16    |    13    |    10    |
|     5      |          |    20     |    19    |    16    |    13    |
|     6      | Wight    |    --     |    20    |    19    |    16    |
|     7      | Mummy    |    --     |    --    |    20    |    19    |
|     8      | Wraith   |    --     |    --    |    --    |    20    |

## Cleric Level Progression


| Level |  XP   | HD  | Saving Throw | BAB | Spell Level |          Special          | 
|:-----:|:-----:|:---:|:------------:|:---:|:-----------:|:-------------------------:|
|   1   |   0   | 1d6 |      15      |  0  |      1      | Divine Magic, Turn Undead |
|   2   | 1,600 | 2d6 |      14      |  0  |      1      |                           |
|   3   | 3,200 | 3d6 |      13      |  1  |      1      |                           |
|   4   | 6,400 | 4d6 |      12      |  1  |      2      |                           |

## Cleric Basic Spell List

### Cantrips
- [[Bless]]

### Level 1
```dataview
LIST
FROM #cleric_basic 
WHERE file.frontmatter.spell_level = 1
```

### Level 2
```dataview
LIST
FROM #cleric_basic 
WHERE file.frontmatter.spell_level = 2
```
### Level 3
```dataview
LIST
FROM #cleric_basic 
WHERE file.frontmatter.spell_level = 3
```

