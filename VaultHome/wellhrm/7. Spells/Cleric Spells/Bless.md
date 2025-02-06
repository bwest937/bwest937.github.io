---
spell_level: 0
dg-publish: "true"
spell_class: "[[Cleric]]"
---

#### `=this.file.name`

**Class:** [[Cleric]]
**Spell Level:** `=this.spell_level`  
**Range:**  60 ft
**Duration:**  1 hr
**Tags:** #cleric_basic #cantrip #daily

This spell can be cast once per day on a number of allies equal to the cleric's level. It grants +1 to attack and morale rolls for an hour. The spell takes a turn to cast, and the recipient(s) cannot already be in combat when the spell is cast.

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___

