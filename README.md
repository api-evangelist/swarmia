# Swarmia (swarmia)

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

Swarmia is an engineering-effectiveness analytics platform that combines software delivery metrics (DORA), developer experience, investment balance, and AI adoption insights. Its REST API lets teams export built-in and custom reports, ingest deployment and events data, manage teams and memberships, and record time off, authenticated with Bearer API tokens.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/swarmia/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/swarmia/refs/heads/main/apis.yml)

## Tags

- Engineering Effectiveness
- Developer Productivity
- DORA
- Software Delivery
- Analytics

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Swarmia Metrics Export API

Machine-readable, built-in and custom reports - code metrics, DORA metrics, AI assistant adoption, and saved custom reports - retrieved as JSON or CSV using a Bearer API token with the entityQuery scope.

- **Human URL:** [https://help.swarmia.com/settings/integrations/swarmia-apis](https://help.swarmia.com/settings/integrations/swarmia-apis)
- **Base URL:** `https://app.swarmia.com/api/v1`

#### Tags

- Metrics
- DORA
- Reports
- Export

#### Properties

- [Documentation](https://help.swarmia.com/settings/integrations/swarmia-apis)
- [API Reference](https://app.swarmia.com/api/v1/openapi.json)
- [OpenAPI](openapi/swarmia-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/swarmia.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/swarmia.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Swarmia Deployments & Events Ingestion API

Posts deployment and fix-deployment events to Swarmia (POST https://hook.swarmia.com/deployments) so delivery and DORA metrics reflect manual or CI/CD releases, plus daily AI-tool usage ingestion for external assistants.

- **Human URL:** [https://help.swarmia.com/settings/organization/configuring-deployments-in-swarmia/generate-deployments-via-the-deployment-api](https://help.swarmia.com/settings/organization/configuring-deployments-in-swarmia/generate-deployments-via-the-deployment-api)
- **Base URL:** `https://hook.swarmia.com`

#### Tags

- Deployments
- Events
- Ingestion
- DORA

#### Properties

- [Documentation](https://help.swarmia.com/settings/organization/configuring-deployments-in-swarmia/generate-deployments-via-the-deployment-api)
- [OpenAPI](openapi/swarmia-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/swarmia.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/swarmia.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Swarmia Investment Categories API

Legacy Export API v0 endpoints for investment balance, software capitalization (CapEx), effort (FTE) reporting, and team/member and time-off management, returning CSV for finance and engineering-investment workflows.

- **Human URL:** [https://help.swarmia.com/settings/integrations/swarmia-apis/export-api](https://help.swarmia.com/settings/integrations/swarmia-apis/export-api)
- **Base URL:** `https://app.swarmia.com/api/v0`

#### Tags

- Investment Balance
- Capitalization
- Effort
- Teams

#### Properties

- [Documentation](https://help.swarmia.com/settings/integrations/swarmia-apis/export-api)
- [OpenAPI](openapi/swarmia-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/swarmia.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/swarmia.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Swarmia Webhooks & Notifications API

Event-driven integration surface - Swarmia subscribes to GitHub webhooks (checks, Actions, deployments, issues, pull requests) and pushes working-agreement nudges, pull-request reminders, and daily digests to Slack and Microsoft Teams.

- **Human URL:** [https://help.swarmia.com/resources/security-and-data-retention/data-access](https://help.swarmia.com/resources/security-and-data-retention/data-access)
- **Base URL:** `https://app.swarmia.com/api/v1`

#### Tags

- Webhooks
- Notifications
- Slack
- GitHub

#### Properties

- [Documentation](https://help.swarmia.com/resources/security-and-data-retention/data-access)
- [Documentation](https://help.swarmia.com/getting-started/integrations/slack)
- [OpenAPI](openapi/swarmia-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/swarmia)
- [LinkedIn](https://www.linkedin.com/company/swarmia)
- [Website](https://www.swarmia.com)
- [Documentation](https://help.swarmia.com)
- [Plans](plans/swarmia-plans-pricing.yml)
- [Rate Limits](rate-limits/swarmia-rate-limits.yml)
- [Fin Ops](finops/swarmia-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
