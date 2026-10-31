# Nylas

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

Nylas provides a unified SaaS platform that enables applications to integrate email, calendar, contacts, scheduling, and meeting notetaking across major providers such as Google, Microsoft, iCloud, Yahoo, and generic IMAP services. The API suite includes REST endpoints for messaging, calendar events, contact management, authentication flows, and administrative controls, supporting both standard OAuth and Nylas‑Connect mechanisms. It also offers SDKs for multiple languages, a CLI, and a hosted MCP server for autonomous agent accounts, facilitating AI‑driven interactions without direct OAuth handling. Official SDKs cover Node.js, Python, Ruby and Kotlin/Java, alongside a CLI, a hosted MCP server, and Agent Accounts that provision a Nylas-hosted mailbox and calendar for autonomous agents without requiring an OAuth flow.

**Areas:** Calendar · Communications · Contacts · Email · Messaging · Scheduling · A2A

## Nylas on APIs.io

Everything profiled for Nylas is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nylas/](https://apis.io/providers/nylas/)** — or go straight to one of the APIs or properties below.

### APIs (37)

- [Nylas Contacts API](https://apis.io/apis/nylas/nylas-contacts-api/) — Contacts. Read, create, update and delete a grant's contacts and contact groups.
- [Nylas Drafts API](https://apis.io/apis/nylas/nylas-drafts-api/) — Drafts. Compose, update, send and delete drafts, manage attachments, and generate draft bodies and replies with Smart Compose.
- [Nylas Events API](https://apis.io/apis/nylas/nylas-events-api/) — Events. Create, update, delete and list calendar events, including recurring events, group events and RSVP handling.
- [Nylas Messages API](https://apis.io/apis/nylas/nylas-messages-api/) — Messages. List, search, read, update and delete email messages. Send immediately, schedule a send and cancel a scheduled send, with folders, signatures and…
- [Nylas Threads API](https://apis.io/apis/nylas/nylas-threads-api/) — Threads. List, search, read and update email threads, and manage thread-level folders and state.
- [Nylas Notetaker API](https://apis.io/apis/nylas/nylas-notetaker-api/) — Meeting notetaker. Send a notetaker to a Google Meet, Microsoft Teams or Zoom call, then retrieve the recording, transcript, summary and action items.…
- [Nylas Amazon SNS Notifications API](https://apis.io/apis/nylas/nylas-amazon-sns-notifications-api/) — Amazon SNS notification channels allow you to receive Nylas event notifications through Amazon Simple Notification Service (SNS) instead of webhooks. To use…
- [Nylas App migration API](https://apis.io/apis/nylas/nylas-app-migration-api/) — Before you begin, you should already have: - Linked your v2 and v3 Nylas organizations. If you're not sure if your organizations are linked and you have a…
- [Nylas Applications API](https://apis.io/apis/nylas/nylas-applications-api/) — In the context of the Nylas APIs, an "application" is the object record of your Nylas application. <div id="admonition-info">🔍 <b>The term "application" can…
- [Nylas Attachments API](https://apis.io/apis/nylas/nylas-attachments-api/) — You can use the `attachments` schema in a [Send Message request](/docs/reference/api/messages/send-message/) to send attachments, regardless of the email…
- [Nylas Authentication APIs API](https://apis.io/apis/nylas/nylas-authentication-apis-api/) — Nylas provides two ways to handle authentication: - **Bring Your Own (BYO) Authentication**, which uses the [`/v3/connect/custom`…
- [Nylas Availability API](https://apis.io/apis/nylas/nylas-availability-api/) — Nylas Scheduler uses the `/v3/scheduling/availability` endpoint to retrieve availability information. When you make a request, Nylas validates the provided…
- [Nylas Bookings API](https://apis.io/apis/nylas/nylas-bookings-api/) — Nylas Scheduler uses the `/v3/scheduling/bookings` endpoint to manage bookings. Bookings work the same way when the organizer is an [Agent…
- [Nylas Calendar API](https://apis.io/apis/nylas/nylas-calendar-api/) — The Nylas Calendar API allows you to create and manage calendars, and access the events they contain. Nylas uses the same commands to manage calendars…
- [Nylas Configurations API](https://apis.io/apis/nylas/nylas-configurations-api/) — A configuration is a collection of event settings and preferences. Nylas Scheduler stores Configuration objects in the Scheduler database and loads them as…
- [Nylas Connector credentials API](https://apis.io/apis/nylas/nylas-connector-credentials-api/) — A Nylas connector credential is a special type of record that securely stores information (such as provider settings) that allows you to connect using an…
- [Nylas Connectors (Integrations) API](https://apis.io/apis/nylas/nylas-connectors-integrations-api/) — In Nylas, a connector (formerly called an "integration") stores information that allows your Nylas application to connect to a third party services, such as…
- [Nylas Data migration API](https://apis.io/apis/nylas/nylas-data-migration-api/) — In Nylas v2, you used the unique Nylas ID to locate data and objects in Nylas's synced data. In Nylas v3, you use the provider ID directly. These APIs look…
- [Nylas Folders API](https://apis.io/apis/nylas/nylas-folders-api/) — To simplify your experience, the Nylas Email API uses the same commands to manage both folders and labels, and can refer to specific folders using the…
- [Nylas Group Events API](https://apis.io/apis/nylas/nylas-group-events-api/) — Group meetings let you host events with multiple participants. Unlike one-on-one meetings, group events are designed for collaborative scheduling where…
- [Nylas Lists API](https://apis.io/apis/nylas/nylas-lists-api/) — The Lists endpoints let you manage typed collections of values (email addresses, domains, or top-level domains) that can be referenced by Rules using the…
- [Nylas Manage API keys API](https://apis.io/apis/nylas/nylas-manage-api-keys-api/) — The Manage API Keys endpoints let you create, list, and delete API keys from your Nylas application outside of the Nylas Dashboard. ## Nylas Service Account…
- [Nylas Manage Domains API](https://apis.io/apis/nylas/nylas-manage-domains-api/) — The Manage Domains endpoints let you register, verify, update, and delete email domains for use with [Transactional…
- [Nylas Manage Grants API](https://apis.io/apis/nylas/nylas-manage-grants-api/) — Grants are the main objects that power Nylas, because they _grant_ your Nylas application specific scopes of access (for example, permission to read email…
- [Nylas Policies API](https://apis.io/apis/nylas/nylas-policies-api/) — The Policies endpoints let you define the operational configuration for Nylas Agent Accounts, including message limits, attachment constraints, spam…
- [Nylas Pub/Sub Notifications API](https://apis.io/apis/nylas/nylas-pub-sub-notifications-api/) — Nylas offers two ways to get notifications of what's happening on the provider. You can either subscribe to webhook notifications, or you can set up a…
- [Nylas Room resources API](https://apis.io/apis/nylas/nylas-room-resources-api/) — The Nylas Contacts API allows you to return information about rooms that you can book for meetings, conferences, and other events. ## Room resource booking…
- [Nylas Rules API](https://apis.io/apis/nylas/nylas-rules-api/) — The Rules endpoints let you define automated filtering and routing logic for Nylas Agent Accounts. Each rule specifies a `trigger` (`inbound` or…
- [Nylas Sessions API](https://apis.io/apis/nylas/nylas-sessions-api/) — Nylas Scheduler uses session IDs to authorize requests to the [`/v3/scheduling/availability`](/docs/reference/api/availability/) and…
- [Nylas Signatures API](https://apis.io/apis/nylas/nylas-signatures-api/) — The Nylas Signatures API lets you create and store HTML email signatures on Nylas, and reference them by ID when sending messages or creating drafts. Nylas…
- [Nylas Smart compose API](https://apis.io/apis/nylas/nylas-smart-compose-api/) — The Smart Compose endpoints extend the Nylas Messages API. Currently, Smart Compose supports only two methods of getting AI responses: you can either…
- [Nylas Standalone Notetaker API](https://apis.io/apis/nylas/nylas-standalone-notetaker-api/) — Nylas Notetaker is a real-time meeting bot that you can invite to your online meetings. It records and transcribes your discussion, and delivers results to…
- [Nylas Transactional send API](https://apis.io/apis/nylas/nylas-transactional-send-api/) — Nylas' Transactional Send endpoint lets you send messages directly from an email domain that you've verified with Nylas. You can use this to send password…
- [Nylas v2 Redirects API](https://apis.io/apis/nylas/nylas-v2-redirects-api/) — Nylas Scheduler uses the `/v3/scheduling/should-redirect/<V2_SCHEDULER_SLUG>` endpoint to redirect existing v2 Scheduling Pages to v3.
- [Nylas Webhook Notifications API](https://apis.io/apis/nylas/nylas-webhook-notifications-api/) — Your application receives information about changes to user accounts and data through Nylas webhooks. <div id="admonition-info"> 🔍 <b>The term "webhook" can…
- [Nylas Workspaces API](https://apis.io/apis/nylas/nylas-workspaces-api/) — Workspaces group and organize grants in a Nylas application by a common attribute, such as the email address domain (for example, `nylas.com`). ## Assign…
- [Nylas Templates and Workflows API](https://apis.io/apis/nylas/nylas-templates-and-workflows-api/) — The Templates and Workflows API from Nylas — 12 operation(s) for templates and workflows.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (2)

Event-driven and webhook contracts.

- [Nylas Notifications](https://apis.io/asyncapis/nylas/nylas-notifications-asyncapi/)
- [Nylas Webhooks](https://apis.io/asyncapis/nylas/nylas-webhooks/)

#### Event channels (3)

Individual events and webhooks the provider emits.

- [{topic}](https://apis.io/channels/nylas/topic/)
- [{topicArn}](https://apis.io/channels/nylas/topicarn/)
- [webhookDelivery](https://apis.io/channels/nylas/webhookdelivery/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Nylas MCP Server](https://apis.io/servers/nylas/nylas-mcp-server/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Nylas Agentic Access](https://apis.io/agentic-access/nylas/nylas-agentic-access/)

#### JSON Schema (93)

The data models the API reads and writes.

- [200-delete](https://apis.io/schemas/nylas/nylas-200-delete/)
- [Amazon SNS Channel Payload](https://apis.io/schemas/nylas/nylas-amazon-sns-input-payload/)
- [Android](https://apis.io/schemas/nylas/nylas-android-callbackw-settings/)
- [ApplicationObject](https://apis.io/schemas/nylas/nylas-application-object/)
- [AutodetectObject](https://apis.io/schemas/nylas/nylas-autodetect-object/)
- [Open Hours](https://apis.io/schemas/nylas/nylas-availability-open-hours/)
- [availability_rules](https://apis.io/schemas/nylas/nylas-availability-rules/)
- [availability_specific_time_availability](https://apis.io/schemas/nylas/nylas-availability-specific-time-availability/)
- [Nylas booking.cancelled notification object](https://apis.io/schemas/nylas/nylas-booking-cancelled.schema/)
- [Nylas booking.created notification object](https://apis.io/schemas/nylas/nylas-booking-created.schema/)
- [Nylas booking.pending notification object](https://apis.io/schemas/nylas/nylas-booking-pending.schema/)
- [Nylas booking.reminder notification object](https://apis.io/schemas/nylas/nylas-booking-reminder.schema/)
- [Nylas booking.rescheduled notification object](https://apis.io/schemas/nylas/nylas-booking-rescheduled.schema/)
- [booking_update](https://apis.io/schemas/nylas/nylas-booking-update/)
- [booking_update_group](https://apis.io/schemas/nylas/nylas-booking-update-group/)
- [Nylas calendar.created notification object](https://apis.io/schemas/nylas/nylas-calendar-created.schema/)
- [Nylas calendar.deleted notification object](https://apis.io/schemas/nylas/nylas-calendar-deleted.schema/)
- [Nylas calendar.updated notification object](https://apis.io/schemas/nylas/nylas-calendar-updated.schema/)
- [configuration](https://apis.io/schemas/nylas/nylas-configuration/)
- [ConnectorObject](https://apis.io/schemas/nylas/nylas-connector-object/)
- [Nylas contact.deleted notification object](https://apis.io/schemas/nylas/nylas-contact-deleted.schema/)
- [Nylas contact.updated notification object](https://apis.io/schemas/nylas/nylas-contact-updated.schema/)
- [CredentialObject](https://apis.io/schemas/nylas/nylas-credential-object/)
- [Destination Payload](https://apis.io/schemas/nylas/nylas-destination-input-payload/)
- [Destination Update Payload](https://apis.io/schemas/nylas/nylas-destination-update-payload/)
- …and 68 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Nylas Context](https://apis.io/jsonld/nylas/nylas-context/)

#### Collections (11)

Postman and Open Collection request collections.

- [Nylas API (v3)](https://apis.io/collections/nylas/open-nylas/)
- [Nylas API (v3) Admin API](https://apis.io/collections/nylas/open-nylas-admin-api/)
- [Nylas API (v3) Admin Auth API](https://apis.io/collections/nylas/open-nylas-auth-api/)
- [Nylas API (v3) Admin Calendars API](https://apis.io/collections/nylas/open-nylas-calendars-api/)
- [Nylas API (v3) Admin Contacts API](https://apis.io/collections/nylas/open-nylas-contacts-api/)
- [Nylas API (v3) Admin Drafts API](https://apis.io/collections/nylas/open-nylas-drafts-api/)
- [Nylas API (v3) Admin Events API](https://apis.io/collections/nylas/open-nylas-events-api/)
- [Nylas API (v3) Admin Grants API](https://apis.io/collections/nylas/open-nylas-grants-api/)
- [Nylas API (v3) Admin Messages API](https://apis.io/collections/nylas/open-nylas-messages-api/)
- [Nylas API (v3) Admin Scheduling API](https://apis.io/collections/nylas/open-nylas-scheduling-api/)
- [Nylas API (v3) Admin Threads API](https://apis.io/collections/nylas/open-nylas-threads-api/)

#### Overlays (40)

OpenAPI overlays, including conversational phrasing for each operation.

- [Nylas Amazon Sns Notifications Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-amazon-sns-notifications-api-phrasing-overlay/)
- [Nylas App Migration Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-app-migration-api-phrasing-overlay/)
- [Nylas Application Level Templates Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-application-level-templates-api-phrasing-overlay/)
- [Nylas Application Level Workflows Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-application-level-workflows-api-phrasing-overlay/)
- [Nylas Applications Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-applications-api-phrasing-overlay/)
- [Nylas Attachments Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-attachments-api-phrasing-overlay/)
- [Nylas Authentication Apis Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-authentication-apis-api-phrasing-overlay/)
- [Nylas Availability Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-availability-api-phrasing-overlay/)
- [Nylas Bookings Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-bookings-api-phrasing-overlay/)
- [Nylas Calendar Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-calendar-api-phrasing-overlay/)
- [Nylas Configurations Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-configurations-api-phrasing-overlay/)
- [Nylas Connector Credentials Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-connector-credentials-api-phrasing-overlay/)
- [Nylas Connectors Integrations Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-connectors-integrations-api-phrasing-overlay/)
- [Nylas Contacts Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-contacts-api-phrasing-overlay/)
- [Nylas Data Migration Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-data-migration-api-phrasing-overlay/)
- [Nylas Drafts Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-drafts-api-phrasing-overlay/)
- [Nylas Events Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-events-api-phrasing-overlay/)
- [Nylas Folders Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-folders-api-phrasing-overlay/)
- [Nylas Grant Level Templates Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-grant-level-templates-api-phrasing-overlay/)
- [Nylas Grant Level Workflows Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-grant-level-workflows-api-phrasing-overlay/)
- [Nylas Group Events Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-group-events-api-phrasing-overlay/)
- [Nylas Lists Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-lists-api-phrasing-overlay/)
- [Nylas Manage Api Keys Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-manage-api-keys-api-phrasing-overlay/)
- [Nylas Manage Domains Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-manage-domains-api-phrasing-overlay/)
- [Nylas Manage Grants Api Phrasing Overlay](https://apis.io/overlays/nylas/nylas-manage-grants-api-phrasing-overlay/)
- …and 15 more published on APIs.io

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Nylas API Rules](https://apis.io/rules/nylas/nylas-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Nylas Authentication](https://apis.io/security/nylas/nylas-authentication/)
- [Nylas Domain Security](https://apis.io/security/nylas/nylas-domain-security/)
- [Nylas Trust Center](https://apis.io/security/nylas/nylas-trust-center/)
- [Nylas Vulnerability Disclosure](https://apis.io/security/nylas/nylas-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Nylas Plans Pricing](https://apis.io/plans/nylas/nylas-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Nylas Rate Limits](https://apis.io/rate-limits/nylas/nylas-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Nylas Finops](https://apis.io/finops/nylas/nylas-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.nylas.com/)
- [Documentation](https://developer.nylas.com/)
- [Getting started](https://developer.nylas.com/docs/v3/getting-started/)
- [API reference](https://developer.nylas.com/docs/reference/api/)
- [Pricing](https://www.nylas.com/pricing/)
- [Support](https://developer.nylas.com/docs/support/)
- [Changelog](https://developer.nylas.com/docs/changelogs/)
- [Blog](https://www.nylas.com/blog/)
- [Security](https://www.nylas.com/security/)
- [Compliance](https://trust.nylas.com/public)
- [Terms of service](https://www.nylas.com/legal/terms/)
- [Privacy policy](https://www.nylas.com/legal/privacy-policy/)
- [Status](https://status-v3.nylas.com/)

## API Evangelist rating

**Kin Score 87.4** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 88.3 |
| Contract quality | 79.9 |
| Contract governance | 45.5 |
| Operational transparency | 83.7 |
| Developer ergonomics | 94.6 |
| Access clarity | 88.9 |

**Agent readiness 57.2** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | yes |
| Consent Identity | yes |
| Agent Card | flavored (partial credit) |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 56.9** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nylas/](https://apis.io/providers/nylas/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Nylas: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nylas/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
