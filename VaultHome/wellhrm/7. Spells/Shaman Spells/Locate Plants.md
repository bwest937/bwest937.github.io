---
spell_level: 2
spell_class: "[[Highland Shaman]]"
dg-publish: "true"
---

#### `=this.file.name`

**Class:** [[Highland Shaman]]
**Spell Level:** `=this.spell_level`  
**Range:**  60 ft + 10 ft per caster level + 10 ft per caste level[[Number MD]]
**Duration:**  1 minute per caster level
**Tags:** #shaman_basic #locate_spell

Within the spell’s range, the caster perceives the correct direction (as the crow flies) toward a particular kind of plant named in the casting of the spell.

*Related:*
```dataview
LIST file.frontmatter.spell_class
FROM #locate_spell
WHERE !contains(file.name, this.file.name)
```
*Other Versions:*
