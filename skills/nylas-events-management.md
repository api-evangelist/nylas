---
name: nylas-events-management
description: Create, retrieve, update, and delete calendar events for a grant.
api: openapi/nylas-events-api-openapi.yml
operations:
- create-event
- get-all-events
- get-events-id
- put-events-id
- delete-events-id
generated: '2026-10-02'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/nylas-events-api-openapi.yml ; every operationId checked against the contract
---

# nylas-events-management

Create, retrieve, update, and delete calendar events for a grant.

## Steps

1. 1. `create-event` – requires authentication header (e.g., `Authorization: Bearer <ACCESS_TOKEN>`).
2. 2. `get-all-events` – requires authentication header; supports pagination via query parameters if provided by the API.
3. 3. `get-events-id` – requires authentication header and the path parameter `event_id`.
4. 4. `put-events-id` – requires authentication header, the path parameter `event_id`, and the request body with event fields to update.
5. 5. `delete-events-id` – requires authentication header and the path parameter `event_id`.

## Rules

- Authentication: Include a valid `Authorization: Bearer <ACCESS_TOKEN>` header (or use `NYLAS_API_KEY` or `SCHEDULER_SESSION_TOKEN` as supported).
- Idempotency: `create-event` and `put-events-id` are not guaranteed to be idempotent; repeat requests may create duplicate resources.
- Pagination: `get-all-events` may return paginated results; follow `next_cursor` or similar pagination tokens as documented.
- Errors: On failure, the API returns standard HTTP error codes; no specific rate‑limit headers are defined.
