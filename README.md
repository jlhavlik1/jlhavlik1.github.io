# jlhavlik1.github.io

Personal site for John Lyon Havlik — MD, MBA, psychiatry resident at Stanford.

A single hand-authored `index.html` styled as a Jupyter notebook. No build step,
no framework, no runtime dependencies — the content ships as real HTML, so it
renders instantly, works without JavaScript, and previews cleanly when shared.

```
index.html          the page: semantic HTML + inline CSS, ~53 KB
favicon.svg         terminal-prompt mark
cv.pdf              curriculum vitae
assets/
  headshot.webp     optimized portrait (JPEG fallback)
  og.png            1200×630 link-preview card
  fonts/            Space Grotesk + JetBrains Mono, latin subset, variable
```

Interactivity (expand/collapse, timeline) is plain CSS and native
`<details>` — no JavaScript required. Deployed by GitHub Pages from `main`.
