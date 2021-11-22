---

copyright:
  years: 2021
lastupdated: "2021-06-14"

keywords: financial services 

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# What is {{site.data.keyword.cloud_notm}} for Financial Services?
{: #what-is-fscloud}

{{site.data.keyword.cloud_notm}} for Financial Services is a solution platform and ecosystem program built on an industry-informed framework of controls, architectures, and operations that mitigates systemic risk in using public cloud for mission-critical workloads with client-sensitive data.
{: shortdesc}

To view all services that are Financial Services Validated in {{site.data.keyword.cloud_notm}}, go to the [catalog](https://cloud.ibm.com/catalog?search=label%3Afs_ready#services) and select the **Financial Services Validated** filter in the Compliance section.

However, there are required services to use to maintain an {{site.data.keyword.cloud_notm}} for Financial Services solution. Others are optional. The following services are required for a validated architecture when using {{site.data.keyword.vpc_full}} services. 

* {{site.data.keyword.cloud_notm}} Activity Tracking (requires the use of {{site.data.keyword.cos_full_notm}})
* {{site.data.keyword.cloud_notm}} {{site.data.keyword.alb_full}}
* {{site.data.keyword.cloud_notm}} {{site.data.keyword.fl_full}}
* {{site.data.keyword.iamlong}}
* {{site.data.keyword.cos_full_notm}} or {{site.data.keyword.block_storage_is_full}}
* {{site.data.keyword.tg_full_notm}}
* {{site.data.keyword.vpc_full}}
* {{site.data.keyword.cloud_notm}} {{site.data.keyword.vpe_full}}
* {{site.data.keyword.cloud_notm}} {{site.data.keyword.vpn_full}} or {{site.data.keyword.dl_full_notm}} (Connect and Dedicated 2.0)
* {{site.data.keyword.IBM_notm}} {{site.data.keyword.hscrypto}}
* {{site.data.keyword.openshiftlong_notm}} or {{site.data.keyword.vsi_is_full}}

For the most security, it's recommended that you use the {{site.data.keyword.cloud_notm}} CLI to create resources by using [private endpoints](/docs/cli?topic=cli-service-connection).
{: tip}

You can also set your team up to be alerted if they are creating a service that is not Financial Services Validated by enabling the Financial Services Validated setting in your account. For more information, see [Validate financial services for your account](/docs/account?topic=account-enabling-fs-validated).

To learn more about {{site.data.keyword.cloud_notm}} for Financial Services, see the [product page](https://www.ibm.com/cloud/financial-services).
