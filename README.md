# 🎲 Would You Rather?

**Press the button. Get whimsically stuck between two impossible, weirdly-linked options.**

A tiny, dependency-free web app: hit one button and it serves up an absurd
"would you rather" dilemma pairing two silly options — like *"a superhero whose
powers only work when nobody's watching"* vs *"a time traveler who can only go
back exactly twelve seconds."*

## Features

- 🎲 **One-click dilemmas** — a big built-in pool (~1,200+ pairings), with
  **no repeats within a session**.
- 🐉 **Whimsical dark wizard/dragon theme.**
- 🔊 **Read-aloud** — reads the dilemma using your device's speech synthesis,
  with a voice picker.
- 📱 **Self-contained** — a single `index.html`, no build step, no dependencies.

## Run it

It's a static page — just open `index.html` in a browser, or serve it locally:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying with GitHub Pages

This repo ships a GitHub Actions workflow (`.github/workflows/pages.yml`) that
deploys the site on every push to `main`. Set **Settings → Pages → Build and
deployment → Source** to **GitHub Actions** (one time, or it self-enables on
first deploy). Once deployed, it's live at
`https://<your-username>.github.io/would-you-rather/`.
