# Anatomy of an iPhone

An interactive single-page guide to the iPhone supply chain — which company makes
each component and where in the world it comes from. No build step, no
dependencies: just `index.html`.

## Live site

Published via GitHub Pages (branch `main`, root folder):
http://www.bwang.io/electabuzz/

To publish changes, just push to `main` — Pages redeploys automatically.

## Updating the content

All data lives in the `COMPONENTS` and `COUNTRIES` arrays in the `<script>`
block at the bottom of `index.html`. Edit those arrays to add suppliers or
components — the cards, filters, and country grid render from them.

Content reflects publicly reported information about the iPhone 17-generation
supply chain as of mid-2026. Not affiliated with Apple Inc.
