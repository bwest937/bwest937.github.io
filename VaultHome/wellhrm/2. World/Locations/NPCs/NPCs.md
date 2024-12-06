#### `=this.file.name`
```dataview
LIST
WHERE contains(file.folder, this.file.folder) AND !contains(file.name, this.file.name)
```