# helpersync-marketing

Static marketing site for HelperSync — deployed to Cloudflare Pages at [helper-sync.com](https://helper-sync.com).

## Contents

- `index.html` — landing page
- `privacy.html` — Privacy Policy (drafted in Termly, self-hosted; served at `/privacy`)
- `terms.html` — Terms of Service (drafted in Termly, self-hosted; served at `/terms`)

## Local preview

```sh
npx http-server . -p 5000 -c-1
# open http://localhost:5000
```

## Deploy

Cloudflare Pages auto-deploys on push to `main`.

## Brand

Visual system mirrors the native app — see `BRAND_SPEC_FOR_NATIVE.md` in the
[`helpersync-native`](https://github.com/deaconlock/helpersync-native) repo for the
authoritative palette, typography, and motif spec. Source of truth for the visual
language is the original HelperSync web app at
[`deaconlock/HelperSync`](https://github.com/deaconlock/HelperSync).
