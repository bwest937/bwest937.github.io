---
spell_level: 3
spell_class: [[Cleric]]
dg-publish: true
---

#### `=this.file.name`

**Class:** `=this.spell_class`
**Spell Level:** `=this.spell_level`  
**Range:**  Very close
**Duration:**  3 questions
**Tags:** #cleric_basic 

The caster can ask **three questions** of a corpse, and it will answer, although the answers might be cryptic. Only higher-level Clerics have enough spiritual power to command answers of long-dead corpses. 

The caster can ask three questions of a corpse, and it will answer, although the answers might be cryptic. It takes a lot of spiritual power to command answers of long-dead corpses. For this spell, you must declare how many [[MD]] to use as usual, but they are rolled *in sequence*. 

- If rolling one [[MD]], the body can have been dead that many days.
- The second [[MD]] is for months. 
- The third [[MD]] is for years.
- The fourth [[MD]] for centuries.


*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
