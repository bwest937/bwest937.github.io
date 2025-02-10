---
dg-publish: "true"
cssclasses: wideTable
---

##### C1: Class Table
```dataview
TABLE WITHOUT ID file.link as Class, string(file.frontmatter.ancestries) as Ancestries, string(file.tags) as Tags
FROM "6. Rules/Classes"
WHERE !contains(file.name, this.file.name) and !contains(file.name, "ZZ")
```