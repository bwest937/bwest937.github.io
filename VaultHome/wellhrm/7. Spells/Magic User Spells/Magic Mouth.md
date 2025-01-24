---
spell_level: 2
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** `=this.spell_class`
**Spell Level:** `=this.spell_level`  
**Range:**  Touch
**Duration:**  Permanent until triggered or dispelled
**Tags:** 

This enchantment is set upon an object, and the magic is triggered when certain conditions established by the caster are met. When that happens, a mouth appears on the object and speaks the message it has been commanded to speak. The message may be up to 30 words long

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
