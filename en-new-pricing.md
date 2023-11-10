---

copyright:
  years: 2020, 2023
lastupdated: "2023-11-02"

keywords: event-notifications, event notifications, about event notifications pricing

subcollection: event-notifications

---
{{site.data.keyword.attribute-definition-list}}

# Event Notifications Pricing
{: #en-new-pricing}

## New Pricing effective from 1 November 2023

| Event Type    |        | Event Description |Price                                                                                                                                                                                                    |
| ------------------ | ----------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Incoming events    | Ingested events (all sources)       | An ingested event is one that is received and passed through a filter (including pass-all filters). If a source is connected to Event Notifications but no filters are defined for it (i.e. the source is not connected to any topics), the incoming events are dropped and you are not charged.  See the Event Notifications [documentation](/docs/event-notifications?topic=event-notifications-en-source) for a complete list of event sources. | $1.05 per million                                                                                                                                                                                                    |
|            Outbound HTTP        | Outbound HTTP notifications         | IBM supports outbound HTTP messages to IBM Cloud services like Object Storage and Code Engine, to third party destinations like Slack, ServiceNow, MSTeams and to generic webhook endpoints.  Commonly used to build automation and event-driven applications.  See the Event Notifications [documentation](/docs/event-notifications?topic=event-notifications-en-destination) for a complete list of destinations.                                        | $1.05 per million                                                                                                                                                                                                    |
|        Email            | Outbound email from cloud.ibm.com   | Emails from IBM Cloud services may be sent using IBM-owned domains and contain content generated by the IBM Cloud services.  Commonly used for cloud alerts.                                                                                                                                                                                                                             | $41.80 per million                                                                                                                                                                                                   |
|          Email          | Outbound email from your own domain |  If you would like to send emails from your application and containing your own content, you will need to set up a custom-domain email destination.  After setting this up, IBM will provide an IP address which you will need to add to your DNS record.  See the Event Notifications documentation for [details](/docs/event-notifications?topic=event-notifications-en-destinations-custom-email)                                                                | $150 per million messages<br>$0.12 per gigabyte                                                                                                                                                                      |
|          SMS          | Outbound SMS text messages          | IBM supports text messaging to 90+ countries. Notifications from IBM Cloud services may be sent using IBM-owned phone numbers.                                                                                                   | $15.70 per thousand SMS Units. See [price list by country](/docs/event-notifications?topic=event-notifications-en-destinations-sms#en-destinations-sms-charge)  |
|          Push Notifications          | Pre-production push destination     |  Limited to 500 devices or 5000 outbound digital messages. For testing and pre-production use.  Each target platform requires a destination.                                                                                                                                                                                                                                             | $15.70 per destination per month                                                                                                                                                                                        |
|            Push Notifications        | Production push destination         |  Unlimited devices and notifications.  For production use.  Each target platform requires a destination.                                                                                                                                                                                                                                                                                | $52.30 per destination per month                                                                                                                                                                                        |
|           Push Notifications         | Outbound push notifications         | Available for Android, iOS, Huawei devices, and Chrome, Firefox, Safari browsers.                                                                                                                                                                                                                                                                                                         | 0 - 10 Million: Free <br>10 Million - 110 Million: $1 per million <br>Above 110 Million: $0.5 per million  |





## Old Pricing valid till 31 October 2023 for reference

| Price and Unit                                              |
| ----------------------------------------------------------- |
| $1.05 USD/Million Ingested Events <br>$0.000001 USD/Outbound Digital Message HTTP <br>$0.000042 USD/Outbound Digital Message Email <br>$0.0157 USD/Outbound Digital Message SMS Unit <br>$52.30 USD/Push Destination Instance <br>$0.000002 USD/Outbound Digital Message Push <br>$15.70 USD/Push Pre-prod Destination Instance <br>$0.00015 USD/Outbound Digital Message Custom Domain Email <br>$0.12 USD/Gigabyte Transmitted Outbound Custom Domain Email |