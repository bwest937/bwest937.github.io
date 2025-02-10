---
ancestries:
  - "[[Humans]]"
  - "[[Halflings]]"
dg-publish: "true"
cssclasses: wideTable
---

## `=this.file.name`
 ![[Highland Shaman.png|right|300]]
 >[!info] 
**Prime Abilities:** Charisma
**Hit Dice:** 1d6
**Armour:**  Leather armor, wooden shield
**Weapons:** Clubs, staves, and spears. For ranged, slings and crossbows.
**Ancestries:** `=this.ancestries`
**Tags:** #caster 


### Description

The face of a Highland Shaman is intricately inscribed in blue woad tattoos and their hair and beards are plaited into long braids. They cover their weapons and shields in fetishes and charms and paint them in patterns of blue and white. Wearing animal skins and carved deer skull helms, they strike a ferocious and animalistic figure on any field of battle.

Whether fighting with their clans or smaller groups, they inspire fervor in their companions. This is often the reason why the clans are victorious in battle.

### Combat

Highland Shaman can use leather armor and wooden shields, but need a free hand to cast. Their weapons all contain some natural elements. They aren't great at ranged combat but can handle a crossbow if needed (they've had enough fired at them to understand the principle). They are capable combatants and wield their Nature-based magic to heal and support their clan and party members.

**Immunity to Fear:** Highland Shamans are immune to fear effects.
**Inspire Fight:** At 3rd Level, Highland Shamans gain an inspiring aura with a radius of 60ft. Members of their clan receive the Shaman’s Charisma bonus on to-hit rolls and saving throws.
  
### Natural Magic

**Nature Magic:** Shaman know all the first level spells on the basic Nature spell list. They do not use spellbooks, but do need to get a good rest to access their magic with ease.
**Learning New Spells:** Shamans primarily learn new spells from the basic spell list when gaining a level. To do so, they must secure psychedelic sacraments and retreat into a wild natural setting for a vision quest. When they return, they roll 1d4 and learn that many new spells of their choice of the appropriate level from the basic Nature spell list.
**Using Magic Items:** Shaman can use the same magic items as [[Cleric|Clerics]], but not their scrolls.

#### Nature Scrolls
Highland Shamans can use scrolls of Nature spells and instantly recognize any scrolls of their current Spell Level. Higher level spells need to be identified by a [[Magic User]] or another [[Highland Shaman]] of sufficient level before they can be learned. ^01b3ca

![[Learn Spell From Scroll or Book|clean]]


  
## Highland Shaman Level Progression

| Level |   XP   | HD  | Saving Throw | BAB | Spell Level |            Special             |
|:-----:|:------:|:---:|:------------:|:---:|:-----------:|:------------------------------:|
|   1   |   0    | 1d6 |      15      |  0  |      1      | Nature Magic, Immunity to Fear |
|   2   | 2,500  | 2d6 |      14      |  0  |      2      |                                |
|   3   | 5,000  | 3d6 |      13      |  0  |      2      |         Inspire Fight          |
|   4   | 10,000 | 4d6 |      12      |  1  |      3      |                                |

# Highland Shaman Basic Spell List

### Cantrips
- [[Speak From Beyond]]

### Level 1
```dataview
LIST
FROM #shaman_basic  
WHERE file.frontmatter.spell_level = 1
```

### Level 2
```dataview
LIST
FROM #shaman_basic
WHERE file.frontmatter.spell_level = 2
```

### Level 3

```dataview
LIST
FROM #shaman_basic
WHERE file.frontmatter.spell_level = 3
```