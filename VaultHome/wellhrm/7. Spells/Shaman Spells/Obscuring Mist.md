---
spell_level: 2
spell_class: "[[Highland Shaman]]"
dg-publish: "true"
---

#### `=this.file.name`

**Class:** `=this.spell_class`
**Spell Level:** `=this.spell_level`  
**Range:**   20 ft + 10 ft per caster level + 10 ft per caste level[[Number MD]]
**Duration:**  1 turn per caster level
**Tags:** #shaman_basic 

A misty vapor seethes outward from the casting point, billowing forth to fill a radius of 20 ft + 10 ft per caster level + 10 ft per caste level[[Number MD]].

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```

