---
spell_level: 2
spell_class: "[[Highland Shaman]]"
dg-publish: "true"
---

#### `=this.file.name`

**Class:** `=this.spell_class`
**Spell Level:** `=this.spell_level`  
**Range:**  thrown 30 ft
**Duration:**  caster level + [[MD Sum]] turns
**Tags:** #shaman_basic 

Flame ignites from nowhere in the palm of the caster’s hand, causing no damage to the caster, but otherwise is as hot as natural fire. It can be used while held, or thrown to a distance of 30 feet to ignite flammable materials. For so long as the sprit-fire is in the caster’s hand, it can be extinguished immediately whenever the caster wishes it gone.

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___

