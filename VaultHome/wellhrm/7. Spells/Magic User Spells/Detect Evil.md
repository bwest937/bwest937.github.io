---
spell_level: 2
tags:
  - "#mu_basic"
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:** `=this.spell_level`  
**Range:**  120ft
**Duration:**  20 minutes per [[MD]]
**Tags:** `=this.tags`

The caster detects any evil enchantments, evil auras, and supernatually evil creatures (most undead and demons) within the spell’s range. Poison is not inherently evil and cannot be detected by means of this spell. Whether there is any distinction between “Evil” and “Chaos” is left to the Referee; in most campaigns, they are exactly the same.


*Related:*
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
