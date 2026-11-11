# GT Project Monaco website

The website for GT Project Monaco, a Georgia Tech student team building an electric boat for the Energy Class of the 2027 Monaco Energy Boat Challenge. Live at https://gtprojectmonaco.com.

> This repository is public, and every file in it is served on the live site. Keep contact lists, budgets, logins and other private notes out of it. The full project handoff package (briefings, sponsor lists, call notes) is shared privately.

## What's here

| File | Purpose |
|---|---|
| `index.html` | The whole site in one self-contained file: CSS, the three.js hero scene, shaders and inline SVG logos. Fonts come from Google Fonts |
| `robots.txt`, `sitemap.xml` | Added in v116 so web filters and search engines can categorize the site |
| `docs/open.html` | Helper page used by the sponsor outreach tool to open Outlook compose tabs three seconds apart. Don't delete it |

## How it deploys

- Cloudflare Pages is connected to this repo: branch `main`, no build command, output directory `/`.
- A push to `main` is live in about a minute on gtprojectmonaco.com and gtprojectmonaco.pages.dev.
- The domain is registered at Namecheap with its nameservers pointed at Cloudflare, so DNS lives in Cloudflare.

## How to keep working on it

- Edit `index.html` and push to `main`. Commit messages follow a version pattern, for example `v117: add share image`. The last version is v117.
- Keep the established design. The rules and their reasons are in the website brief in the handoff package.
- Open items as of the Nov 2026 handoff:
  1. Ask the major web-filter vendors (Palo Alto, Zscaler, Cisco Talos, FortiGuard, Symantec, Forcepoint, Trellix) to categorize the domain as Education. A sponsor's corporate firewall blocked it as "unknown".
  2. Add a share preview image (`og:image`).
  3. Point the Instagram and LinkedIn footer links at real accounts.
  4. Replace the "TBD" sponsor stickers with real logos as sponsors sign.
  5. Test on a real iPhone.
