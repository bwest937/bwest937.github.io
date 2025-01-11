---
spell_level: 2
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:** `=this.spell_level`  
**Range:**  60 + ([[MD Sum]] x 10) feet
**Duration:**  1 turn
**Tags:** #mu_basic #locate_spell 

Within the spell’s range, the caster perceives the correct direction (as the crow flies) toward an object the caster specifies by description in the spell. The object must be something the caster has seen, although the spell can detect an object in a general class of items known to the caster: stairs, gold, etc.


*Related:*
```dataview
LIST file.frontmatter.spell_class
FROM #locate_spell
WHERE !contains(file.name, this.file.name)
```

*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
