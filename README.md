# Resilience (resilience-cyber)

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
