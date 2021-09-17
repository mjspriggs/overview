---



copyright:

  years: 2020
lastupdated: "2020-10-29"

keywords: terms of use, IBM Cloud, ip addresses, IP address policy

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:external: target="_blank" .external}

# IP Address Policy
{: #ip_address_policy}

## 1. IP Address Ownership
{: #ip_address_ownership}

International Business Machines Corporation or its subsidiaries that ({{site.data.keyword.IBM}}) own any IP addresses assigned to Client, which are to be used only with the Cloud Services. Use of the IP addresses terminates upon expiration or termination of a service, at which time the IP addresses will be reclaimed and may be re-issued to other customers in the future. 

## 2. Client-Provided IP Addresses
{: #client_provided_ips}

Clients may provide their own Regional Internet Registry (RIR) issued IP addresses, subject to certain technical limitations and verification of ownership, by submitting a support case and providing a Letter of Authority to specify Client-owned IP prefixes. If {{site.data.keyword.IBM_notm}} approves a request those IP addresses will be announced via Border Gateway Protocol (BGP) on the Client's behalf and routed to identified Client servers. Client retains ownership of those IP addresses. At Client's request, or upon cancellation of the services, {{site.data.keyword.IBM_notm}} will cease to announce and route those IP addresses. While {{site.data.keyword.IBM_notm}} will make reasonable efforts to ensure that BGP prefixes are accepted by all upstream ISPs, we cannot guarantee global reachability for Client-owned IPs. 

## 3. Review / Justification / Efficiency Guidelines
{: #review_justification_efficiency}

Because IPv4 addresses are a scarce resource, RIRs require ISPs to document that they are efficiently utilizing existing assigned addresses and are planning efficient utilization of any addresses being requested. RIR policies and RFC2050 promote conservation and deter wasteful use or stockpiling of IP space. {{site.data.keyword.IBM_notm}} is required to abide by these policies when {{site.data.keyword.IBM_notm}} requests additional IP addresses to allocate. Therefore, when requested by {{site.data.keyword.IBM_notm}}, Client provides information necessary to enable {{site.data.keyword.IBM_notm}} to obtain RIR-issued IP addresses to support the Cloud Services. 

All Client IP address requests are subjected to review by {{site.data.keyword.IBM_notm}} to ensure efficient utilization and are not guaranteed to be approved. During the review, Client is required to provide details about how each IP address would be utilized and technical justification as to why additional IP addresses are needed. {{site.data.keyword.IBM_notm}} may take steps to validate such information, including network scanning and server configuration inspection. 

An initial review may take up to 2 business days, and depending on size and complexity, may require additional time for completion. Accounts with open abuse tickets will have their IP requests held for processing until all abuse issues have been resolved. 
