# Yitian Wei — Portfolio Website

A five-page portfolio site in plain HTML & CSS. No build tools, no frameworks.
Brand system: cobalt blue (#093180), muted blue (#496091), off-white (#FFFEFA), Quicksand —
matching the Personal Identity project, so the whole site is on-brand.

## Pages
```
portfolio/
├── index.html                      ← Home / Work (landing page)
├── about.html                      ← About Me (with an illustrated "interests" panel)
├── work-personal-identity.html     ← In-depth case study (Personal Brand Identity)
├── work-alethia.html               ← ALETHIA magazine showcase
├── work-bcspca.html                ← BC SPCA annual report showcase
├── css/styles.css                  ← all styling (brand colors at the top)
├── images/                         ← all project images (already included)
└── Yitian_Wei_GraphicDesigner_2026.pdf  ← downloadable résumé
```

## Status: complete ✅
All images are embedded — Personal Identity, ALETHIA, and BC SPCA are all done.
The About page uses a custom illustrated panel (cats · hiking · games · animal welfare ·
bilingual · design) instead of a photo. Nothing else is required.

## If you ever want to tweak things
- **Brand colors:** `css/styles.css` → the `:root { }` block at the top.
- **Swap the interests panel for a real photo later:** in `about.html`, replace the
  `<div class="portrait">…</div>` SVG block with
  `<div class="portrait"><img src="images/portrait.jpg" alt="Yitian Wei" /></div>`
  and add `images/portrait.jpg`.
- **Reflection / copy:** all text is plain HTML — edit any wording directly.

## Hosting on GitHub Pages
1. Repo with the **contents** of this folder at the root (so `index.html` is at the top level).
2. Settings → Pages → Deploy from branch → `main` → `/ (root)` → Save.
3. Live in a minute or two.

To preview locally, double-click `index.html`.
