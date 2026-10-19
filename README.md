# marilometa.github.io

Source for the personal portfolio of **Marilo Meta**, Salesforce MVP and CRM architect.

**Live site:** https://marilometa.github.io/

## What's here

| File | Purpose |
|---|---|
| `index.html` | The whole site: one self-contained page with inline CSS and a little JavaScript |
| `404.html` | Branded "page not found" page |
| `favicon.svg` | Site icon |
| `og-image.png` | 1200×630 preview image used when the link is shared on LinkedIn, Slack and similar |
| `robots.txt`, `sitemap.xml` | Search engine hints |

There is no build step and no dependencies. Fonts load from Google Fonts.

## How it's published

GitHub Pages serves the `main` branch. Every push to `main` redeploys the site, usually within a minute. If a change doesn't show, hard-refresh the browser (Ctrl or Cmd + Shift + R).

## Editing notes

- Colors, fonts and spacing are defined as CSS variables at the top of `index.html`.
- The page is checked at phone widths from 320px up. Keep text at 12px or larger and links easy to tap.
- After changing the title or summary, also update the matching `og:` and `twitter:` meta tags and the JSON-LD block in the page head.

## Content rules

- Case studies describe the work only. **No client names, client data, credentials or confidential details.**
- Numbers and roles appear only once they can be backed up.
- Work for the current employer is kept separate from independent consulting.

## Related repositories

- [salesforce-finance-layer](https://github.com/marilometa/salesforce-finance-layer): interim revenue and billing architecture on Salesforce
- [salesforce-revenue-recognition](https://github.com/marilometa/salesforce-revenue-recognition): reference architecture for the post-Closed Won handoff
- [community-conference-kit](https://github.com/marilometa/community-conference-kit): data model and playbook for running a community-led conference

© 2026 Marilo Meta
