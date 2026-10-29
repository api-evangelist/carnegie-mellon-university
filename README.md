# Carnegie Mellon University

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

Carnegie Mellon University is a private research university in Pittsburgh, Pennsylvania, ranked 49th in the QS World University Rankings. It operates no central developer portal, no API gateway and no institution-wide developer program — api.cmu.edu and data.cmu.edu do not exist as developer surfaces — but unlike most of this cohort it does genuinely engineer public APIs, in three unrelated units that share no identifier, envelope or error model. The Delphi research group runs the Delphi Epidata API for real-time epidemiological surveillance; the CERT Coordination Center at the Software Engineering Institute runs the Vulnerability Notes API, the machine-readable record of coordinated vulnerability disclosure; and University Libraries self-hosts the Library Publishing Service, five open-access journals behind a REST API and a conformant OAI-PMH 2.0 provider on CMU's own hardware. None of the three publishes an OpenAPI, a changelog on the API host, a status page or a deprecation policy, and both research APIs return errors with HTTP 200. Everything else that carries CMU's name is a tenancy: KiltHub is figshare, Canvas is Instructure, and the eleven figshare-derived contracts this profile held until 2026-08-19 were a vendor's engineering credited to the university.

**Areas:** University · Higher Education · Education · United States · Private Research University · Research · Epidemiology · Public Health · Cybersecurity · Vulnerability Disclosure · Scholarly Publishing · Institutional Repository

## Carnegie Mellon University on APIs.io

