---
spell_level: 3
dg-publish: "true"
spell_class: "[[Cleric]]"
---

#### `=this.file.name`

**Class:** [[Cleric]]
**Spell Level:** `=this.spell_level`  
**Range:**  90 ft
**Duration:**  1 turn
**Tags:** #cleric_basic 

Within the spell’s range, the caster perceives the correct direction (as the crow flies) toward an object the caster specifies by description in the spell. The object must be something the caster has seen, although the spell can detect an object in a general class of items known to the caster: stairs, gold, etc.


*Related*: 
*Other Versions:* 
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
