---
tag: reference
created: 2026-10-29 06:40
---
# Tag: reference

> Curated knowledge, external sources, documentation, books, and evergreen reference material.

---

## Notes
```base
filters:
  and:
    - file.hasTag("reference")
    - not:
        - file.inFolder("Views")

properties:
  aliases:
    displayName: "Label"

views:
  - type: table
    name: "References"
    order:
      - file.name
      - aliases
      - created
```
