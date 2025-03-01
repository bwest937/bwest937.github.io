---
spell_level: 1
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### Magic Missile, Ellas Constellation

**Class:** [[Magic User]]
**Spell Level:** Magic-User, 1st Level  
**Range:** 150 ft
**Duration:**  Immediate
**Tags:** #mu_basic #missile_spells 

Roll 1d4 for each [[MD]]. This many tiny star-shaped magic missiles appear above the battlefield that may be directed to targets however the caster chooses. Each missile hits automatically and does 1HP of damage. For every odd-level (not counting 1st) of the caster, add a d4 to the initial roll. For example, a level 3 Magic-User would add 1 extra d4.

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