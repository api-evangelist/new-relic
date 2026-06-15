# New Relic (new-relic)

New Relic provides observability platform APIs for monitoring, analyzing, and optimizing your entire software stack with real-time insights into applications, infrastructure, and customer experience.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Analysis
- Analytics
- APM
- DevOps
- Infrastructure
- Monitoring
- Observability
- Performance
- Platform

## Timestamps

- **Created:** 2025-01-13
- **Modified:** 2026-05-19

## APIs

### New Relic REST API v2

The New Relic REST API v2 is the original HTTP REST interface for querying application performance data, configuring alerts, and managing account settings. New Relic recommends NerdGraph (GraphQL) for new integrations, as the REST API v2 is in maintenance mode with minimal ongoing development.

- **Human URL:** [https://docs.newrelic.com/docs/apis/rest-api-v2/get-started/introduction-new-relic-rest-api-v2/](https://docs.newrelic.com/docs/apis/rest-api-v2/get-started/introduction-new-relic-rest-api-v2/)
- **Base URL:** `https://api.newrelic.com/v2/`

#### Tags

- APM
- Applications
- Monitoring
- REST

#### Properties

- [Documentation](https://docs.newrelic.com/docs/apis/rest-api-v2/get-started/introduction-new-relic-rest-api-v2/)
- [OpenAPI](openapi/new-relic-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/new-relic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/)
- [API Reference](https://docs.newrelic.com/docs/apis/rest-api-v2/api-explorer-v2/introduction-new-relics-rest-api-explorer/)
- [JSON Schema](json-schema/openapi-mobile-application-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-synthetics-condition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-metric-parser-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-application-links-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-external-service-condition-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-label-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-label-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-external-service-condition-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-metric-data-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-policy-channels-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-deployment-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-application-instance-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-app-summary-data-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-deployment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-browser-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-app-summary-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-policy-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-application-instance-links-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-policy-channels-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-incident-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-channel-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-channel-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-label-origins-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-violation-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-app-settings-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-condition-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-deployment-links-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-incident-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-metric-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-metric-data-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-key-transaction-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-mobile-application-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-condition-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-label-links-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-application-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-policy-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-application-instance-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-ijkterms-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-violation-entity-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-recent-event-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-external-service-condition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-label-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-deployment-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-nrql-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-browser-application-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-browser-application-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-channel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-incident-links-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-condition-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-application-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-timeslice-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-violation-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-end-user-summary-data-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-condition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-metric-list-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-application-host-links-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-channel-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-external-service-condition-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-channel-links-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-nrql-condition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-synthetics-condition-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-policy-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-end-user-summary-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-synthetics-condition-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-application-host-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-browser-application-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-nrql-condition-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-key-transaction-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-metric-parser-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-nrql-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-application-host-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-app-settings-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-nrql-condition-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-violation-links-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-key-transaction-links-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-recent-event-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-synthetics-condition-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-user-defined-condition-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-user-defined-condition-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-deployment-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-nrql-condition-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-crash-summary-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-label-response-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-application-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-label-links-body-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openapi-mobile-summary-data-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/new-relic-openapi-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### New Relic NerdGraph API

NerdGraph is New Relic's primary GraphQL API for querying observability data, managing account configuration, and accessing the full breadth of New Relic platform capabilities. It is the recommended API for new integrations, replacing the older REST API v2 for most use cases.

- **Human URL:** [https://docs.newrelic.com/docs/apis/nerdgraph/get-started/introduction-new-relic-nerdgraph/](https://docs.newrelic.com/docs/apis/nerdgraph/get-started/introduction-new-relic-nerdgraph/)
- **Base URL:** `https://api.newrelic.com/graphql`

#### Tags

- GraphQL
- Monitoring
- Observability
- Platform

#### Properties

- [Documentation](https://docs.newrelic.com/docs/apis/nerdgraph/get-started/introduction-new-relic-nerdgraph/)
- [API Reference](https://docs.newrelic.com/docs/apis/nerdgraph/get-started/nerdgraph-explorer/)
- [Authentication](https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/)
- [Rate Limits](https://docs.newrelic.com/docs/apis/nerdgraph/nerdgraph-usage-limits/)
- [Getting Started](https://docs.newrelic.com/docs/apis/nerdgraph/get-started/introduction-new-relic-nerdgraph/)
- [Console](https://api.newrelic.com/graphiql)
- [Resources](https://www.postman.com/new-relic/new-relic-graphql-api-collection/documentation/btuxnnc/new-relic-nerdgraph-graphql-api-collection)
- [Postman Collection](collections/new-relic-event-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-event-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-log-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-log-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-metric-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-metric-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### New Relic Metric API

The New Relic Metric API is an HTTP endpoint for ingesting dimensional metric data directly into the New Relic platform. It accepts JSON payloads via POST requests and is the underlying API used by Telemetry SDKs and open source exporters such as Prometheus and DropWizard.

- **Human URL:** [https://docs.newrelic.com/docs/data-apis/ingest-apis/metric-api/introduction-metric-api/](https://docs.newrelic.com/docs/data-apis/ingest-apis/metric-api/introduction-metric-api/)
- **Base URL:** `https://metric-api.newrelic.com/metric/v1`

#### Tags

- Ingest
- Metrics
- Monitoring
- Telemetry

#### Properties

- [Documentation](https://docs.newrelic.com/docs/data-apis/ingest-apis/metric-api/introduction-metric-api/)
- [API Reference](https://docs.newrelic.com/docs/data-apis/ingest-apis/metric-api/report-metrics-metric-api/)
- [Authentication](https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/)
- [Rate Limits](https://docs.newrelic.com/docs/data-apis/ingest-apis/metric-api/metric-api-limits-restricted-attributes/)
- [OpenAPI](openapi/new-relic-metric-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/new-relic-metric-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-metric-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/new-relic-metric-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/metric-api-common-block-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/metric-api-summary-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/metric-api-metric-data-object-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/metric-api-metric-data-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/metric-api-metric-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/metric-api-accepted-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/new-relic-metric-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### New Relic Event API

The New Relic Event API allows you to send custom event data to the New Relic platform via HTTP POST. Custom events submitted through this API can be queried and visualized using NRQL, making it suitable for tracking arbitrary business or application events.

- **Human URL:** [https://docs.newrelic.com/docs/data-apis/ingest-apis/event-api/introduction-event-api/](https://docs.newrelic.com/docs/data-apis/ingest-apis/event-api/introduction-event-api/)
- **Base URL:** `https://insights-collector.newrelic.com/v1/accounts`

#### Tags

- Custom Data
- Events
- Ingest
- Telemetry

#### Properties

- [Documentation](https://docs.newrelic.com/docs/data-apis/ingest-apis/event-api/introduction-event-api/)
- [Authentication](https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/)
- [OpenAPI](openapi/new-relic-event-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/new-relic-event-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-event-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/new-relic-event-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Rate Limits](https://docs.newrelic.com/docs/data-apis/custom-data/custom-events/data-requirements-limits-custom-event-data/)
- [JSON Schema](json-schema/event-api-success-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/event-api-custom-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/event-api-event-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/new-relic-event-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### New Relic Log API

The New Relic Log API enables log data to be sent directly to the New Relic platform via HTTP POST requests. It accepts compressed JSON payloads and provides an alternative to log forwarding agents when direct integration is preferred.

- **Human URL:** [https://docs.newrelic.com/docs/logs/log-api/introduction-log-api/](https://docs.newrelic.com/docs/logs/log-api/introduction-log-api/)
- **Base URL:** `https://log-api.newrelic.com/log/v1`

#### Tags

- Ingest
- Log Management
- Logs
- Telemetry

#### Properties

- [Documentation](https://docs.newrelic.com/docs/logs/log-api/introduction-log-api/)
- [Authentication](https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/)
- [API Reference](https://docs.newrelic.com/docs/logs/forward-logs/enable-log-management-new-relic/)
- [OpenAPI](openapi/new-relic-log-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/new-relic-log-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-log-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/log-api-log-data-object-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/log-api-accepted-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/log-api-log-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/log-api-common-block-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/log-api-log-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/new-relic-log-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### New Relic Trace API

The New Relic Trace API allows distributed tracing data to be sent directly to New Relic in either New Relic format or Zipkin JSON v2 format. It is used by Telemetry SDKs, open source integrations, and custom tracing implementations that need to report span data without a full APM agent.

- **Human URL:** [https://docs.newrelic.com/docs/distributed-tracing/trace-api/introduction-trace-api/](https://docs.newrelic.com/docs/distributed-tracing/trace-api/introduction-trace-api/)
- **Base URL:** `https://trace-api.newrelic.com/trace/v1`

#### Tags

- Distributed Tracing
- Ingest
- Telemetry
- Traces

#### Properties

- [Documentation](https://docs.newrelic.com/docs/distributed-tracing/trace-api/introduction-trace-api/)
- [API Reference](https://docs.newrelic.com/docs/distributed-tracing/trace-api/trace-api-general-requirements-limits/)
- [Authentication](https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/)
- [OpenAPI](openapi/new-relic-trace-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/new-relic-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rate Limits](https://docs.newrelic.com/docs/distributed-tracing/trace-api/trace-api-general-requirements-limits/)
- [JSON Schema](json-schema/trace-api-new-relic-trace-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trace-api-accepted-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trace-api-common-block-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trace-api-zipkin-span-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trace-api-span-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trace-api-zipkin-trace-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trace-api-span-batch-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/new-relic-trace-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### New Relic Alerts API

The New Relic Alerts REST API provides endpoints for programmatically managing alert policies, conditions, notification channels, and muting rules. New Relic recommends using NerdGraph for new alert management integrations, as the REST Alerts API is in maintenance mode.

- **Human URL:** [https://docs.newrelic.com/docs/alerts/scale-automate/rest-api/rest-api-calls-alerts/](https://docs.newrelic.com/docs/alerts/scale-automate/rest-api/rest-api-calls-alerts/)
- **Base URL:** `https://api.newrelic.com/v2/`

#### Tags

- Alerts
- Monitoring
- Notifications
- REST

#### Properties

- [Documentation](https://docs.newrelic.com/docs/alerts/scale-automate/rest-api/rest-api-calls-alerts/)
- [Authentication](https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/)
- [Postman Collection](collections/new-relic-event-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-event-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-log-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-log-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-metric-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-metric-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### New Relic Synthetics API

The New Relic Synthetics API, available through NerdGraph, allows you to programmatically create, update, delete, and query synthetic monitors including ping monitors, scripted API monitors, browser monitors, and broken links monitors. A legacy REST-based Synthetics API is also available but NerdGraph is the recommended approach.

- **Human URL:** [https://docs.newrelic.com/docs/synthetics/synthetic-monitoring/administration/synthetics-api/](https://docs.newrelic.com/docs/synthetics/synthetic-monitoring/administration/synthetics-api/)
- **Base URL:** `https://api.newrelic.com/graphql`

#### Tags

- Monitoring
- Synthetics
- Testing
- Uptime Monitoring

#### Properties

- [Documentation](https://docs.newrelic.com/docs/synthetics/synthetic-monitoring/administration/synthetics-api/)
- [API Reference](https://docs.newrelic.com/docs/apis/nerdgraph/examples/synthetics-api/overview/)
- [Authentication](https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/)
- [Postman Collection](collections/new-relic-event-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-event-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-log-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-log-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-metric-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-metric-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### New Relic Infrastructure Alerts API

The New Relic Infrastructure Alerts REST API provides endpoints for creating and managing infrastructure-specific alert conditions such as host, process, and integration alert conditions. It uses the infra-api.newrelic.com endpoint and is separate from the general Alerts REST API.

- **Human URL:** [https://docs.newrelic.com/docs/infrastructure/infrastructure-alerts/rest-api-calls-new-relic-infrastructure-alerts/](https://docs.newrelic.com/docs/infrastructure/infrastructure-alerts/rest-api-calls-new-relic-infrastructure-alerts/)
- **Base URL:** `https://infra-api.newrelic.com/v2/`

#### Tags

- Alerts
- Infrastructure
- Monitoring
- REST

#### Properties

- [Documentation](https://docs.newrelic.com/docs/infrastructure/infrastructure-alerts/rest-api-calls-new-relic-infrastructure-alerts/)
- [Authentication](https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/)
- [Postman Collection](collections/new-relic-event-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-event-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-log-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-log-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-metric-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-metric-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### New Relic Browser API

The New Relic Browser API provides JavaScript methods for extending and customizing browser monitoring data collection within the New Relic browser agent. Developers can use it to add custom attributes, record custom events, track page actions, and control agent behavior programmatically.

- **Human URL:** [https://docs.newrelic.com/docs/browser/new-relic-browser/browser-apis/using-browser-apis/](https://docs.newrelic.com/docs/browser/new-relic-browser/browser-apis/using-browser-apis/)
- **Base URL:** `https://bam.nr-data.net`

#### Tags

- Browser
- JavaScript
- Monitoring
- Real User Monitoring

#### Properties

- [Documentation](https://docs.newrelic.com/docs/browser/new-relic-browser/browser-apis/using-browser-apis/)
- [Authentication](https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/)
- [SDK](https://github.com/newrelic/newrelic-browser-agent)
- [Postman Collection](collections/new-relic-event-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-event-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-log-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-log-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-metric-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-metric-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### New Relic Partnership API

The New Relic Partnership API is a web service API for New Relic partners that enables them to create, edit, upgrade, downgrade, and cancel New Relic accounts on behalf of their customers. It is available only to New Relic partner accounts with partnership-level access.

- **Human URL:** [https://docs.newrelic.com/docs/new-relic-partnerships/partner-integration-guide/partner-account-maintenance/partner-api/](https://docs.newrelic.com/docs/new-relic-partnerships/partner-integration-guide/partner-account-maintenance/partner-api/)
- **Base URL:** `https://rpm.newrelic.com/api/v2/partners/`

#### Tags

- Account Management
- Partners
- Platform

#### Properties

- [Documentation](https://docs.newrelic.com/docs/new-relic-partnerships/partner-integration-guide/partner-account-maintenance/partner-api/)
- [Authentication](https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/)
- [Postman Collection](collections/new-relic-event-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-event-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-log-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-log-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-metric-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-metric-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### New Relic Telemetry SDKs

The New Relic Telemetry SDKs are open source client libraries for sending metrics, events, logs, and traces (MELT) to New Relic using the ingest APIs. SDKs are available for Java, Python, Node.js, Go, .NET, and C, and are released under the Apache 2.0 license on GitHub.

- **Human URL:** [https://docs.newrelic.com/docs/data-apis/ingest-apis/telemetry-sdks-report-custom-telemetry-data/](https://docs.newrelic.com/docs/data-apis/ingest-apis/telemetry-sdks-report-custom-telemetry-data/)
- **Base URL:** `https://metric-api.newrelic.com`

#### Tags

- Client Libraries
- Open Source
- SDKs
- Telemetry

#### Properties

- [Documentation](https://docs.newrelic.com/docs/data-apis/ingest-apis/telemetry-sdks-report-custom-telemetry-data/)
- [SDK](https://docs.newrelic.com/docs/data-apis/ingest-apis/telemetry-sdks-report-custom-telemetry-data/)
- [GitHub Repository](https://github.com/newrelic/newrelic-telemetry-sdk-java)
- [SDK](https://github.com/newrelic/newrelic-telemetry-sdk-python)
- [SDK](https://github.com/newrelic/newrelic-telemetry-sdk-go)
- [SDK](https://github.com/newrelic/newrelic-telemetry-sdk-dotnet)
- [Postman Collection](collections/new-relic-event-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-event-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-log-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-log-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-metric-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-metric-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### New Relic OpenTelemetry OTLP Endpoint

New Relic provides a native OTLP (OpenTelemetry Protocol) endpoint that accepts metrics, traces, and logs from any OpenTelemetry-instrumented application or OTLP exporter. It supports both gRPC and HTTP/protobuf transport and is the recommended integration path for OpenTelemetry users.

- **Human URL:** [https://docs.newrelic.com/docs/opentelemetry/best-practices/opentelemetry-otlp/](https://docs.newrelic.com/docs/opentelemetry/best-practices/opentelemetry-otlp/)
- **Base URL:** `https://otlp.nr-data.net`

#### Tags

- Ingest
- OpenTelemetry
- OTLP
- Telemetry

#### Properties

- [Documentation](https://docs.newrelic.com/docs/opentelemetry/best-practices/opentelemetry-otlp/)
- [Getting Started](https://docs.newrelic.com/docs/opentelemetry/opentelemetry-introduction/)
- [API Reference](https://docs.newrelic.com/docs/opentelemetry/best-practices/opentelemetry-data-overview/)
- [Postman Collection](collections/new-relic-event-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-event-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-log-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-log-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-metric-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-metric-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### New Relic Control

New Relic Control is an observability control plane that unifies Fleet Control, Agent Control, and Pipeline Control into a single management layer. It enables DevOps and platform teams to remotely deploy, configure, update, and monitor New Relic agents and OpenTelemetry collectors across Kubernetes clusters and hosts without manual per-host intervention. Fleet Control manages agent lifecycles at scale via a remote configuration API.

- **Human URL:** [https://docs.newrelic.com/docs/new-relic-control/getting-started/](https://docs.newrelic.com/docs/new-relic-control/getting-started/)
- **Base URL:** `https://api.newrelic.com`

#### Tags

- Agent Management
- Automation
- Fleet Control
- Observability
- Platform

#### Properties

- [Documentation](https://docs.newrelic.com/docs/new-relic-control/getting-started/)
- [API Reference](https://docs.newrelic.com/docs/new-relic-control/fleet-control/overview/)
- [Getting Started](https://docs.newrelic.com/docs/new-relic-control/getting-started/)
- [Postman Collection](collections/new-relic-event-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-event-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-log-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-log-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-metric-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-metric-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### New Relic NRQL Lookups API

The New Relic NRQL Lookups API is a REST API for managing lookup tables that can be used to enrich NRQL query results. It supports creating, updating, downloading, listing, and deleting lookup tables in both CSV and JSON formats, enabling automated lookup table maintenance for data enrichment workflows.

- **Human URL:** [https://docs.newrelic.com/docs/apis/lookups-service-api/lookups-service-api/](https://docs.newrelic.com/docs/apis/lookups-service-api/lookups-service-api/)
- **Base URL:** `https://nrql-lookup.service.newrelic.com`

#### Tags

- Data Enrichment
- Lookups
- NRQL
- REST

#### Properties

- [Documentation](https://docs.newrelic.com/docs/apis/lookups-service-api/lookups-service-api/)
- [Authentication](https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/)
- [Postman Collection](collections/new-relic-event-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-event-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-log-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-log-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-metric-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-metric-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### New Relic Security Data API

The New Relic Security Data API allows vulnerability and security finding data to be sent directly to New Relic via HTTP POST. It accepts JSON payloads describing detected vulnerabilities or security events, enabling integration with third-party vulnerability assessment tools and custom security scanning solutions for use with New Relic Security RX.

- **Human URL:** [https://docs.newrelic.com/docs/data-apis/ingest-apis/security-data-api/](https://docs.newrelic.com/docs/data-apis/ingest-apis/security-data-api/)
- **Base URL:** `https://security-api.newrelic.com/security/v1`

#### Tags

- Compliance
- Ingest
- Security
- Vulnerabilities

#### Properties

- [Documentation](https://docs.newrelic.com/docs/data-apis/ingest-apis/security-data-api/)
- [Authentication](https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/)
- [Postman Collection](collections/new-relic-event-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-event-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-log-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-log-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-metric-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-metric-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### New Relic Mobile SDK

The New Relic Mobile SDK provides iOS and Android APIs for extending mobile monitoring data collection beyond what the agent captures automatically. Developers can add custom attributes, record custom events, track user interactions, report handled exceptions, set custom user IDs, and control agent behavior within iOS (Swift/Objective-C) and Android (Java/Kotlin) applications.

- **Human URL:** [https://docs.newrelic.com/docs/mobile-monitoring/new-relic-mobile/mobile-sdk/mobile-sdk-api-guide/](https://docs.newrelic.com/docs/mobile-monitoring/new-relic-mobile/mobile-sdk/mobile-sdk-api-guide/)
- **Base URL:** `https://mobile-collector.newrelic.com`

#### Tags

- Android
- iOS
- Mobile
- Monitoring
- SDK

#### Properties

- [Documentation](https://docs.newrelic.com/docs/mobile-monitoring/new-relic-mobile/mobile-sdk/mobile-sdk-api-guide/)
- [API Reference](https://docs.newrelic.com/docs/mobile-monitoring/new-relic-mobile-ios/get-started/introduction-new-relic-mobile-ios/)
- [GitHub Repository](https://github.com/newrelic/newrelic-ios-agent)
- [SDK](https://github.com/newrelic/newrelic-android-agent)
- [SDK](https://github.com/newrelic/newrelic-unity-agent)
- [Postman Collection](collections/new-relic-event-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-event-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-log-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-log-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-metric-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-metric-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/new-relic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/new-relic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://newrelic.com/)
- [Pricing](https://newrelic.com/pricing)
- [Documentation](https://docs.newrelic.com/)
- [Terms of Service](https://newrelic.com/termsandconditions/terms)
- [Privacy Policy](https://newrelic.com/termsandconditions/privacy)
- [Blog](https://newrelic.com/blog)
- [Partners](https://newrelic.com/solutions/partners)
- [Trust Center](https://trust.newrelic.com/)
- [Login](https://login.newrelic.com/login)
- [Sign Up](https://newrelic.com/signup)
- [Console](https://one.newrelic.com/)
- [Portal](https://developer.newrelic.com/)
- [Authentication](https://docs.newrelic.com/docs/apis/intro-apis/new-relic-api-keys/)
- [Support](https://support.newrelic.com/)
- [Status Page](https://status.newrelic.com/)
- [GitHub Organization](https://github.com/newrelic)
- [Support](https://discuss.newrelic.com/)
- [Getting Started](https://docs.newrelic.com/docs/new-relic-solutions/get-started/intro-new-relic/)
- [Changelog](https://docs.newrelic.com/whats-new/)
- [Changelog](https://docs.newrelic.com/docs/release-notes/)
- [Rate Limits](https://docs.newrelic.com/docs/data-apis/manage-data/view-system-limits/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/new-relic)
- [GitHub Organization](https://opensource.newrelic.com/)
- [YouTube](https://www.youtube.com/@NewRelicInc)
- [JSON-LD](json-ld/new-relic-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/new-relic-metric-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/new-relic-event-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [X (Twitter)](https://twitter.com/newrelic)
- [LinkedIn](https://www.linkedin.com/company/new-relic-inc-)
- [Security](https://newrelic.com/security)
- [Security](https://newrelic.com/security/compliance-certifications)
- [C L I](https://github.com/newrelic/newrelic-cli)
- [C L I](https://docs.newrelic.com/docs/new-relic-solutions/build-nr-ui/newrelic-cli/)
- [GitHub Repository](https://registry.terraform.io/providers/newrelic/newrelic/latest/docs)
- [GitHub Repository](https://github.com/newrelic/terraform-provider-newrelic)
- [Resources](https://www.postman.com/new-relic/)
- [Documentation](https://docs.newrelic.com/docs/apis/intro-apis/introduction-new-relic-apis/)
- [Documentation](https://docs.newrelic.com/docs/nrql/get-started/introduction-nrql-new-relics-query-language/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](https://newrelic.com/instant-observability)
- [SDK](https://github.com/newrelic/newrelic-java-agent)
- [SDK](https://github.com/newrelic/newrelic-python-agent)
- [SDK](https://github.com/newrelic/node-newrelic)
- [SDK](https://github.com/newrelic/go-agent)
- [SDK](https://github.com/newrelic/newrelic-dotnet-agent)
- [SDK](https://github.com/newrelic/newrelic-ruby-agent)
- [SDK](https://github.com/newrelic/newrelic-php-agent)
- [SDK](https://github.com/newrelic/infrastructure-agent)
- [GitHub Repository](https://github.com/newrelic/helm-charts)
- [Code Examples](https://github.com/newrelic/newrelic-opentelemetry-examples)
- [Spectral Rules](rules/new-relic-spectral-rules.yml)
- [Vocabulary](vocabulary/new-relic-vocabulary.yaml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
