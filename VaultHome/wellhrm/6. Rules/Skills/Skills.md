---
dg-publish: "true"
---

## Skills
In general, characters can just do anything they reasonably ought to know how to do. Skill checks are only to be used when there are meaningful consequences for failure, time pressure, or both.

### Normie Skills
 These are 1d6 rolls, usually +/- a relevant ability mod. Certain classes and races may be better or worse.

```dataview
TABLE WITHOUT ID file.link as Skill, ability as Ability, die as Die, base as "Base Chance", string(advantage) as Advantage
FROM "6. Rules/Skills"
WHERE contains(file.tags, "#normal_skill")
```


### Class Skills

```dataview
TABLE WITHOUT ID file.link as Skill, ability as Ability, die as Die, base as "Base Chance", string(advantage) as "Known By"
FROM "6. Rules/Skills"
WHERE contains(file.tags, "#class_skill")
```