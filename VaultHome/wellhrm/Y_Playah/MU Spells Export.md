
## Magic User Spells
```dataview
TABLE rows.file.name as Spells
FROM #mu_basic or #found_spell 
SORT file.name
GROUP BY file.frontmatter.spell_level as "Spell Level"

```

---

```dataviewjs 
// Embeds via dataviewjs 

let pages = dv.pages("#mu_basic or #found_spell").groupBy(p => p.spell_level)
for (let level of pages) {
    dv.header(2, "Level " + level.key);
    level.rows.file.sort(g => g.name).forEach(f => {dv.el("p","![[" + f.path + "|clean]]")});
}

               

``` 


