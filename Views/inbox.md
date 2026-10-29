---
tag: inbox
created: 2026-10-29 06:40
---
# Tag: inbox

> Quick captures, unprocessed thoughts, and newly created items awaiting classification or review.

---

## Notes
```base
filters:
  and:
    - file.hasTag("inbox")
    - not:
        - file.inFolder("Views")

properties:
  aliases:
    displayName: "Label"

views:
  - type: table
    name: "Inbox Notes"
    order:
      - file.name
      - aliases
      - created
```
