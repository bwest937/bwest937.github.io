
## Cleric Spells
```dataview
TABLE rows.file.name as Spells
FROM #cleric_basic 
SORT file.name
GROUP BY file.frontmatter.spell_level as "Spell Level"

```

---

```dataviewjs 
// Embeds via dataviewjs 

let pages = dv.pages("#cleric_basic").groupBy(p => p.spell_level)
for (let level of pages) {
    dv.header(2, "Level " + level.key);
    level.rows.file.sort(g => g.name).forEach(f => {dv.el("p","![[" + f.path + "|clean]]")});
}

               

``` 


