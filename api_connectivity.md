---
copyright:
  years: 2023
lastupdated: "2023-07-11"

keywords:
subcollection: planning-analytics

content-type: howto

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



# Establishing API connectivity for {{site.data.keyword.PA_SaaS_short}}
{: #api_connectivity}

This document outlines the steps required to achieve connectivity to a {{site.data.keyword.PA_SaaS_short}} instance via the OData API.

## Retrieve API key from IBM Cloud

In this section, you will retrieve an API key from IBM Cloud.

1. Log in to [IBM Cloud](https://cloud.ibm.com/).

2. Click the **Manage** menu, and then select **Access (IAM)**.

3. Click **API keys**.

4. Click on **Create an IBM Cloud API key**.

5. Copy the API key or click **Download** to save it. After the time frame indicated on the screen, the API key will expire, and you will not be able to retrieve it again. If you fail to retrieve the key, or lose it, you will be required to make a new one.

## Retrieve access token from IBM Cloud

In this section, you will use the API key you retrieved to retrieve an access token from IBM Cloud.

1. Open a terminal.

2. Create a variable for the API key.
    - Enter this command into the terminal: `PAW_API_KEY="(your API key)"`.
    - This will be used to retreive an acccess token in the next step.

3. Generate an access token.
    - Enter this command into the terminal: `ACCESS_TOKEN=$(curl https://iam.cloud.ibm.com/identity/token -H 'Accept: application/json' -d 'grant_type=urn:ibm:params:oauth:grant-type:apikey&apikey+${PAW_API_KEY} -sf | jq -r.access_token)`.

4. Retrieve the access token.
    - Enter this command into the terminal : `echo $ $ACCESS_TOKEN`.

## Retrieve server ID's

In this section, you will access the OData API, and retrieve a list of all instances in a data center, and their accompanying ID's. To gain direct access to a specific instance, you will require the service unique id.

1. Retrieve the server ID's.
    - Enter this command into the terminal: `curl https://us-east.planning-analytics.cloud.ibm.com/api/v0/tm1/Servers -H "Authorization: Bearer $ACCESS_TOKEN" -sf | jq -C`.

    - The planning analytics URL will vary depending on the data centre you provisioned your service
at. The URL used above is for the Washington DC data Centre. If you are not certain of the URL you
should use, you can retrieve it from your service launch page.

2. The server will return a list of all instances that can you can access.

## Retrieving active databases

In this section, you will retrieve a list of active databases.

1. Retrieve a list of active databases.
    - Enter this command into the terminal: `curl https://us-east.planning-analytics.cloud.ibm.com/api/4WBG0PXNT6U0F/v0/tm1/Servers -H "Authorization: Bearer $ACCESS_TOKEN" -sf | jq -C`.
    - Replace the instance ID used above (`4WBG0PXNT6U0F`) with the instance ID for the server you want to access.

2. The server will return a list of all active databases.

## Retrieving cubes from a database

In this section, you will retrive the cubes from a database.

1. Retrieve the cubes from a database:
    - Enter this command into the terminal: `curl https://us-east.planning-analytics.cloud.ibm.com/api/4WBG0PXNT6U0F/v0/tm1/IssueReports/Cubes -H "Authorization: Bearer $ACCESS_TOKEN" -sf | jq -C`.

    - Replace the database used above (`IssueReports`) with the database you wish to retrive cubes from.

2. The server will return a list of cubes that are within the database.
