---
copyright:
  years: 2023
lastupdated: "2023-01-31"

keywords:
subcollection: planning-analytics

content-type: tutorial
services:
account-plan: lite, enterprise
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

# Known issues and limitations
{: #Known issues and limitations}

Known issues and limitations includes a list of known issues and a list of functionality that is not available for this release.
{: shortdesc}

## Closed Beta
This Beta is open only to partners that have received an invitation and have accepted the terms of the Beta.

## V11 to V12 conversion
The contents of the **Applications** folder are not included.

## Model size restrictions
The Enterprise instances have a maximum of 64 GB of RAM and 400 GB of storage space. This quota is for the combination of all databases in the production and non-production environments.

## Flat file load & export
- Only drag and drop (browse) is available.
- Limited to files smaller than 500 MB.
- Limited to CSV or TXT files.
- You can create flat files through a TI process. You cannot retrieve the files from the repository.

## REST API connection
The REST API will not be exposed for the Beta.

## ODBC connection
- New ODBC connection technology is included: **ODBCIS**.
- A new Windows-only client requires installation and setup.
- A new configuration parameter has been exposed: **ODBCServiceRoot**.
- ODBCServiceRoot accepts a URL. This connects the TM1 server with the ODBCIS client.


## Log file access
No logs available.

## Known issues for Planning Analytics for Excel
This release of {{site.data.keyword.planninganalytics_short}} (Beta) includes the following list of known issues:
{: shortdesc}
- You can connect through PAfE.
- You can publish websheets.
- Custom report accessory functions. For more information, see **Worksheet function limitations** below.

## Known issues for Planning Analytics Spreadsheet Services
This release of {{site.data.keyword.planninganalytics_short}} (Beta) includes the following list of known issues:
{: shortdesc}
- Action button's TI step.
- Exports.
- Spreading via UI (spread codes should work).
- Drill UI.
- Custom report accessory functions. For more information, see **Worksheet function limitations** below.
- Medium and large Websheets might be slow or not open.
- Sandboxes/sandbox UI (commit data & reset data).
- In cell UI's/picklist.
- Undo/Redo (all reports).
- PAW synchronization.
- Add/browse comments.
- Holds-Context menu options.
- Subset UDC's not supported TM1.
- Subnm element selection drop down not supported.
- Websheets without an extension will only open when dragged and dropped.

## Worksheet function limitations
The following worksheet functions are not available for this release:
{: shortdesc}
- DBSA
- DFRST
- DIMIX
- DIMNM
- DIMSIZ
- DNEXT
- DNLEV
- DTYPE
- ELCOMP
- ELCOMPN
- ELISCOMP
- ELISPAR
- ELLEV
- ELPAR
- ELPARN
- ELSLEN
- ELWEIGHT
- SUBSIZ
- DBS
- DBSS
- DBSW
- DBRA
- TM1USER
- TABDIM
- TM1ELLIST
