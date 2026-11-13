---
"@ui-sdk/core": patch
---

An agent's `setValue` now refuses a number written with grouped digits, like "1,499.5", instead of setting 1, and gives a component whose value is a list, like a multiple Select, one value or label as a list of one instead of a string.
