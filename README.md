# Platz Summer Beach

A small 3D walk-around of Seminyak beach by Platz Summer: coconut warung, surf shed, lineup, and sarong meditation, with live visitors via Supabase Realtime.

- Live site: https://platz-summer-beach.trudy0610.workers.dev
- The whole site is one file: `public/index.html`. Cloudflare deploys it on every push to `main` with `npx wrangler deploy` (see `wrangler.jsonc`).
- `public/index.html` carries its own `<!doctype>`, UTF-8 charset and viewport meta; keep them when updating the page.
