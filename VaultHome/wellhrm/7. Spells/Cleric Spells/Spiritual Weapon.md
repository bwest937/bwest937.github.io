---
spell_level: 2
dg-publish: true
spell_class: "[[Cleric]]"
---

#### `=this.file.name`

**Class:** [[Cleric]]
**Spell Level:** `=this.spell_level`  
**Range:**  30 ft
**Duration:**  1 round per caster level + [[MD Sum]] / 2 rounds
**Tags:** #cleric_basic #osric 

To cast this spell, the cleric throws a melee weapon they can wield into the air, invoking the power of his or her god(s). The real weapon disappears, replaced with a mist-like shape of divine force that attacks at the cleric’s will while the cleric concentrates upon maintaining it (limited, of course, to the duration of the spell). The weapon strikes as a magical weapon for purposes of affecting creatures hit only by magic weapons (as if it were a +1 weapon, with an additional +1 per three levels of the caster), but it has no actual bonus on to hit rolls. The spiritual weapon attacks as if it were wielded by the cleric, at the cleric’s level and with any appropriate to hit and damage bonuses (or penalties). The weapon does damage as a normal version of the thrown weapon.

*Related:*
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
