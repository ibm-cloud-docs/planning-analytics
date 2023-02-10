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

# Modeling in {{site.data.keyword.planninganalytics_short}}
{: #model-in-planning-analytics-workspace}

IBM® Planning Analytics Workspace includes a modeling environment that you can use to model user data with cubes, dimensions, hierarchies, attributes, and security for IBM Planning Analytics.

OLAP modeling and modeling concepts can be confusing. This video will help you to understand some of the basic concepts of what they are and why we model data for analyzes:
{: shortdesc}

![The beginner's guide to OLAP modeling and modeling concepts](https://www.youtube.com/embed/5GOjioIcs8g){: video output="iframe" data-script="none" id="youtubeplayer1" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen}

**Note:** {{site.data.keyword.planninganalytics_short}} modeling is supported on IBM Planning Analytics Local 2.0.0 or later. Modeling is not supported in Planning Analytics Workspace on TM1 databases that are installed with version 10.3.0 or earlier.

You can use the {{site.data.keyword.planninganalytics_short}} modeling tools to convert business requirements into precise cubes, dimensions, hierarchies, and calculations so that planning and analytics outcomes make sense to business users.

Build and maintain the structure of a financial model independently, without coding.
Transform and load data easily into a financial model, which increases transparency and confidence in results.
Build a step-by-step financial process for multiple users based on roles and security permissions, without coding.
Modelers can define business logic by using an integrated development environment.
To use {{site.data.keyword.planninganalytics_short}} modeling, you must log in with a user name that has the Modeler role.

{{site.data.keyword.planninganalytics_short}} modeling supports the following tasks:
- [Creating cubes](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=mipaw-cubes)
- [Using rules](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=mipaw-rules)
- [Editing dimensions](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=mipaw-dimensions)
- [Managing hierarchies](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=d-hierarchies)
- [Creating attributes](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=ma-create-member-attributes)
- [Managing security](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=mipaw-object-security)

To understand why you should use the {{site.data.keyword.planninganalytics_short}} tools to model your data, consider the following benefits.

## Query performance
{: #query-performance}

You can create more manageable dimensions by creating more than one hierarchy in a dimension.

For example, you can create a single time dimension. A year dimension must be the same for every year to compare data between two years. This approach gives you the ability to create a new year easily, and query performance is faster because you have only one dimension in the cube.

You can create a time dimension with multiple hierarchies that represent years and months to do yearly comparisons per month.

If you create two dimensions, one for year and one for months, you gain the ability to split the years and months across two axes and you can compare data between years.

## RAM savings
{: #ram-savings}

If you model with dimensions, you can put the dimensions on the cube axes. Dimensions describe the data, and you can query against them. But dimensions cost RAM memory. Therefore, you can use hierarchies to model your data instead of dimensions.

If you model with attributes, it keeps your cube structure simple but it describes the dimension members only, not the data itself. You can't use attributes to query data. Creating a dimension for attributes that you want to query on creates complexity.

You can use hierarchies to model your data and get the same granularity that attributes give you with the benefit of being able to query on the data. You can query directly with hierarchies on the axes or with set filtering. You save on storage costs and complexity if you model with hierarchies.

## Flexibility
{: #flexibility}

Using hierarchies to add versions creates flexibility. For example, you might need to change your organizational hierarchy for planned changes. One dimension might be the organization and you can use hierarchies in the dimension to represent the organization in the future year. This hierarchy might represent the data differently from the previous year's hierarchy. With multiple hierarchies that represent the organization, you can roll up the data in multiple ways.

Hierarchies are named and contain members. You can reuse the same consolidated members in multiple hierarchies. You can use hierarchies to group these members without the need for specific consolidated names.

## Standards
{: #standards}

Hierarchies conform to OLAP Industry standards. {{site.data.keyword.planninganalytics_short}} modeling uses MDX and TM1 REST APIs to access TM1 data. The TM1 REST APIs support the hierarchy model and follow the ODATA standard.

- [The modeler role](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=mipaw-modeler-role)

  If you are enabled as an Administrator or a Modeler in {{site.data.keyword.planninganalytics_short}}, you can design dimensions, hierarchies, views, and attributes to define the business logic for your application.

- [Steps to building a model](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=mipaw-steps-building-model)

  You design a model in response to a business need. For example, a company wants to plan its expenses for the next 12 months by expense line. The company collects the information from a number of departments that are spread across a wide geographical area.

- [Dimensions](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=mipaw-dimensions)

  Dimensions are lists of related members. Two or more dimensions are used to make a cube that can be used for planning and analysis.

- [Cubes](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=mipaw-cubes)

  {{site.data.keyword.planninganalytics_short}} stores the data that you need for planning and analysis in cubes.

- [Rules](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=mipaw-rules)

  You can create complex data calculations in {{site.data.keyword.planninganalytics_short}} with business rules.

- [Configure drill-through to reveal detailed data](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=mipaw-configure-drill-through-reveal-detailed-data)

  You can associate a cube cell with extra data, which can provide underlying detail for the cell or other information relevant to the cell. When you complete the configuration that is required to establish this association, users can drill through to the additional data directly from an Exploration view.

- [Object security](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=mipaw-object-security)

  Modelers manage the security for cubes, dimensions, and processes in the settings editor, and security for dimension members in the security view in the dimension editor. You can assign security to these objects for any non-administrative user group in Planning Analytics Workspace.

- [TurboIntegrator processes](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=mipaw-turbointegrator-processes)

  {{site.data.keyword.planninganalytics_short}} provides the ability to create, edit, and execute TurboIntegrator processes.

- [TurboIntegrator chores](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=mipaw-turbointegrator-processes)

  You can create a chore to execute one or more TurboIntegrator processes in a specified sequence and at defined intervals.

- [Translate a model](https://www.ibm.com/docs/planning-analytics/2.0.0?topic=mipaw-translate-model)

  You can translate a model in {{site.data.keyword.planninganalytics_short}} by creating translated values for attributes. You can translate dimensions, members, cubes, attributes, views, processes, and public sets.
