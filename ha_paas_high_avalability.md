---

copyright:
  years: 2023
lastupdated: "2023-01-31"

keywords: high avalability, responsibilities

subcollection: planning-analytics

---

{{site.data.keyword.attribute-definition-list}}



# Understanding high availability for {{site.data.keyword.PA_SaaS_short}}
{: #ha}





[High availability](#x2284708){: term} (HA) is a core discipline in an IT infrastructure to keep your apps up and running, even after a partial or full site failure. The main purpose of high availability is to eliminate potential points of failures in an IT infrastructure.
{: shortdesc}

## Responsibilities
{: #ha-responsibilities}






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






