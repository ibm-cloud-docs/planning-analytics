---

copyright:
  years: 2024
lastupdated: "2024-02-20"

keywords: Planning Analytics release notes

subcollection: planning-analytics

content-type: release-note

---

<!-- {: release-note: data-hd-content-type='release-note'}-->

{{site.data.keyword.attribute-definition-list}}
<!-- You must add the release-note content type in your attribute definitions AND to each release note H2. This ensures that the release note entry is pulled into the notifications library.  -->

# Release notes for {{site.data.keyword.PA_SaaS_short}}
{: #planning-analytics-relnotes}

Use these release notes to learn about the latest updates to {{site.data.keyword.PA_SaaS_short}}, grouped by date. Release notes are available for a minimum of three years. All updates to components within {{site.data.keyword.PA_SaaS_short}} are cumulative and include new features and fixes from prior releases.
{: shortdesc}

<!--
## How should I set up my release notes page?
{: #relnotes-page-setup}
{: release-note}

* Use "Release notes for xxx" as your page title, where xxx is the short name with no trademarks.
* Name the file `release-notes.md` for URL readability.
* If you require multiple release notes files, group under a "Release Notes" topicgroup and use a unique name for each file.
* Add each release as an H2 or H3, depending on how frequently your service releases updates. If you release monthly or less, use an H2 for each entry. If you release several times a month, use an H2 with the month to group each H3 entry in that month.
* The first entry in your release notes file should introduce your service and reflect the release date of the service.
* Use a definition list entry for each update, change, or new item in that release.
* Set the `release-note` content type attribute definition at the top of your file.
* Set the `release-note` content type attribute on a new line following each H2 release entry.
* Do not repeat task steps. Summarize and link to task topic.
* Do not include security bulletins or maintenance notifications in this file. There is a separate process for these types of notifications.

## What should I include in my release note entries?
{: #release-notes-content-include}
{: release-note}

Use a definition list to highlight each item covered in the release. Each entry should summarize the release details. You want to make sure you are not re-documenting information that is already available in documentation because then you'd have to maintain it in two places. If a more detailed explanation for the change exists out in a documentation page, then link out to the doc. For guidance on coding definition lists, [Definition lists](https://test.cloud.ibm.com/docs/writing?topic=writing-lists#definition-lists).

Because this content is single-sourced and pulled into the Status UI, you can only include the following markup in your definition list entries: paragraph, ordered list item, unordered list item, code phrase, links, keyrefs, bold, and italics. Any other markup is not supported.

For guidance on what to include on this page, review [Release notes guidance](https://test.cloud.ibm.com/docs/writing?topic=writing-releasenotes). -->

## 20 February 2024
{: #planning-analytics-feb2024}
{: release-note}

Planning Analytics Workspace update
:   Planning Analytics Workspace within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.93.

:   For more information on new and changed features in Planning Analytics Workspace, see [What's new in Planning Analytics Workspace](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=wnipaw-2093-whats-new-february-20-2024). To see which issues were fixed in this Planning Analytics Workspace update, review the [Planning Analytics Workspace 2.0.93 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_workspace_2093_sc-3.pdf).

Planning Analytics for Microsoft Excel update
:   Planning Analytics for Microsoft Excel within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.93.

:   For more information on new and changed features in Planning Analytics for Microsoft Excel, see [What's new in Planning Analytics for Microsoft Excel](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=wnipame-2093-feature-updates-february-9-2024). To see which issues were fixed in this Planning Analytics for Microsoft Excel update, review the [Planning Analytics for Microsoft Excel 2.0.93 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_for_msexcel_2093_sc%20.pdf).

Planning Analytics Spreadsheet Services update
:   Planning Analytics Spreadsheet Services/TM1 Web within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.93.

:   For more information on new and changed features in Planning Analytics Spreadsheet Services/TM1 Web, see [What's new in Planning Analytics Spreadsheet Services](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=wnitw-2093-feature-updates-february-9-2024). To see which issues were fixed in this Planning Analytics Spreadsheet Services update, review the [Planning Analytics Spreadsheet Services 2.0.93 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_spreadsheet_services_2093_sc.pdf).

Planning Analytics Engine update
:   Planning Analytics Engine within {{site.data.keyword.PA_SaaS_short}} has been updated to version 12.3.8. 

:   To see which issues were fixed in this Planning Analytics Engine update, review the [Planning Analytics Engine 12.3.8 fix list](https://www.ibm.com/support/pages/ibm-planning-analytics-20-fix-lists#anchor4).

Improved availability of manual database backups in Planning Analytics Workspace on Planning Analytics as a Service
:   A new location for manual database backups in Planning Analytics Workspace on Planning Analytics as a Service makes it easier to access and use backups.

:   Prior to Planning Analytics Workspace 2.0.93, manual database backups were stored in the .backupsets directory of File Manager on the Modeling Workbench, which is within the Planning Analytics Workspace database. This location made it impossible to access manual backups when the database was unavailable.

:   Conversely, automated database backups were stored to a location external to the database, which remains accessible even when the associated Planning Analytics Workspace database is unavailable.

:   As of Planning Analytics Workspace 2.0.93, both manual and automated database backups in Planning Analytics Workspace on Planning Analytics as a Service are stored in a location external to the database. All manual backups created in Planning Analytics Workspace 2.0.93 or later and all automated backups appear on the database Backups tab, regardless of the current state of the database.

:   This change means that manual backups created prior to Planning Analytics Workspace 2.0.93 and stored in File Manager no longer appear on the Backups tab. You can, however, continue to access any such backups directly through File Manager.


## 21 December 2023
{: #planning-analytics-dec2123}
{: release-note}

Planning Analytics Engine update
:   Planning Analytics Engine within {{site.data.keyword.PA_SaaS_short}} has been updated to version 12.3.7. 

:   To see which issues were fixed in this Planning Analytics Engine update, review the [Planning Analytics Engine 12.3.7 fix list](https://www.ibm.com/support/pages/system/files/inline-files/IBM%20Planning%20Analytics%20Engine%2012.3.7%20Fix%20List.pdf).

## 11 December 2023
{: #planning-analytics-dec1123}
{: release-note}

Planning Analytics Workspace update
:   Planning Analytics Workspace within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.92.

:   For more information on new and changed features in Planning Analytics Workspace, see [What's new in Planning Analytics Workspace](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=wnipaw-2092-whats-new-december-12-2023). To see which issues were fixed in this Planning Analytics Workspace update, review the [Planning Analytics Workspace 2.0.92 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_workspace_2092_sc.pdf).

Planning Analytics for Microsoft Excel update
:   Planning Analytics for Microsoft Excel within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.92.

:   For more information on new and changed features in Planning Analytics for Microsoft Excel, see [What's new in Planning Analytics for Microsoft Excel](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=wnipame-2092-feature-updates-december-11-2023). To see which issues were fixed in this Planning Analytics for Microsoft Excel update, review the [Planning Analytics for Microsoft Excel 2.0.92 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_for_msexcel_2092_sc.pdf).

Planning Analytics Spreadsheet Services update
:   Planning Analytics Spreadsheet Services/TM1 Web within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.92.

:   For more information on new and changed features in Planning Analytics Spreadsheet Services/TM1 Web, see [What's new in Planning Analytics Spreadsheet Services](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=wnitw-2092-feature-updates-december-11-2023). To see which issues were fixed in this Planning Analytics Spreadsheet Services update, review the [Planning Analytics Spreadsheet Services 2.0.92 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_spreadsheet_services_2092_sc.pdf).

Planning Analytics Engine update
:   Planning Analytics Engine within {{site.data.keyword.PA_SaaS_short}} has been updated to version 12.3.5. 

:   For more information on new and changed features in Planning Analytics Engine, see [What's new in Planning Analytics Engine](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=engine-1235-whats-new-december-11-2023). To see which issues were fixed in this Planning Analytics Engine update, review the [Planning Analytics Engine 12.3.5 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_engine_1235.pdf).

## 30 October 2023
{: #planning-analytics-oct3023}
{: release-note}

Planning Analytics Workspace update
:   Planning Analytics Workspace within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.91.

:   For more information on new and changed features in Planning Analytics Workspace, see [What's new in Planning Analytics Workspace](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=workspace-2091-whats-new-october-30-2023). To see which issues were fixed in this Planning Analytics Workspace update, review the [Planning Analytics Workspace 2.0.91 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_workspace_2091_sc-1.pdf).

Planning Analytics for Microsoft Excel update
:   Planning Analytics for Microsoft Excel within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.91.

:   For more information on new and changed features in Planning Analytics for Microsoft Excel, see [What's new in Planning Analytics for Microsoft Excel](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=excel-2091-feature-updates-october-30-2023). To see which issues were fixed in this Planning Analytics for Microsoft Excel update, review the [Planning Analytics for Microsoft Excel 2.0.91 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_for_msexcel_2091_sc.pdf).

Planning Analytics Spreadsheet Services update
:   Planning Analytics Spreadsheet Services/TM1 Web within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.91.

:   For more information on new and changed features in Planning Analytics Spreadsheet Services/TM1 Web, see [What's new in Planning Analytics Spreadsheet Services](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=web-2091-feature-updates-october-30-2023). To see which issues were fixed in this Planning Analytics Spreadsheet Services update, review the [Planning Analytics Spreadsheet Services 2.0.91 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_spreadsheet_services_2091_sc.pdf).

Planning Analytics Engine update
:   Planning Analytics Engine within {{site.data.keyword.PA_SaaS_short}} is version 12.3.4. To see which issues were fixed in this Planning Analytics Engine update, review the [Planning Analytics Engine 12.3.4 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_engine_1234.pdf).

## 05 October 2023
{: #planning-analytics-oct0523}
{: release-note}

Planning Analytics Engine update
:   Planning Analytics Engine within {{site.data.keyword.PA_SaaS_short}} is version 12.3.3. To see which issues were fixed in this Planning Analytics Engine update,review the [Planning Analytics Engine 12.3.3 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_engine_1233.pdf).


## 25 July 2023
{: #planning-analytics-jul2523}
{: release-note}

Planning Analytics Workspace update
:   Planning Analytics Workspace within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.89.

:   For more information on new and changed features in Planning Analytics Workspace 2.0.89, see [What's new in Planning Analytics Workspace](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=wnipaw-2089-whats-new-july-24-2023). To see which issues were fixed in this Planning Analytics Workspace update, review the [Planning Analytics Workspace 2.0.89 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_workspace_2089_sc.pdf).

Planning Analytics for Microsoft Excel update
:   Planning Analytics for Microsoft Excel within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.89.

:   For more information on new and changed features in Planning Analytics for Microsoft Excel, see [What's new in Planning Analytics for Microsoft Excel](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=wnipame-2089-feature-updates-july-17-2023). To see which issues were fixed in this Planning Analytics for Microsoft Excel update, review the [Planning Analytics for Microsoft Excel 2.0.89 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_for_msexcel_2089_sc.pdf).

Planning Analytics Engine update
:   Planning Analytics Engine within {{site.data.keyword.PA_SaaS_short}} is version 12.3.0.

## 21 June 2023
{: #planning-analytics-jun2123}
{: release-note}

Planning Analytics Workspace update
:   Planning Analytics Workspace within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.88.

:   For more information on new and changed features in Planning Analytics Workspace 2.0.88, see [What's new in Planning Analytics Workspace](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=workspace-2088-whats-new-june-21-2023). To see which issues were fixed in this Planning Analytics Workspace update, review the [Planning Analytics Workspace 2.0.88 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_workspace_2088_sc.pdf).

Planning Analytics Spreadsheet Services update
:   Planning Analytics Spreadsheet Services/TM1 Web within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.88.

:   For more information on new and changed features in Planning Analytics Spreadsheet Services/TM1 Web version 2.0.88, see [What's new in Planning Analytics Spreadsheet Services](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=web-2088-feature-updates-june-16-2023). To see which issues were fixed in this Planning Analytics Spreadsheet Services update, review the [Planning Analytics Spreadsheet Services 2.0.88 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_spreadsheet_services_2088_sc.pdf).

Planning Analytics Engine update
:   Planning Analytics Engine within {{site.data.keyword.PA_SaaS_short}} is version 12.2.0.

## 16 May 2023
{: #planning-analytics-may1623}
{: release-note}

Planning Analytics Workspace update
:   Planning Analytics Workspace within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.87.

:   For more information on new and changed features in Planning Analytics Workspace 2.0.87, see [What's new in Planning Analytics Workspace](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=wnipaw-2087-whats-new-may-16-2023). To see which issues were fixed in this Planning Analytics Workspace update, review the [Planning Analytics Workspace 2.0.87 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_workspace_2087_sc.pdf).

Planning Analytics Spreadsheet Services update
:   Planning Analytics Spreadsheet Services/TM1 Web within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.87.

:   For more information on new and changed features in Planning Analytics Spreadsheet Services/TM1 Web, see [What's new in Planning Analytics Spreadsheet Services](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=wnitw-2087-feature-updates-may-12-2023). To see which issues were fixed in this Planning Analytics Spreadsheet Services update, review the [Planning Analytics Spreadsheet Services 2.0.87 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_spreadsheet_services_2087_sc.pdf).

Planning Analytics Engine update
:   Planning Analytics Engine within {{site.data.keyword.PA_SaaS_short}} has been updated to version 12.2.0.


## 18 April 2023
{: #planning-analytics-apr1823}
{: release-note}

Planning Analytics Workspace update
:   Planning Analytics Workspace within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.86.

:   For more information on new and changed features in Planning Analytics Workspace 2.0.86, see [What's new in Planning Analytics Workspace](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=wnipaw-2086-whats-new-april-18-2023). To see which issues were fixed in this Planning Analytics Workspace update, review the [Planning Analytics Workspace 2.0.86 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_workspace_2086_sc.pdf).

Planning Analytics Spreadsheet Services update
:   Planning Analytics Spreadsheet Services/TM1 Web within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.86.

:   For more information on new and changed features in Planning Analytics Spreadsheet Services/TM1 Web, see [What's new in Planning Analytics Spreadsheet Services](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=wnitw-2086-feature-updates-april-11-2023). To see which issues were fixed in this Planning Analytics Spreadsheet Services update, review the [Planning Analytics Spreadsheet Services 2.0.86 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_spreadsheet_services_2086_sc.pdf).

Planning Analytics Engine update
:   Planning Analytics Engine within {{site.data.keyword.PA_SaaS_short}} has been updated to version 12.1.1.

:   To see which issues were fixed in this Planning Analytics Engine update, review the [Planning Analytics Engine 12.1.1 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_engine_1211.pdf).

## 22 March 2023
{: #planning-analytics-mar2223}
{: release-note}

Planning Analytics Workspace update
:   Planning Analytics Workspace within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.85.

:   For more information on new and changed features in Planning Analytics Workspace 2.0.85, see [What's new in Planning Analytics Workspace](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=wnipaw-2085-whats-new-march-22-2023). To see which issues were fixed in this Planning Analytics Workspace update, review the [Planning Analytics Workspace 2.0.85 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_workspace_2085_sc.pdf).

## 28 February 2023
{: #planning-analytics-feb2823}
{: release-note}

Planning Analytics Workspace update
:   Planning Analytics Workspace within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.84.

:   For more information on new and changed features in Planning Analytics Workspace 2.0.84, see [What's new in Planning Analytics Workspace](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=wnipaw-2084-whats-new-february-16-2023). To see which issues were fixed in this Planning Analytics Workspace update, review the [Planning Analytics Workspace 2.0.84 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_workspace_2084_sc.pdf).

Planning Analytics Spreadsheet Services update
:   Planning Analytics Spreadsheet Services/TM1 Web within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.83.

:   For more information on new and changed features in Planning Analytics Spreadsheet Services/TM1 Web, see [What's new in Planning Analytics Spreadsheet Services](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=web-2083-feature-updates-february-17-2023). To see which issues were fixed in this Planning Analytics Spreadsheet Services update, review the [Planning Analytics Spreadsheet Services 2.0.83 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_spreadsheet_services_2083_sc-1.pdf).

Planning Analytics for Microsoft Excel update
:   Planning Analytics for Microsoft Excel within {{site.data.keyword.PA_SaaS_short}} has been updated to version 2.0.83.

:   For more information on new and changed features in Planning Analytics for Microsoft Excel, see [What's new in Planning Analytics for Microsoft Excel](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=excel-2083-feature-updates-february-10-2023). To see which issues were fixed in this Planning Analytics for Microsoft Excel update, review the [Planning Analytics for Microsoft Excel 2.0.83 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_for_msexcel_2083_sc.pdf).

Planning Analytics Engine update
:   Planning Analytics Engine within {{site.data.keyword.PA_SaaS_short}} has been updated to version 12.0.1.

:   To see which issues were fixed in this Planning Analytics Engine update, review the [Planning Analytics Engine 12.0.1 fix list](https://www.ibm.com/support/pages/system/files/inline-files/ibm_fixlist_planning_analytics_engine_1201.pdf).

## 31 January 2023
{: #planning-analytics-jan3123}
{: release-note}

Introducing {{site.data.keyword.PA_SaaS_short}}.
:   {{site.data.keyword.PA_SaaS_short}} is a a fully-managed planning, analytics, profitability, modeling, and reporting solution. These applications are supported by the Planning Analytics in-memory database that provides on-demand analytics of complex multidimensional data in real time.
