---
spell_level: 1
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### Hold Door

**Class:** [[Magic User]]
**Spell Level:** Magic-User, 1st Level  
**Range:**  30 ft
**Duration:**  2d6 + [[MD Sum]] turns
**Tags:** #mu_basic #door_spells 

This spell holds a door closed for the spell’s duration or until dispelled. Creatures with magic resistance can shatter the spell without effort.

*Related:*
```dataview
LIST file.frontmatter.spell_class
FROM #door_spells
WHERE !contains(file.name, this.file.name)
```
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___

