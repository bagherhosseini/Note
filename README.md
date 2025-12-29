Textarea — simple in-browser editor

A minimal, client-side note editor that stores content in the URL hash.

Highlights
- Single-file HTML pages: `index.html`, `md.html`, `qr.html`, `404.html`.
- All styling is inline (no external CSS). I applied a modern, minimal dark-first style and responsive layout.
- Light / Dark toggle added on all pages; preference persists to `localStorage`. System preference is used by default.
- Placeholder text appears in `index.html` and `md.html` when the editor is empty.
- Functionality unchanged: content is saved to the hash, downloadable via Ctrl/Cmd+S.

How to run
1. Open `index.html` (or `md.html`) in a browser (double-click or drag into a browser window).
2. Start typing; your notes are auto-saved to the URL hash.
3. Use the theme toggle (top-right) to switch between light and dark modes.

Files changed (styling & UI)
- index.html — inline modern style, placeholder, theme toggle
- md.html — inline modern style, placeholder, theme toggle
- qr.html — inline modern style, theme toggle
- 404.html — inline modern style, theme toggle

Notes
- No functionality was removed; only styling and small UI helpers (placeholder + theme toggle) were added.
- The project is fully static — no build steps required.
