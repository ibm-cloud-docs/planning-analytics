---
copyright:
  years: 2023
lastupdated: "2023-01-31"

keywords:
subcollection: planning-analytics

content-type: tutorial

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

# Inviting users to your Planning Analytics as a Service environment
{: #inviting_users_environment}

You can use {{site.data.keyword.PA_SaaS_full}} to invite additional users to access your service instance. You must first invite users into your IBM Cloud account using Identity Access Management (IAM) and then add the same users to Planning Analytics Workspace.

## Inviting users to your service instance

To invite users using IAM into your IBM Cloud account, complete the following steps:

1. In the **Manage** dropdown menu, click **Access(IAM)**.

1. Click **Invite Users** in the **Manage access and users** dashboard.

1. In the text box, enter the email adresses of the users you want to invite to your IBM Cloud account.

1. Configure the users’ access policy.

    - If you have created an access group with defined access for the service, click **Access groups** then select the group to which you want to assign the invited users. For more information on access groups, see [Assigning access to resources by using access groups](https://cloud.ibm.com/docs/account?topic=account-access-getstarted).

    or

    1. Click **Access policy** to define access for the users you are inviting.

    2. Select the service for which you want to define access: **Planning Analytics** for a production environment or **Planning Analytics Dev** for a development environment.

    3. Click **Next**.

    4. Specify the **Resources** for which you want to grant access, then click **Next** .

    5. Specify the levels of **Resource group access** you want to assign, then click **Next**. You can select a level to view a definition of the access that is provided by the level.

    6. Under **Service access**, select the **Planning Analytics User** role to allow users to log into your Planning Analytics service instance(s).

    7. Under **Platform access**, selct the appropriate level of platform access required for the **Planning Analytics User**. You can select a level to view a definition of the access that is provided by the level.

1. Click **Review**.

1. Once the process is reviewed, click **Add** to move your desired access to the **Access summary** pane.

1. Click **Invite**. Your users will receive an email invitation, inviting them to access your IBM Cloud account. They will need to accept this invite before they can access the Service Instance.

## Inviting users into Planning Analytics Workspace

The user who created the {{site.data.keyword.PA_SaaS_full}} instance from the IBM Cloud Catalog is given the administrator role in Planning Analytics Workspace by default and can log in to the workspace. This user is also given the environment administrator role, which allows them to create and manage additional environments within the service instance.

<!-- Need more information on how to add the user manually
Should the instructions outline how users can be added through the import to .csv files? -->

Once the administrator is logged into Planning Analytics Workspace, all users that have been invited into IAM must now also be invited into Planning Analytics Workspace and assigned roles though Planning Analytics Administration. To learn more about inviting users to Planning Analytics Workspace and assigning roles, see [Administer users on cloud](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=groups-administer-users-cloud).

If a user who has been invited in IAM is not added to Planning Analytics Workspace, they receive a message instructing them to contact their administrator when attempting to access Planning Analytics Workspace. Adding them to Planning Analytics Workspace will resolve the issue.
{: note}
