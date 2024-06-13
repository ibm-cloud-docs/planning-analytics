---

copyright:
  years: 2023
lastupdated: "2023-01-31"

keywords: Planning Analytics as a Service, business continuity

subcollection: planning-analytics

---

{{site.data.keyword.attribute-definition-list}}



# Understanding business continuity and disaster recovery for {{site.data.keyword.PA_SaaS_short}}
{: #bc-dr}





[Disaster recovery](#x2113280){: term} involves a set of policies, tools, and procedures for returning a system, an application, or an entire data center to full operation after a catastrophic interruption. It includes procedures for copying and storing an installed system's essential data in a secure location, and for recovering that data to restore normalcy of operation.
{: shortdesc}

## Responsibilities
{: #bc-dr-responsibilities}

See [Shared responsibilities for IBM products.](/docs/overview?topic=overview-shared-responsibilities) for details on responsibility ownership between {{site.data.keyword.IBM_notm}} and the customer when using {{site.data.keyword.PA_SaaS_short}}.

## Disaster recovery strategy
{: #bc-dr-strategy}

{{site.data.keyword.cloud_notm}} has [business continuity](#x3026801){: term} plans in place to provide for the recovery of services within hours if a disaster occurs. You are responsible for your data backup and associated recovery of your content.

{{site.data.keyword.PA_SaaS_short}} provides mechanisms to protect your data and restore service functions. Business continuity plans are in place to achieve targeted [recovery point objective](#x3429911){: term} (RPO) and [recovery time objective](#x3167918){: term} (RTO) for the service. The following table outlines the targets for {{site.data.keyword.PA_SaaS_short}}.

| Disaster recovery objective | Target Value   |
|---|---|
|  RPO | 24 hours  |
|  RTO | 4 hours  |
{: caption="Table 1. RPO and RTO for {{site.data.keyword.PA_SaaS_short}}" caption-side="bottom"}
