---

spell_level: 1
spell_class:
---

#### `=this.file.name`

**Class:** `=this.file.spell_class`
**Spell Level:** `=this.spell_level`  
**Range:**  Ally not in combat
**Duration:**  1 hr
**Tags:** 

Spell description...

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
