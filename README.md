# Deucon website

The website for **Deucon (Pty) Ltd**, electrical engineering consultants based in Durban, KwaZulu-Natal.

It is a single static page: plain HTML, CSS and a little JavaScript. There is no build step, no database and nothing to install.

## Files

| Path | What it is |
|---|---|
| `index.html` | The whole website |
| `brand/logo/` | Logo files (SVG and PNG), favicon and social profile picture |
| `images/sectors/` | Photos for the "Where we work" section |

## Editing contact details

Email, cell number, social links and the "years of experience" figure all live in one place: the `DEUCON` settings block near the bottom of `index.html`. Change them there and every button and link on the page updates.

## Strict rules

These rules are also written at the top of `index.html`.

1. **No em dashes, ever.** Do not use the long em dash character anywhere, in page text or code. Rewrite with a comma, full stop, colon or brackets instead. The short en dash in time ranges (08:00 to 17:00) is allowed.
2. **Check before publishing.** Search the files for the em dash character before every upload. There must be zero matches.
3. **Contact details live in one place.** Only edit them in the `DEUCON` settings block.

## Previewing locally

Open `index.html` in a browser, or serve the folder with any static server, for example:

```bash
npx http-server@14.1.1 . -p 8642
```

## Publishing

The site can be hosted anywhere that serves static files, for example GitHub Pages or the existing xneelo hosting for deucon.co.za. Email for deucon.co.za is handled separately, so changing where the website is hosted does not affect email.
