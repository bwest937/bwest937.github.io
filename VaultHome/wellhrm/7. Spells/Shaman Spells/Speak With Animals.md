---
spell_level: 2
spell_class: "[[Highland Shaman]]"
dg-publish: "true"
---

#### `=this.file.name`

**Class:** `=this.spell_class`
**Spell Level:** `=this.spell_level`  
**Range:**  Caster
**Duration:**  1 hr
**Tags:** #shaman_basic 

The caster can speak with normal animals. There is a good chance that the animals provide reasonable assistance if requested, and they will not attack — unless the caster uses the spell to say something particularly offensive.

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___

