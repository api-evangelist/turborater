# TurboRater

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

TurboRater is a personal lines comparative insurance rating platform from Insurance Technologies Corporation (ITC), now part of Zywave (marketed within Zywave Sales Cloud). It lets agencies, carriers, lead providers, and online aggregators quote auto, homeowners, condominium, renters, dwelling fire, and motorcycle coverage from 200+ carriers in a single workflow. ITC exposes a web service-based rating API (a service-oriented version of TurboRater it first offered to third parties in 2010, extended with a homeowner rating API in 2016) that returns real-time rates from hundreds of carriers and can pull quote data as XML or ITC's proprietary Turbo Tags (TT2) format, plus a real-time bridge that hands a completed quote into an agency point-of-sale or management system. The rating API is partner- and subscription-gated - access, carrier appointments, and the developer documentation are provisioned through ITC/Zywave sales rather than a public developer portal, so the specific endpoints below are honestly modeled from published behavior, not copied from a public API reference.

**Areas:** Insurance · Insurtech · Comparative Rating · Auto Insurance · Home Insurance · Quotes · Real-Time Rating · Personal Lines · ITC · Zywave

## TurboRater on APIs.io

Everything profiled for TurboRater is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/turborater/](https://apis.io/providers/turborater/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [TurboRater Rating and Quotes API](https://apis.io/apis/turborater/turborater-rating-quotes-api/) — Submit a single comparative rating request and receive real-time premiums and coverage back from many carriers at once, across auto, homeowners,…
- [TurboRater Applicants and Risk API](https://apis.io/apis/turborater/turborater-applicants-api/) — Capture the applicant, drivers, vehicles, dwelling, and coverage detail that a comparative rating request is built from, so a single point of data entry can…
- [TurboRater Real-Time Bridge API](https://apis.io/apis/turborater/turborater-realtime-bridge-api/) — Hand a completed quote from TurboRater into a downstream point-of-sale, agency management, or website platform in real time, or export it for daily…
- [TurboRater Results Retrieval API](https://apis.io/apis/turborater/turborater-results-retrieval-api/) — Pull the quote and rate results a rating request produced, in either XML or ITC's proprietary TurboTags (TT2) format, so any third-party system can consume…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Turborater Domain Security](https://apis.io/security/turborater/turborater-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Turborater Plans Pricing](https://apis.io/plans/turborater/turborater-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Turborater Rate Limits](https://apis.io/rate-limits/turborater/turborater-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Turborater Finops](https://apis.io/finops/turborater/turborater-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.turborater.com)
- [Documentation](https://www.turborater.com/products/rating/features/integration)

## API Evangelist rating

**Kin Score 9.1** — minimal · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 9.5 |
| Access clarity | 7.9 |

**Agent readiness 0.6** — human-only

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

**Regulatory alignment 5.3** — Insurance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/turborater/](https://apis.io/providers/turborater/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for TurboRater: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/turborater/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
