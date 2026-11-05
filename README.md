# Saikrishna Bulusu — Research Portfolio (Portfolio V3)

Static research portfolio built with the Claude Design (Design Composer) runtime.

- `index.html` — the page (Design Composer template + logic)
- `support.js` — the DC client runtime (loads React/ReactDOM, renders the template)
- `assets/` — images, video, and presentation referenced by the page
- Verified documents (transcript, LOR, certificate) are shared on request, not hosted here

## Local preview
Serve over HTTP (not `file://`, the runtime uses `fetch(location.href)`):

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Deployed via GitHub Pages.
