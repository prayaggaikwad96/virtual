---
'@tanstack/virtual-core': patch
'@tanstack/marko-virtual': patch
---

Retry a clamped end-anchor sync after the scrollable content grows during a prepend, without allowing a later explicit scroll command to be overridden by the retained retry.
