---
spell_level: 1
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:** `=this.spell_level`
**Range:**  Self
**Duration:** 1 hour
**Tags:** #mu_basic 

Creates a magical field of protection immediately around the caster, blocking out all enchanted monsters such as elementals and demons). Evil monsters suffer a –1 per [[MD]] penalty to hit the caster, and the caster gains +1 per [[MD]] on all saving throws against such attacks. If the caster already has any magical bonuses to saving throws or armor class, the bonus from the magic circle has no effect, although the protective circle still functions against enchanted creatures. This spell may be reversed by a Cleric of Chaos to protect from good.

*Related:*
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___