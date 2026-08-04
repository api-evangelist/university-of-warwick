# University of Warwick (university-of-warwick)

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
