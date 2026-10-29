---
tag: project
created: 2026-10-29 06:40
---
# Tag: project

> Active projects, outcomes, key deliverables, and trackable initiatives.

---

## Notes
```base
filters:
  and:
    - file.hasTag("project")
    - not:
        - file.inFolder("Views")

properties:
  aliases:
    displayName: "Label"

views:
  - type: table
    name: "Projects"
    order:
      - file.name
      - aliases
      - created
```
