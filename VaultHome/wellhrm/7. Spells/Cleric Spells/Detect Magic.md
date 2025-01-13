---
spell_level: 1
dg-publish: "true"
spell_class: "[[Cleric]]"
---

#### `=this.file.name`

**Class:** `=this.spell_class`
**Spell Level:** `=this.spell_level`  
**Range:** 60 ft + 10 x [[MD]]
**Duration:** 20 minutes
**Tags:** #cleric_basic 

The caster can perceive, in places, people, or things, the presence of a magical spell or enchantment. For example, magical items may be discovered in this fashion, as can the presence of a charm secretly laid upon a person.

*Related:* 
*Other Versions:* [[7. Spells/Magic User Spells/Detect Magic|Detect Magic (MU)]] [[7. Spells/Shaman Spells/Detect Magic|Detect Magic (Shaman)]]
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name
WHERE !contains(file.name, this.file.name)
```
___
