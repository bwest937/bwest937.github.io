---
spell_level: 1
dg-publish: "true"
spell_class: "[[Highland Shaman]]"
---

#### `=this.file.name`

**Class:** [[Highland Shaman]]
**Spell Level:** `=this.spell_level`  
**Range:**   60 feet + 10 feet per caster level + 10 feet per [[Number MD]]
**Duration:**  1 minute per caster level
**Tags:** #shaman_basic #locate_spell 

Within the spell’s range, the caster perceives the correct direction (as the crow flies) toward a particular kind of animal named in the casting of the spell.

*Related:* 
```dataview
LIST file.frontmatter.spell_class
FROM #locate_spell
WHERE !contains(file.name, this.file.name)
```
*Other Versions:*
___


