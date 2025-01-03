
```
const tCount = dv.pages("")
    .file.tasks.filter(task => 
        dv.func.contains(task.tags, "⛑️")
          && !task.completed)
    .length;
```


```dataviewjs 
// Embeds via dataviewjs 
//const pages = dv.pages('"7. Spells/Magic User Spells"').where(page => page.spell_level == 2);
const pages = dv.pages('"7. Spells/Magic User Spells"').where(page => dv.func.contains(page.tags, "mu_basic"));
// Sort by file name .sort(page => page.file.path); 
// For each page... 
for (const page of pages) { 
// (except this one -- no infinite loops!) 
    if (page.file.path == dv.current().file.path) { continue; } 
    // ...create an embed link. 
    dv.paragraph("![[" + page.file.path + "]]"); } 

``` 