---
spell_level: 2
dg-publish: "true"
spell_class: "[[Cleric]]"
---

#### `=this.file.name`

**Class:** [[Cleric]]
**Spell Level:** `=this.spell_level`  
**Range:**  30 ft radius centered on caster
**Duration:**  Concentration
**Tags:** #cleric_basic #osric

Once the spell is cast, the cleric must maintain a sonorous chanting of holy words and prayers, which not only lend divine favor to the cleric and his or her allies but also bring disfavor to their foes. For so long as the cleric continues to chant, their allies (within the area of effect) gain a bonus of +1 to all attack rolls, damage rolls, and saving throws. Enemies within the spell’s area of effect also suffer a –1 to all such die rolls. If the cleric breaks concentration, the effect of the spell will end. Moving quicker than half-speed or being silenced automatically breaks concentration.

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___




  