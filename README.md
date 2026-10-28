# Aave

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

Aave is a decentralized, non-custodial liquidity protocol where users supply assets to earn yield and borrow against collateral. The protocol runs on Ethereum and many L2s (Arbitrum, Optimism, Base, Polygon, Avalanche, zkSync, Scroll, Metis) and exposes developer surfaces beyond on-chain contracts: official Aave V3 / V4 TypeScript SDKs, Aave Kit (React + TypeScript + GraphQL), and protocol subgraphs hosted on The Graph for indexed market, reserve, user, and historical data.

**Areas:** DeFi · Lending · Borrowing · Liquidity · Protocol · Subgraph · GraphQL

## Aave on APIs.io

Everything profiled for Aave is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/aave/](https://apis.io/providers/aave/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Aave V3 Pool (Smart Contracts)](https://apis.io/apis/aave/v3-pool/) — Core Aave V3 protocol contracts — Pool, L2 Pool, Wrapped Token Gateway, PoolAddressesProvider, Pool Configurator, Interest Rate Strategy, Access Control…
- [Aave V4 Protocol (Smart Contracts)](https://apis.io/apis/aave/v4-protocol/) — Next-generation Aave V4 protocol implementation with unified liquidity layer, hub-and-spoke architecture, and improved risk management. Source available in…
- [Aave V3 SDK](https://apis.io/apis/aave/sdk-v3/) — Official TypeScript SDK for Aave V3 that wraps protocol interactions — supply, borrow, repay, withdraw, swap collateral, repay-with-collateral, and read…
- [Aave V4 SDK](https://apis.io/apis/aave/sdk-v4/) — Official TypeScript SDK for the Aave V4 protocol, exposing typed operations for supplying, borrowing, and reading V4 hub state.
- [Aave Kit](https://apis.io/apis/aave/kit/) — Higher-level toolkit (React + TypeScript + GraphQL) for embedding Aave market data and protocol actions into apps. Built on top of the Aave SDK and protocol…
- [Aave Protocol Subgraphs](https://apis.io/apis/aave/protocol-subgraphs/) — The Graph subgraphs that index Aave V2 and V3 reserves, users, liquidations, flash loans, rewards, and historical balances. Queried via GraphQL across each…
- [aave-utilities](https://apis.io/apis/aave/utilities/) — TypeScript helper library exposing math, formatting, and contract-call helpers for building UIs and analytics on top of Aave V2 and V3 markets.
- [Aave Interface](https://apis.io/apis/aave/interface/) — Open-source web interface (app.aave.com) for interacting with the Aave protocol — a reference implementation that integrates the SDK, Kit, and subgraphs.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Aave GraphQL API](https://apis.io/graphqls/aave/aave-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [MCP Server](https://apis.io/servers/aave/mcp-server/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Aave Domain Security](https://apis.io/security/aave/aave-domain-security/)
- [Aave Trust Center](https://apis.io/security/aave/aave-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Aave Plans Pricing](https://apis.io/plans/aave/aave-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Aave Rate Limits](https://apis.io/rate-limits/aave/aave-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Aave Finops](https://apis.io/finops/aave/aave-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://aave.com)
- [Documentation](https://aave.com/docs)
- [Blog](https://aave.com/blog)

## API Evangelist rating

**Kin Score 15.8** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 70.0 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 26.3 |
| Developer ergonomics | 16.7 |
| Access clarity | 13.2 |

**Agent readiness 3.7** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 10.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/aave/](https://apis.io/providers/aave/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Aave: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/aave/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
