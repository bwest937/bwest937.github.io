---
spell_level: 1
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:**  `=this.spell_level`
**Range:**  Self
**Duration:**  2 turns
**Tags:** #mu_basic 

The caster conjures up an invisible shield that interposes itself in front of attacks. The shield improves the caster’s armor class to 17 against missile attacks and to 15 against other (melee) attacks. If the caster’s armor class is already better than the spell would grant, the spell has no effect.

*Related:*
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___



