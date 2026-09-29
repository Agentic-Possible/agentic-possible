# Agentic Possible

Minimal landing page for a Detroit-based software and automation consultancy.

## Run locally

No build step is required. Open `public/index.html` directly, or run:

```bash
python3 -m http.server 8000 --directory public
```

Then visit `http://localhost:8000`.

## Customize

- Update the contact email in `public/index.html`.
- Edit copy directly in `public/index.html`.
- Design tokens and responsive styles live in `public/styles.css`.

## Deploy

Cloudflare Workers serves the files in `public/` at `agenticpossible.com` and `www.agenticpossible.com`. After signing in with Wrangler, deploy changes with:

```bash
wrangler deploy
```

GitHub pushes do not trigger a deployment automatically.
