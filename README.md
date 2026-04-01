<p align="center">
  <img src="https://img.shields.io/badge/status-live-brightgreen" alt="Live">
  <img src="https://img.shields.io/badge/hosting-Cloudflare%20Pages-F38020" alt="Cloudflare Pages">
  <img src="https://img.shields.io/badge/build-zero--config-blue" alt="Zero Config">
  <img src="https://img.shields.io/badge/vibe-jaws-0070a0" alt="Jaws Vibes">
</p>

<h1 align="center">Chum the Waters</h1>
<p align="center"><strong>Something's in the water.</strong></p>
<p align="center">
  <a href="https://chumthewaters.com">chumthewaters.com</a>
</p>

<p align="center">
  <img src="preview.png" alt="Chum the Waters Preview" width="500">
</p>

---

## About

Jaws-themed linktree. The whole page is an animated underwater scene: sky-to-deep-ocean CSS gradient, a shark fin drifting across the surface, the Orca boat as an SVG silhouette, and a great white rising from the bottom. Social links sit on floating yellow barrels from the movie.

Links out to Twitch, YouTube, X, and Discord for the "Chum" brand.

## Features

- Full-viewport ocean scene built entirely in CSS (no background image for the water)
- Custom Jaws font (`amity-jack.ttf`) for the title
- Animated shark fin, bobbing boat, and barrel links with staggered animations
- No scroll, no JavaScript

## Assets

| File | What it is |
|------|-----------|
| `amity-jack.ttf` | Jaws movie font |
| `barrel.png` | Yellow barrel for link buttons |
| `boat.png` | Orca boat silhouette |
| `shark.png` | Great white from below |
| `shark-side.png` | Surface fin |

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Vanilla HTML/CSS, 729 lines |
| Font | Custom (amity-jack.ttf) |
| Animations | CSS keyframes only |
| Hosting | Cloudflare Pages |

## Deploy

```bash
wrangler pages deploy . --project-name=chumthewaters-com
```
