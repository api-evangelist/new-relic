---
name: new-relic-manage-alert-channels
description: Create, list, and delete alert notification channels in New Relic.
api: openapi/new-relic-alerts-api-openapi.yml
operations:
- getAlertsChannels
- postAlertsChannels
- deleteAlertsChannelsChannelId
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/new-relic-alerts-api-openapi.yml ; every operationId checked against the contract
---

# new-relic-manage-alert-channels

Create, list, and delete alert notification channels in New Relic.

## Steps

1. 1. List existing channels using `getAlertsChannels` – requires the `Api-Key` header.
2. 2. Create a new channel with `postAlertsChannels` – send a JSON body with channel fields and include the `Api-Key` header.
3. 3. Delete a channel using `deleteAlertsChannelsChannelId` – provide the `channel_id` path parameter and the `Api-Key` header.

## Rules

- Auth: Provide the API key in the `Api-Key` request header (scheme: APIKeyHeader).
- Idempotency: POST and DELETE operations are not idempotent; repeat calls may create duplicate channels or return 404 if the channel no longer exists.
