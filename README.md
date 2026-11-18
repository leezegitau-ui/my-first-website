# Leezegitau — Digital Designer & Developer

A responsive portfolio landing page built with plain HTML, CSS, and JavaScript. The selected-work cards are clearly presented as self-initiated concepts, not client claims.

## Run locally

No build step or dependencies are needed. Open `index.html` in a browser, or start a local server from the repository root:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Customize

- Update the name, introduction, service descriptions, and contact email in `index.html`.
- Edit colors, typography, and responsive layouts in `styles.css`.
- Update menu, project filters, and copy-email behavior in `script.js`.

The page uses Google Fonts when a network connection is available and falls back to system fonts otherwise. The email copy button requires a secure context (HTTPS or localhost); if clipboard access is unavailable, it opens the email application instead.
