# Project Hail Mary UX: themed edition

Live page: `index.html` (self-contained, fonts embedded). Themes are swappable:

- `?theme=nothing`: Nothing style (Ndot dot-matrix numerals, Aeonik Pro, deep-navy glass)
- `?theme=original`: the original slate/amber look

The choice is remembered in `localStorage` (`site-theme`). The switcher sits in the header.

`themes.css` holds every design token for both themes, keyed by `<html data-theme="...">`,
so the same themes can be applied to other pages.

PDFs: `hail-mary-ux-nothing.pdf`, `hail-mary-ux-original.pdf`.
