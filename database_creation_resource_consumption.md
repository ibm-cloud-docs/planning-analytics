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

# Creating a database
{: #Database_creation_resource_consumption}

Your service instance of {{site.data.keyword.planninganalytics_short}} does not come with a pre-created database. To create a database, complete the following steps:

1. On the Planning Analytics Workspace home page, click **Administration**.

2. Click the  **Databases** tile.

3. Click **Add**.

4. A new dialog will appear. Specify the appropriate database configuration.

    - Each Database requires its own storage space.
    - Replicas enable High Availability. A value of 1 represents no High Availability and a value of 2 or more enables High Availability.
    - Overall RAM used is represented by the amount of Selected Memory (GB) multiplied by the number of Replicas. For example, 8 GB with 2 replicas means 16 GB in total will be in use.

5. Once you have set up the configuration, click **Create**.
