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
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Calendar
- Communications
- Contacts
- Email
- Messaging
- Scheduling
- Notetaker

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-09-28

## APIs

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

### Nylas Messages API

Messages. List, search, read, update and delete email messages. Send immediately, schedule a send and cancel a scheduled send, with folders, signatures and attachments alongside.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/messages/](https://developer.nylas.com/docs/reference/api/messages/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Message

#### Properties

- [OpenAPI](openapi/nylas-messages-api-openapi.yml)

### Nylas Threads API

Threads. List, search, read and update email threads, and manage thread-level folders and state.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/threads/](https://developer.nylas.com/docs/reference/api/threads/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Threads

#### Properties

- [OpenAPI](openapi/nylas-threads-api-openapi.yml)

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

### Nylas Amazon SNS Notifications API

Amazon SNS notification channels allow you to receive Nylas event notifications through Amazon Simple Notification Service (SNS) instead of webhooks.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/amazon-sns-notifications/](https://developer.nylas.com/docs/reference/api/amazon-sns-notifications/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Amazon SNS Notifications

#### Properties

- [AsyncAPI](asyncapi/nylas-notifications-asyncapi.yml)
- [OpenAPI](openapi/nylas-amazon-sns-notifications-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas App migration API

Before you begin, you should already have:

- **Human URL:** [https://developer.nylas.com/docs/reference/api/](https://developer.nylas.com/docs/reference/api/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- App migration

#### Properties

- [OpenAPI](openapi/nylas-app-migration-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Application-level templates API

Application-level templates let you create reusable messages with dynamic content. Each template is linked to the Nylas application associated with the API key specified in a [Create Template request](https://developer.nylas.com/docs/reference/api/application-level-templates/create-app-level-template/).

- **Human URL:** [https://developer.nylas.com/docs/reference/api/application-level-templates/](https://developer.nylas.com/docs/reference/api/application-level-templates/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Application-level templates

#### Properties

- [OpenAPI](openapi/nylas-application-level-templates-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Application-level workflows API

Application-level workflows automatically send messages to certain users when a defined event is triggered. For example, if you want to send a confirmation message when a user schedules a booking, you can create a workflow that listens for [`booking.created` events](https://developer.nylas.com/docs/reference/notifications/#booking-created-notifications).

- **Human URL:** [https://developer.nylas.com/docs/reference/api/application-level-workflows/](https://developer.nylas.com/docs/reference/api/application-level-workflows/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Application-level workflows

#### Properties

- [OpenAPI](openapi/nylas-application-level-workflows-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Applications API

In the context of the Nylas APIs, an "application" is the object record of your Nylas application.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/applications/](https://developer.nylas.com/docs/reference/api/applications/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Application

#### Properties

- [OpenAPI](openapi/nylas-applications-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Attachments API

You can use the `attachments` schema in a [Send Message request](https://developer.nylas.com/docs/reference/api/messages/send-message/) to send attachments, regardless of the email provider. You use the [Drafts](https://developer.nylas.com/docs/reference/api/drafts/) endpoints to add and modify files attached to drafts. The Attachments endpoints let you download or get the metadata for existing attachments. For more information, see [Working with email attachments](https://developer.nylas.com/docs/v3/email/attachments/).

- **Human URL:** [https://developer.nylas.com/docs/reference/api/attachments/](https://developer.nylas.com/docs/reference/api/attachments/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Attachments

#### Properties

- [OpenAPI](openapi/nylas-attachments-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Authentication APIs API

Nylas provides two ways to handle authentication:

- **Human URL:** [https://developer.nylas.com/docs/reference/api/authentication-apis/](https://developer.nylas.com/docs/reference/api/authentication-apis/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Authentication APIs

#### Properties

- [OpenAPI](openapi/nylas-authentication-apis-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Availability API

Nylas Scheduler uses the `/v3/scheduling/availability` endpoint to retrieve availability information. When you make a request, Nylas validates the provided session ID and uses it to retrieve the related Configuration object.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/availability/](https://developer.nylas.com/docs/reference/api/availability/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Availability

#### Properties

- [OpenAPI](openapi/nylas-availability-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Bookings API

Nylas Scheduler uses the `/v3/scheduling/bookings` endpoint to manage bookings.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/bookings/](https://developer.nylas.com/docs/reference/api/bookings/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Booking

#### Properties

- [OpenAPI](openapi/nylas-bookings-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Calendar API

The Nylas Calendar API allows you to create and manage calendars, and access the events they contain. Nylas uses the same commands to manage calendars across providers, and you can refer to specific calendars using the provider's `calendar_id`.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/calendar/](https://developer.nylas.com/docs/reference/api/calendar/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Calendar

#### Properties

- [OpenAPI](openapi/nylas-calendar-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Configurations API

A configuration is a collection of event settings and preferences. Nylas Scheduler stores Configuration objects in the Scheduler database and loads them as Scheduling Pages in the Scheduler UI.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/configurations/](https://developer.nylas.com/docs/reference/api/configurations/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Configurations

#### Properties

- [OpenAPI](openapi/nylas-configurations-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Connector credentials API

A Nylas connector credential is a special type of record that securely stores information (such as provider settings) that allows you to connect using an administrator account. Nylas securely stores, hashes, and encrypts the connector credential's sensitive data, and the contents vary depending on the authentication provider.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/connector-credentials/](https://developer.nylas.com/docs/reference/api/connector-credentials/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Connector credentials

#### Properties

- [OpenAPI](openapi/nylas-connector-credentials-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Connectors (Integrations) API

In Nylas, a connector (formerly called an "integration") stores information that allows your Nylas application to connect to a third party services, such as a provider auth application from Google (GCP), Microsoft (Azure), or to an IMAP provider. You must create a connector in your Nylas application for each specific provider before you can create Grants and access user data from that provider.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/connectors-integrations/](https://developer.nylas.com/docs/reference/api/connectors-integrations/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Connectors (Integrations)

#### Properties

- [OpenAPI](openapi/nylas-connectors-integrations-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Data migration API

In Nylas v2, you used the unique Nylas ID to locate data and objects in Nylas's synced data. In Nylas v3, you use the provider ID directly. These APIs look up the provider IDs for your v2 data.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/](https://developer.nylas.com/docs/reference/api/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Data Migration

#### Properties

- [OpenAPI](openapi/nylas-data-migration-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Folders API

To simplify your experience, the Nylas Email API uses the same commands to manage both folders and labels, and can refer to specific folders using the provider's `folder_id`. The Email API also exposes provider-specific fields (for example, Google's `background_color` field).

- **Human URL:** [https://developer.nylas.com/docs/reference/api/folders/](https://developer.nylas.com/docs/reference/api/folders/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Folders

#### Properties

- [OpenAPI](openapi/nylas-folders-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Grant-level templates API

Grant-level templates let you create reusable messages with dynamic content. Each template is linked to the grant specified in a [Create Template request](https://developer.nylas.com/docs/reference/api/grant-level-templates/create-grant-level-template/).

- **Human URL:** [https://developer.nylas.com/docs/reference/api/grant-level-templates/](https://developer.nylas.com/docs/reference/api/grant-level-templates/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Grant-level templates

#### Properties

- [OpenAPI](openapi/nylas-grant-level-templates-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Grant-level workflows API

Grant-level workflows automatically send messages to certain users when a defined event is triggered. For example, if you want to send a confirmation message when a user schedules a booking, you can create a workflow that listens for [`booking.created` events](https://developer.nylas.com/docs/reference/notifications/#booking-created-notifications).

- **Human URL:** [https://developer.nylas.com/docs/reference/api/grant-level-workflows/](https://developer.nylas.com/docs/reference/api/grant-level-workflows/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Grant-level workflows

#### Properties

- [OpenAPI](openapi/nylas-grant-level-workflows-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Group Events API

Group meetings let you host events with multiple participants. Unlike one-on-one meetings, group events are designed for collaborative scheduling where multiple attendees are invited to the same event.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/group-events/](https://developer.nylas.com/docs/reference/api/group-events/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Group Events

#### Properties

- [OpenAPI](openapi/nylas-group-events-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Lists API

The Lists endpoints let you manage typed collections of values (email addresses, domains, or top-level domains) that can be referenced by Rules using the `in_list` condition operator. Lists provide a way to maintain dynamic allow lists and block lists that are evaluated during inbound rule processing and outbound send evaluation without needing to update individual rules.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/lists/](https://developer.nylas.com/docs/reference/api/lists/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- List

#### Properties

- [OpenAPI](openapi/nylas-lists-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Manage API keys API

The Manage API Keys endpoints let you create, list, and delete API keys from your Nylas application outside of the Nylas Dashboard.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/manage-api-keys/](https://developer.nylas.com/docs/reference/api/manage-api-keys/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Manage API keys

#### Properties

- [OpenAPI](openapi/nylas-manage-api-keys-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Manage Domains API

The Manage Domains endpoints let you register, verify, update, and delete email domains for use with [Transactional Send](https://developer.nylas.com/docs/v3/getting-started/transactional-send/) and [Nylas Agent Accounts](https://developer.nylas.com/docs/v3/agent-accounts/).

- **Human URL:** [https://developer.nylas.com/docs/reference/api/manage-domains/](https://developer.nylas.com/docs/reference/api/manage-domains/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Manage Domains

#### Properties

- [OpenAPI](openapi/nylas-manage-domains-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Manage Grants API

Grants are the main objects that power Nylas, because they _grant_ your Nylas application specific scopes of access (for example, permission to read email messages) to the user's resources and data on their provider. They also represent access granted to your application for certain resources.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/manage-grants/](https://developer.nylas.com/docs/reference/api/manage-grants/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Manage Grants

#### Properties

- [OpenAPI](openapi/nylas-manage-grants-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Policies API

The Policies endpoints let you define the operational configuration for Nylas Agent Accounts, including message limits, attachment constraints, spam detection settings, and linked rules for inbound message filtering. Each policy is scoped to your application and can be assigned to one or more Agent Accounts, or attached to a [workspace](https://developer.nylas.com/docs/reference/api/workspaces/) to apply its limits and spam settings to the Agent Accounts it contains.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/policies/](https://developer.nylas.com/docs/reference/api/policies/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Policies

#### Properties

- [OpenAPI](openapi/nylas-policies-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Pub/Sub Notifications API

Nylas offers two ways to get notifications of what's happening on the provider. You can either subscribe to webhook notifications, or you can set up a notification channel.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/pubsub-notifications/](https://developer.nylas.com/docs/reference/api/pubsub-notifications/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Pub/Sub Notifications

#### Properties

- [AsyncAPI](asyncapi/nylas-notifications-asyncapi.yml)
- [OpenAPI](openapi/nylas-pub-sub-notifications-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Room resources API

The Nylas Contacts API allows you to return information about rooms that you can book for meetings, conferences, and other events.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/room-resources/](https://developer.nylas.com/docs/reference/api/room-resources/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Room resources

#### Properties

- [OpenAPI](openapi/nylas-room-resources-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Rules API

The Rules endpoints let you define automated filtering and routing logic for Nylas Agent Accounts. Each rule specifies a `trigger` (`inbound` or `outbound`), matching conditions, and actions to perform when those conditions are met.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/rules/](https://developer.nylas.com/docs/reference/api/rules/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Rules

#### Properties

- [OpenAPI](openapi/nylas-rules-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Sessions API

Nylas Scheduler uses session IDs to authorize requests to the [`/v3/scheduling/availability`](https://developer.nylas.com/docs/reference/api/availability/) and [`/v3/scheduling/bookings`](https://developer.nylas.com/docs/reference/api/bookings/) endpoints.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/sessions/](https://developer.nylas.com/docs/reference/api/sessions/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Sessions

#### Properties

- [OpenAPI](openapi/nylas-sessions-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Signatures API

The Nylas Signatures API lets you create and store HTML email signatures on Nylas, and reference them by ID when sending messages or creating drafts. Nylas appends the signature to the end of the email body at send time.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/signatures/](https://developer.nylas.com/docs/reference/api/signatures/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Signatures

#### Properties

- [OpenAPI](openapi/nylas-signatures-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Smart compose API

The Smart Compose endpoints extend the Nylas Messages API. Currently, Smart Compose supports only two methods of getting AI responses: you can either receive them as a REST response in a single JSON blob, or use server-sent events (SSE) to stream the response tokens as Nylas receives them.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/smart-compose/](https://developer.nylas.com/docs/reference/api/smart-compose/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Smart compose

#### Properties

- [OpenAPI](openapi/nylas-smart-compose-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Standalone Notetaker API

Nylas Notetaker is a real-time meeting bot that you can invite to your online meetings. It records and transcribes your discussion, and delivers results to you using the Nylas API and webhook notifications.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/standalone-notetaker/](https://developer.nylas.com/docs/reference/api/standalone-notetaker/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Standalone Notetaker

#### Properties

- [OpenAPI](openapi/nylas-standalone-notetaker-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Transactional send API

Nylas' Transactional Send endpoint lets you send messages directly from an email domain that you've verified with Nylas. You can use this to send password reset emails, account verifications, or system notifications.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/transactional-send/](https://developer.nylas.com/docs/reference/api/transactional-send/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Transactional send

#### Properties

- [OpenAPI](openapi/nylas-transactional-send-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas v2 Redirects API

Nylas Scheduler uses the `/v3/scheduling/should-redirect/<V2_SCHEDULER_SLUG>` endpoint to redirect existing v2 Scheduling Pages to v3.

- **Human URL:** [https://developer.nylas.com/docs/unlisted/redirect-v2-scheduling-pages/](https://developer.nylas.com/docs/unlisted/redirect-v2-scheduling-pages/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- v2 Redirects

#### Properties

- [OpenAPI](openapi/nylas-v2-redirects-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

### Nylas Webhook Notifications API

Your application receives information about changes to user accounts and data through Nylas webhooks.

- **Human URL:** [https://developer.nylas.com/docs/reference/api/webhook-notifications/](https://developer.nylas.com/docs/reference/api/webhook-notifications/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Webhook Notifications

#### Properties

- [AsyncAPI](asyncapi/nylas-notifications-asyncapi.yml)
- [OpenAPI](openapi/nylas-webhook-notifications-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)
- JSON Schema: 54 notification schemas in [json-schema/](json-schema/)

### Nylas Workspaces API

Workspaces group and organize grants in a Nylas application by a common attribute, such as the email address domain (for example, `nylas.com`).

- **Human URL:** [https://developer.nylas.com/docs/reference/api/workspaces/](https://developer.nylas.com/docs/reference/api/workspaces/)
- **Base URL:** `https://api.us.nylas.com`

#### Tags

- Workspace

#### Properties

- [OpenAPI](openapi/nylas-workspaces-api-openapi.yml)
- [API Reference](https://developer.nylas.com/docs/reference/notifications/)
- [Documentation](https://developer.nylas.com/docs/v3/notifications/)
- [Documentation](https://developer.nylas.com/docs/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Authentication](https://developer.nylas.com/docs/v3/auth/)
- [Rate Limits](https://developer.nylas.com/docs/dev-guide/platform/rate-limits/)
- [Error Codes](https://developer.nylas.com/docs/api/errors/)
- [Pricing](https://www.nylas.com/pricing/)
- [Signup](https://dashboard-v3.nylas.com/register)
- [Status Page](https://status-v3.nylas.com/)
- [SDKs](https://github.com/nylas/nylas-nodejs)
- [SDKs](https://github.com/nylas/nylas-python)
- [SDKs](https://github.com/nylas/nylas-ruby)
- [SDKs](https://github.com/nylas/nylas-java)
- [API Reference](https://developer.nylas.com/docs/reference/api/application-level-templates/)

## Common Properties

- [Nylas Business Capability Map](capabilities/nylas-capability-edges.yml)
- [Agentic Access](agentic-access/nylas-agentic-access.yml)
- [Trust Center](security/nylas-trust-center.yml)
- [Vulnerability Disclosure](security/nylas-vulnerability-disclosure.yml)
- [Domain Security](security/nylas-domain-security.yml)
- [Authentication](authentication/nylas-authentication.yml)
- [Linked In](https://www.linkedin.com/company/nylas)
- [Website](https://www.nylas.com/)
- [Documentation](https://developer.nylas.com/)
- [Blog](https://www.nylas.com/blog/)
- [Git Hub Org](https://github.com/nylas)
- [Terms of Service](https://www.nylas.com/legal/terms/)
- [Privacy Policy](https://www.nylas.com/privacy-policy/)
- [Status Page](https://status-v3.nylas.com/)
- [Llms Text](https://developer.nylas.com/llms.txt)
- [Developer Portal](https://developer.nylas.com/)
- [API Reference](https://developer.nylas.com/docs/reference/api/)
- [Notifications reference](https://developer.nylas.com/docs/reference/notifications/)
- [UI components reference](https://developer.nylas.com/docs/reference/ui/)
- [Getting Started](https://developer.nylas.com/docs/v3/getting-started/)
- [Node.js SDK](https://github.com/nylas/nylas-nodejs)
- [Python SDK](https://github.com/nylas/nylas-python)
- [Ruby SDK](https://github.com/nylas/nylas-ruby)
- [Java/Kotlin SDK](https://github.com/nylas/nylas-java)
- [CLI](https://cli.nylas.com/)
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
- [Signup](https://dashboard-v3.nylas.com/register)
- [Nylas MCP Server](https://mcp.us.nylas.com)
- [Nylas MCP Server manifest](mcp/nylas-mcp.yml)
- [Vocabulary](vocabulary/nylas-vocabulary.yml)
- [Conformance](conformance/nylas-conformance.yml)
- [Agent Card](a2a/nylas-a2a.yml)
- [security.txt](https://developer.nylas.com/.well-known/security.txt)
- [Content Signal](https://developer.nylas.com/robots.txt)
- [APICatalog](https://developer.nylas.com/.well-known/api-catalog)
- [Well-Known](well-known/nylas-well-known.yml)
- [Provider scopes Nylas requests](https://developer.nylas.com/docs/dev-guide/scopes/)
- [Try it console on every API reference page (US/EU, API key or access token)](https://developer.nylas.com/docs/reference/api/)
- [Nylas sample applications](https://github.com/nylas-samples)
- [Nylas cookbook](https://developer.nylas.com/docs/cookbook/)
- [Newsroom](https://www.nylas.com/newsroom/)
- [Leadership](https://www.nylas.com/company/about/)
- [Subprocessors](https://www.nylas.com/security/subprocessors/)
- [US and EU regions](https://developer.nylas.com/docs/dev-guide/platform/data-residency/)
- [Privacy rights requests (access, correction, deletion, portability)](https://www.nylas.com/privacy-policy/)
- [GPC treated as an opt-out of targeted advertising](https://www.nylas.com/privacy-policy/)
- [Notetaker announces in the meeting chat that it is recording and transcribing](https://developer.nylas.com/docs/v3/notetaker/custom-announcements/)
- [Nylas notifications over webhooks, Pub/Sub and SNS](asyncapi/nylas-notifications-asyncapi.yml)
- [Notification envelope](json-schema/nylas-notification-envelope.schema.json)
- [JSONLDContext](json-ld/nylas-context.jsonld)
- [Nylas API contract ruleset](rules/nylas-rules.yml)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