Everything profiled for Carnegie Mellon University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/carnegie-mellon-university/](https://apis.io/providers/carnegie-mellon-university/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [CMU Web Login (Shibboleth SAML 2.0 Identity Provider)](https://apis.io/apis/carnegie-mellon-university/web-login-sso/) — Carnegie Mellon's campus-wide single sign-on identity provider, running Shibboleth on CMU's own host and address space (login.cmu.edu, 128.2.42.22). Its…
- [KiltHub Institutional Repository (figshare) — tenant](https://apis.io/apis/carnegie-mellon-university/kilthub-figshare-tenant/) — KiltHub is Carnegie Mellon's institutional repository for research data and scholarly output. The data, the collections and the DOIs are CMU's; the…
- [Canvas LTI 1.3 Advantage (Instructure) — tenant](https://apis.io/apis/carnegie-mellon-university/canvas-lti-tenant/) — CMU's learning management system serves an LTI 1.3 / LTI Advantage JWKS at canvas.cmu.edu/api/lti/security/jwks, so the LTI standard is genuinely in play in…
- [CMU Eats API (ScottyLabs) — student-operated](https://apis.io/apis/carnegie-mellon-university/cmu-eats-scottylabs/) — A public JSON API for Carnegie Mellon dining locations, hours and menus, built and run by ScottyLabs, a CMU student organization, at api.cmueats.com. It…
- [Carnegie Mellon University Articles API](https://apis.io/apis/carnegie-mellon-university/carnegie-mellon-university-articles-api/) — Published articles.
- [Carnegie Mellon University Covidcast API](https://apis.io/apis/carnegie-mellon-university/carnegie-mellon-university-covidcast-api/) — COVIDcast real-time indicator signals across geographies.
- [Carnegie Mellon University Feeds API](https://apis.io/apis/carnegie-mellon-university/carnegie-mellon-university-feeds-api/) — Syndication.
- [Carnegie Mellon University Fluview API](https://apis.io/apis/carnegie-mellon-university/carnegie-mellon-university-fluview-api/) — US ILINet influenza-like-illness surveillance (CDC FluView).
- [Carnegie Mellon University Forecasts API](https://apis.io/apis/carnegie-mellon-university/carnegie-mellon-university-forecasts-api/) — Delphi's own nowcasts and forecasts.
- [Carnegie Mellon University Issues API](https://apis.io/apis/carnegie-mellon-university/carnegie-mellon-university-issues-api/) — Issues within a journal.
- [Carnegie Mellon University Journals API](https://apis.io/apis/carnegie-mellon-university/carnegie-mellon-university-journals-api/) — The journals CMU Libraries publishes.
- [Carnegie Mellon University Meta API](https://apis.io/apis/carnegie-mellon-university/carnegie-mellon-university-meta-api/) — Service metadata and version.
- [Carnegie Mellon University Notes API](https://apis.io/apis/carnegie-mellon-university/carnegie-mellon-university-notes-api/) — Vulnerability Notes.
- [Carnegie Mellon University Oai Pmh API](https://apis.io/apis/carnegie-mellon-university/carnegie-mellon-university-oai-pmh-api/) — OAI-PMH 2.0 metadata harvesting provider.
- [Carnegie Mellon University Preprints API](https://apis.io/apis/carnegie-mellon-university/carnegie-mellon-university-preprints-api/) — Preprint repository objects.
- [Carnegie Mellon University Vendors API](https://apis.io/apis/carnegie-mellon-university/carnegie-mellon-university-vendors-api/) — Per-vendor coordination status.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Carnegie Mellon University Agentic Access](https://apis.io/agentic-access/carnegie-mellon-university/carnegie-mellon-university-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [CERT/CC Vulnerability Note](https://apis.io/schemas/carnegie-mellon-university/carnegie-mellon-university-cert-vulnerability-note/)
- [Delphi Epidata response envelope](https://apis.io/schemas/carnegie-mellon-university/carnegie-mellon-university-delphi-epidata-envelope/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Carnegie Mellon University Context](https://apis.io/jsonld/carnegie-mellon-university/carnegie-mellon-university-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Carnegie Mellon University KiltHub Repository Vocabulary](https://apis.io/vocabularies/carnegie-mellon-university/carnegie-mellon-university-vocabulary/)

#### Examples (6)

Example requests and responses.

- [Carnegie Mellon University Cert Note Cves Example](https://apis.io/examples/carnegie-mellon-university/carnegie-mellon-university-cert-note-cves-example/)
- [Carnegie Mellon University Cert Vendor Statements Example](https://apis.io/examples/carnegie-mellon-university/carnegie-mellon-university-cert-vendor-statements-example/)
- [Carnegie Mellon University Cert Vulnerability Note Example](https://apis.io/examples/carnegie-mellon-university/carnegie-mellon-university-cert-vulnerability-note-example/)
- [Carnegie Mellon University Delphi Covidcast Example](https://apis.io/examples/carnegie-mellon-university/carnegie-mellon-university-delphi-covidcast-example/)
- [Carnegie Mellon University Delphi Error Example](https://apis.io/examples/carnegie-mellon-university/carnegie-mellon-university-delphi-error-example/)
- [Carnegie Mellon University Delphi Fluview Example](https://apis.io/examples/carnegie-mellon-university/carnegie-mellon-university-delphi-fluview-example/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Carnegie Mellon University — jsonschema rules](https://apis.io/rules/carnegie-mellon-university/carnegie-mellon-university-jsonschema-spectral-rules/)
- [Carnegie Mellon University API Rules](https://apis.io/rules/carnegie-mellon-university/carnegie-mellon-university-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Carnegie Mellon University Authentication](https://apis.io/security/carnegie-mellon-university/carnegie-mellon-university-authentication/)
- [Carnegie Mellon University Domain Security](https://apis.io/security/carnegie-mellon-university/carnegie-mellon-university-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Carnegie Mellon University Scopes](https://apis.io/scopes/carnegie-mellon-university/carnegie-mellon-university-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Carnegie Mellon University Plans Pricing](https://apis.io/plans/carnegie-mellon-university/carnegie-mellon-university-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Carnegie Mellon University Rate Limits](https://apis.io/rate-limits/carnegie-mellon-university/carnegie-mellon-university-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Carnegie Mellon University Finops](https://apis.io/finops/carnegie-mellon-university/carnegie-mellon-university-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.cmu.edu/)
- [Documentation](https://cmu-delphi.github.io/delphi-epidata/)
- [API reference](https://cmu-delphi.github.io/delphi-epidata/api/README.html)
- [Support](https://www.cmu.edu/computing/support/)
- [Blog](https://www.cmu.edu/news/)
- [Terms of service](https://www.cmu.edu/legal/)
- [Privacy policy](https://www.cmu.edu/legal/privacy-notice)
- [GitHub](https://github.com/cmu-delphi)

## API Evangelist rating

**Kin Score 36.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 23.5 |
| Contract governance | 17.4 |
| Operational transparency | 23.7 |
| Developer ergonomics | 35.7 |
| Access clarity | 42.1 |

**Agent readiness 32.1** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 34.3** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/carnegie-mellon-university/](https://apis.io/providers/carnegie-mellon-university/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Carnegie Mellon University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/carnegie-mellon-university/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
