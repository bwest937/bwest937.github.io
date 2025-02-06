---
spell_level: 2
dg-publish: "true"
spell_class: "[[Cleric]]"
---

#### `=this.file.name`

**Class:** [[Cleric]]
**Spell Level:** `=this.spell_level`  
**Range:**  180 ft
**Duration:**  9 turns
**Tags:** #cleric_basic 

The caster targets 1d4 living bipeds of human size or smaller, such as goblins or dryads, who must make a save per [[MD]]. If they faiil they are completely immobilized. The caster may also target a single person, in which case the saving throw(s) is made with a penalty of –2.

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___

