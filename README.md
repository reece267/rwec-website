# RW Electrical Consulting — Website

Static landing page for RW Electrical Consulting, hosted on Cloudflare (Workers static assets).

## Stack

Plain HTML, CSS and vanilla JS — no build step, no framework, no dependencies.

## Structure

```
index.html
assets/
  css/styles.css
  js/main.js
  images/
```

## Local preview

Open `index.html` directly in a browser, or serve the folder with any static file server.

## Deployment (Cloudflare)

Deployed via Cloudflare's Git-connected Workers flow, serving the repo root as static assets
(see `wrangler.jsonc`). No build step — deploy command is just `npx wrangler deploy`.

Connect this repo in the Cloudflare dashboard and it will deploy on every push to the
main branch.
