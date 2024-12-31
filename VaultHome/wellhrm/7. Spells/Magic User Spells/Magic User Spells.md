
```dataview
TABLE WITHOUT ID file.link as "Spell", file.frontmatter.spell_level as "Spell Level", string(file.tags) as Tags
FROM "7. Spells/Magic User Spells"
WHERE !contains(file.name, this.file.name)
```