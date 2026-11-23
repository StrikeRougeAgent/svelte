---
'svelte': patch
---

perf: record a flush's writes in order, so that effects read back only their own writes instead of rescanning every write in the batch
