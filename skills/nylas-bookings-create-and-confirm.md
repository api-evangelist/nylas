---
name: nylas-bookings-create-and-confirm
description: Create a new booking and then confirm it.
api: openapi/nylas-bookings-api-openapi.yml
operations:
- post-bookings
- get-bookings-id
- put-bookings-id
generated: '2026-10-02'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/nylas-bookings-api-openapi.yml ; every operationId checked against the contract
---

# nylas-bookings-create-and-confirm

Create a new booking and then confirm it.

## Steps

1. 1. `post-bookings` – requires an `Authorization` header with an ACCESS_TOKEN, NYLAS_API_KEY, or SCHEDULER_SESSION_TOKEN; request body includes booking details.
2. 2. `get-bookings-id` – requires an `Authorization` header; path parameter `booking_id` returned from step 1.
3. 3. `put-bookings-id` – requires an `Authorization` header; path parameter `booking_id` and request body to confirm the booking.

## Rules

- Authentication: include an `Authorization` header using one of the supported schemes (ACCESS_TOKEN, NYLAS_API_KEY, SCHEDULER_SESSION_TOKEN).
- Idempotency: the `put-bookings-id` operation is idempotent; repeated calls with the same `booking_id` will not create duplicate confirmations.
