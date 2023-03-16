---

copyright:
  years: 2023
lastupdated: "2023-01-31"

keywords: data, securing data, data security, encryption

subcollection: planning-analytics

---

{{site.data.keyword.attribute-definition-list}}

# Securing your data in {{site.data.keyword.PA_SaaS_short}}
{: #mng-data}

<!-- The title of your H1 should be Securing your data in _service-name_, where _service-name_ is the non-trademarked short version keyref, but the trademarked version is used in the first occurrence in this topic. Include your service name as a search keyword at the top of your Markdown file. See the example keywords above. -->

To ensure that you can securely manage your data when you use {{site.data.keyword.PA_SaaS_full}}, it is important to know what data is stored and encrypted and how you can delete any stored data.
{: shortdesc}

<!-- Work with your offering's SMEs to fill out the following sections as applicable to your offering. -->

## How your data is stored and encrypted in {{site.data.keyword.PA_SaaS_short}}
{: #data-storage}

{{site.data.keyword.PA_SaaS_short}} stores personal data in one of three data stores:

- Amazon Relational Database Service (RDS): Might contain user's email address, first name, last name, and phone number
- Amazon MemoryDB for Redis: Might contain user's email address
- MongoDB Atlas: Might contain user's email address

Users can update their personal data directly within {{site.data.keyword.PA_SaaS_short}}.

Data is encrypted in transit by mutual TLS connections.
Data is encrypted at rest by the Amazon RDS, Amazon MemoryDB for Redis, and MongoDB Atlas services.

### Deleting {{site.data.keyword.PA_SaaS_short}} instances
{: #service-delete}

Deleting the {{site.data.keyword.PA_SaaS_short}} instance deletes all data.

The {{site.data.keyword.PA_SaaS_short}} data retention policy describes how long your data is stored after you delete the service. The data retention policy is included in the {{site.data.keyword.PA_SaaS_short}} service description, which you can find in the [{{site.data.keyword.cloud_notm}} Terms and Notices](/docs/overview?topic=overview-terms).
