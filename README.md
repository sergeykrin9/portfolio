# Portfolio · Sergey Krinitsyn

A single-page portfolio site for an AI Product Engineer. Dark theme, warm-amber accents, custom typography (Inter + Instrument Serif + JetBrains Mono). Zero build step — plain HTML + Tailwind via CDN.

**Live:** [putksebe.su/cv](https://putksebe.su/cv)

## What's here

- [`index.html`](./index.html) — the portfolio page (~1100 lines, self-contained)
- [`assets/photo.jpg`](./assets/photo.jpg) — hero photo
- [`resume-en.md`](./resume-en.md) · [`resume-ru.md`](./resume-ru.md) — text resumes downloadable directly from the site

## Design choices

- **Dark + warm amber accent** — sets a different tone from the standard "minimalist tech portfolio." Reads as serious without feeling corporate.
- **Serif headings (Instrument Serif), sans body (Inter), mono details (JetBrains Mono)** — three-font system used consistently.
- **No JavaScript framework** — the page is 33KB of HTML. Loads instantly, no build pipeline.
- **8 project cards** with bento layout for the two featured ones.
- **Photo fallback** — if the image fails to load, a subtle "SK" monogram appears in its place (graceful degradation).

## Run locally

```bash
python3 -m http.server 5180 --directory .
# open http://localhost:5180
```

## Deploy

The repo deploys cleanly to any static host:

- **Vercel:** `npx vercel --prod`
- **Netlify:** drag the folder onto [app.netlify.com/drop](https://app.netlify.com/drop)
- **Firebase Hosting:** add a target in `firebase.json` and `firebase deploy --only hosting`
- **GitHub Pages:** enable Pages from the repo settings

## What I wanted to avoid

- The generic "AI gradient + glass card + glow" aesthetic — every AI engineer portfolio looks the same now.
- "Hi, I'm X. I'm passionate about technology." — useless filler text.
- Stack icons in a grid — pulls focus from actual work.

Instead: short prose, six labeled stack categories, eight project cards with stack + scope + outcome triplets.

---

**Author:** Sergey Krinitsyn · [putksebe.su/cv](https://putksebe.su/cv) · sergeykrin98@gmail.com
