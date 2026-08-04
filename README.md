# Pulley

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
