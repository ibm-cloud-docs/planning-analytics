---

copyright:
  years: 2023
lastupdated: "2023-01-31"

keywords: high avalability, responsibilities

subcollection: planning-analytics

---

{{site.data.keyword.attribute-definition-list}}

<!--Name your file `ha.md` and include it in the **Reference** nav group in your `toc.yaml` file.-->

# Understanding high availability for {{site.data.keyword.PA_SaaS_short}}
{: #ha}

<!-- The title of your H1 should be Understanding high availability for _service-name_, where _service-name_ is the non-trademarked short version keyref. Include your service name as a search keyword at the top of your Markdown file. See the example keywords above. -->

<!-- The short description should be a single, concise paragraph that contains one or two sentences and no more than 50 words. Summarize your offering's strategy for HA. The following is a suggested short description._
{: shortdesc} -->

[High availability](#x2284708){: term} (HA) is a core discipline in an IT infrastructure to keep your apps up and running, even after a partial or full site failure. The main purpose of high availability is to eliminate potential points of failures in an IT infrastructure.
{: shortdesc}

## Responsibilities
{: #ha-responsibilities}

<!-- If there is specific responsibility documentation for the product , comment the next paragraph-->
<!-- To find out more about responsibility ownership for using {{site.data.keyword.cloud}} products between {{site.data.keyword.IBM_notm}} and the customer, see [Shared responsibilities for {{site.data.keyword.cloud_notm}} products](/docs/overview?topic=overview-shared-responsibilities).-->

<!-- If there is specific responsibility documentation available for the product, provide a linked reference on the following paragraph or elaborate on the current document-->

See [Shared responsibilities for IBM products.](/docs/overview?topic=overview-shared-responsibilities) for details on responsibility ownership between {{site.data.keyword.IBM_notm}} and the customer when using {{site.data.keyword.PA_SaaS_short}}.

## What level of availability do I need?
{: #ha-level}

You can achieve high availability on different levels in your IT infrastructure and within different components of your cluster. The level of availability that is right for you depends on several factors, such as your business requirements, the service level agreements (SLAs) that you have with your customers, and the resources that you want to expend.

## What level of availability does {{site.data.keyword.cloud_notm}} offer?
{: #ha-service}

The level of availability that you set up for your cluster impacts your coverage under the {{site.data.keyword.cloud_notm}} high availability service level agreement terms.

Service level objectives (SLOs) describe the design points that the {{site.data.keyword.cloud_notm}} services are engineered to meet. {{site.data.keyword.PA_SaaS_short}} is designed to achieve the following availability target.

| Availability target | Target Value   |
|---|---|
|  Availability % | 99.99  |
{: caption="Table 1. SLO for {{site.data.keyword.PA_SaaS_short}}" caption-side="bottom"}

The SLO is not a warranty and {{site.data.keyword.IBM_notm}} will not issue credits for failure to meet an objective. Refer to the SLAs for commitments and credits that are issued for failure to meet any committed SLAs. For a summary of all SLOs, see [{{site.data.keyword.cloud_notm}} service level objectives](/docs/overview?topic=overview-slo).


<!--##Locations-->
<!--{: #ha-locations}-->

<!--For more information about service availability within regions and data centers, see [Service and infrastructure availability by location](/docs/overview?topic=overview-services_region).-->
