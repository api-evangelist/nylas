# Nylas (nylas)

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

Nylas connects your application to every email inbox and calendar in the world. The Nylas v3 platform provides REST APIs for email, calendar, contacts, scheduling, meeting notetaking, authentication, and administration across Google, Microsoft, Exchange, iCloud, Yahoo and any IMAP provider. Official SDKs cover Node.js, Python, Ruby and Kotlin/Java, alongside a CLI, a hosted MCP server, and Agent Accounts that provision a Nylas-hosted mailbox and calendar for autonomous agents without requiring an OAuth flow.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nylas/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nylas/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Calendar
- Communications
- Contacts
- Email
- Messaging
- Scheduling

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-04-28

## APIs

### Nylas API

The Nylas v3 REST API provides programmatic access to email, calendar, contacts, meeting notetaking, scheduling, authentication and administration across Google, Microsoft, Exchange, iCloud, Yahoo and any IMAP provider. Resources are scoped to a grant, which represents one authenticated mailbox and calendar. The entries below are facets of this single contract.

- **Human URL:** [https://developer.nylas.com/](https://developer.nylas.com/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Calendar
- Communications
- Contacts
- Email
- Messaging
- Scheduling

#### Properties

- [OpenAPI](https://developer.nylas.com/_spec-files/nylas-api.yaml)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Sign Up](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status.nylas.com/)
- [Node.js SDK](https://github.com/nylas/nylas-nodejs)
- [Python SDK](https://github.com/nylas/nylas-python)
- [Ruby SDK](https://github.com/nylas/nylas-ruby)
- [Java/Kotlin SDK](https://github.com/nylas/nylas-java)

### Nylas Admin API

Application-level administration: Nylas applications, API keys, custom domains, connectors and connector credentials, workspaces, and the rules, policies and lists that govern them.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/applications/](https://developer.nylas.com/docs/reference/api/applications/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Admin

#### Properties

- [OpenAPI](openapi/nylas-admin-api-openapi.yml)

### Nylas Auth API

Authentication. Hosted OAuth 2.1 authorization and token exchange, custom (non-OAuth) grant creation for Agent Accounts, token refresh and revocation, and ID token validation.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/authentication-apis/](https://developer.nylas.com/docs/reference/api/authentication-apis/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Authentication

#### Properties

- [OpenAPI](openapi/nylas-auth-api-openapi.yml)

### Nylas Calendars API

Calendars. List and manage a grant's calendars, query free/busy availability across participants, and read room and resource calendars.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/calendar/](https://developer.nylas.com/docs/reference/api/calendar/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Calendars

#### Properties

- [OpenAPI](openapi/nylas-calendars-api-openapi.yml)

### Nylas Contacts API

Contacts. Read, create, update and delete a grant's contacts and contact groups.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/contacts/](https://developer.nylas.com/docs/reference/api/contacts/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Contacts

#### Properties

- [OpenAPI](openapi/nylas-contacts-api-openapi.yml)

### Nylas Drafts API

Drafts. Compose, update, send and delete drafts, manage attachments, and generate draft bodies and replies with Smart Compose.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/drafts/](https://developer.nylas.com/docs/reference/api/drafts/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Drafts

#### Properties

- [OpenAPI](openapi/nylas-drafts-api-openapi.yml)

### Nylas Events API

Events. Create, update, delete and list calendar events, including recurring events, group events and RSVP handling.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/events/](https://developer.nylas.com/docs/reference/api/events/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Event

#### Properties

- [OpenAPI](openapi/nylas-events-api-openapi.yml)

### Nylas Grants API

Grants. A grant represents one authenticated mailbox and calendar. List, retrieve and delete grants, and inspect grant state and scopes.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/manage-grants/](https://developer.nylas.com/docs/reference/api/manage-grants/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Grants

#### Properties

- [OpenAPI](openapi/nylas-grants-api-openapi.yml)

### Nylas Messages API

Messages. List, search, read, update and delete email messages. Send immediately, schedule a send and cancel a scheduled send, with folders, signatures and attachments alongside.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/messages/](https://developer.nylas.com/docs/reference/api/messages/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Message

#### Properties

- [OpenAPI](openapi/nylas-messages-api-openapi.yml)

### Nylas Scheduling API

Scheduler. Booking configurations, scheduling sessions, availability lookups and booking lifecycle management for hosted and component-based booking flows.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/configurations/](https://developer.nylas.com/docs/reference/api/configurations/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Scheduling

#### Properties

- [OpenAPI](openapi/nylas-scheduling-api-openapi.yml)

### Nylas Threads API

Threads. List, search, read and update email threads, and manage thread-level folders and state.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/threads/](https://developer.nylas.com/docs/reference/api/threads/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Threads

#### Properties

- [OpenAPI](openapi/nylas-threads-api-openapi.yml)

### Nylas Notifications API

Change notifications. Nylas pushes events for messages, threads, calendars, events, grants and Notetaker over three interchangeable transports carrying the same payloads: HTTPS webhooks, Google Cloud Pub/Sub, and Amazon SNS. Covers subscription CRUD, delivery testing, mock payloads and the source IP ranges to allowlist. There is no polling requirement, and no WebSocket or SSE surface.

- **Human URL:** [https://developer.nylas.com/docs/reference/notifications/](https://developer.nylas.com/docs/reference/notifications/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Webhooks
- Notifications
- Event

#### Properties

- [OpenAPI](openapi/nylas-notifications-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)

### Nylas Notetaker API

Meeting notetaker. Send a notetaker to a Google Meet, Microsoft Teams or Zoom call, then retrieve the recording, transcript, summary and action items. Available grant-scoped, or standalone with no connected mailbox required.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/notetaker/](https://developer.nylas.com/docs/reference/api/notetaker/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Notetaker
- Transcription
- Meetings

#### Properties

- [OpenAPI](openapi/nylas-notetaker-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/api/notetaker/)
- [Documentation](https://developer.nylas.com/docs/v3/notetaker/)

### Nylas Templates and Workflows API

Reusable email templates and automation workflows, at both application and grant scope. Define a template once and send against it, or trigger a workflow on an inbound event.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/application-level-templates/](https://developer.nylas.com/docs/reference/api/application-level-templates/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Templates
- Workflows
- Automation

#### Properties

- [OpenAPI](openapi/nylas-templates-workflows-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

## Common Properties

- [Agentic Access](agentic-access/nylas-agentic-access.yml)
- [Trust Center](security/nylas-trust-center.yml)
- [Vulnerability Disclosure](security/nylas-vulnerability-disclosure.yml)
- [Domain Security](security/nylas-domain-security.yml)
- [Authentication](authentication/nylas-authentication.yml)
- [LinkedIn](https://www.linkedin.com/company/nylas)
- [Website](https://www.nylas.com/)
- [Documentation](https://developer.nylas.com/)
- [Blog](https://www.nylas.com/blog/)
- [GitHub Org](https://github.com/nylas)
- [Terms of Service](https://www.nylas.com/legal/terms/)
- [Privacy Policy](https://www.nylas.com/legal/privacy-policy/)
- [Status Page](https://status.nylas.com/)
- [LLMs Text](https://developer.nylas.com/llms.txt)
- [Developer Portal](https://developer.nylas.com/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Notifications reference](https://developer.nylas.com/docs/reference/notifications/)
- [UI components reference](https://developer.nylas.com/docs/reference/ui/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Node.js SDK](https://github.com/nylas/nylas-nodejs)
- [Python SDK](https://github.com/nylas/nylas-python)
- [Ruby SDK](https://github.com/nylas/nylas-ruby)
- [Java/Kotlin SDK](https://github.com/nylas/nylas-java)
- [C L I](https://cli.nylas.com/)
- [Postman](https://developer.nylas.com/docs/v3/api-references/postman/)
- [Postman Workspace](https://www.postman.com/trynylas/workspace/nylas-api/overview)
- [Agent Skills](https://developer.nylas.com/.well-known/agent-skills/index.json)
- [Support](https://developer.nylas.com/docs/support/)
- [Change Log](https://developer.nylas.com/docs/changelogs/)
- [Deprecation Policy](https://developer.nylas.com/docs/support/product-lifecycle/)
- [Security](https://www.nylas.com/security/)
- [Compliance](https://trust.nylas.com/public)
- [Webhooks](https://developer.nylas.com/docs/v3/notifications/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Idempotency](https://developer.nylas.com/docs/v3/email/idempotent-send/)
- [Pricing](https://www.nylas.com/pricing/)
- [Sign Up](https://dashboard-v3.nylas.com/register)
- [Nylas MCP Server](https://mcp.us.nylas.com)
- [Nylas MCP Server manifest](mcp/nylas-mcp.yml)
- [Vocabulary](vocabulary/nylas-vocabulary.yml)
- [Conformance](conformance/nylas-conformance.yml)
- [Agent Card](a2a/nylas-a2a.yml)
- [Security.txt](https://developer.nylas.com/.well-known/security.txt)
- [Content Signal](https://developer.nylas.com/robots.txt)
- [API Catalog](https://developer.nylas.com/.well-known/api-catalog)
- [Well-Known](well-known/nylas-well-known.yml)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
