# Resilience

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

Resilience is a United States cyber-risk company that underwrites cyber insurance and technology errors-and-omissions coverage while running the security analytics and claims service around it. Founded in 2016 by operators out of US military and intelligence backgrounds and headquartered in San Francisco, it distributes through brokers rather than direct-to-consumer, and positions itself as a specialty cyber carrier whose underwriting is fed by its own risk model — the Threatonomics Risk Graph — plus a 24/7 in-house Risk Operations Center and claims/incident-response team. Product lines are cyber insurance, technology E&O, claims and incident response, security investment prioritization, and multi-entity/portfolio risk, sold in the US and in UK, Canadian, German, French, Italian and Spanish locales. Its API posture is partner-gated and honest to record as such: there is no developer portal, no public API reference, no downloadable OpenAPI, and no public Postman collection anywhere on cyberresilience.com. The only machine-facing surface is portal.cyberresilience.com, a client and broker application that 302-redirects to an Auth0 tenant at auth.cyberresilience.com requesting an access token for the private audience https://api.prod.resilienceinsurance.app — an internal product API, not a published one. No ACORD, AL3, ACORD XML, NGDS, IVANS, Applied Epic or Vertafore reference appears anywhere on the public site, which is itself a finding for a US specialty carrier: this is a direct-underwriting, broker-relationship distribution model rather than an agency-download one.

**Areas:** Insurance · United States · Cyber Insurance · Property and Casualty · Insurtech · Underwriting · Claims · Risk Data · Technology Errors and Omissions · Brokerage · Specialty Insurance

## Resilience on APIs.io

Everything profiled for Resilience is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/resilience-cyber/](https://apis.io/providers/resilience-cyber/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Resilience Identity (Auth0 Authorization Server)](https://apis.io/apis/resilience-cyber/resilience-identity-auth0-authorization-server/) — The only publicly documented, machine-readable surface Resilience operates. portal.cyberresilience.com — the gated client and broker application — redirects…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Resilience Cyber Authentication](https://apis.io/security/resilience-cyber/resilience-cyber-authentication/)
- [Resilience Cyber Domain Security](https://apis.io/security/resilience-cyber/resilience-cyber-domain-security/)
- [Resilience Cyber Trust Center](https://apis.io/security/resilience-cyber/resilience-cyber-trust-center/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Resilience Cyber Scopes](https://apis.io/scopes/resilience-cyber/resilience-cyber-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://cyberresilience.com/)
- [Sign up](https://portal.cyberresilience.com/)
- [Support](https://cyberresilience.com/contact-us/)
- [Blog](https://cyberresilience.com/blog/)
- [Compliance](https://trust.cyberresilience.com/)
- [Trust centre](https://trust.cyberresilience.com/)
- [Terms of service](https://cyberresilience.com/terms-and-conditions/)
- [Privacy policy](https://cyberresilience.com/privacy-policy/)

## API Evangelist rating

**Kin Score 19.2** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 0.0 |
| Developer ergonomics | 11.9 |
| Access clarity | 22.4 |

**Agent readiness 2.5** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
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

**Regulatory alignment 34.2** — Insurance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/resilience-cyber/](https://apis.io/providers/resilience-cyber/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Resilience: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/resilience-cyber/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
