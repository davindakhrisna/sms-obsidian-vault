---
tag: ""
created: "{{date}} {{time}}"
---
# Tag: 

> Overview, scope, and reflections for this tag.

---

## Notes
```base
filters:
  and:
    - file.hasTag("")
    - not:
        - file.inFolder("Views")

properties:
  aliases:
    displayName: "Label"

views:
  - type: table
    name: "All Notes"
    order:
      - file.name
      - aliases
      - created
```
