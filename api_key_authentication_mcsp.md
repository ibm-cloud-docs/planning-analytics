---
copyright:
  years: 2023
lastupdated: "2023-11-03"

keywords:
subcollection: planning-analytics

content-type: tutorial

---

{{site.data.keyword.attribute-definition-list}}

# Using API key-based authentication for {{site.data.keyword.PA_SaaS_full}} with MCSP
{: #api__key_based_authentication}

This topic contains details for API key-based authentication for {{site.data.keyword.PA_SaaS_short}} with MCSP.  This topic does not apply to {{site.data.keyword.PA_SaaS_short}} without MCSP. You must have access to Planning Analytics Workspace to generate an API key.

1. Click your user name on the Planning Analytics Workspace home page, then click **Manage API Keys**.

2. On the **API Keys** page, click **Generate Key**.

3. Enter an **API Key name** and, optionally, a **Description**. 

4. Click **Create**.

5. When the key is successfully created, click **Copy to clipboard** and save the key in a secure manner. The API key is displayed for a brief period of time and is unrecoverable after the success notification closes. 

You can now use Basic authentication to log into {{site.data.keyword.PA_SaaS_short}} with MCSP at `https://<PA-SaaS-url>/api/<tenantID>/v0/rolemgmt/v1/users/me`. For example, if your {{site.data.keyword.PA_SaaS_short}} URL is `https://us-east-1.planninganalytics.saas.ibm.com/` and yout tenant ID is 123xyv, you'd use `https://us-east-1.planninganalytics.saas.ibm.com/api/123xyz/v0/rolemgmt/v1/users/me` to log in.

Log in with the user name **apikey** and use the API key that you generated as the password. 

The login returns a paSession cookie that can be reused in additional calls to the Planning Analytics databases or Workspace API endpoints.
