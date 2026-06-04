# University of York (university-of-york)

The University of York is a public research university in York, United Kingdom, ranked #184 in the QS World University Rankings 2025 and a member of the Russell Group. This repository catalogs the university's confirmed public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile. York does not run a dedicated public developer portal; its verifiable programmatic surface is standards-based and library/research oriented.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-york/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-york-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, United Kingdom, Research, Library, Open Access, OAI-PMH

## APIs

- **White Rose Research Online (OAI-PMH)** — OAI-PMH 2.0 metadata harvesting for the shared York/Leeds/Sheffield EPrints research repository. Docs: https://eprints.whiterose.ac.uk/about.html — Base URL: https://eprints.whiterose.ac.uk/cgi/oai2
- **White Rose eTheses Online (OAI-PMH)** — OAI-PMH 2.0 metadata harvesting for the shared theses repository. Docs: https://etheses.whiterose.ac.uk/ — Base URL: https://etheses.whiterose.ac.uk/cgi/oai2
- **YorSearch Library Discovery (Ex Libris Primo)** — Primo discovery service on an Alma backend (view id 44YORK-NUI); Primo REST/PNX APIs exist but are not openly documented by the university. Docs: https://www.york.ac.uk/library/resources/yorsearch-help/

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-york-plans-pricing.yml](plans/university-of-york-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-york-rate-limits.yml](rate-limits/university-of-york-rate-limits.yml)
- FinOps: [finops/university-of-york-finops.yml](finops/university-of-york-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.york.ac.uk/
- GitHub: https://github.com/university-of-york
- LinkedIn: https://uk.linkedin.com/school/uniofyork/
- Status: https://status.york.ac.uk/
- Review: [review.yml](review.yml)

## Notes

All entries were verified by directly probing each URL on 2026-06-03. Both White Rose OAI-PMH endpoints returned valid HTTP 200 Identify responses; the YorSearch Primo UI and the official website, GitHub org, and status page returned HTTP 200. The GitHub organization is verified against the york.ac.uk domain but hosts internal IT/faculty engineering tooling rather than published external APIs. No `data.york.ac.uk` open-data API resolved (HTTP 000). The LinkedIn page exists publicly but returns LinkedIn's 999 anti-bot status to automated probes. No endpoints or documentation URLs were fabricated; nothing was cataloged that could not be confirmed live.

## Maintainers

- Kin Lane — kin@apievangelist.com
