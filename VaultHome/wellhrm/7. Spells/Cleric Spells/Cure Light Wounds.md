---
spell_level: 1
dg-publish: "true"
spell_class: "[[Cleric]]"
---

#### `=this.file.name`

**Class:** [[Cleric]]
**Spell Level:** `=this.spell_level`  
**Range:**  Touch
**Duration:**  Immediate
**Tags:** #cleric_basic #cure_spell #reversible 

Cures [[MD Sum]]+1 hit points of damage.

*Related:* 
```dataview
LIST file.frontmatter.spell_class
FROM #cure_spell
WHERE !contains(file.name, this.file.name)
```
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___

