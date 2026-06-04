# Carnegie Mellon University (carnegie-mellon-university)

Carnegie Mellon University is a private research university in Pittsburgh, Pennsylvania, United States, ranked #50 in the QS World University Rankings 2025. This repository catalogs CMU's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile. CMU has no single central developer portal; its strongest public API presence is in research and library infrastructure — most notably the Delphi Epidata API and the KiltHub institutional repository.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/carnegie-mellon-university/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=carnegie-mellon-university-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, United States, Research, Epidemiology, Open Data, Library, Institutional Repository

## APIs

- **Delphi Epidata API** — Real-time and historical epidemiological surveillance data (COVIDcast, fluview, and more), maintained by CMU's Delphi research group. Verified returning live JSON. Docs: https://cmu-delphi.github.io/delphi-epidata/ — GitHub: https://github.com/cmu-delphi/delphi-epidata
- **KiltHub Repository OAI-PMH (figshare)** — OAI-PMH metadata harvesting for CMU's institutional repository of research data and scholarly outputs, hosted on figshare (CMU set `portal_231`). Docs: https://docs.figshare.com/#oai_pmh — Repository: https://kilthub.cmu.edu/
- **CMU Web Login (Shibboleth SSO)** — Campus-wide Shibboleth/SAML single sign-on identity service for affiliated service providers. Docs: https://www.cmu.edu/computing/services/security/identity-access/authentication/sso-provider.html

## Plans

- [plans/carnegie-mellon-university-plans-pricing.yml](plans/carnegie-mellon-university-plans-pricing.yml)

## Rate Limits

- [rate-limits/carnegie-mellon-university-rate-limits.yml](rate-limits/carnegie-mellon-university-rate-limits.yml)

## FinOps

- [finops/carnegie-mellon-university-finops.yml](finops/carnegie-mellon-university-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

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
