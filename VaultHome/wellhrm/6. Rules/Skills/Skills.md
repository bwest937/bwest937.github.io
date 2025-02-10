---
dg-publish: "true"
---

## Skills
In general, characters can just do anything they reasonably ought to know how to do. Skill checks are only to be used when there are meaningful consequences for failure, time pressure, or both.

### Normie Skills
 These are mostly 1d6 rolls, usually +/- a relevant ability mod. Certain classes and races may be better or worse but everyone can do these things.

##### Table SK1: Normie Skills 
```dataview
TABLE WITHOUT ID file.link as Skill, ability as Ability, die as Die, base as "Base Chance", string(advantage) as Advantage
FROM "6. Rules/Skills"
WHERE contains(file.tags, "#normal_skill")
```


### Class Skills
Class-specific skills that represent abilities well above what even an experienced adventurer can usually do. Other classes usually can't attempt these skills, but common sense applies. For example, you don't have to be a [[Hunter]] to notice footprints.

##### Table SK2: Class Skills 
```dataview
TABLE WITHOUT ID file.link as Skill, ability as Ability, die as Die, base as "Base Chance", string(advantage) as "Known By"
FROM "6. Rules/Skills"
WHERE contains(file.tags, "#class_skill")
```