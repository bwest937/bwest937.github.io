---
spell_level: 2
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:** `=this.spell_level`  
**Range:**  10 ft/caster level
**Duration:**  1 hr per [[MD]]
**Tags:** #mu_basic #invis_spells 

The caster can perceive invisible objects and creatures

*Related:*
```dataview
LIST file.frontmatter.spell_class
FROM #invis_spells
WHERE !contains(file.name, this.file.name)
```
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___

