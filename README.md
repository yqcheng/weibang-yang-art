# Weibang Yang · 杨位榜

A responsive, single-page artist website with six original painting photographs, the artist's biography, an accessible artwork viewer, image enlargement, and email inquiries.

## Run locally

Requires Node.js. No dependencies or build step.

```sh
node preview.mjs
```

Open http://localhost:4173.

## Files

- `dist/index.html`: page and biography
- `dist/style.css`: responsive layout and visual design
- `dist/app.js`: artwork titles, years, descriptions, and viewer behavior
- `dist/assets/`: original artwork photos and favicon
- `.openai/hosting.json`: existing Sites hosting identity

## Hosting

The `dist` directory is ready to serve through any static web host. The existing hosted site is https://weibang-yang-art.dear-clock-9881.chatgpt.site/ (access depends on its sharing settings).

Inquiry address: 4415yqc@gmail.com. Update both `dist/index.html` and `dist/app.js` to change it.

The artwork photographs and text belong to their respective owners. This repository grants no license to reproduce or redistribute the artwork.
