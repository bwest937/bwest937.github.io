---
spell_level: 1
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** [[Magic User]]
**Spell Level:** `=this.spell_level`  
**Range:**  150 ft
**Duration:**  Missiles dissipate after caster level + 1 per [[MD]] rounds
**Tags:** #found_spell #missile_spells 


Bright green, ethereal balls of energy appear at the casters fingertips. A single missile is generated for each [[MD]]. These can be thrown all at once, or as many per round as the caster desires until they dissipate. The caster must make an attack roll to hit (add level + INT mod) for each missile. Successful hits score 1d6 [[Exploding Damage]], with no saving throw.

*Lore:*
Discovered by **Glornkus the Oft-Cursed** in Otterdale

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


