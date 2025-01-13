---
spell_level: 1
dg-publish: "true"
spell_class: "[[Highland Shaman]]"
---

#### `=this.file.name`

**Class:** `=this.spell_class`
**Spell Level:** `=this.spell_level`  
**Range:** 60 + (10 x [[MD]]) ft
**Duration:** 20 minutes
**Tags:** #shaman_basic  

The caster can perceive, in places, people, or things, the presence of a magical spell or enchantment. For example, magical items may be discovered in this fashion, as can the presence of a charm secretly laid upon a person.

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name
WHERE !contains(file.name, this.file.name)
```
___
