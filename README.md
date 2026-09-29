# Live Code Editor

A single-file HTML/CSS/JS playground with an instant live preview. No build step, no dependencies — it's one HTML file you can open in any browser.

**Live version:** https://live-code-editor-hjies922f87.qoder.website

## Using it

- **Local:** download `live-editor.html` and double-click it (or drag it into a browser).
- **Online:** open the live link above — same editor, no install.

## Features

- Three code panels (HTML, CSS, JavaScript) on the left, live preview on the right
- Preview updates as you type (debounced ~150 ms)
- JavaScript errors appear in a red bar instead of failing silently
- Your code is auto-saved in the browser (localStorage), so it's still there when you come back
- **Reset** restores the starter template (asks for confirmation first)
- **Save as .html** downloads a standalone HTML file with your code baked in

## Files

| Path | Purpose |
| --- | --- |
| `live-editor.html` | The editor — source of truth, editable by hand |
| `web/index.html` | Copy deployed to the Qoder Site (hosted live version) |

## Notes

- Everything runs client-side in the browser; nothing is uploaded or stored on a server.
- To update the hosted version, edit `live-editor.html`, copy it to `web/index.html`, and republish the site.
