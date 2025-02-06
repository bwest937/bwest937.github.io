---
spell_level: 1
dg-publish: "true"
spell_class: "[[Cleric]]"
---

#### `=this.file.name`

**Class:** [[Cleric]]
**Spell Level:** `=this.spell_level`  
**Range:**  Self
**Duration:**  Until target death
**Tags:** #cleric_basic 

You indicate an undead or demonic creature you can see to be the target of your holy smite. Until that creature dies, you add +1 per [[MD]] to all attack and damage rolls against them. You can only smite one creature at a time.

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___



