# Polina Kuzina — Portfolio

Static one-page portfolio (GitHub Pages). No build step.

## Stack

- Single `index.html`
- Tailwind CSS via CDN (config in `<head>`)
- Google Fonts: Playfair Display (headings), Inter (body)
- Vanilla JavaScript (language toggle, scroll animations, mobile menu, case dialog)

## Run locally

Open `index.html` in a browser, or from the project folder:

```bash
npx serve
```

## Languages

English and Russian live in the same file. Every UI string is duplicated:

- `<span class="lang-en">...</span>`
- `<span class="lang-ru">...</span>`

The page language is stored in `localStorage` under the key `lang`.
