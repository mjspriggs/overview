---

copyright:
  years: 2021
lastupdated: "2021-05-19"

keywords: service endpoints, private endpoints, virtual private endpoints, vpe, vpe for vpc

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# Privately connecting to {{site.data.keyword.cloud_notm}} services
{: #endpoints-support}

An increased focus on security is required by customers that use cloud-based services for production workloads. For many customers, accessing services in a secure manner is not only a sensible corporate policy, but in some cases required by compliance regulations. {{site.data.keyword.IBM}} has enhanced the connectivity options for customers who require isolated connectivity options for their workloads by providing the options of virtual private endpoints (VPE) for Virtual Private Cloud (VPC) and {{site.data.keyword.cloud}} service endpoints.
{: shortdesc} 

To interact with the product APIs, you can use public endpoints, VPE for VPC, or service endpoints.

* Public endpoints: You can connect to resources in all regions in your account over the {{site.data.keyword.cloud_notm}} public network.
* VPE for VPC: After you create private endpoints in your VPC, you can connect by using a private IP address that's accessible only from your VPC. This option is available for VPC users.   
* Service endpoints: After you enable virtual routing and forwarding (VRF) and turn on service endpoints for your account, you can connect by using a private IP address that's accessible only through the {{site.data.keyword.cloud_notm}} private network. This option is available for classic infrastructure users.

By using VPE for VPC or service endpoints, you can privately connect to {{site.data.keyword.cloud_notm}} platform services and service products in the catalog that support this type of private connectivity. 

Go to the [API docs](https://{DomainName}/docs?tab=api-docs) for the service that you want to connect to and see the Endpoint URLs section to view the endpoints for that service.
{: tip}

## Virtual private endpoints for VPC
{: #vpe-overview}

VPE for VPC provides private connectivity to select {{site.data.keyword.cloud_notm}} services originating from the VPC network of your choosing, without traversing the public backbone. All connectivity is contained within {{site.data.keyword.cloud_notm}}. By using a service that supports VPE for VPC, you can connect to the service from your VPC network by assigning the IP address of your choosing, which is allocated from a subnet within your VPC. 

VPEs are virtual IP interfaces that are bound to an endpoint gateway created on a per service or service instance basis, depending on the service operation model. The endpoint gateway is a virtualized function that scales horizontally, is redundant and highly available, and spans all availability zones of your VPC. Endpoint gateways enable communications from virtual server instances in your VPC to {{site.data.keyword.cloud_notm}} services, with all traffic going over the {{site.data.keyword.cloud_notm}} backbone. VPE for VPC gives you the experience of controlling all the private addressing within your cloud.

For more information, see [About virtual private endpoint gateways](/docs/vpc?topic=vpc-about-vpe).


## {{site.data.keyword.cloud_notm}} service endpoints
{: #cloud-service-endpoints-overview}

For classic infrastructure users, the cloud service endpoints feature provides the option of using private routes to connect to {{site.data.keyword.cloud_notm}} services. These private routes are not accessible or reachable over the internet. You can protect your data from threats from the public network and logically extend your private network. This capability enables an enterprise with strict security requirements to have confidence in moving workloads to the {{site.data.keyword.IBM_notm}} public cloud. 

For more information, see [Enabling virtual routing and forwarding (VRF) and service endpoints](/docs/account?topic=account-vrf-service-endpoint). 




