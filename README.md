# SkyWorld Stall — Store frontend

Public storefront. Static files only — walang Node server dito.

## Setup

1. I-edit ang `config.js`:

```js
window.SKYWORLD_CONFIG = {
  API_BASE: 'https://api.yourdomain.com', // URL ng backend
};
```

2. Serve as static site:

```bash
# local test (any static server)
npx serve .
# or: python3 -m http.server 5173
```

3. Siguraduhing naka-lista ang origin mo sa backend `ALLOWED_ORIGINS`.

## Deploy

- GitHub Pages / Netlify / Vercel / Cloudflare Pages / any static host
- Root = this folder (`index.html` at root)
