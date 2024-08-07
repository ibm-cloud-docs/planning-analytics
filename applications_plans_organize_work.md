---
copyright:
  years: 2023
lastupdated: "2023-01-31"

keywords:
subcollection: planning-analytics

content-type: how-to
completion-time: 15m
---

{{site.data.keyword.attribute-definition-list}}

# Using applications and plans to organize work
{: #using-applications-and-plans-to-organize-work}

Applications and plans let you organize logically related {{site.data.keyword.planninganalytics_full}} assets such as books, views, and websheets in containers.
{: shortdesc}

An application contains related assets that are grouped in sections. These sections might reflect the structure of your organization, planning and budgeting requirements, or any other relevant grouping of assets. While an application contains logically related assets, there are no implied or required actions associated with the assets or sections in an application.

A plan contains assets that are grouped in steps. These steps can represent discrete tasks or contributions that must be completed in a planning or budgeting process. While steps can be ordered in a plan, there is no requirement for contributors to complete the steps sequentially; they can be completed in any order. Steps can also be assigned a due date for contributions.

Access to sections in an application or steps in a plan are controlled by {{site.data.keyword.planninganalytics_short}} user group assignments. When a user group is assigned to a section or step, the security for the contained assets is updated to include the user group.

Application and plan security is applied only to {{site.data.keyword.planninganalytics_short}} user groups and roles. There are no links or dependencies to TM1 object security. It is the responsibility of the {{site.data.keyword.planninganalytics_short}} administrator to ensure that the {{site.data.keyword.planninganalytics_short}} user groups have the requisite TM1® security permissions to view and edit assets.
{: important}

When you log in to {{site.data.keyword.planninganalytics_short}}, your applications and plans are visible on the **Your Applications** tab at the bottom of the Home page. Applications are identified by the Application ![Application icon](images/paw_application_icon.jpg "Application icon") icon, while plans show the Plan ![Plan icon](images/paw_plan_icon.jpg "Plan icon") icon.

![Home page](images/paw_apps_plans_on_home_page.jpg "{{site.data.keyword.planninganalytics_short}} Home page"){: caption="Figure 1. A screenshot of the {{site.data.keyword.planninganalytics_short}} Home page." caption-side="bottom"}

Administrators can see all applications and plans on the Home page, regardless of state or group assignments. Modelers, analysts and consumers can see open applications or plans in which they are a member of at least one of the user groups assigned to the included assets.

- [Applications](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=work-applications)

  An application contains related assets, such as books, views, and websheets, that are grouped in sections. These sections might reflect the structure of your organization, planning and budgeting requirements, or any other relevant grouping of assets. While an application contains logically related assets, there are no implied or required actions associated with the assets or sections in an application.

- [Plans](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=work-plans)

  A plan contains assets that are grouped in steps. These steps can represent discrete tasks or contributions that must be completed in a planning or budgeting process. Each step in a plan must be completed by contributing data to the books, views, and websheets in the step.


