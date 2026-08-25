# TRACE — project page

Static project page for **TRACE: From Slow Thinking to Fast Execution for Mobile Embodied
Agents** (anonymous submission, under review).

Everything is a single `index.html` plus assets. No build step, no dependencies.

```
index.html            the page
assets/fig/*.webp     figures rendered from the current submission source
assets/video/*.mp4    clips from the physical testbeds
```

## Preview locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Publishing

The page is served by GitHub Pages from the default branch root
(Settings → Pages → Deploy from a branch → `main` / `/root`). `.nojekyll` keeps Pages from
running Jekyll over the assets.

## Recordings

The vehicle, cabin, and robot clips are real recordings from the testbeds described on the
page. Every face is blurred frame by frame before publication. No author or institution
identity appears on the page while the paper is under review.
