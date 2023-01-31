---
copyright:
  years: 2023
lastupdated: "2023-01-31"

keywords: logging, LogDNA, platform logs
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

# Enabling logging on Planning Analytics as a Service
{: #enabling-logging}
{: step}
Planning Analytics as a Service logs message issued by the Planning Analtics database. You must configure a logging instance in the region where your Planning Analtics instance is running to monitor these logs.
{: shortdesc}

1. Log in to you IBM Cloud account.
1. On the IBM Cloud home page, click the **Navigation** menu.
1. Click **Observability**, then **Logging**.
1. On the Logging page, click **Options**, then **Create**.
1. On the IBM Log Analysis page, click the **Location** option and select the location where your Planning Analytics instance is provisioned.
1. Click Create to create a new logging instance.
1. Click **Configure platform logs**.
1. Click the **Configure instance by region** option and select the region where you just created the logging instance
1. Click the **Instances in location** option and select the logging instance you just created.
1. Click **Open dashboard** to monitor your logs.

For more information about using IBM Log Analysis to monitor logs, see [Monitoring logs in your account](https://cloud.ibm.com/docs/log-analysis?topic=log-analysis-monitor_logs).

For descriptions of Planning Analytics logging messages, see [Viewing the message log](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=log-viewing-tm1-server-message#ViewingtheTM1ServerMessageLog_N160908).
