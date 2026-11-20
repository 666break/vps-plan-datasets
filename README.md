# VPS plan datasets

Small, reusable datasets on entry-level VPS plans and provider footprints. Each row is transcribed from a public comparison page on ServerBudget (https://serverbudget.com), which states that its figures were checked against provider pricing pages. Where the source page itself states an "as of" date or a price caveat, that wording is preserved verbatim rather than cleaned up.

These files are provided as-is for anyone comparing hosting options. Prices change; verify against the provider before buying.

## Contents

| File | What it holds | Source page |
|---|---|---|
| `vps-plans.csv` | Entry and mid-tier plans, price / vCPU / RAM / storage / traffic | https://serverbudget.com/best-vps |
| `three-way-entry.csv` | DigitalOcean vs Vultr vs Hostinger entry plans, with billing terms | https://serverbudget.com/digitalocean-vs-vultr-vs-hostinger |
| `datacenters.csv` | Provider datacenter footprints and notes | https://serverbudget.com/cheap-vps-hosting |
| `vultr-billing-modes.csv` | Vultr plan rows showing hourly vs monthly billing | https://serverbudget.com/vultr-pricing |

`index.html` is a standalone, no-dependency browser tool that loads the embedded plan data and lets you sort and filter by provider, vCPU, RAM and monthly price. Open it directly in a browser; it makes no network calls.

Provenance and extraction date are recorded in `SOURCES.md`.

Data first extracted 2026-11-20.
