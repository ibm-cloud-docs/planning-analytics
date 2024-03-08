---
copyright:
  years: 2023
lastupdated: "2023-11-27"

keywords:
subcollection: planning-analytics

content-type: how-to
services:
account-plan: lite, enterprise
completion-time: 15m
---

{{site.data.keyword.attribute-definition-list}}

# Egress IP addresses
{: #egress_ip_addresses}

{{site.data.keyword.PA_SaaS_short}} employs three Network Address Translation (NAT) gateways per cluster to ensure that all requests external to the cluster are routed through a central egress point. This ensures that the external endpoint sees one of the three remote IP addresses, depending on the availability zone in Planning Analytics where the request was initiated.
{: shortdesc}

Table 1 documents the egress IP addresses by region:

| Region             | IP Addresses       |
|-------------------|------------|
| Ohio              | 3.135.114.169  \n 18.116.216.50  \n 52.14.102.157|
| Frankfurt         | 3.68.1.94  \n 18.158.43.41  \n 18.159.169.10| 
| Sydney             | 3.105.44.155  \n 13.54.96.230  \n 52.63.210.127|
{: caption="Table 1. Egress IP addresses" caption-side="bottom"}

Table 2 documents the egress IP addresses for {{site.data.keyword.PA_SaaS_short}} on MCSP by region:

| Region             | IP Addresses       |
|-------------------|------------|
| us-east-1            | 3.224.15.70  \n 50.19.228.111  \n 52.45.46.218|
| eu-central-1         | 18.156.189.119  \n 3.78.118.23  \n 35.157.50.137| 
| ap-southeast-2       | 3.25.4.210  \n 3.104.192.243  \n 54.79.240.176|
{: caption="Table 2. Egress IP addresses - MCSP" caption-side="bottom"}
