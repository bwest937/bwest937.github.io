---
spell_level: 1
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:** Magic-User, 1st Level  
**Range:** 150 ft
**Duration:**  Immediate
**Tags:** #mu_basic #missile_spells

A magical missile for every [[MD]] flies where the caster directs, with a range of 150 feet. The missile hits automatically, doing 1d4+1 points of damage.

For every odd-level (not counting 1st) of the caster, add a missile to the total. For example, a level 5 Magic-User would add 2 extra missiles.

*Related:*
```dataview
LIST file.frontmatter.spell_class
FROM #missile_spells
WHERE !contains(file.name, this.file.name)
```
*Other Versions:* 
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___

