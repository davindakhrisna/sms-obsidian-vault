---
tag: idea
created: 2026-10-29 06:40
---
# Tag: idea

> Insights, mental models, atomic concepts, and creative sparks.

---

## Notes
```base
filters:
  and:
    - file.hasTag("idea")
    - not:
        - file.inFolder("Views")

properties:
  aliases:
    displayName: "Label"

views:
  - type: table
    name: "Ideas"
    order:
      - file.name
      - aliases
      - created
```
