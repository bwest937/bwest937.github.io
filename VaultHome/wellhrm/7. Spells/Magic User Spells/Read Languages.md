---
spell_level: 1
dg-publish: "true"
spell_class: "[[Magic User]]"
---
#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:** `=this.spell_level`
**Range:**  Normal reading distance
**Duration:**  One or two readings
**Tags:** #mu_basic 

This spell allows the caster to decipher directions, instructions, and formulae in languages unknown to the caster. This can be particularly useful for treasure maps, but it does not solve any codes.

*Related:*
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___

