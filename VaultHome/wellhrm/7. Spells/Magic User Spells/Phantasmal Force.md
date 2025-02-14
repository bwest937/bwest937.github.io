---
spell_level: 2
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:** `=this.spell_level`  
**Range:** 240 ft
**Duration:**  Until concentration ends
**Tags:** #illusion

This spell creates an illusion that seems realistic to all who view it. The illusion disappears when it is touched, but if the viewer believes the illusion is real, it can cause damage. Unless the Referee rules otherwise, victims of the spell are permitted a saving throw, and the illusion cannot cause more than 2d6 points of damage per victim. This depends on circumstances; a truly brilliant use of the spell can be quite devastating, and a poorly thought-out illusion might cause almost immediate disbelief.

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
