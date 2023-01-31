---
copyright:
  years: 2023
lastupdated: "2023-01-31"

keywords: activity tracking, user events, platform events
subcollection: planning-analytics

content-type: howto
services:
account-plan: lite
completion-time: 15m

---

{:codeblock: .codeblock}
{:note: .note}
{:pre: .pre}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:table: .aria-labeledby="caption"}
{:tip: .tip}
{:video: .video}
{:external: target="_blank" .external}
{:step: data-tutorial-type='step'}

# Enabling activity tracking on {{site.data.keyword.PA_SaaS_short}}
{: #enabling-activity-tracking}
{: step}

{{site.data.keyword.PA_SaaS_short}} uses the IBM Activity Tracker service to capture user actions and relevant security events. You must configure an Activity Tracker instance in the region where your Planning Analtics instance is running to monitor these events.
{: shortdesc}

1. Log in to you IBM Cloud account.
1. On the IBM Cloud home page, click the **Navigation** menu.
1. Click **Observability**, then **Activity Tracker**.
1. On the Activity Tracker page, click **Create**.
1. On the IBM Cloud Activity Tracker page, click the **Location** option and select the location where your Planning Analytics instance is provisioned.
1. Click **Create** to create a new logging instance.
1. Click **Configure platform logs**.
1. Click the **Configure instance by region** option and select the region where you just created the logging instance
1. Click the **Instances in location** option and select the logging instance you just created.
1. Click **Open dashboard** to track avtivity.
