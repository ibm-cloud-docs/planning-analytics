---

copyright:
  years: 2023
lastupdated: "2023-03-12"

keywords: logging, log analysis

subcollection: planning-analytics

---

{{site.data.keyword.attribute-definition-list}}

# Logging for {{site.data.keyword.PA_SaaS_short}}
{: #logging}

After you provision {{site.data.keyword.PA_SaaS_short}} to add log management capabilities to your {{site.data.keyword.cloud}} architecture, you can enable platform logs to view and analyze {{site.data.keyword.PA_SaaS_short}} logs.
{: shortdesc}

## Platform logs
{: #logging_ov}

Platform logs are logs that are exposed by logging-enabled services and the platform in {{site.data.keyword.cloud_notm}}. You must configure a {{site.data.keyword.la_short}} instance in a region to monitor these logs.

For more information, see [Configuring IBM Cloud platform logs](/docs/log-analysis?topic=log-analysis-config_svc_logs).

## Viewing logs
{: #logging_view}

{{site.data.keyword.PA_SaaS_short}} services generate platform logs in the same region where they are available. You can view, monitor, and manage {{site.data.keyword.PA_SaaS_short}} logs through the {{site.data.keyword.la_full_notm}} instance that is marked as **platform logs** in the region.

To launch the {{site.data.keyword.la_short}} web UI to view these logs, see [Navigating to the web UI](/docs/log-analysis?topic=log-analysis-launch).

For more information about the locations where {{site.data.keyword.PA_SaaS_short}} logs are available, see [IBM Cloud services that generate IBM Log Analysis logs by location](/docs/log-analysis?topic=log-analysis-cloud_services_locations#cs_locations_analytics).

## Fields per log type
{: #logging_fields}

Table 1 outlines the fields that are included in each log record:

| Field             | Type       | Description             |
|-------------------|------------|-------------------------|
| `Thread ID`       | Required   | ID number of the thread in the TM1 server that generated the logging event. Example: 2488 |
| `Message Level`   | Required   | Severity level of the message being reported: DEBUG, INFO, WARN, ERROR, or FATAL |
| `Date and Time`   | Required   | Date and time the message was logged, reported in the format: yyyy-mm-dd hh:mm.ss,millisecond.|
| `messageID`       | Required   | ID of the log that is generated. |
| `TM1 Logger Name` | Required   | Name of the TM1 sub-component that generated the message or activity. |
| `Message Text`    | Required   | Pre-defined text message that describes the error or activity being reported. |
{: caption="Table 1. Log record fields" caption-side="bottom"}
