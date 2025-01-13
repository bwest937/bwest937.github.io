---
spell_level: 3
spell_class: "[[Magic User]]"
dg-publish: "true"
---

#### `=this.file.name`

**Class:** `=this.spell_class`
**Spell Level:** `=this.spell_level`  
**Range:**  60 ft
**Duration:**  2 hrs
**Tags:** #mu_basic 

Clairvoyance allows the caster to see through most materials and obstacles within a range of 60 feet. The spell works through [[MD Sum]] feet of solid stone. The spell’s effect cannot pass through even a thin sheeting of lead, however, for this metal blocks it completely.

*Related:* 
- [[Clairaudience]]
  
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
