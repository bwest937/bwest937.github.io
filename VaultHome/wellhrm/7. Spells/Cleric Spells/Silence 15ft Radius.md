---
spell_level: 2
dg-publish: "true"
spell_class: "[[Cleric]]"
---

#### `=this.file.name`

**Class:** [[Cleric]]
**Spell Level:** `=this.spell_level`  
**Range:**  180 ft
**Duration:**  12 turns
**Tags:** #cleric_basic 

Magical silence falls in an area with a 15-foot radius around the targeted creature or object, and moves with it. Nothing from this area, no matter how loud, can be heard outside the radius.

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___


