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
**Tags:** #cleric_basic #cure_spell #reversible #osric

This powerful spell allows the cleric permanently to remove virtually all forms of blindness. The reverse of the spell permits a saving throw, and the cleric must successfully touch the spell’s intended target to inflict blindness (permanent duration).

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

