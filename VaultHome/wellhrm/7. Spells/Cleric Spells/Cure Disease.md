---
spell_level: 3
spell_class: "[[Cleric]]"
dg-publish: "true"
---

#### `=this.file.name`

**Class:** `=this.spell_class`
**Spell Level:** `=this.spell_level`  
**Range:**  Touch
**Duration:**  Immediate (permanent)
**Tags:** #cleric_basic #reversible 

Cures the spell’s recipient of any diseases, including magically-inflicted ones. An evil reversal of this spell allows a Chaotically aligned Cleric to cause disease.

*Related:* 
- [[Cure Blindness]]
  
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
