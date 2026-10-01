# TRU Portal Forge

Static two-page handoff. No server. No telemetry.

- `tru.html` answers only from the KJV lane built into that file.
- A miss waits 4 seconds, then opens `portal.html#q=...`. Stay cancels it.
- `portal.html` answers only by quoting a built note or a manual you dropped.
- Dropped manuals stay in IndexedDB on that browser. Bake writes a portable HTML.

This is not the 31 MB Canonbound file and not an offline Grok. Put this folder beside `TRU.html` on Pages. Do not replace it.

GitHub Pages: site under about 1 GB, avoid single files over 100 MB. `file://` cannot fetch sibling manuals. The File API plus IndexedDB is the local path.
