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

# Adding an environment
{: #adding_an_environment}

One environment will be created with each instance. In {{site.data.keyword.PA_SaaS_full}}, you now have the ability to create and manage additional environments (Dev or Prod), and invite specific Planning Analytics Workspace users to environments though self-serve. The following steps will allow you to create a secondary environment in Planning Analytics Administration.

1. Log in to your Planning Analytics service instance.

2. On the Planning Analytics Workspace home page, click the **Administration** tile.

3. On the **Administration** page, click the **Environments** tab.

4. Click **Add** and enter the environment name. Select if this will be a **Development** or **Production** environment, then click **Create**.

To create or manage environments, you need environment admin privileges. The first user is given this privilege by default and it can be granted to other Administrators by enabling the toggle for that user. Users can have different access privilege for each environment.
{: note}

The first environment created cannot be deleted, and there must always be one environment.
{: note}

The resource quota is shared between environments. The **Service Instance Quota** in **Planning Analytics Administration** will show your total quota, and how much has been used.
