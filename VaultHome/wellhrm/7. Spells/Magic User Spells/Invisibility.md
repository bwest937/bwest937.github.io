---
spell_level: 2
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:** `=this.spell_level`  
**Range:**  240ft
**Duration:**  Until dispelled or an attack is made
**Tags:** #mu_basic #invis_spells

The object of this spell, whether a person or a thing, becomes invisible to both normal sight and darkvision. The result is that an invisible creature cannot be attacked unless its approximate location is known, and all attacks are made with disadvantage. If the invisible creature makes an attack, the spell is broken. Otherwise, it lasts until dispelled or removed by the caster.


*Related:*
```dataview
LIST file.frontmatter.spell_class
FROM #invis_spells
WHERE file.name != this.file.name
```
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___



