---
"@ui-sdk/core": patch
---

`setValue` on a Date Picker or Calendar now refuses text that isn't an ISO date, like `"25/12/2026"`, and keeps the value instead of clearing it.
