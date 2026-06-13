# Pulley

Cap table management platform for founders and finance leaders. Pulley provides
tools to manage equity and tokens from seed stage through IPO, including cap table
management, 409A valuations, stock-based compensation reporting, and integrations
with leading HRIS platforms and custodians.

**Website:** https://pulley.com/
**Blog:** https://pulley.com/blog
**Pricing:** https://pulley.com/pricing
**Help Center:** https://help.pulley.com
**LinkedIn:** https://www.linkedin.com/company/pulley-cap-table
**X:** https://x.com/pulleyapp

## API

Pulley provides a REST API enabling programmatic management of cap table data
including stakeholders, equity grants, option pools, SAFEs, convertible instruments,
vesting schedules, and investor reporting. The API powers integrations with HRIS
platforms (Rippling, Gusto, BambooHR, Workday) and custodians (Coinbase Prime,
Fireblocks, BitGo).

## Plans and Pricing

Pulley offers tiered annual subscription pricing for both equity and token products:

| Plan | Price | Stakeholders |
|------|-------|-------------|
| Startup | $1,200/year | 25 |
| Growth | $3,500/year | 40 |
| Enterprise | Custom | Custom |
| Token Cap Table | $4,500/year | 25 |
| Distributions | $4,500/year | 25 |
| 409A Valuation | From $10,000 | N/A |

See [plans/pulley-plans-pricing.yml](plans/pulley-plans-pricing.yml) for full details.

## Rate Limits

Pulley does not publicly document specific API rate limits. HRIS integrations
operate as one-way syncs from HR systems to Pulley. Custodian integrations use
API key authentication governed by each custodian's rate limit policies.

See [rate-limits/pulley-rate-limits.yml](rate-limits/pulley-rate-limits.yml).

## FinOps

Cost is primarily driven by stakeholder count and plan tier. A 15% bundle discount
applies when 409A valuations are purchased with an equity plan subscription.

See [finops/pulley-finops.yml](finops/pulley-finops.yml).

---

*APIs.json profile maintained by [Kin Lane](mailto:kin@apievangelist.com)*
