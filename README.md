# Monte Carlo

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
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

**Areas:** Data Observability · Data Quality · Data Reliability · Data Lake · Data Warehouse · Data Lineage · Monitoring · AI Observability

## Monte Carlo on APIs.io

Everything profiled for Monte Carlo is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/monte-carlo/](https://apis.io/providers/monte-carlo/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Monte Carlo GraphQL API](https://apis.io/apis/monte-carlo/graphql-api/) — GraphQL API for the Monte Carlo data observability platform. Provides programmatic access to monitors, incidents, assets, lineage, custom rules, warehouses,…
- [Monte Carlo Push Ingest API](https://apis.io/apis/monte-carlo/push-ingest-api/) — A REST write API for pushing observability data into Monte Carlo from sources its pull-based collectors cannot reach. Three endpoints — POST…
- [Monte Carlo MCP Server](https://apis.io/apis/monte-carlo/mcp-server/) — A first-party, fully hosted Model Context Protocol server that gives AI agents direct access to Monte Carlo — investigating alerts, exploring assets and…
- [Monte Carlo Graph QL API](https://apis.io/apis/monte-carlo/monte-carlo-graph-ql-api/) — The Graph QL API from Monte Carlo — 1 operation(s) for graph ql.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Monte Carlo GraphQL API](https://apis.io/graphqls/monte-carlo/monte-carlo-graphql/)

#### MCP servers (2)

Model Context Protocol servers that expose the API to agents.

- [monte-carlo](https://apis.io/servers/monte-carlo/monte-carlo/)
- [Moved to /providers/monte-carlo/](https://apis.io/servers/monte-carlo/monte-carlo-data-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Monte Carlo Agentic Access](https://apis.io/agentic-access/monte-carlo/monte-carlo-agentic-access/)

#### Collections (2)

Postman and Open Collection request collections.

- [Monte Carlo GraphQL API](https://apis.io/collections/monte-carlo/open-monte-carlo/)
- [Monte Carlo Graphql API](https://apis.io/collections/monte-carlo/open-monte-carlo-graphql-api/)

#### Overlays (2)

OpenAPI overlays, including conversational phrasing for each operation.

- [Monte Carlo Graph Ql Api Overlay](https://apis.io/overlays/monte-carlo/monte-carlo-graph-ql-api-overlay/)
- [Monte Carlo Graph Ql Api Phrasing Overlay](https://apis.io/overlays/monte-carlo/monte-carlo-graph-ql-api-phrasing-overlay/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Monte Carlo Authentication](https://apis.io/security/monte-carlo/monte-carlo-authentication/)
- [Monte Carlo Domain Security](https://apis.io/security/monte-carlo/monte-carlo-domain-security/)
- [Monte Carlo Trust Center](https://apis.io/security/monte-carlo/monte-carlo-trust-center/)
- [Monte Carlo Vulnerability Disclosure](https://apis.io/security/monte-carlo/monte-carlo-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Monte Carlo Scopes](https://apis.io/scopes/monte-carlo/monte-carlo-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Monte Carlo Plans Pricing](https://apis.io/plans/monte-carlo/monte-carlo-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Monte Carlo Rate Limits](https://apis.io/rate-limits/monte-carlo/monte-carlo-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://montecarlo.ai/)
- [Documentation](https://docs.getmontecarlo.com)
- [Getting started](https://docs.getmontecarlo.com/docs/welcome)
- [API reference](https://apidocs.getmontecarlo.com/)
- [Pricing](https://montecarlo.ai/request-for-pricing/)
- [Changelog](https://docs.getmontecarlo.com/changelog)
- [Blog](https://montecarlo.ai/blog/feed)
- [Terms of service](https://montecarlo.ai/terms-of-service)
- [Privacy policy](https://montecarlo.ai/privacy-policy)
- [GitHub](https://github.com/monte-carlo-data)
- [Status](https://status.getmontecarlo.com/)

## API Evangelist rating

**Kin Score 67.5** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 53.2 |
| Contract governance | 18.2 |
| Operational transparency | 84.2 |
| Developer ergonomics | 67.9 |
| Access clarity | 85.5 |

**Agent readiness 58.6** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | unknown |
| Agent Skills | yes |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 39.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/monte-carlo/](https://apis.io/providers/monte-carlo/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Monte Carlo: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/monte-carlo/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
