---
spell_level: 1
dg-publish: "true"
spell_class: "[[Cleric]]"
---

#### Light

**Class:** [[Cleric]]
**Spell Level:** `=this.spell_level`
**Range:** 60 ft
**Duration:** 1 hour + 1 turn/[caster level]
**Tags:** #cleric_basic #reversible #light_spell 

This spell has three common usages:

1. **Conjuring light:** In a 15ft radius. The magical light is sufficient for reading, but is not as bright as daylight. The spell may be cast upon an object, in which case the light moves with the object.
2. **Blinding a creature:** By casting the spell upon its eyes. If the target fails a saving throw, it is blinded for the duration. A blind creature attacks with disadvantage.
3. **Cancelling darkness:** Light may cancel a [[Darkness]] spell of equal MD (or reduce the effect of a [[Darkness]] spell cast with more MD).


If cast with 2+ [[MD]], the light is as bright as sunlight and has the same effects as sunlight.


*Related:*
```dataview
LIST file.frontmatter.spell_class
FROM #light_spell
WHERE !contains(file.name, this.file.name)
```

*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___