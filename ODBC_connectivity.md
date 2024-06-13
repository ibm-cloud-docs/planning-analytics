---
copyright:
  years: 2023
lastupdated: "2023-01-31"

keywords:
subcollection: planning-analytics

content-type: learn

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

# Enabling ODBC connectivity
{: #ODBC_connectivity}

ODBC connectivity in {{site.data.keyword.PA_SaaS_full}} is provided by the Planning Analytics ODBC Data Connector.

The Planning Analytics ODBC Data Connector (sometimes referred to as ODBCIS) transforms local ODBC data sources to an OData compliant REST API service that can be used by the Planning Analytics Engine database. You can use this service as the ODBC data source for TurboIntegrator processes in {{site.data.keyword.planninganalytics_short}}. You can use processes to import data, create and maintain metadata/objects, and manage security on your Planning Analytics Engine database.

To use  the ODBCServiceRoot configuration parameter to specity the location of the service, complete the following steps:

1. On the Planning Analytics Workspace home page, click the **Administration** tile.

2. Click the **Databases** tile.

3. Select the database on which you want to set the ODBCDerviceRoot configuration parameter.

4. Click the **Configuration** tab.

5. Select **External Database**.

6. Enter the URL provided by the ODBC Data Connector in the **ODBCServiceRoot parameter** text box.










For more information on using the Planning Analytics ODBC Data Connector to make on-prem data available to the Planning Analytics Engine in Planning Analytics as a Service, see [Using the IBM® Planning Analytics Data Connector](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=engine-using-planning-analytics-odbc-data-connector).

For more information on using TurboIntegrator processes to import and manipulate data from an external data source, see [TurboIntegrator processes](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=mipaw-turbointegrator-processes).
