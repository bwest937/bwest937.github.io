---
spell_level: 1
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:** `=this.spell_level`
**Range:** 60 ft + 10 x [[MD]]
**Duration:** 20 minutes
**Tags:** #mu_basic 

The caster can perceive, in places, people, or things, the presence of a magical spell or enchantment. For example, magical items may be discovered in this fashion, as can the presence of a charm secretly laid upon a person.

*Related:*
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___