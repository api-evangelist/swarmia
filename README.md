# Swarmia (swarmia)

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
