---
tag: journal
created: 2026-10-29 07:05
---
# Tag: journal

> Daily logs, focus trackers, and evening reflections.

---

## Entries
```base
filters:
  and:
    - file.hasTag("journal")
    - not:
        - file.inFolder("Views")

properties:
  aliases:
    displayName: "Label"

views:
  - type: table
    name: "All Journals"
    order:
      - file.name
      - aliases
      - created
```
