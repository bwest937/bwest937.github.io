---
spell_level: 1
dg-publish: "true"
spell_class: "[[Cleric]]"
---

#### `=this.file.name`

**Class:** [[Cleric]]
**Spell Level:** `=this.spell_level`  
**Range:**  Close/Touch (Referee’s discretion)
**Duration:**  Immediate
**Tags:** #cleric_basic 

Enough food and water for up to a dozen people is made pure, removing spoilage and #poison

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
