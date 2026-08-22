# Carnegie Mellon University (carnegie-mellon-university)

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

Carnegie Mellon University is a private research university in Pittsburgh, Pennsylvania, United States, ranked #50 in the QS World University Rankings 2025. This repository catalogs CMU's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile. CMU has no single central developer portal; its strongest public API presence is in research and library infrastructure — most notably the Delphi Epidata API and the KiltHub institutional repository.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/carnegie-mellon-university/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=carnegie-mellon-university-api-evangelist&utm_content=repo

## Type

- Index / Producer / Public — `x-type: university`, `x-category: Private Research University`

## Tags

University, Higher Education, Education, United States, Private Research University, Research, Epidemiology, Public Health, Cybersecurity, Vulnerability Disclosure, Scholarly Publishing, Institutional Repository, Identity Federation, Open Access, Open Data

## APIs

Every surface carries an `x-operator`: **institution** (CMU's own host and engineering), **tenant**
(CMU's data on a vendor's platform) or **vendor** (not recorded here at all). Re-profiled 2026-08-19
under the university pipeline.

### Institution-operated

- **Delphi Epidata API** (`institution`) — Real-time and historical epidemiological surveillance data (COVIDcast, FluView, Delphi's own forecasts), operated by CMU's Delphi research group. Five endpoints verified live 2026-08-19; `/epidata/version` returned 4.1.44. Errors arrive with HTTP 200 and are signalled only in the body's `result` field. Base: https://api.delphi.cmu.edu/epidata — Docs: https://cmu-delphi.github.io/delphi-epidata/
- **CERT/CC Vulnerability Notes API** (`institution`) — The machine-readable record of coordinated vulnerability disclosure, operated by the CERT Division of the Software Engineering Institute, an FFRDC operated by Carnegie Mellon. Returns Vulnerability Notes, the CVEs each case covers, and per-vendor coordination statements. Lives on cert.org rather than cmu.edu, which is why the cohort audit could not see it. Base: https://kb.cert.org/vuls/api — Docs: https://certcc.github.io/
- **CMU Library Publishing Service API + OAI-PMH** (`institution`) — REST API and conformant OAI-PMH 2.0 provider for the five open-access journals University Libraries publishes. Self-hosted at 128.2.24.32, inside CMU's own /16 — the institution's own machine, not a vendor tenancy. Base: https://lps.library.cmu.edu/api — Site: https://lps.library.cmu.edu/
- **CMU Web Login (Shibboleth SAML 2.0 IdP)** (`institution`) — Campus-wide SAML identity provider on CMU's own host, publishing readable metadata and registered with InCommon/eduGAIN under the Research & Scholarship entity category. https://login.cmu.edu/idp/shibboleth

### Tenant relationships

- **KiltHub Institutional Repository** (`tenant`, figshare) — CMU's research data repository. The data and DOIs are CMU's; the platform, API and OAI-PMH endpoint are figshare's. `kilthub.cmu.edu` is a CNAME to `FIGSHARE.COM`; records are harvestable only from `api.figshare.com/v2/oai` using `set=portal_231`. https://kilthub.cmu.edu/
- **Canvas LTI 1.3 Advantage** (`tenant`, Instructure) — An LTI Advantage JWKS is served on a CMU hostname, but `canvas.cmu.edu` is a CNAME to `CMU-VANITY.INSTRUCTURE.COM`. The courses are CMU's; the LTI engineering is not.
- **CMU Eats API** (`tenant`, ScottyLabs) — Dining locations, hours and menus, built and run by a CMU student organization at `api.cmueats.com`. It exists because CMU's own dining application is a Blazor catch-all that returns an SPA shell with HTTP 200 for every path, including nonsense. Endorsement by CMU: unverified.

### Removed 2026-08-19

Ten figshare-derived OpenAPIs (`altmetric`, `articles`, `authors`, `collections`, `institutions`,
`oauth`, `other`, `profiles`, `projects`, `symplectic`) and twenty derived Postman/OpenCollection
files whose every request URL was `api.figshare.com`. They were one vendor contract, split by tag,
credited to Carnegie Mellon eleven times over — the same document that gave the eight top-scoring
universities in this catalog an identical agent-readiness score of 38.9.

## Plans

- [plans/carnegie-mellon-university-plans-pricing.yml](plans/carnegie-mellon-university-plans-pricing.yml)

## Rate Limits

- [rate-limits/carnegie-mellon-university-rate-limits.yml](rate-limits/carnegie-mellon-university-rate-limits.yml)

## FinOps

- [finops/carnegie-mellon-university-finops.yml](finops/carnegie-mellon-university-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Common Properties

- Website: https://www.cmu.edu/
- GitHub: https://github.com/cmu-delphi
- SourceCode: https://github.com/cmu-lib
- LinkedIn: https://www.linkedin.com/school/carnegie-mellon-university/
- Authentication: https://www.cmu.edu/computing/services/security/identity-access/authentication/sso-provider.html

## Notes

All endpoints were probed during cataloging on 2026-06-03. The Delphi Epidata API and KiltHub OAI-PMH endpoint were verified returning live data. The former Heinz College `courses_api` now 302-redirects to a student web page and is no longer a usable public API, so it was excluded. The Schedule of Classes is a servlet-based web UI, not a documented API, and was not cataloged as an API. No endpoints were fabricated — only URLs and properties verified to resolve are included.

## Maintainers

- Kin Lane — kin@apievangelist.com
