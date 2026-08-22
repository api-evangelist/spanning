# Spanning (spanning)

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

Spanning (by Kaseya) is a SaaS backup and recovery platform providing cloud-to-cloud data protection for Microsoft 365, Google Workspace, and Salesforce. It protects over 24,000 organizations and 2.5 million users with automated daily backups, unlimited on-demand backups, infinite retention, and granular point-in-time restore. Spanning exposes RESTful APIs for managing user licenses and exporting backed-up account data for Google Workspace and Microsoft 365.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Data Protection
- SaaS Backup
- Cloud Backup
- Microsoft 365
- Google Workspace
- Salesforce

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-19

## APIs

### Spanning Backup for Google Workspace API

RESTful API for managing Spanning Backup for Google Workspace. Supports user license management (assign, unassign, list, get), shared drives backup management (list, export), and export operations (initiate, list, get). Authentication uses API tokens obtained from the Spanning admin portal Settings tab.

- **Human URL:** [https://spanning.com/products/google-workspace-backup/](https://spanning.com/products/google-workspace-backup/)
- **Base URL:** `https://api.spanningbackup.com`

#### Tags

- Data Protection
- SaaS Backup
- Google Workspace
- Cloud Backup

#### Properties

- [Documentation](https://api.spanningbackup.com/index.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/openapi/spanning-google-workspace-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/rules/spanning-rules.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/json-schema/spanning-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/json-structure/spanning-user-structure.json)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/json-ld/spanning-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/spanning/refs/heads/main/vocabulary/spanning-vocabulary.yml)
- [Postman Collection](collections/spanning-google-workspace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spanning-google-workspace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spanning Backup for Microsoft 365 API

RESTful API for managing Spanning Backup for Microsoft 365. Region-specific endpoints (US, EU, AP, CA, UK) for user license management and data export operations. Authentication uses API tokens obtained from the Spanning admin portal.

- **Human URL:** [https://spanning.com/products/microsoft-365-backup/](https://spanning.com/products/microsoft-365-backup/)
- **Base URL:** `https://o365-us.spanningbackup.com`

#### Tags

- Data Protection
- SaaS Backup
- Microsoft 365
- Cloud Backup

#### Properties

- [Documentation](https://o365-docs.spanningbackup.com/)
- [GitHub Repository](https://github.com/SpanningCloudApps/SB365-Powershell)
- [Postman Collection](collections/spanning-google-workspace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spanning-google-workspace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/spanning-cloud-apps)
- [Website](https://spanning.com)
- [Documentation](https://spanning.com/resources)
- [API Reference](https://api.spanningbackup.com/index.html)
- [Git Hub](https://github.com/SpanningCloudApps)
- [Pricing](https://spanning.com/pricing/)
- [Integrations](https://www.spanning.com/partners/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
