# CLAUDE.md

## Project Overview
Personal website for Soham Patwardhan, hosted on GitHub Pages at sohampatwardhan.github.io.

## Tech Stack
- Single-file static site (index.html) with inline CSS and JavaScript
- WebGL starfield animation with shooting stars
- Progressive Web App (PWA) with service worker (sw.js) and manifest.json
- No build tools or package.json — pure static files

## Key Files
- `index.html` — entire site (styles, markup, WebGL shaders, JS)
- `sw.js` — service worker (network-first caching)
- `manifest.json` — PWA manifest
- `icons/` — PWA icons (192px, 512px)
- `CHANGELOG.md` — version history

## Conventions
- Always update CHANGELOG.md when committing changes
- Social link order: LinkedIn, GitHub, Reddit, Email, Phone, SMS, WhatsApp
- Mobile breakpoint: 600px
- Star count: 3000 desktop, 1500 mobile
