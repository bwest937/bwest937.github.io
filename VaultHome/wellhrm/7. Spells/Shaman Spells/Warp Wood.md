---
spell_level: 2
spell_class: "[[Highland Shaman]]"
dg-publish: "true"
---

#### `=this.file.name`

**Class:** `=this.spell_class`
**Spell Level:** `=this.spell_level`  
**Range:**  60 ft
**Duration:**  Permanent
**Tags:** #shaman_basic 

This spell warps, bends, and twists wood. The volume of about one 2-inch x 4-inch x 5-foot plank may be affected per [[MD Sum]] — the volume of a spear or several arrows. However, keep in mind that springing a door open or causing a leak in a ship’s planking does not actually require much of the constituent wood to be warped

*Related:* 
*Other Versions:*
```dataview
LIST file.frontmatter.spell_class
FROM "7. Spells"
WHERE file.name = this.file.name AND !contains(file.path, this.file.path)
```
___
