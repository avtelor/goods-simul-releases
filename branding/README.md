# Inventier branding assets

Public-facing brand images, primarily hosted here for **Auth0 Universal Login** which requires publicly fetchable URLs for logos / favicons. This repo is `goods-simul-releases` which is already public (it's also the electron-updater release channel), so GitHub's raw URLs work without authentication.

## Files

| File | Used for | Notes |
|---|---|---|
| `inventier-logo.png` | Auth0 Universal Login Logo URL | 256×256 transparent PNG. Source: `public/favicon.png` in [avtelor/goods-simul](https://github.com/avtelor/goods-simul). Drop in a refreshed version here whenever the master logo changes upstream. |

## URLs to use in Auth0 dashboard

```
https://raw.githubusercontent.com/avtelor/goods-simul-releases/main/branding/inventier-logo.png
```

Served via GitHub's CDN with a 5-minute cache TTL — fine for a sign-in page.
