---

copyright:

  years: 2023

lastupdated: "2023-01-31"

keywords: roles and responsibilities, shared responsibilities, IBM responsibility, customer responsibility

subcollection: planning-analytics

---

{{site.data.keyword.attribute-definition-list}}

# Shared responsibilities for using {{site.data.keyword.PA_SaaS_notm}}
{: #shared-responsibilities}

In {{site.data.keyword.cloud}}, as is the case for other cloud service providers, the responsibilities for managing the lifecycle of, operating, and securing products are shared between {{site.data.keyword.IBM}} and the customer.

The responsibility of completing the following types of tasks on various products can be exclusive to {{site.data.keyword.IBM_notm}}, the customer, or shared between the two. The tasks for each type of product are grouped in the following categories:

* Incident and operations management: Includes tasks such as monitoring, event management, high availability, problem determination, recovery, and full state backup and recovery.
* Change management: Includes tasks such as deployment, configuration, upgrades, patching, configuration changes, and deletion.
* Identity and access management: Includes tasks such as authentication, authorization, access control policies, and approving, granting, and revoking access.
* Security and regulation compliance: Includes tasks such as security controls implementation and compliance certification.
* Disaster recovery: Includes tasks such as providing dependencies on disaster recovery sites, provision disaster recovery environments, data and configuration backup, replicating data and configuration to the disaster recovery environment, and failover on disaster events.


When you're reviewing the following section, the table list resources for each category and who manages them. The following list describes what constitutes each type of resource in {{site.data.keyword.cloud_notm}}.


Data
:   Customer-owned content that includes all data that is managed and controlled by the customer. Examples include information that is stored into volumes, files, and databases hosted on {{site.data.keyword.cloud_notm}} resources and data processed, stored, and logged by the client applications hosted on {{site.data.keyword.cloud_notm}}. It doesn't include client metadata, the information that is used by {{site.data.keyword.IBM_notm}} to provide services to the customer and support and operate the client account, services, and resources that are always considered to be shared responsibility between client and {{site.data.keyword.IBM_notm}}.

Applications
:   Customer-owned software components, such as executables, web applications, middleware, frameworks, libraries, and other software packages that the client developed or acquired by third parties and deployed in {{site.data.keyword.cloud_notm}}.

Service instance
:   An entity that consists of resources that are reserved for a particular service.

Operating systems
:   The operating system software and configuration that are deployed in virtual or bare metal servers, such as Linux, Windows, or similar to the ones provided in [stock images](/docs/vpc?topic=vpc-about-images).

Virtual and bare metal servers
:   The virtual or bare metal servers that are ordered and managed through {{site.data.keyword.cloud_notm}} services.

Virtual storage
:   The block, file, or Object Storage buckets ordered and managed through {{site.data.keyword.cloud_notm}}.

Virtual network
:   Network resources such as VLAN, VPC, subnets, or IPs provided by [classic infrastructure](/docs/vlans?topic=vlans-getting-started) and [VPC](/docs/vpc?topic=vpc-about-networking-for-vpc) services that are ordered and managed through {{site.data.keyword.cloud_notm}}.

Hypervisor
:   The software and configuration that is deployed in physical servers to host and manage the lifecycle of virtual servers.

Physical servers and memory
:   The physical compute devices and resources, such as cores, memory, and GPUs used to host the virtual or bare metal servers.

Physical storage
: The physical storage devices and resources, such as disks and storage devices that are used to host the virtual block, file, or Object Storage buckets.

Physical network and devices
:   The physical network devices and resources, such as switches, routers, gateways, firewalls, and load balancers that are used to host the virtual network resources.

Facilities and data centers
:   The physical data center buildings with power, cooling, and rooms for all the {{site.data.keyword.cloud_notm}} physical equipment.



## Details on {{site.data.keyword.PA_SaaS_notm}} responsibilities
{: #managed-responsibilities}

{{site.data.keyword.PA_SaaS_short}} requires that customers be solely responsible only for some aspects of the data or applications that customers add to the service. {{site.data.keyword.PA_SaaS_short}} is multi-tenant, accessed remotely, hosted on virtual resources, created in {{site.data.keyword.IBM_notm}}-owned accounts, and have control plane and data plane security that is owned by {{site.data.keyword.IBM_notm}}.

| Resource | Incident and Operations Management | Change Management | Identity and Access Management | Security and Regulation Compliance | Disaster Recovery |
| - | - | - | - | - | - |
| Data |{{site.data.keyword.IBM_notm}}  | {{site.data.keyword.IBM_notm}} | Customer | Customer | {{site.data.keyword.IBM_notm}} |
| Application | Customer | Customer | Customer | Customer | Customer |
| Service instance | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared |
| Virtual and bare metal servers | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Virtual storage | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Virtual network | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Hypervisor | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical servers and memory | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical storage | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical network and devices | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Facilities and data centers | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
{: caption="Table 1. Shared responsibilities for Planning Analytics as a Service" caption-side="top"}

For disaster recovery, {{site.data.keyword.IBM_notm}} is responsible to ensure that other regions that are not impacted by the disaster are fully operational and will recover the impacted region by the disaster as quickly as possible.
{: note}
