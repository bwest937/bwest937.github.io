---
spell_level: 2
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:** `=this.spell_level`  
**Range:**  Close
**Duration:**  Permanent until dispelled
**Tags:** #mu_basic #door_spells

As with a [[Hold Door]] spell, wizard lock holds a door closed, but it is permanent until dispelled. Creatures with magic resistance can shatter the spell without effort. 
Any [[Magic-User]] at least three levels higher than the caster can open the portal, and a knock spell will open it as well, although the spell is not permanently destroyed in these cases.

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



