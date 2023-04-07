---

copyright:

  years: 2020, 2023

lastupdated: "2023-04-10"

keywords: roles and responsibilities, shared responsibilities, IBM responsibility, customer responsibility

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# Shared responsibilities for using {{site.data.keyword.cloud_notm}} products
{: #shared-responsibilities}

In {{site.data.keyword.cloud}}, as is the case for other cloud service providers, the responsibilities for managing the lifecycle of, operating, and securing products are shared between {{site.data.keyword.IBM}} and the customer.

The responsibility of completing the following types of tasks on various products can be exclusive to {{site.data.keyword.IBM_notm}}, the customer, or shared between the two. The tasks for each type of product are grouped in the following categories:

* Incident and operations management: Includes tasks such as monitoring, event management, high availability, problem determination, recovery, and full state backup and recovery.
* Change management: Includes tasks such as deployment, configuration, upgrades, patching, configuration changes, and deletion.
* Identity and access management: Includes tasks such as authentication, authorization, access control policies, and approving, granting, and revoking access.
* Security and regulation compliance: Includes tasks such as security controls implementation and compliance certification.
* Disaster recovery: Includes tasks such as providing dependencies on disaster recovery sites, provision disaster recovery environments, data and configuration backup, replicating data and configuration to the disaster recovery environment, and failover on disaster events.


When you're reviewing the following sections, the tables list resources for each category and who manages them. The following list describes what constitutes each type of resource in {{site.data.keyword.cloud_notm}}.


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


{{site.data.keyword.cloud_notm}} supports the following types of products and the corresponding shared responsibility models. For more information about each specific service, see the documentation for that service.
{: note}

## Infrastructure-as-a-service
{: #iaas-services-responsibilities}

Infrastructure-as-a-service (IaaS) products that are managed by {{site.data.keyword.IBM_notm}} are multi-tenant, accessed remotely, hosted on {{site.data.keyword.IBM_notm}} physical infrastructure, created in customer-owned accounts, and have control plane and data plane security that is owned by {{site.data.keyword.IBM_notm}}. Examples of this product type are Virtual Servers and Bare Metal Servers with the related block volumes that are connected to the customer account private subnets. You can find a list of these types of products in the {{site.data.keyword.cloud_notm}} catalog on the Services tab. Each product is in an infrastructure subcategory within the Compute or VPC infrastructure categories.


| Resource | Incident and Operations Management | Change Management | Identity and Access Management | Security and Regulation Compliance | Disaster Recovery |
| - | - | - | - | - | - |
| Data | Customer | Customer | Customer | Customer | Customer |
| Application | Customer | Customer | Customer | Customer | Customer |
| Operating system | Customer | Customer | Customer | Customer | Customer |
| Virtual and bare metal servers | Shared | Shared | Shared | Shared | Shared |
| Virtual storage | Shared | Shared | Shared | Shared | Shared |
| Virtual network | Shared | Shared | Shared | Shared | Shared |
| Hypervisor | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical servers and memory | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | Shared | Shared | {{site.data.keyword.IBM_notm}} |
| Physical storage | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical network and devices | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Facilities and data centers | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
{: caption="Table 1. Shared responsibilities for IaaS products" caption-side="top"}

For areas marked as shared responsibilities, the customer is responsible for all the configurations, and {{site.data.keyword.IBM_notm}} is responsible for all underlying management. For disaster recover, the customer is responsible for creating resources in a secondary region and managing the application and data disaster recovery.
{: note}


## Managed products
{: #managed-responsibilities}

Products that are managed by {{site.data.keyword.IBM_notm}} require customer responsibilities only for the data or applications that customers add to the service. They are multi-tenant, accessed remotely, hosted on {{site.data.keyword.IBM_notm}} virtual resources, created in {{site.data.keyword.IBM_notm}}-owned accounts, and have control plane and data plane security that is owned by {{site.data.keyword.IBM_notm}}. Examples of this product type are {{site.data.keyword.cloud_notm}} databases or {{site.data.keyword.cloudant_short_notm}} database instances. You can find a list of these types of products in the {{site.data.keyword.cloud_notm}} catalog on the Services tab. However, any products that are listed in an infrastructure subcategory are infrastructure-as-a-service type products.

| Resource | Incident and Operations Management | Change Management | Identity and Access Management | Security and Regulation Compliance | Disaster Recovery |
| - | - | - | - | - | - |
| Data |Customer  | Customer | Customer | Customer | Customer |
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
{: caption="Table 2. Shared responsibilities for fully-managed products" caption-side="top"}

For disaster recovery, {{site.data.keyword.IBM_notm}} is responsible to ensure that other regions that are not impacted by the disaster are fully operational and will recover the impacted region by the disaster as quickly as possible.
{: note}

## Managed products on customer's resources
{: #managed-offerings-on-customers-resources-responsibilities}

Managed products on customer's resources are orchestrated by {{site.data.keyword.IBM_notm}}. They are single-tenant and data plane products. They are accessed locally in customer accounts, data plane hosted on virtual resources in the customer's account, control plane security owned by {{site.data.keyword.IBM_notm}}, and data plane security owned by the customer. {{site.data.keyword.cloud_notm}} products of this type include {{site.data.keyword.containerlong_notm}} on classic infrastructure and {{site.data.keyword.openshiftlong}} on classic infrastructure.

| Resource | Incident and Operations Management | Change Management | Identity and Access Management | Security and Regulation Compliance | Disaster Recovery |
| - | - | - | - | - | - |
| Data | Customer | Customer | Customer | Customer | Customer |
| Application | Customer | Customer | Customer | Customer | Customer |
| Service instance | Shared | Shared | Shared | Shared | Shared |
| Operating system | Shared | Shared | Shared | Shared | Shared |
| Virtual and bare metal servers | Shared | Shared | Shared | Shared | Shared |
| Virtual storage | Shared | Shared | Shared | Shared | Shared |
| Virtual network | Shared | Shared | Shared | Shared | Shared |
| Hypervisor | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical servers and memory | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical storage | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical network and devices | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Facilities and data centers | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
{: caption="Table 3. Shared responsibilities for self-managed products" caption-side="top"}

For areas marked as shared responsibilities, the customer is responsible for all the configurations, and {{site.data.keyword.IBM_notm}} is responsible for all underlying management. For disaster recovery, the customer is responsible for creating resources in a secondary region and managing the application and data disaster recovery.
{: note}

## Software packages
{: #software-packages}

Software packages are deployed by {{site.data.keyword.IBM_notm}} as single tenant instances, and they are accessed locally in the customer account. The software instance is hosted on resources in the customer's accounts. The software deployment control plane security is owned by {{site.data.keyword.IBM_notm}}, and the software instance security is owned by the customer.

A generic software deployment control plane manages the lifecycle of deployed software package instances. At a minimum, it manages the deployment, upgrade, and delete actions. As the packages become smarter, the generic control plane might also manage the start, stop, migration, scaling, monitoring, backup, and restore tasks.

You can find a list of software in the {{site.data.keyword.cloud_notm}} catalog on the Software tab.

| Resource | Incident and Operations Management | Change Management | Identity and Access Management | Security and Regulation Compliance | Disaster Recovery |
| - | - | - | - | - | - |
| Data | Customer | Customer | Customer | Customer | Customer |
| Application | Customer | Customer | Customer | Customer | Customer |
| Software packages | Shared | Shared | Customer | Customer | Shared |
| Operating system | Shared | Shared | Customer | Customer | Shared |
| Virtual and bare metal servers | Shared | Shared | Shared | Shared | Shared |
| Virtual storage | Shared | Shared | Shared | Shared | Shared |
| Virtual network | Shared | Shared | Shared | Shared | Shared |
| Hypervisor | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical servers and memory | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical storage | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Physical network and devices | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
| Facilities and data centers | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} | {{site.data.keyword.IBM_notm}} |
{: caption="Table 4. Shared responsiblities for software packages" caption-side="top"}

For areas marked as shared responsibilities, the customer is responsible for all the configurations, and {{site.data.keyword.IBM_notm}} is responsible for all underlying management. For disaster recovery, the customer is responsible for creating resources in a secondary region and managing the application and data disaster recovery.
{: note}

## Deployable architectures
{: #deployable-architectures-RACI}

Review the following sections for the specific responsibilities for you and for {{site.data.keyword.IBM_notm}} when you use a deployable architecture.

| Timeline | Responsibility | Who is responsible (R) | Who is accountable (A) | Who is consulted (C) | Who is informed (I) |
| - | - | - | - | - | - |
| **Day 0** |  |  |  |  |   |
|  |  Creation of {{site.data.keyword.cloud_notm}} deployable architecture | {{site.data.keyword.IBM_notm}} | n/a | n/a | Customer |
|   | {{site.data.keyword.cloud_notm}} Terraform Provider | {{site.data.keyword.IBM_notm}} | n/a | n/a | n/a |
|  |  3rd Party Terraform Providers used within templates | Customer | | | |
|  |  IBM-provided template adheres to declared controls | {{site.data.keyword.IBM_notm}} | | | |
| **Day 1** |  |  |  |  |  |
|   | Running default configuration (out of the box) | {{site.data.keyword.IBM_notm}} | n/a | n/a | Customer |
|   | Executing IBM-provided templates via Schematics  | {{site.data.keyword.IBM_notm}} | | | |
|   | Executing templates locally using Terraform directly | Customer | | | |
|   | Customize modules/configurations with pre-supported modules | {{site.data.keyword.IBM_notm}} | n/a | n/a | Customer |
|   | Issues found in IBM-provided versions of Terraform modules  | {{site.data.keyword.IBM_notm}} | n/a | n/a | Customer |
|   | Provide info to reproduce problem, using the IBM-provided version of modules obtained from IBM Catalog and TechZone Accelerator Toolkit Module Catalog  | Customer | n/a | n/a | n/a |
|   | IBM-provided preset JSON configuration overrides for templates  | {{site.data.keyword.IBM_notm}} | n/a | n/a | Customer |
|   | Customization of IBM-provided templates at code level (Terraform, Ansible, etc.). For example, adding or removing custom modules to an IBM-provided template.  | Customer | n/a | n/a | n/a |
|   | Issues with IBM Cloud-provided stock operating system images | 3rd Party OS Vendor | | | |
|   | Applying patches and security updates to operating system in customer instances | Customer | | | |
|   | Issues with IBM Container Images | {{site.data.keyword.IBM_notm}} | | | |
|   | Issues with 3rd-Party & Open Source Container Images | Customer (3rd Party Vendor/Open Source community) | | | |
|   | Obtaining software distributions from vendors or open source communities  \n Storing software installation packages in cloud buckets in customer account | Customer (3rd Party Vendor/Open Source community) | | | |
|   | Installing software and OS patches into customer-managed virtual machines | Customer | | | |
|   | {{site.data.keyword.cloud_notm}} resource outages or issues that occur during automated template execution by using {{site.data.keyword.cloud_notm}} Terraform Provider | {{site.data.keyword.IBM_notm}} | | | |
|   | {{site.data.keyword.cloud_notm}} catalog and Schematics  | {{site.data.keyword.IBM_notm}} | | | |
| **Day 2** |  |  |  |  |  |
|   | Provide ability for drift detection | {{site.data.keyword.IBM_notm}} | n/a | n/a | Customer |
|   | Remediate any configurations detected in drift detection | Customer | n/a | n/a | n/a |
|   | Release of new version of out of box configuration | {{site.data.keyword.IBM_notm}} | n/a | n/a | Customer |
|   | Lifecycle after deployment | Customer | n/a | n/a | n/a |
|   | If bug or issue regarding the automation or terraform script appears from the out of box config | IBM, solution owner | | | |
|   | If bug or issue regarding the services the terraform creates from a deployable architecture  | IBM, service owner | | | |
|   | Monitoring and awareness of {{site.data.keyword.cloud_notm}} incidents that impact infrastructure deployed by automation  | Customer | | | |
{: row-headers}
{: caption="Table 5. Shared responsiblities for deployable architectures" caption-side="top"}
{: summary="The first column is used to provide categories for following rows that describe tasks completed on a timeline from Day 0 to Day 2. Rows 2 through 5 are Day 0 tasks, rows 7 through 22 are Day 1 tasks, rows 24 through 30 are Day 2 tasks"}

For more information on the {{site.data.keyword.bpshort}} IBM versus user responsibilities, see [User responsibilities by using {{site.data.keyword.bplong_notm}}](/docs/schematics?topic=schematics-responsibilities).

### RACI definitions
{: #RACI-definitions}

Responsible (R)
:   This team member does the work to complete the task. Every task needs at least one responsible party, but it’s okay to assign more.

Accountable (A)
:   This person delegates work and is the last one to review the task or deliverable before it’s deemed complete. On some tasks, the responsible party might also serve as the accountable one. Be sure you have only one accountable person who is assigned to each task or deliverable.

Consulted (C)
:   Every deliverable is strengthened by a review and consultation from more than one team member. Consulted parties are typically the people who provide input based on either how it will impact their future project work or their domain of expertise on the deliverable itself.

Informed (I)
:   These team members must be kept in the loop on project progress, rather than roped into the details of every deliverable.
