# Imperial Nomad Tours

A responsive, bilingual-ready static tour website inspired by Imperial Nomad Tours. It supports English, Mongolian, Chinese, Russian, Thai, Brazilian Portuguese, French, and Italian. Language selection is saved in the browser.

## Deploy

This is plain HTML, CSS, and JavaScript. It does not need Python, Node.js, a build step, or dependencies.

Upload these files together to the root of any static web host:

- `index.html`
- `styles.css`
- `app.js`
- `locale-data.js`

For example, publish the folder with GitHub Pages, Netlify, or Cloudflare Pages. Routes use URL hashes, so region and information pages work without server-side routing or rewrite rules.

For a quick local preview, open `index.html` in a browser.

The photos and typefaces load from Unsplash and Google Fonts, so those visual assets need an internet connection. Locale strings live in [locale-data.js](locale-data.js); untranslated keys fall back to English.
