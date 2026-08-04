# Monte Carlo (monte-carlo)

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

Monte Carlo is a data and AI observability platform that monitors data warehouses, lakes, and pipelines for freshness, volume, schema, and quality anomalies, helping data teams detect, resolve, and prevent data downtime across Snowflake, Databricks, BigQuery, Redshift, and other modern data stack tools. Monte Carlo exposes a GraphQL API at https://api.getmontecarlo.com/graphql used for programmatic access to monitors, incidents, lineage, assets, alerts, custom rules, and lake/metastore integrations, with a supporting Python SDK and CLI (pycarlo / montecarlo). Authentication uses an API Key ID and Token pair sent via headers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/monte-carlo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/monte-carlo/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Data Observability
- Data Quality
- Data Reliability
- Data Lake
- Data Warehouse
- Lineage
- Monitoring
- AI Observability

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Monte Carlo GraphQL API

GraphQL API for the Monte Carlo data observability platform. Provides programmatic access to monitors, incidents, assets, lineage, custom rules, warehouses, lakes, metastores, and alerts. Authentication uses an account or personal API Key ID and Token sent via the x-mcd-id and x-mcd-token headers (or as a Bearer token).

- **Human URL:** [https://docs.getmontecarlo.com/docs/api](https://docs.getmontecarlo.com/docs/api)
- **Base URL:** `https://api.getmontecarlo.com/graphql`

#### Tags

- Data Observability
- GraphQL
- Monitoring
- Data Quality
- Lineage

#### Properties

- [Documentation](https://docs.getmontecarlo.com/docs/api)
- [Developer  Resources](https://docs.getmontecarlo.com/docs/developer-resources)
- [Data  Lakes  Integration](https://docs.getmontecarlo.com/docs/data-lakes)
- [Python  S D K (pycarlo)](https://github.com/monte-carlo-data/python-sdk)
- [C L I](https://github.com/monte-carlo-data/monte-carlo-cli)
- [M C P  Server](https://docs.getmontecarlo.com/docs/mcp-server)
- [Postman Collection](collections/monte-carlo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/monte-carlo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/monte-carlo-data)
- [Website](https://www.montecarlodata.com)
- [Documentation](https://docs.getmontecarlo.com)
- [GitHub Organization](https://github.com/monte-carlo-data)
- [Pricing](https://www.montecarlodata.com/pricing/)
- [Sign Up](https://www.montecarlodata.com/request-a-demo/)
- [L L Ms Txt](https://docs.getmontecarlo.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
