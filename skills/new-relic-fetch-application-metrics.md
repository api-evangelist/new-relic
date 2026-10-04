---
name: new-relic-fetch-application-metrics
description: Retrieve a list of applications and fetch their metric data.
api: openapi/new-relic-applications-api-openapi.yml
operations:
- getApplications
- getApplicationsIdMetrics
- getApplicationsIdMetricsData
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/new-relic-applications-api-openapi.yml ; every operationId checked against the contract
---

# new-relic-fetch-application-metrics

Retrieve a list of applications and fetch their metric data.

## Steps

1. 1. Call `getApplications` – requires header `Api-Key` for authentication.
2. 2. Call `getApplicationsIdMetrics` – requires path parameter `application_id` and header `Api-Key`.
3. 3. Call `getApplicationsIdMetricsData` – requires path parameter `application_id`, query parameters for the metric request, and header `Api-Key`.

## Rules

- Auth: Provide the API key in the `Api-Key` request header (APIKeyHeader scheme).
- Rate limiting: No rate limit is defined; on exhaustion the response has no specific HTTP status.
