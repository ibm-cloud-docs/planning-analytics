---
copyright:
  years: 2023, 2024
lastupdated: "2024-05-28"

keywords: event, auditing, platform events, service events

subcollection: #planning-analytics

---

{{site.data.keyword.attribute-definition-list}}

<!-- Make sure that the AT events file has the H1 ID set to: {: #at_events} -->

# Auditing events for {{site.data.keyword.PA_SaaS_short}}
{: #at_events}

As a security officer, auditor, or manager, you can use the {{site.data.keyword.at_full}} service to track how users and applications interact with the {{site.data.keyword.PA_SaaS_short}} service in {{site.data.keyword.cloud_notm}}.
{: shortdesc}

{{site.data.keyword.at_full_notm}} records user-initiated activities that change the state of a service in {{site.data.keyword.cloud_notm}}. You can use this service to investigate abnormal activity and critical actions and to comply with regulatory audit requirements. In addition, you can be alerted about actions as they happen. The events that are collected comply with the Cloud Auditing Data Federation (CADF) standard. For more information, see the [getting started tutorial for {{site.data.keyword.at_full_notm}}](/docs/activity-tracker?topic=activity-tracker-getting-started).

<!--As of 28 March 2024, the {{site.data.keyword.at_full_notm}} service is deprecated and will no longer be supported as of 30 March 2025. Customers will need to migrate to {{site.data.keyword.logs_full_notm}} before 30 March 2025. During the migration period, customers can use {{site.data.keyword.at_full_notm}} along with {{site.data.keyword.logs_full_notm}}. Activity tracking events are the same for both services. For information about migrating from {{site.data.keyword.at_full_notm}} to {{site.data.keyword.logs_full_notm}} and running the services in parallel, see [migration planning](/docs/cloud-logs?topic=cloud-logs-migration-intro).
{: important}-->

## List of platform events
{: #at_actions_platform}

The following table lists the actions that generate a platform event:

| Action                                   | Description |
|------------------------------------------|---------|
| `planning-analytics.instance.create`           | An event is generated when you provision a service instance. |
| `planning-analytics.instance.update`           | An event is generated when you rename a service instance or when you change the service plan. |
| `planning-analytics.instance.delete`           | An event is generated when a service instance is deleted. |
| `planning-analytics.instance.schedule_reclaim` | An event is generated when a service instance is pending_reclamation. |
| `planning-analytics.instance.restore`          | An event is generated when a service instance is restored. |
{: caption="Table 1. Actions that generate platform events" caption-side="bottom"}

The following table lists the actions that generate an event for managing service credentials that are associated to a service instance:

| Action                         | Description |
|--------------------------------|---------|
| `planning-analytics.key.create` | An event is generated when an API key is created for a service instance through the *Service credentials* section of the service instance UI. |
| `planning-analytics.key.delete` | An event is generated when an API key that is associated with a service instance is deleted from the *Service credentials* section of the service instance UI. |
{: caption="Table 2. Actions that generate service credentials events" caption-side="bottom"}

## List of management events
{: #at_actions}

The following table lists the {{site.data.keyword.PA_SaaS_short}} actions that generate a management event:

| Action             | Description      |
|--------------------|------------------|
| `planning-analytics.group.added` | An event is generated when a group is added to the planning analytics workspace instance.   |
| `planning-analytics.group.deleted` | An event is generated when a group is deleted from the planning analytics workspace instance.  |
| `planning-analytics.group.updated` | An event is generated when the membership of a group is updated in the planning analytics workspace instance.   |
| `planning-analytics.user.added` | An event is generated when a user is added to the planning analytics workspace instance.   |
| `planning-analytics.user.deleted` | An event is generated when a user is deleted from the planning analytics workspace instance.   |
| `planning-analytics.user.login` | An event is generated when a user logs into the Planning Analytics Workspace instance.   |
| `planning-analytics.user.logout` | An event is generated when a user logs out of the Planning Analytics Workspace instance.   |
| `planning-analytics.user-environment.switch` | An event is generated when a user switches to a different Planning Analytics Workspace environment.   |
| `planning-analytics.user.updated` | An event is generated when a user is updated in the planning analytics workspace instance.   |
| `planning-analytics.tm1.create` | An event is generated when you create a tm1 database.  |
| `planning-analytics.tm1.start` | An event is generated when you start a tm1 database.  |
{: caption="Table 3. Actions that generate management events" caption-side="bottom"}

## List of data events
{: #at_actions_data}

The following table lists the {{site.data.keyword.PA_SaaS_short}} actions that generate a data event:

| Action             | Description      |
|--------------------|------------------|
| `planning-analytics.content.acl.modified` | An event is generated when access control to a planning analytics workspace object is modified.  |
| `planning-analytics.content.created` | An event is generated when a planning analytics workspace object is created.  |
| `planning-analytics.content.deleted` | An event is generated when a planning analytics workspace object is deleted.   |
| `planning-analytics.content.moved` | An event is generated when a planning analytics workspace object is moved.   |
{: caption="Table 4. Actions that generate data events" caption-side="bottom"}

## Viewing events
{: #at_ui}

Events that are generated by an instance of the {{site.data.keyword.PA_SaaS_short}} service are automatically forwarded to the {{site.data.keyword.at_full_notm}} service instance that is available in the same location.

{{site.data.keyword.at_full_notm}} can have only one instance per location. To view events, you must access the web UI of the {{site.data.keyword.at_full_notm}} service in the same location where your service instance is available. For more information, see [Launching the UI](/docs/activity-tracker?topic=activity-tracker-launch).
