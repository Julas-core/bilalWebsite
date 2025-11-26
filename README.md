# Bilal's Cafe — Static Site

A simple static restaurant/cafe website built with only HTML and CSS.

Files
- `index.html` — Home (welcome, featured dishes)
- `menu.html` — Full menu with categories and prices
- `about.html` — Story and chef info
- `gallery.html` — Image gallery (uses placeholder SVGs in `images/`)
- `contact.html` — Static map image + contact and opening hours
- `css/styles.css` — Main stylesheet
- `images/` — Placeholder SVG images (replace with real photos)

Preview locally
1. Open `index.html` directly in your browser, or run a simple file server.

Powershell (if you have Python installed):

```powershell
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

Next steps
- Replace `images/*.svg` with real photos (optimize for web).
- Add real contact email/phone and an embedded interactive map if desired.
- Optionally convert to a template engine or static site generator for easy updates.
