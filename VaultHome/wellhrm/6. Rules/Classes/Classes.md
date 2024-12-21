

```dataview
TABLE WITHOUT ID file.link as Class, string(file.tags) as Tags
FROM "6. Rules/Classes"
WHERE !contains(file.name, this.file.name)
```

