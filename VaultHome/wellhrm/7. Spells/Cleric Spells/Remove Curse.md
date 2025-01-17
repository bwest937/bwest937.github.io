---
spell_level: 3
spell_class: [[Cleric]]
dg-publish: true
---

#### `=this.file.name`

**Class:** `=this.spell_class`
**Spell Level:** `=this.spell_level`  
**Range:**  Very close
**Duration:**  Immediate
**Tags:** #cleric_basic 

This spell removes one curse from a person or object. Some curses may be more powerful than this spell can handle.

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
