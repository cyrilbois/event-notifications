---

copyright:
  years: 2019, 2021
lastupdated: "2021-09-06"

keywords: event notifications activity tracker events, event notifications events, event notifications audit, event notifications audit events, event notifications audit logs

subcollection: event notifications

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:codeblock: .codeblock}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:deprecated: .deprecated}
{:download: .download}
{:preview: .preview}

# Auditing events
{: #en-at_events}

As a security officer, auditor, or manager, you can use the {{site.data.keyword.at_full_notm}} service to track how users and applications interact with the {{site.data.keyword.en_short}} service in {{site.data.keyword.Bluemix_notm}}.
{: shortdesc}

{{site.data.keyword.at_full_notm}} records user-initiated activities that change the state of a service in {{site.data.keyword.cloud_notm}}. You can use this service to investigate abnormal activity and critical actions and to comply with regulatory audit requirements. In addition, you are alerted about actions as they happen. The events that are collected comply with the Cloud Auditing Data Federation (CADF) Standard. For more information, see the [getting started tutorial for {{site.data.keyword.at_full_notm}}](/docs/activity-tracker?topic=activity-tracker-getting-started).

## List of events
{: #en-events}

The following list of {{site.data.keyword.en_short}} data events are sent to {{site.data.keyword.at_full_notm}}.


| Action             | Description      |
| -------------------| -----------------|
| `event-notifications.topics.read` | Retrieved a topic or failed to read|
| `event-notifications.topics.create` | Created a topic or failed to create |
| `event-notifications.topics.list` | Retrieved the list of topics or failed to list topics|
| `event-notifications.topics.update` | Updated a topic or failed to update|
| `event-notifications.destinations.read` | Retrieved a destination or failed to retrieve|
| `event-notifications.destinations.create` | Created a destination or failed to create  |
| `event-notifications.destinations.list` | Retrieved the list of destinations or failed to list|
| `event-notifications.destinations.update` | Updated a destination or failed to update|
| `event-notifications.sources.read` | Retrieved a source or failed to read |
| `event-notifications.sources.create`|Created a source or failed to create|
| `event-notifications.sources.list`| Retrieved the list of sources or failed to list sources|
| `event-notifications.sources.update` | Updated a source or failed to update |
| `event-notifications.subscriptions.read` | Retrieved a subscription or failed to read|
| `event-notifications.subscriptions.create` | Created a subscription or failed to create|
| `event-notifications.subscriptions.list` | Retrieved the list of subscriptions or failed to list subscriptions|
| `event-notifications.subscriptions.update` | Updated a subscription or failed to update|
| `event-notifications.event_categories.read`| Retrieved an event or failed to read|
| `event-notifications.event_categories.create` | Created an event or failed to create|
| `event-notifications.event_categories.list` | Retrieved the list of events or failed to list|
| `event-notifications.event_categories.update`|Updated an event or failed to update|

{: caption="Table 1. Overview of {{site.data.keyword.en_short}} actions that generate {{site.data.keyword.at_full_notm}} events" caption-side="top"}


## Viewing events
{: #at_ui}

Events that are generated by {{site.data.keyword.en_short}} are automatically forwarded to the {{site.data.keyword.at_full_notm}} service instance available in the same location.

{{site.data.keyword.at_full_notm}} can have only one instance per location. To view events, you must access the web UI of the I{{site.data.keyword.at_full_notm}} service in the same location where your service instance is available.

1. Create a service instance of [{{site.data.keyword.at_full_notm}}](/docs/activity-tracker?topic=activity-tracker-getting-started).
2. [Launch the {{site.data.keyword.at_full_notm}} web console](/docs/activity-tracker?topic=activity-tracker-launch) to access your events.