---
spell_level: 2
tags:
  - "#mu_basic"
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:** `=this.spell_level`  
**Range:** 60ft
**Duration:**  2 hrs
**Tags:** `=this.tags`

The caster can detect the thoughts of other beings at a distance of 60 feet. To pick up thoughts, the caster must focus their concentration in one direction for one turn. If multiple creatures are within range in the direction being focused on, the caster perceives an incomprehensible mix of all their thoughts. If the caster focuses for an additional turn, they can filter out and understand a single creature’s thoughts. The caster can magically understand thoughts in languages they do not speak. The spell cannot penetrate more than two feet of stone, and is blocked by even a thin sheet of lead.

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___



