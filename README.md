# ATLAS Pilot Plan B Portal

Static fallback for the ATLAS commodity trading simulation. Used only if the live platform is unreachable on pilot day.

This repo is **auto-mirrored** from the private orchestrator repo via GitHub Action; do not edit files here directly — changes will be overwritten on the next mirror run.

## Pages

- `index.html` — landing (public, no password)
- `teams/<variant-slug>.html` — 30 team briefings (each encrypted with a unique team password via [staticrypt](https://github.com/robinmoisson/staticrypt))
- `facilitator.html` — full offline calculator (encrypted with the facilitator password)
- `assets/styles.css` — shared design tokens

Generated: 2026-05-08T07:01:18.654Z
