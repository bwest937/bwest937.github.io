---
spell_level: 2
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:** `=this.spell_level`  
**Range:**  Ally not in combat
**Duration:**  Immediate
**Tags:** #mu_basic #door_spells 

This spell unlocks and unbars all doors, gates, and portals within its range, including those held or locked by normal magic.


*Related:*
```dataview
LIST file.frontmatter.spell_class
FROM #door_spells
WHERE !contains(file.name, this.file.name)
```
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___




