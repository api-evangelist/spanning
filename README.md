# Spanning (spanning)

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
