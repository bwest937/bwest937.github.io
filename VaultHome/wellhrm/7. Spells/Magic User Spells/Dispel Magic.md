---
spell_level: 3
spell_class: "[[Magic User]]"
---

#### `=this.file.name`

**Class:** `=this.spell_class`
**Spell Level:** `=this.spell_level`  
**Range:** 120 ft
**Duration:**  1 turn for an item
**Tags:** #mu_basic 

Dispel magic, although not powerful enough to permanently disenchant a magic item (which it nullifies for 10 minutes), can be used to completely dispel most other spells and enchantments. The chance of successfully dispelling magic is a percentage based on the ratio of the level of the dispelling caster over the level of original caster (or hit dice of the monster), plus [[MD Sum]].

> [!example] 
> A 6th-level Magic-User attempting to dispel a charm cast by a 12th-level Magic-User has a base 50% chance of success: (6/12 = 0.50, or 50%). If they roll a 5 on their [[MD]], they have a 55% chance to dispel the charm.
> If the 12th-level Magic-User was dispelling the 6th-level Magic-User’s charm, success would be certain without even adding the [[MD Sum]] (12/6 = 2.00 or 200%).



*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
