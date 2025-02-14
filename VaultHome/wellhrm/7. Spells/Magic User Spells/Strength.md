---
spell_level: 2
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:** `=this.spell_level`  
**Range:**  Touch
**Duration:**  1 hr x [[MD Sum]]
**Tags:** #mu_basic 

This spell may be cast upon a [[Fighter]] or a [[Cleric]]. For the duration of the spell, a [[Fighter]] gains 2d4 points of [[Strength]], and a [[Cleric]] gains 1d6 points of [[Strength]]. Strength cannot exceed 18 unless the Referee chooses to allow additional bonuses resulting from the additional Strength.

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
