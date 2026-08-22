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

The University of Warwick is a public research university in Coventry, England, and a member of the Russell Group. This repository catalogs the institution's programmable footprint as an APIs.json profile, with every surface attributed to the party that actually operates it.

Warwick is one of the stronger institutions in this cohort: it genuinely operates its own APIs rather than pointing at a vendor's. Tabula, its teaching-and-learning administration system, is built and run by Warwick's own Information and Digital Group (IDG) software engineering team, and three of its calendar endpoints are fully public. Warwick also runs its own Shibboleth SAML identity provider and a self-hosted EPrints institutional repository with a live OAI-PMH endpoint.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-warwick/refs/heads/main/apis.yml

## Type

- University / Public Research University / Index / Consumer / 3rd-Party

## Tags

University, Higher Education, Education, Research, United Kingdom, Russell Group, Identity Federation, Research Repository, Course Catalog, Timetabling, Student Information System, Open Data

## Surfaces, by who operates them

Every entry carries an `x-operator`. For a university this is the question that matters: most machine-readable surfaces that appear to belong to an institution are a vendor's contract running under the institution's name.

### Institution-operated

- **Tabula API** (`tabula.warwick.ac.uk/api/v1`) — teaching and learning administration: departments, modules, coursework, small group teaching, monitoring points, profiles, timetabling, jobs. Built by Warwick IDG. Term dates, term weeks and holiday dates are **public and need no credentials**; verified returning live JSON and iCalendar on 2026-08-19. Everything else requires Web Sign-on.
- **Warwick Shibboleth Identity Provider** (`idp.warwick.ac.uk/idp/shibboleth`) — SAML 2.0 federation metadata, unauthenticated and machine-readable, carrying REFEDS SIRTFI assurance and the Research and Scholarship entity category.
- **Warwick Web Sign-on OAuth Services** (`websignon.warwick.ac.uk/oauth`) — OAuth 1.0a with nine documented Warwick-specific scopes across Sitebuilder, Search, Files, Blogs, Forums, Exam Timetabling, Printer Credits and SSO.
- **WRAP OAI-PMH** (`wrap.warwick.ac.uk/cgi/oai2`) — self-hosted EPrints 3.4.5 institutional repository. Seven metadata formats including RIOXX 2.0 and OpenAIRE, 312 harvestable sets.
- **Files.Warwick API** — file storage automation, prose documentation only.
- **Warwick Moodle Web Services** — Warwick's own Moodle instance. Host and instance are Warwick's, but the API contract is upstream Moodle's, so no specification is derived here.

### Tenant relationships (real institutional facts, vendor contracts)

- **Warwick Library Discovery** — `encore.lib.warwick.ac.uk` redirects to `warwick.summon.serialssolutions.com`, a Warwick tenancy on the Summon platform (Serials Solutions / ProQuest).
- **Warwick SU Membership API** — the Students' Union is a separate legal entity and its site runs on the MSL platform (ukmsl.com). Not the University's engineering.

## What Warwick does not publish

Recorded honestly, because an accurate absence is a useful measurement:

- **No OpenAPI, AsyncAPI, JSON Schema, apis.json or Postman collection** for any Warwick API. Both OpenAPI documents in this repository were derived by API Evangelist from Warwick's prose documentation and live probes, and are marked `method: derived` / `probed`. They are ours, not Warwick's.
- No changelog, release notes, status page, deprecation policy or Sunset headers.
- No public issue tracker or developer community.
- No OpenID Connect discovery document (`/.well-known/openid-configuration` returns 404). Delegated authorization is OAuth 1.0a, not OAuth 2.0.
- Sandbox access is by email request, not self-service.

## Agent surface

Warwick publishes an `llms.txt` that documents a real capability rather than only listing links: appending `?markdown` to any `warwick.ac.uk` page URL returns that page rendered as Markdown. This was verified — the stated policy and the deployed behaviour agree.

## Artifacts

- OpenAPI: `openapi/` (pristine pre-refine copies in `openapi/_original/`)
- JSON Schema: `json-schema/` — term dates, term weeks, holiday dates, error envelope
- Examples: `examples/` — verbatim live responses captured unauthenticated
- Authentication: `authentication/university-of-warwick-authentication.yml`
- Scopes: `scopes/university-of-warwick-oauth-scopes.yml`
- Errors: `errors/university-of-warwick-problem-types.yml`
- Conformance: `conformance/university-of-warwick-conformance.yml`
- Lifecycle: `lifecycle/university-of-warwick-lifecycle.yml`
- Vocabulary: `vocabulary/university-of-warwick-vocabulary.yml`
- Rules: `rules/university-of-warwick-openapi-spectral-rules.yml`
- Plans, rate limits, FinOps, security, JSON-LD, review

## Education-regime conformance

Probed against the Kin Score `education` regime standards. Conforming: **oai-pmh**, **shibboleth**, **saml**. Partial: **datacite** (DataCite kernel-4 metadata schema in the OpenAIRE profile; no evidence WRAP mints its own DOIs). Not found: scim, lti, oneroster, ed-fi, caliper, qti, orcid, crossref. Additional standards met: RIOXX 2.0, OpenAIRE 4.0, Dublin Core, RFC 5545 iCalendar, RFC 9116 security.txt, llms.txt.

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Notes

- All pointers in `apis.yml` were verified live on 2026-08-19. The LinkedIn page returns 999 (standard anti-bot response) but exists.
- `warwick.ac.uk/opensource` returns HTTP 200 but renders a Web Sign-on wall; Warwick's internal engineering pages could not be read and no pointer is emitted to it.
- `moodle.warwick.ac.uk` returned HTTP 500 when probed.
- The `security.txt` Expires field is 2026-08-27 — valid at probe time but expiring imminently.
- No endpoints were fabricated. Every path in the derived OpenAPIs was both documented by Warwick and probed live; gated paths returned the documented 401 envelope rather than 404, which is how their existence was confirmed without credentials.

## Maintainers

- Kin Lane — kin@apievangelist.com
