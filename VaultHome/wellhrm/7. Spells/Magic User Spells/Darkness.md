---
spell_level: 1
dg-publish: "true"
spell_class: "[[Magic User]]"
---

#### Darkness

**Class:** [[Magic User]]
**Spell Level:** `=this.spell_level`
**Range:** 60 ft
**Duration:** 1 hour + 1 turn/level
**Tags:** #mu_basic #light_spell

This spell has three common usages:

1. **Conjuring dark:** Creates a 15ft radius area of magical blackness, preventing normal sight (but not infravision). If cast with 2+ [[MD]], the dark is darker than night and prevents infravision. The spell may be cast upon an object, in which case the dark moves with the object.

2. **Blinding a creature:** By casting the spell upon its eyes. If the target fails a saving throw, it is blinded for the duration. A blind creature attacks with disadvantage.

3. **Cancelling darkness:** Darkness may cancel a [[7. Spells/Magic User Spells/Light|Light]]  spell of equal [[MD]] , or reduce the effect of a [[7. Spells/Magic User Spells/Light|Light]]  spell cast with more [[MD]].

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

