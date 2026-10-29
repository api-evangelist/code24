# Code24

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

CODE24 B.V. is a Dutch healthcare software company in Alkmaar that builds mConsole, a modern, modular electronic health record (EPD) for care and mental-health (GGZ) organisations, together with a family of "24" modules — Lab24, Opname24 (admissions), CrisisMonitor24, CTB24, Connect24, Router24, Dynaform24, Financieel24 and DataWarehouse24. Its architectural position is that a modern EPD must be open: care data is stored in standardised form using openEHR archetypes and Dutch zibs (zorginformatiebouwstenen), and every record is readable and writable through a software interface (API) so other care systems can be integrated without duplicate data entry. Connect24 exposes a FHIR REST API for collecting and transforming patient data to the Dutch MedMij standard; Router24 is a MedMij-qualified DVA that performs the authentication and resource-server roles for routing data to personal health environments (PGOs). CODE24 is also a Value Added Reseller of the Cadasto openEHR open data platform. The API surface is real but commercial: no developer portal, no public API reference and no machine-readable contract are published on any CODE24 host.

**Areas:** Company · Healthcare · Electronic Health Records · openEHR · FHIR · MedMij · Interoperability · Mental Health · Netherlands · Health Data

## Code24 on APIs.io

Everything profiled for Code24 is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/code24/](https://apis.io/providers/code24/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [mConsole EPD API](https://apis.io/apis/code24/mconsole-epd-api/) — mConsole is CODE24's modern EPD (electronic health record). CODE24 states that the record has a software interface (API) with which other care systems can…
- [Connect24 FHIR API](https://apis.io/apis/code24/connect24-fhir-api/) — Connect24 is CODE24's data-transformation service. CODE24 documents it as using a FHIR REST API for reading and writing information, collecting and…
- [Router24 MedMij DVA](https://apis.io/apis/code24/router24-medmij-dva/) — Router24 is CODE24's DVA (dienstverlener zorgaanbieders) solution under the Dutch MedMij afsprakenstelsel. CODE24 states that Router24 fulfils both the…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Code24 Domain Security](https://apis.io/security/code24/code24-domain-security/)
- [Code24 Vulnerability Disclosure](https://apis.io/security/code24/code24-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Code24 Plans Pricing](https://apis.io/plans/code24/code24-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Code24 Rate Limits](https://apis.io/rate-limits/code24/code24-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.code24.nl/)
- [Documentation](https://www.code24.nl/epd-koppelingen-en-integraties)
- [Support](https://support.code24.nl)
- [Blog](https://blog.code24.nl)
- [Security](https://www.code24.nl/kwetsbaarheid-melden)
- [Privacy policy](https://www.code24.nl/privacyverklaring)
- [GitHub](https://github.com/code24-nl)

## API Evangelist rating

**Kin Score 21.4** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 13.2 |
| Developer ergonomics | 16.7 |
| Access clarity | 25.0 |

**Agent readiness 2.5** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
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

**Regulatory alignment 26.6** — Health

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/code24/](https://apis.io/providers/code24/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Code24: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/code24/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
