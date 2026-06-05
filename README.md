# Front (front)

Front is a customer operations platform unifying shared inboxes, chat, SMS, social, and CRM workflows. Front exposes a Core API (conversations, messages, channels, contacts, teammates, analytics), a Channels API for custom messaging integrations, a Plugin SDK for embedded UI apps, a Chat Widget, and Connectors for low-code automations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/front/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/front/refs/heads/main/apis.yml)

## Tags

- Customer Support
- Email
- Inbox
- Customer Operations
- Collaboration
- Omnichannel

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-30

## APIs

### Front Conversations API

Read, create, update, and delete conversations across email, SMS, chat, and social channels. Includes assign, archive, restore, snooze, follow, and merge actions.

#### Tags

- Conversations
- Tickets

#### Properties

- [Documentation](https://dev.frontapp.com/)
- [API Reference](https://dev.frontapp.com/reference/conversations)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Messages API

Send and reply to messages on existing or new conversations across any channel; includes inbound import for sync use cases.

#### Tags

- Messages
- Replies

#### Properties

- [Documentation](https://dev.frontapp.com/reference/messages)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Drafts API

Create, edit, and delete message drafts assigned to a teammate or a shared inbox.

#### Tags

- Drafts

#### Properties

- [Documentation](https://dev.frontapp.com/reference/drafts)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Channels API

Manage channels (email addresses, SMS numbers, chat connectors, custom channels) attached to inboxes.

#### Tags

- Channels

#### Properties

- [Documentation](https://dev.frontapp.com/reference/channels)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Inboxes API

Manage shared inboxes and teammate access; attach channels to inboxes and read inbox configuration.

#### Tags

- Inboxes

#### Properties

- [Documentation](https://dev.frontapp.com/reference/inboxes)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Contacts API

Manage Front contacts and their handles (email, phone, social). Contacts unify customer identity across channels.

#### Tags

- Contacts
- People

#### Properties

- [Documentation](https://dev.frontapp.com/reference/contacts)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Contact Groups API

Group contacts for segmentation and shared visibility across teammates.

#### Tags

- Groups
- Segmentation

#### Properties

- [Documentation](https://dev.frontapp.com/reference/contact-groups)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Accounts API

Read and manage company / account records that group multiple contacts under a single business relationship.

#### Tags

- Accounts
- Companies

#### Properties

- [Documentation](https://dev.frontapp.com/reference/accounts)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Teammates API

Read teammates (Front users) and their availability, roles, and assignments.

#### Tags

- Teammates
- Users

#### Properties

- [Documentation](https://dev.frontapp.com/reference/teammates)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Teams API

Read team membership and team-scoped resources for routing and analytics.

#### Tags

- Teams

#### Properties

- [Documentation](https://dev.frontapp.com/reference/teams)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Comments API

Add, list, and remove internal comments on conversations for collaboration.

#### Tags

- Comments
- Internal Notes

#### Properties

- [Documentation](https://dev.frontapp.com/reference/comments)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Tags API

Manage tags and apply them to conversations for categorization, automation, and reporting.

#### Tags

- Tags

#### Properties

- [Documentation](https://dev.frontapp.com/reference/tags)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Topics API

Read AI-generated topics that classify conversation content for analytics and routing.

#### Tags

- Topics
- AI

#### Properties

- [Documentation](https://dev.frontapp.com/reference/topics)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Rules API

Read configured automation rules; rule definitions are managed from the UI but exposed read-only via the API.

#### Tags

- Rules
- Automation

#### Properties

- [Documentation](https://dev.frontapp.com/reference/rules)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Signatures API

Read teammate and team signatures used on outbound messages.

#### Tags

- Signatures

#### Properties

- [Documentation](https://dev.frontapp.com/reference/signatures)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Shifts API

Manage teammate shifts that drive routing rules and SLA timers.

#### Tags

- Shifts
- Scheduling

#### Properties

- [Documentation](https://dev.frontapp.com/reference/shifts)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Knowledge Base API

Manage knowledge bases, categories, and articles published to customers and used by Front AI for self-service responses.

#### Tags

- Knowledge Base
- Articles

#### Properties

- [Documentation](https://dev.frontapp.com/reference/knowledge-base)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Analytics API

Generate analytics report exports for conversations, response times, SLA performance, and teammate productivity.

#### Tags

- Analytics
- Reports

#### Properties

- [Documentation](https://dev.frontapp.com/reference/analytics)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Events API

Read the historical event stream for the company (assignments, replies, comments, tag changes) for audit and integration use.

#### Tags

- Events
- Audit

#### Properties

- [Documentation](https://dev.frontapp.com/reference/events)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Webhooks API

Subscribe to Front events (conversation.assigned, message.received, message.sent, comment.added) with HMAC-signed deliveries.

#### Tags

- Webhooks
- Subscriptions

#### Properties

- [Documentation](https://dev.frontapp.com/reference/webhooks)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](openapi/front-webhooks-asyncapi.yaml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Front Channels Platform API

Build custom messaging channels that bridge Front to proprietary messaging platforms (e.g. internal portals, niche chat networks).

#### Tags

- Channels
- Custom
- Platform

#### Properties

- [Documentation](https://dev.frontapp.com/reference/custom-channels-api)
- [OpenAPI](openapi/front-channel-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-channel-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-channel-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Plugin SDK

Build embedded UI applications that render inside the Front sidebar to surface third-party context alongside the conversation.

#### Tags

- Plugin
- Embedded UI

#### Properties

- [Documentation](https://dev.frontapp.com/docs/getting-started-with-plugins)
- [Postman Collection](collections/front-channel-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-channel-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Chat Widget

Embed Front's live chat widget on a website or web app to capture live conversations into shared inboxes.

#### Tags

- Chat Widget
- Web

#### Properties

- [Documentation](https://dev.frontapp.com/docs/chat-widget)
- [Postman Collection](collections/front-channel-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-channel-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Connectors

Low-code connector framework for invoking external HTTP APIs from within Front rules and workflows.

#### Tags

- Connectors
- Low-Code

#### Properties

- [Documentation](https://dev.frontapp.com/docs/connectors)
- [Postman Collection](collections/front-channel-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-channel-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Front Links API

Attach hyperlinks from external systems to Front conversations for cross-system traceability.

#### Tags

- Links
- External Resources

#### Properties

- [Documentation](https://dev.frontapp.com/reference/links)
- [OpenAPI](openapi/front-core-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/front-core-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/front-core-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/frontapp)
- [Website](https://front.com/)
- [Documentation](https://dev.frontapp.com/)
- [API Reference](https://dev.frontapp.com/reference)
- [Pricing](https://front.com/pricing)
- [Login](https://app.frontapp.com/)
- [Status Page](https://status.frontapp.com/)
- [Blog](https://front.com/blog)
- [Support](https://help.frontapp.com/)
- [GitHub Organization](https://github.com/frontapp)
- [Privacy Policy](https://front.com/legal/privacy-notice)
- [Terms of Service](https://front.com/legal/terms)
- [Authentication](https://dev.frontapp.com/docs/authentication)
- [Rate Limits](https://dev.frontapp.com/docs/rate-limiting)
- [Webhooks](https://dev.frontapp.com/reference/webhooks)
- [Plans](plans/front-plans-pricing.yml)
- [Rate Limits](rate-limits/front-rate-limits.yml)
- [Fin Ops](finops/front-finops.yml)
- [Features](undefined)
- [Integrations](https://front.com/integrations)
- [L L Ms Txt](https://dev.frontapp.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
