# Sources and provenance

All rows in this repository were transcribed from public pages on ServerBudget on **2026-11-20**. The source site states that its figures were checked against provider pricing pages; this repository does not re-verify them and passes through the source's own caveats verbatim.

| File | Source page (live) | Notes preserved from source |
|---|---|---|
| `vps-plans.csv` | https://serverbudget.com/best-vps | Hetzner row keeps "Not published on fetched page"; promo/list prices kept as printed. |
| `three-way-entry.csv` | https://serverbudget.com/digitalocean-vs-vultr-vs-hostinger | Hostinger renewal price kept as printed ("renews $11.99"). |
| `datacenters.csv` | https://serverbudget.com/cheap-vps-hosting | Datacenter notes kept as printed. |
| `vultr-billing-modes.csv` | https://serverbudget.com/vultr-pricing | VX1 monthly column kept as "no monthly column". |

Provider primary sources linked by the source site (Vultr pricing page):

- https://www.vultr.com/pricing/
- https://api.vultr.com/v2/plans
- https://docs.vultr.com/platform/billing
- https://docs.vultr.com/platform/billing/faq

The source pages were fetched over HTTPS on 2026-11-20 and the table rows were read from the rendered page. If a number changed since, the live source page is authoritative.
