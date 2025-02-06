---
maxlevel: 2
btag: mu_basic
spath: '"7. Spells/Magic User Spells"'
---

```dataview
TABLE rows.file.name as Spells
FROM #mu_basic 
GROUP BY file.frontmatter.spell_level as "Spell Level"
```


```dataviewjs 
// Embeds via dataviewjs 
let maxlevel = dv.current().maxlevel
let btag = dv.current().btag
let spath = dv.current().spath

for (var i = 0; i < maxlevel; i++) {
    dv.header(3, "Level " + i)
    let pages = dv.pages(spath).where(page => dv.func.contains(page.tags, btag)).where(page => page.spell_level == i);
    for (let page of pages) {
        if (page.file.path == dv.current().file.path) { continue; }
        //dv.el("p", "![[" + page.file.path + "|clean]]", { cls: "pdf-col" });
        dv.el("p", "![[" + page.file.path + "|clean]]");
 }
}

``` 



