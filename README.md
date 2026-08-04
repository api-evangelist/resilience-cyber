# Resilience (resilience-cyber)

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

Resilience is a United States cyber-risk company that underwrites cyber insurance and technology errors-and-omissions coverage while running the security analytics and claims service around it. Founded in 2016 and headquartered in San Francisco, it distributes through appointed brokers rather than direct-to-consumer, and positions itself as a specialty cyber carrier whose underwriting is fed by its own risk model — the Threatonomics Risk Graph — plus a 24/7 in-house Risk Operations Center and claims/incident-response team.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/resilience-cyber/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/resilience-cyber/refs/heads/main/apis.yml)

> Not to be confused with [api-evangelist/resilience](https://github.com/api-evangelist/resilience) — National Resilience, the biomanufacturing CDMO at resilience.com. This record is the cyber insurance carrier at cyberresilience.com (formerly Arceo Labs).

## Tags

- Insurance
- United States
- Cyber Insurance
- Property and Casualty
- Insurtech
- Underwriting
- Claims
- Risk Data
- Technology Errors and Omissions
- Broker
- Specialty Insurance

## Timestamps

- **Created:** 2026-07-25
- **Modified:** 2026-07-25

## APIs

**None.** Resilience publishes no public, self-serve API.

Every conventional developer path was probed on 2026-07-25. `developer.`, `developers.`, `docs.` and `api.cyberresilience.com` do not resolve. `/developers`, `/developer`, `/api`, `/partners` and `/integrations` all return HTTP 200 but are WordPress soft-404s that serve the marketing homepage byte-for-byte. There is no API reference, no downloadable OpenAPI or Swagger document, no public Postman collection (0 results), no GraphQL endpoint, no published `.proto`, and no webhook or AsyncAPI event catalog.

The only machine-facing surface is [portal.cyberresilience.com](https://portal.cyberresilience.com/), a client and broker application that 302-redirects to an Auth0 tenant at `auth.cyberresilience.com` requesting an authorization-code + PKCE token for the audience `https://api.prod.resilienceinsurance.app`. A product API exists; it is private, and its host returns 404 for every spec path anonymously.

### Insurance verbs

| Verb | Public API | How it actually happens |
| --- | --- | --- |
| Quote | No | Broker submission and the gated portal |
| Bind | No | Underwriter-mediated through appointed brokers |
| Issue | No | Policy documents delivered inside the gated portal |
| FNOL | No | 24/7 in-house claims team and a "File a Claim" web form |

### ACORD posture

**No ACORD reference found.** Scans of the homepage, brokers page, Threatonomics Risk Graph page, Risk Operations Center page and about page returned zero hits for ACORD, AL3, ACORD XML, NGDS, IVANS, agency download, Applied Epic, Vertafore or AMS360 — and targeted web search found nothing company-specific either. Consistent with the US market seam: Resilience underwrites directly through broker relationships and its own portal, not through the IVANS/agency-download plumbing that moves conventional lines between carriers and agency management systems.

A note on language: Resilience's material describes integrating with a client's cloud services and internal systems for continuous risk assessment. That is Resilience *consuming* customer-side APIs as an inbound data collector — not *publishing* one.

## Products

- Cyber Insurance — <https://cyberresilience.com/products/cyber-insurance/>
- Technology Errors & Omissions — <https://cyberresilience.com/products/technology-errors-and-omissions-insurance/>
- Claims & Incident Response — <https://cyberresilience.com/products/claims-incident-response/>
- Threatonomics Risk Graph — <https://cyberresilience.com/products/threatonomics-risk-graph/>
- Security Investment Prioritization — <https://cyberresilience.com/products/security-investment-prioritization/>
- Multi-Entity & Portfolio Risk — <https://cyberresilience.com/products/multi-entity-and-portfolio-risk/>
- Risk Operations Center — <https://cyberresilience.com/risk-operations-center/>

## Links

- [Website](https://cyberresilience.com/)
- [Blog](https://cyberresilience.com/blog/) · [RSS](https://cyberresilience.com/?feed=rss2)
- [Brokers](https://cyberresilience.com/brokers/)
- [Client / Broker Portal (login required)](https://portal.cyberresilience.com/)
- [Trust Center](https://trust.cyberresilience.com/)
- [LinkedIn](https://www.linkedin.com/company/resilience-cyber/)
- [X](https://x.com/ResilienceSays)
- [YouTube](https://www.youtube.com/@Cyber.Resilience)
- [Careers](https://job-boards.greenhouse.io/resilience)

## Review

See [`review.yml`](review.yml) for the full probe log, HTTP statuses, ACORD evidence, and auth model.
