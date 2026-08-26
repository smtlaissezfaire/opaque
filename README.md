# Opaque

A 6-part business decision simulation delivered through the mail.

This repo is a static site: `index.html`, `styles.css`, and `buy/index.html`.

## Local preview

From the repo root:

```bash
python3 -m http.server 8000
```

Then open:

- Home: [http://localhost:8000/](http://localhost:8000/)
- Buy: [http://localhost:8000/buy/](http://localhost:8000/buy/)

Stop the server with Ctrl+C.

Any local static server works. Serve the repo root so `/buy/` resolves to `buy/index.html`.
