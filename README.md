# bastion-theme

Shared look for Bastion's BIStrainer portals (training.bastionsafe.com and client portals).

- `bastion-theme.css`: the full theme (minified). Every client's BIS "Custom CSS - Responsive" box loads it with one line:
  `@import url("https://theme.bastionsafe.com/bastion-theme.css");`
- `_headers`: tells browsers to keep a copy for 1 hour and show the saved copy while checking for a newer one.

Served by Cloudflare Pages. A new upload here goes live in about a minute; portals pick it up within an hour.

Rules
- Never rename or move `bastion-theme.css`; every client box points at this exact address.
- Source and version history live in `C:\Users\barry\Claude Projects\01) Bastion\BIStrainer\` (BIS-YYYY-MM-DD-bastion-theme-vN.N.css). This file is the minified copy of the current version.
- Current version: v3.18 (2026-10-16).
