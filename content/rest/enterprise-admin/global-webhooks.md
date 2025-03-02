---
title: Global Webhooks
intro: 'Use the REST API to manage global webhooks for your enterprise.'
versions:
  ghes: '*'
  ghae: '*'
topics:
  - API
miniTocMaxHeadingLevel: 3
---

## About global webhooks

These endpoints are only available to [authenticated](/rest/overview/resources-in-the-rest-api#authentication) site administrators Normal users will receive a `404` response. To learn how to configure global webhooks, see [About global webhooks](/enterprise/admin/user-management/about-global-webhooks).

Global webhooks are automatically installed on your enterprise. You can use global webhooks to automatically monitor, respond to, or enforce rules for users, organizations, teams, and repositories on your enterprise.

Global webhooks can subscribe to the [organization](/developers/webhooks-and-events/webhook-events-and-payloads#organization), [user](/developers/webhooks-and-events/webhook-events-and-payloads#user), [repository](/developers/webhooks-and-events/webhook-events-and-payloads#repository), [team](/developers/webhooks-and-events/webhook-events-and-payloads#team), [member](/developers/webhooks-and-events/webhook-events-and-payloads#member), [membership](/developers/webhooks-and-events/webhook-events-and-payloads#membership), [fork](/developers/webhooks-and-events/webhook-events-and-payloads#fork), and [ping](/developers/webhooks-and-events/about-webhooks#ping-event) event types.

{% data reusables.user-settings.enterprise-admin-api-classic-pat-only %}
