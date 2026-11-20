# MERIDIAN · 3D Animated Presentation

An interactive 3D presentation of Niva Bupa's MERIDIAN international health insurance (40 scenes).

## Run it

Open `index.html` in a browser. Everything is in that one file; only the fonts load from the internet.

## Deploy on Vercel

1. Push this repository to GitHub.
2. On vercel.com choose **Add New → Project** and import the repository.
3. Leave every setting at its default (Framework Preset: **Other**, no build command) and press **Deploy**.

Vercel serves `index.html` from the repository root.

## Controls

| Key | Action |
| --- | --- |
| → / Space / click | Next scene |
| ← | Previous scene |
| O | Contents |
| N | Speaker notes |
| F | Fullscreen |
| A | Auto-play |
| 1–5 | Pick a variant (explorer scene) |

## Rebuild from source

The `source/` folder holds the code that `index.html` is built from.

```
cd source
npm install
python3 build.py        # writes dist/meridian.html
cp dist/meridian.html ../index.html
```
