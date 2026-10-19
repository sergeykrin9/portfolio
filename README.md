# Portfolio · Sergei Grin

A static portfolio for AI-assisted development work. Plain HTML with Tailwind CSS loaded from a CDN; no build step.

- `index.html` — portfolio page with project descriptions and four public repositories.
- `assets/photo.jpg` — portrait, with an SG monogram fallback.
- `resume-en.md` and `resume-ru.md` — downloadable CVs.

The visual design uses a dark background, warm amber accents, and Inter, Instrument Serif, and JetBrains Mono typography. Tailwind and Google Fonts require network access.

## Local preview

```bash
python3 -m http.server 5180 --bind 127.0.0.1 --directory .
```

Open http://127.0.0.1:5180. This serves files locally; it does not publish the site.

[Website](https://putksebe.su/cv) · [Email](mailto:sergeykrin98@gmail.com)
