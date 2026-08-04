# TurboRater (turborater)

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

TurboRater is a personal lines comparative insurance rating platform from **Insurance Technologies Corporation (ITC)**, now part of **Zywave** and marketed within Zywave Sales Cloud. It lets agencies, carriers, lead providers, and online aggregators quote auto, homeowners, condominium, renters, dwelling fire, and motorcycle coverage from 200+ carriers in a single, single-entry workflow, with real-time rates backed by carrier underwriting rules.

ITC exposes a **web service-based rating API**. ITC turned TurboRater into a service-oriented application for third parties in 2010, and in 2016 launched a homeowner rating API that returns rates from 40+ homeowner carriers (auto from 180+ carriers) through a single quote request. The API delivers real-time rates and can pull quote data as **XML or ITC's proprietary Turbo Tags (TT2) format**, and it supports a **real-time bridge** that hands a completed quote into a downstream point-of-sale, agency management, or website system (also via .TT2 / AL3 export).

## Access model (important)

The rating API is **partner- and subscription-gated**. There is no public developer portal, no public API reference, no published endpoint hostnames or authentication scheme, and no public pricing. Access, carrier appointments, and developer documentation are provisioned through ITC/Zywave sales to qualified partners (agencies, carriers, lead providers, and online aggregators).

Because of this, the APIs listed in `apis.yml` are **honestly modeled** from published TurboRater/ITC behavior and are flagged **`endpointsModeled=true`**. No concrete request paths, hostnames, or schemas are asserted or fabricated in this entry.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/turborater/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/turborater/refs/heads/main/apis.yml)

## Tags

- Insurance
- InsurTech
- Comparative Rating
- Auto Insurance
- Home Insurance
- Quotes
- Real-Time Rating
- Personal Lines
- ITC
- Zywave

## Timestamps

- **Created:** 2026-07-10
- **Modified:** 2026-07-10

## APIs (modeled)

### TurboRater Rating and Quotes API

Submit a single comparative rating request and receive real-time premiums and coverage back from many carriers at once, across auto, homeowners, condominium, renters, dwelling fire, and motorcycle lines. Core web service-based rating surface offered to third parties since 2010. `endpointsModeled=true`.

### TurboRater Applicants and Risk API

Capture the applicant, drivers, vehicles, dwelling, and coverage detail a comparative rating request is built from, so a single point of data entry is reused across every carrier quote and bridged downstream without re-keying. `endpointsModeled=true`.

### TurboRater Real-Time Bridge API

Hand a completed quote from TurboRater into a downstream point-of-sale, agency management, or website platform in real time, or export it for daily download, using ITC's Turbo Tags 2.0 (.TT2) or AL3 formats. ITC requires a minimum real-time response time and lets agents either bind through TurboRater or bridge the quote into their own system. `endpointsModeled=true`.

### TurboRater Results Retrieval API

Pull the quote and rate results a rating request produced, in either XML or ITC's proprietary TurboTags (TT2) format, so any third-party system can consume premiums, coverages, carrier eligibility, and pay plans. `endpointsModeled=true`.

## Common Properties

- [Website](https://www.turborater.com)
- [LinkedIn](https://www.linkedin.com/company/insurance-technologies-corporation)
- [Documentation](https://www.turborater.com/products/rating/features/integration)
- [Plans](plans/turborater-plans-pricing.yml)
- [Rate Limits](rate-limits/turborater-rate-limits.yml)
- [Fin Ops](finops/turborater-finops.yml)

## WebSocket review

TurboRater does **not** expose a documented public WebSocket API. Its rating integration is request/response web services over HTTPS plus file-based (.TT2 / AL3) bridge/export. The "real-time" behavior is a low-latency synchronous rating request, not a bidirectional or streaming socket. See `review.yml`.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
