---

copyright:

  years: 2022
lastupdated: "2022-03-25"

keywords: rollout

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# Service rollout policy
{: #service-rollout}

{{site.data.keyword.cloud}} has a resilient global network of locations to host your highly available cloud workload. To ensure that the cloud infrastructure and services are consistent and stable across our deployment locations, we created best practices for our service catalog management. These best practices help us to accomplish rollouts in the most efficient manner and minimize business impact, costs, and risks. The following information describes our guidelines on when to expect or how to request that a service is available in your region.

This policy covers all {{site.data.keyword.cloud_notm}} public [MZRs](/docs/overview?topic=overview-locations#table-mzr), public [single campus MZRs](/docs/overview?topic=overview-locations#single-campus-mzr) and public [data centers](/docs/overview?topic=overview-locations#data-centers). 

{{site.data.keyword.IBM}} classifies our services deployed to our public locations as core or market-driven.

## Core services
{: #core-services}

All {{site.data.keyword.IBM}} multi-zone regions contain the following core services, which are the most basic and vital services that are needed for the majority of customer workloads.

* {{site.data.keyword.cloud_notm}} platform (console, CLI, Identity and Access Management, and global catalog)
* {{site.data.keyword.vpc_full}}
   * {{site.data.keyword.block_storage_is_full}}
   * {{site.data.keyword.vsi_is_full}}
   * {{site.data.keyword.vpn_vpc_full}}
   * {{site.data.keyword.cloud}} Transit Gateway
   * {{site.data.keyword.nlb_full}}
   * {{site.data.keyword.alb_full}}
   * {{site.data.keyword.vpe_full}}
   * {{site.data.keyword.cloud}} DNS Services
* {{site.data.keyword.cos_full_notm}}
* {{site.data.keyword.databases-for-postgresql_full_notm}}
* {{site.data.keyword.keymanagementservicefull_notm}} 
* {{site.data.keyword.contdelivery_full}}
* {{site.data.keyword.registrylong_notm}}
* {{site.data.keyword.containerlong_notm}}
* {{site.data.keyword.openshiftlong_notm}}

The {{site.data.keyword.cloud_notm}} platform, including the console, CLI, Identity and Access Management, and global catalog, is a globally accessible instance that is independent of any region or zone. Global resources like the platform are accessible from a global endpoint.
{: note}

## Deployment Tiers
{: #deployments}

{{site.data.keyword.IBM_notm}} identifies the following deployment tiers that can contain core services, market driven services or both.

| Deployment tier |Core service   |Market-driven services|
|------------------------------------------|---------------------------------------------|---------------------------------------------|
|[MZR](/docs/overview?topic=overview-locations#table-mzr)| ![Checkmark icon](../icons/checkmark-icon.svg)    |    ![Checkmark icon](../icons/checkmark-icon.svg)   |
|[Single campus MZR](/docs/overview?topic=overview-locations#single-campus-mzr)|    ![Checkmark icon](../icons/checkmark-icon.svg)   |    ![Checkmark icon](../icons/checkmark-icon.svg)    |
|[Data center](/docs/overview?topic=overview-locations#data-centers)|       |    ![Checkmark icon](../icons/checkmark-icon.svg)    |
{: caption="Table 1. Deployment tiers and service types" caption-side="top"}


### Core service deployments
{: #core-deploy}

Adding new core service to existing MZRs
:   After a new core service is deployed in the first MZR and added to this {{site.data.keyword.cloud_notm}} service rollout policy, the new core service will be deployed to all other MZRs within a period of 90 days.
   
Updating existing core services in existing MZRs
:   After a generally available update to an existing core service is deployed in the first MZR and documented in a release note, the same update will be deployed to all other MZRs within a period of 30 days.

Not all hardware dependent profiles and features are available in all MZRs. If the service you want depends on such a profile or feature, contact [{{site.data.keyword.cloud_notm}} Sales](https://www.ibm.com/cloud?contactmodule){: external} for details on availability. 
{: important}

Some services could deploy sooner.
{: note}

### Market-driven deployments
{: #market-driven-deploy}

Market-driven services are deployed based on sufficient customer demand. To request that one of these services is available in your region, contact [{{site.data.keyword.cloud_notm}} Sales](https://www.ibm.com/cloud?contactmodule){: external}.

Deployments into any location other than an MZR are always market-driven.

Market-driven classification covers any case other than those specified under the MZRs' description.
{: note}

## Related documents
{: #related-docs}

| Document and Link                         | Description                                 |
|-------------------------------------------|---------------------------------------------|
| [SLA](https://www-03.ibm.com/software/sla/sladb.nsf/latest/bm-6605){: external} | {{site.data.keyword.cloud_notm}} SLA  |
| [Shared Responsibility Matrix](/docs/overview?topic=overview-shared-responsibilities)  | {{site.data.keyword.IBM_notm}}'s customer shared responsibility matrix |
| [Availability of services](/docs/overview?topic=overview-services_region) | Listing of services available by location   |
| [SLO](/docs/overview?topic=overview-slo)  | {{site.data.keyword.cloud_notm}} SLO  |
{: caption="Table 2. Related documents" caption-side="top"}
