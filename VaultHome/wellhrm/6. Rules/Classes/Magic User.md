---
classname: Magic User
ancestries:
  - "[[Humans]]"
  - "[[Elves]]"
dg-publish: "true"
cssclasses:
  - wideTable
---

## `=this.file.name`

 >[!info] `=this.classname`  ![[SW Magic User.png]]
**Prime Abilities:** Intelligence
**Hit Dice:** 1d4
**Armour:** None
**Weapons:** Dagger, staff, crossbow
**Ancestries:** `=this.ancestries`
**Tags:** #caster #arcane

 
### Description
Magic-users are adventurers whose study of arcane secrets has taught them how to cast spells. Magic-users are able to cast a greater number of increasingly powerful spells as they advance in level.

  
### Combat
Magic-users can only use daggers, staves and crossbows and are unable to use shields or wear any kind of armor. This makes them very vulnerable in combat.

### Save Bonus

Magic-Users gain a bonus of +2 on all saving throw rolls against spells, including spells from magic wands and staffs


### Arcane Magic

**Arcane Magic:** Magic-Users carry [[spellbooks]] containing the formulae for arcane spells. A first level magic-user selects (2 + INT bonus) number of Level 1 spells and (INT bonus) number Level 2 spell from the basic spell lists for their starting spellbook. They always get [[Magic Dart]].

#### Arcane Scrolls
Magic-Users uniquely can attempt to identify any scroll with [[Read Magic]]. ^ebc509

![[Read Magic|clean]]


**Learning New Spells:** To permanently learn a spell, a Magic-User must record a spell in their spellbook. When a Magic-User increases their Spell Level, any spells already in their spellbook of the new Spell Level become available to them without chance of mishap. New spells may be found in the world in scrolls and spellbooks or learned from other arcane practitioners.

![[Learn Spell From Scroll or Book|clean]]

**Magical Research:** Magic-users may research new spells. This process, and the spell to be created, requires the approval of the DM. As a baseline, engaging in such research requires a minimum expenditure of 1,000 gold pieces and a week of game time for a first-level spell, and the time and money doubling for each additional Spell Level. *Working with other characters (even those of different traditions) and finding useful tomes or other relevant artifacts may significantly reduce the time and gp needed.*
   

## Magic-User Level Progression


| Level |   XP   | HD  | Saving Throw | BAB | Spell Level |   Special    | 
|:-----:|:------:|:---:|:------------:|:---:|:-----------:|:------------:|
|   1   |   0    | 1d4 |      15      |  0  |      1      | Arcane Magic |
|   2   | 2,500  | 2d4 |      14      |  0  |      1      |              |
|   3   | 5,000  | 3d4 |      13      |  0  |      2      |              |
|   4   | 10,000 | 4d4 |      12      |  1  |      2      |              |

# Magic-User Basic Spell List

### Cantrips
- [[7. Spells/Magic User Spells/Magic Dart|Magic Dart]]

### Level 1
```dataview
LIST
FROM #mu_basic 
WHERE file.frontmatter.spell_level = 1
```

### Level 2
```dataview
LIST
FROM #mu_basic 
WHERE file.frontmatter.spell_level = 2
```

### Level 3

```dataview
LIST
FROM #mu_basic 
WHERE file.frontmatter.spell_level = 3
```