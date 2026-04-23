# nextgennetworkacademy.github.io

> Storefront landing page for [nextgennetworkacademy.com](https://nextgennetworkacademy.com)

## What this repo is

This is the **storefront only** — the `index.html` landing page served at `nextgennetworkacademy.com`. One file. No build tools. No dependencies. Pure HTML/CSS/JS.

The actual content (guides, labs, how-tos) lives in the [`ngna-content`](https://github.com/nextgennetworkacademy/ngna-content) repo, served via MkDocs.

## Repo structure

```
nextgennetworkacademy.github.io/
├── index.html      ← the entire storefront
├── 404.html        ← custom 404 page
└── CNAME           ← custom domain config
```

## Local preview

```bash
# No build step needed — just open in browser
open index.html

# Or serve locally
python3 -m http.server 8000
```

## Custom domain setup

1. Add `nextgennetworkacademy.com` to the `CNAME` file
2. In GitHub repo Settings → Pages → set custom domain
3. Update DNS at your registrar:
   - `A` records pointing to GitHub Pages IPs
   - `CNAME` for `www` pointing to `nextgennetworkacademy.github.io`

## Design

Retro arcade aesthetic — `Press Start 2P` pixel font, `Share Tech Mono` monospace, neon green `#39ff14` on near-black `#0a0a0f`. Scanline overlay. CRT grid background. No frameworks, no dependencies.

## Related repos

| Repo | Purpose |
|------|---------|
| [`ngna-content`](https://github.com/nextgennetworkacademy/ngna-content) | MkDocs content site (learn, labs) |
| [`avd-campus-tags`](https://github.com/nextgennetworkacademy/avd-campus-tags) | Working lab: AVD CloudVision campus tags |
