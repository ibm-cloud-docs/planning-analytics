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

Once the administrator is logged into Planning Analytics Workspace, each user that has been invited into IAM must now also be invited into Planning Analytics Workspace and assigned roles though Planning Analytics Administration.

1. On the Planning Analytics Workspace hmoe page, click the **Administration** tile.

1. Click **Users & Groups**.

1. Click the **Users** tab.

1. Click **Add** and enter the first name, last name, and email address of the new user.

1. Select a role. The Analyst role is selected by default. You can change the role later. For more information about roles, see [User roles](https://www.ibm.com/docs/en/planning-analytics/2.0.0?topic=workspace-user-roles).

1. Click **Add**.

1. If you invite a user with the Administrator role, you have the option to assign the user *Environments admin priveleges*, which allows the user to administer, create, and delete environemnts. If you want to assign these priveleges to an Administrator, enable the **Environments admin priveleges** option on the users's **Details** tab.

If a user who has been invited in IAM is not added to Planning Analytics Workspace, they receive a message instructing them to contact their administrator when attempting to access Planning Analytics Workspace. Adding them to Planning Analytics Workspace will resolve the issue.
{: note}

<!--When you send an invitation, the user receives an emailed invitation indicating the email address of the administrator who sent the invitation, as well as the account associated with the invitation.

The invitation is valid for 28 days. A user cannot access Planning Analytics Workspace if they do not accept the invitation. If the user declines the invitation or does not accept within 28 days, the invitation is revoked and you must send a new invitation to grant access to the user.

Note that invitation and confirmation emails come from several different IBM systems and email accounts. Tell your users to expect these emails.-->
