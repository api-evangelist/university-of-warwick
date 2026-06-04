# University of Warwick (university-of-warwick)

The University of Warwick is a public research university in Coventry, England, ranked #49 in the QS World University Rankings 2025. This repository catalogs the institution's public developer/API footprint as an APIs.json profile. Warwick's APIs are provided primarily by its IT Services / IDG Software Engineering team and include the Tabula teaching-and-learning REST API, the Files.Warwick file APIs, OAuth-protected web services, the Warwick SU Membership API, and the WRAP institutional repository's OAI-PMH endpoint.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-warwick/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-warwick-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, United Kingdom, Student Information System, Timetabling

## APIs

- **Tabula API** — REST API for teaching and learning administration (timetabling, profiles, coursework, small group teaching, monitoring points). Docs: https://warwick.ac.uk/services/idg/services-support/web/tabula/api/ and https://warwick.ac.uk/services/idg/services-support/web/tabula/api/timetabling
- **Files.Warwick API** — HTTP APIs for automating tasks against the Files.Warwick storage service. Docs: https://warwick.ac.uk/services/its/servicessupport/web/files/api/
- **Warwick OAuth Web Services** — OAuth 1.0 access to Sitebuilder, Warwick Search, Files.Warwick, Blogs, Forums, Exam Timetabling, Printer Credits and Web Sign-on. Docs: https://warwick.ac.uk/services/its/servicessupport/web/sign-on/help/oauth/apis/
- **Warwick SU Membership API** — Students' Union API to validate membership and retrieve member rosters. Docs: https://www.warwicksu.com/membershipapi/about/
- **WRAP OAI-PMH** — Warwick Research Archive Portal institutional repository, harvestable via OAI-PMH. Docs: https://wrap.warwick.ac.uk/ — Endpoint: https://wrap.warwick.ac.uk/cgi/oai2

## Plans

- plans/university-of-warwick-plans-pricing.yml

## Rate Limits

- rate-limits/university-of-warwick-rate-limits.yml

## FinOps

- finops/university-of-warwick-finops.yml

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://warwick.ac.uk/
- GitHub: https://github.com/universityofwarwick (official, verified)
- LinkedIn: https://www.linkedin.com/school/the-university-of-warwick/
- Developer Portal: https://warwick.ac.uk/services/idg/services-support/web/

## Notes

- All documentation URLs above were verified live (HTTP 200) on 2026-06-03; the LinkedIn page returns 999 (standard anti-bot response) but exists.
- Most Warwick APIs are gated behind Warwick web sign-on / OAuth credentials and are not openly consumable without an account.
- No endpoints were fabricated — only resources confirmed in official documentation are cataloged.

## Maintainers

- Kin Lane — kin@apievangelist.com
