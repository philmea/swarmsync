# OneField marketing site

A single-page marketing site built from the content in [`docs/`](../docs). It is
one self-contained `index.html` (inline CSS and JS, Google Fonts only), so it
needs no build step.

Preview locally:

```bash
python3 -m http.server -d website 8000
```

Calls to action link to the published docs at https://philmea.github.io/swarmsync/
and to sign-up at https://onefield.io. Every claim on the page comes from the
docs. When the docs change, update the matching section here.
