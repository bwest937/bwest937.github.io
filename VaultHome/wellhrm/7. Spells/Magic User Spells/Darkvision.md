---
spell_level: 3
spell_class: [[Magic User]]
dg-publish: true
---

#### `=this.file.name`

**Class:** `=this.spell_class`
**Spell Level:** `=this.spell_level`  
**Range:**  40 ft
**Duration:**  1 day
**Tags:** #mu_basic #light_spell 

The recipient of the spell gains [[6. Rules/Ancestry/Darkvision|Darkvision]].

*Related:* 
```dataview
LIST file.frontmatter.spell_class
FROM #light_spell
WHERE !contains(file.name, this.file.name)
```

*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
