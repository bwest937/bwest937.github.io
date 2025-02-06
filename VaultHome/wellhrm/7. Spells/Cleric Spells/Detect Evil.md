---
spell_level: 1
tags:
  - "#cleric_basic"
dg-publish: "true"
spell_class: "[[Cleric]]"
---

#### `=this.file.name`

**Class:** [[Cleric]]
**Spell Level:** `=this.spell_level`  
**Range:**  120ft
**Duration:**  1 hr
**Tags:** `=this.tags`

The caster detects any evil enchantments, evil auras, and supernaturally evil creatures (most undead and demons) within the spell’s range. Poison is not inherently evil and cannot be detected by means of this spell. Whether there is any distinction between “Evil” and “Chaos” is left to the Referee; in most campaigns, they are exactly the same.


*Related:*
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
