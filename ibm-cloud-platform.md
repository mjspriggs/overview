---


copyright:
  years: 2016, 2023

lastupdated: "2023-04-10"


keywords: console, platform overview, overview, catalog, IBM Cloud catalog

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# What is the {{site.data.keyword.Bluemix_notm}} platform?
{: #whatis-platform}

The {{site.data.keyword.cloud}} platform combines platform as a service (PaaS) with infrastructure as a service (IaaS) to provide an integrated experience. The platform scales and supports both small development teams and organizations, and large enterprise businesses. Globally deployed across data centers around the world, the solution you build on {{site.data.keyword.cloud}} spins up fast and performs reliably in a tested and supported environment you can trust!
{: .shortdesc}

{{site.data.keyword.cloud_notm}} provides solutions that enable higher levels of compliance, security, and management, with proven architecture patterns and methods for rapid delivery for running mission-critical workloads. Available in data centers worldwide, with multizone regions in North and South America, Europe, Asia, and Australia, you are enabled to deploy locally with global scalability.

{{site.data.keyword.cloud_notm}} offers the most open and secure public cloud for business with a next-generation hybrid cloud platform, advanced data and AI capabilities, and deep enterprise expertise across 20 industries. Solutions are available depending on your needs for working in the public cloud, on-premises, or a combination:

* With public cloud, the resources are made available to you over the public internet. It is a multi-tenant environment, and resources like hardware and infrastructure are managed by {{site.data.keyword.IBM}}.
* A [hybrid cloud solution](https://www.ibm.com/cloud/hybrid){: external} is a combination of public and private, giving you the flexibility to move workloads between the two based on your business and technological needs. {{site.data.keyword.IBM_notm}} uses {{site.data.keyword.openshiftlong_notm}}, the market-leading hybrid cloud container platform for hybrid solutions that enables you to build once and deploy anywhere. With {{site.data.keyword.satellitelong_notm}}, you can create a hybrid environment that brings the scalability and on-demand flexibility of public cloud services to the applications and data that runs in your secure private cloud.
* Support for [multicloud](https://www.ibm.com/cloud/learn/multicloud){: external} and hybrid multicloud solutions is also available, which makes it easy for you to work with different vendors. [{{site.data.keyword.cloud_notm}} Paks](https://www.ibm.com/cloud/paks){: external} are software products for hybrid clouds that enable you to develop apps once and deploy them anywhere.
* [Virtual Private Cloud (VPC)](/docs/vpc?topic=vpc-getting-started) is available as a public cloud service that lets you establish your own private cloud-like computing environment on shared public cloud infrastructure. With VPC, enterprises can define and control a virtual network that is logically isolated from all other public cloud tenants, creating a private, secure place on the public cloud.

With our open source technologies, such as Kubernetes, Red Hat OpenShift, and a full range of compute options, including virtual machines, containers, bare metal, and serverless, you have the control and flexibility that's required to support workloads in your hybrid environment. You can deploy cloud-native apps while also ensuring workload portability.

Whether you need to migrate apps to the cloud, modernize your existing apps by using cloud services, ensure data resiliency against regional failure, or use new paradigms and deployment topologies to innovate and build your cloud-native apps, the platform's open architecture is built to accommodate your use case.

## What's built into the platform?
{: #built-into-platform}

As the following diagram illustrates, the {{site.data.keyword.Bluemix_notm}} platform is composed of multiple components that work together to provide a consistent and dependable cloud experience.

* A robust console that serves as the front end for creating, viewing, managing your cloud resources
* An identity and access management component that securely authenticates users for both platform services and controls access to resources consistently across {{site.data.keyword.Bluemix_notm}}
* A catalog that consists of hundreds of supported products
* A search and tagging mechanism for filtering and identifying your resources
* An account and billing management system that provides exact usage for pricing plans and secure credit card fraud protection

![Components of the {{site.data.keyword.cloud_notm}} platform.](images/IBM-Cloud-Platform.svg "Diagram showing the major components of the {{site.data.keyword.cloud_notm}} platform"){: caption="Figure 1. Components of the {{site.data.keyword.cloud_notm}} platform" caption-side="bottom"}

Whether you have [existing code](/docs/apps?topic=apps-tutorial-byoc#tutorial-byoc) that you want to modernize and bring to the cloud or you're developing a brand new application, your developers can tap into the rapidly growing ecosystem of available services and runtime frameworks in {{site.data.keyword.Bluemix_notm}}.

## Setting up your account
{: #set-up-account}

If you're a developer and you're just trying out {{site.data.keyword.Bluemix_notm}}, you can go straight to the catalog and browse the products that you'd like to explore. Try filtering for all Lite and Free pricing plans to test out {{site.data.keyword.cloud_notm}} with no costs. When you're ready to get started with an environment and get apps running in production, consider setting up the basics in your account:

* Access groups for organizing users and service IDs into one entity to make assigning access a streamlined process
* Resource groups for organizing your resources to make assigning access to a set of resources quick and easy
* IAM access policies for your access groups or individual developers

For more information, see the [best practices for organizing your resources and assigning access](/docs/account?topic=account-account_setup).

As a financial officer for your company, you might be interested in simplifying how you manage billing and usage across multiple teams and departments. With a Subscription account, you can create an {{site.data.keyword.Bluemix_notm}} [enterprise](#x2026915){: term}, which offers centralized account management, consolidated billing, and top-down usage reporting. An enterprise consists of an enterprise account, account groups, and individual accounts.

* The enterprise account is the parent account to all other accounts in the enterprise. Billing for the entire enterprise is managed at the enterprise account level.
* Account groups provide a way to organize related accounts. And, you get a unified view of resource usage costs across all accounts that are included in an account group.
* Similar to stand-alone accounts, accounts in an enterprise contain resources and resource groups and independent access permissions.

For more information, see the [Enterprise account architecture](/docs/enterprise-account-architecture) white paper and the [best practices for setting up an enterprise](/docs/secure-enterprise?topic=secure-enterprise-enterprise-best-practices).

## {{site.data.keyword.Bluemix_notm}} catalog
{: #catalog}

Discover all that {{site.data.keyword.cloud_notm}} has to offer. From services, software, and [deployable architectures](#x10293733){: term} ranging from containers, compute, security, data, AI, and more, find what you need to transform your business.

The available services include options for compute, storage, networking, end-to-end developer solutions for app development, testing and deployment, security management services, traditional and open source databases, and cloud-native services. The lifecycle and operations of services are the responsibility of {{site.data.keyword.IBM_notm}}.

You can also find a number of software products, including [Cloud Paks](https://www.youtube.com/watch?v=DzFhhSR8SSs){: external}, Terraform-based templates, Helm charts, and Operators. The preconfigured software solutions help you build faster. And, with a simplified installation process, you can get started quickly. You manage the deployment and configuration of the software on your own compute resources.

If you're looking for more robust solutions for your enterprise business goals, {{site.data.keyword.cloud_notm}} offers deployable architectures that use cloud automation for deploying common architectural patterns that combine one or more cloud resources that are designed for easy deployment, scalability, and modularity.

And, if you're looking for help in your journey to cloud, check out our professional services. Browse your options for scheduling a consultation with technical experts depending on your needs, such as cloud migration, creating business solutions with {{site.data.keyword.IBM_notm}} Garage, or developing a container security solution that works for you.

The catalog supports command-line interfaces (CLIs) and a RESTful API for you to use to retrieve information about existing products.
{: tip}

### Searching the catalog for services
{: #catalog-filter-options}

All products that are available in {{site.data.keyword.cloud_notm}} are displayed by default in the catalog. You can filter the catalog by type to view a specific type of product, for example, only services, software, or deployable architectures. Enter keywords or set additional filters to further scope your view of the catalog. For example, if you want to deploy an analytics instance to {{site.data.keyword.openshiftlong}}, you can select the **Analytics** category, and filter the results by selecting **Red Hat OpenShift** as the deployment target.

See the following table for the list of filters that you can use to search the catalog.
{: #filters}

| Option      | Description  |
|------------------|-------|
| AI / Machine Learning | Products that enable systems to learn from data rather than through explicit programming |
| Analytics | Products that facilitate the analysis of data, typically large sets of business data, by the use of mathematics, statistics, and other means |
| Blockchain | Products that facilitate the process of recording transactions and tracking assets in a business network |
| Compute | Infrastructure resources that serve as the basis for building apps in the cloud |
| Containers | A standard unit of software that packages up code and all its dependencies so the app runs quickly and reliably from one computing environment to another |
| Converged infrastructure | A way of structuring an information technology (IT) system by grouping multiple components into a single optimized computing package, components of which may include servers; data storage devices; networking equipment; and software for IT infrastructure management, automation and orchestration |
| Databases | Products that provide some form of access to a database without the need for setting up physical hardware, installing software, or configuring for performance |
| Developer tools | Products that support developing, testing, and debugging software |
| Enterprise applications | Bundle of compatible products that deliver enterprise-grade app solutions for information sharing, automation, and agility |
| Integration | Products that facilitate the connection of data, apps, APIs, and devices across an organization to be more efficient, productive, and agile |
| Internet of Things | Products that support receiving and transferring data over wireless networks without human intervention |
| Logging and monitoring | Products that support storing, searching, analyzing, and monitoring log data and events. And, products that support reviewing and managing the operational workflow and processes being logged |
| Mobile | Products with specific or special utility for users creatings things to be used on mobile devices |
| Networking | Products that support or augment the linking of computers so they can operate interactively |
| Security | Products that provide the protection of stored data from theft, leakage, and deletion |
| Storage  | Products that support data to be created, read, updated, and deleted |
{: caption="Table 1. Options for filtering by category" caption-side="top"}
{: #category-svc}
{: tab-title="Category"}
{: tab-group="cfo"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the options for fitering based on filter type."}

| Option | Description |
|--------------|-------|
| EU Supported | Support for the service is restricted to {{site.data.keyword.cloud_notm}} support team members that are located in the European Union (EU) region. This filter is available only if the [EU Supported setting](/docs/account?topic=account-eu-supported) is enabled in the account.  |
| Financial Services Validated | Services are designated as Financial Services Validated when the {{site.data.keyword.cloud_notm}} service or SaaS, or independent software vendor (ISV) product, evidences compliance with the {{site.data.keyword.cloud_notm}} Framework for Financial Services. This filter is available only for {{site.data.keyword.IBM_notm}} products, and if the [Financial Services Validated setting](/docs/account?topic=account-enabling-fs-validated) is enabled in the account. |
| HIPAA Enabled | The service is designated as HIPAA ready, meaning processing, storing, and handling Protected Health Information (PHI) in the service is supported. This filter is available only if the [HIPAA Supported setting](/docs/account?topic=account-enabling-hipaa) is enabled in the account. |
| IAM-enabled | The service is enabled to use {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM) for access control. Access policies are used to assign users and service IDs access to specific resources in an account.|
| Service Endpoint Supported | The service can be connected to over the {{site.data.keyword.cloud_notm}} private network instead of the public network. Connecting directly to service endpoints doesn't require internet access, providing increased security. |
{: caption="Table 1. Options for filtering by compliance" caption-side="top"}
{: #compliance-svc}
{: tab-title="Compliance"}
{: tab-group="cfo"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the options for fitering based on filter type."}

| Option | Description |
|--------------|-------|
| Free | The service includes monthly free allowances for only Pay-As-You-Go or Subscription accounts. |
| Lite | The pricing plan for the service is structured as a free quota. The quota might operate for a specific time period, for example, a month or on a one-off usage basis. |
{: caption="Table 1. Options for filtering by pricing plan" caption-side="top"}
{: #pricingplan-svc}
{: tab-title="Pricing plan"}
{: tab-group="cfo"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the options for fitering based on filter type."}

| Option | Description |
|--------------|-------|
| Beta | The service is available for evaluation and testing purposes. Beta services aren't intended for production use. |
| Deprecated | Deprecated products are in the process of being withdrawn from service and are eligible to be removed after the deprecation period. |
{: caption="Table 1. Options for filtering by release" caption-side="top"}
{: #release-svc}
{: tab-title="Release"}
{: tab-group="cfo"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the options for fitering based on filter type."}

| Option | Description |
|--------------|-------|
| {{site.data.keyword.IBM_notm}} supported | Products that are supported by {{site.data.keyword.cloud_notm}}. |
| Third party supported | Products that are provided by individual service entities. |
| Community supported | Products that are provided by open source communities. |
{: caption="Table 1. Options for filtering services by support type" caption-side="top"}
{: #support-svc}
{: tab-title="Support"}
{: tab-group="cfo"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the options for fitering based on filter type."}

| Option | Description |
|--------------|-------|
| HPC | Products that enable High Performance Computing (HPC) workloads on {{site.data.keyword.cloud_notm}}. For more information, see [High-performance computing on {{site.data.keyword.cloud_notm}}](https://www.ibm.com/cloud/hpc){: external} |
| SAP Certified | An infrastructure service that is certified by SAP to run production SAP workloads. For more information, see [{{site.data.keyword.ibm_cloud_sap}}](/docs/sap).|
| Satellite Enabled | A service that is enabled for use with {{site.data.keyword.cloud_notm}} Satellite. You can run apps consistently across on-premises, edge computing, and public cloud environments. For more information, see [{{site.data.keyword.cloud_notm}} {{site.data.keyword.satelliteshort}}](https://www.ibm.com/cloud/satellite){: external}. |
| Quantum Technologies | A service that is compatible with quantum technologies. For more information, see [{{site.data.keyword.IBM_notm}} Quantum services](http://cloud.ibm.com/quantum){: external}. |
{: caption="Table 1. Options for filtering by run-time environment" caption-side="top"}
{: #supported-env-svc}
{: tab-title="Works with"}
{: tab-group="cfo"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the options for fitering based on filter type."}

You can also scope your view of the catalog by using the **Provider** filter to browse by individual providers, and the **Location** filter to view products available in specific regions.
{: tip}


### Searching the catalog for software
{: #catalog-filter-sw}

The following table lists the filter options you can use when searching the catalog for software.

| Option | Description |
|-----|-----|
| AI / Machine Learning | Products that enable systems to learn from data rather than through explicit programming |
| Analytics | Products that facilitate the analysis of data, typically large sets of business data, by the use of mathematics, statistics, and other means |
| Blockchain | Products that facilitate the process of recording transactions and tracking assets in a business network |
| Compute | Infrastructure resources that serve as the basis for building apps in the cloud |
| Containers | A standard unit of software that packages up code and all its dependencies so the app runs quickly and reliably from one computing environment to another |
| Converged infrastructure | A way of structuring an information technology (IT) system by grouping multiple components into a single optimized computing package, components of which may include servers; data storage devices; networking equipment; and software for IT infrastructure management, automation and orchestration |
| Databases | Products that provide some form of access to a database without the need for setting up physical hardware, installing software, or configuring for performance |
| Developer tools | Products that support developing, testing, and debugging software |
| Enterprise applications | Bundle of compatible products that deliver enterprise-grade app solutions for information sharing, automation, and agility |
| Integration | Products that facilitate the connection of data, apps, APIs, and devices across an organization to be more efficient, productive, and agile |
| Internet of Things | Products that support receiving and transferring data over wireless networks without human intervention |
| Logging and monitoring | Products that support storing, searching, analyzing, and monitoring log data and events. And, products that support reviewing and managing the operational workflow and processes being logged |
| Mobile | Products with specific or special utility for users creatings things to be used on mobile devices |
| Networking | Products that support or augment the linking of computers so they can operate interactively |
| Security | Products that provide the protection of stored data from theft, leakage, and deletion |
| Storage  | Products that support data to be created, read, updated, and deleted |
{: caption="Table 2. Options for filtering by category" caption-side="top"}
{: #swcategoryfilters}
{: tab-title="Category"}
{: tab-group="swfilteroptions"}
{: class="simple-tab-table"}

| Option | Description |
|--------------|-------|
| Cloud Paks | A cloud solution that integrates a container platform, containerized IBM middleware and open source components, and common software services for development and management. |
| Helm charts | A format for packaging a collection of files that describe specific configurations of infrastructure in the form of code.|
| OVA images | Open Virtual Appliance that contains a compressed installable version of a virtual machine.  |
| Operators | A method of packaging and deploying a Kubernetes-native application. |
| Server Images | A template that is used to create instances of virtual servers. |
| Terraform | Infrastructure as code to deploy your application. |
{: caption="Table 2. Options for filtering by delivery method" caption-side="top"}
{: #swsoftwarefilters}
{: tab-title="Delivery method"}
{: tab-group="swfilteroptions"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the options for fitering based on filter type."}

| Option | Description |
|--------------|-------|
| IBM {{site.data.keyword.containershort}} | Used to create a Kubernetes cluster of compute hosts to deploy and manage containerized apps on {{site.data.keyword.cloud_notm}}. |
| {{site.data.keyword.bplong_notm}} | Used for infrastructure as code automation by using terraform templates. |
| {{site.data.keyword.powerSys_notm}} | Used to create a Power server that is distinct from the {{site.data.keyword.cloud_notm}} servers with separate networks and direct-attached storage. The internal networks are fenced but offer connectivity options to  {{site.data.keyword.cloud_notm}} infrastructure or on-premises environments. |
| Red Hat OpenShift | Used to create a {{site.data.keyword.openshiftshort}} cluster of compute hosts to deploy and manage containerized apps on {{site.data.keyword.cloud_notm}}. |
| VMware vCenter Server | Provides deployment and management of VMware virtualized environments. |
| Virtual private cloud | Deploy and manage your server images on virtual private cloud as your infrastructure target. |
{: caption="Table 2. Options for filtering by deployment target" caption-side="top"}
{: #swdeploymenttargetfilters}
{: tab-title="Deployment target"}
{: tab-group="swfilteroptions"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the options for fitering based on filter type."}

| Option | Description |
|--------------|-------|
| Free | The service includes monthly free allowances for only Pay-As-You-Go or Subscription accounts. |
| Lite | The pricing plan for the service is structured as a free quota. The quota might operate for a specific time period, for example, a month or on a one-off usage basis. |
{: caption="Table 2. Options for filtering software by pricing plan" caption-side="top"}
{: #pricingplan-software}
{: tab-title="Pricing plan"}
{: tab-group="swfilteroptions"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the options for fitering based on filter type."}

| Option | Description |
|--------------|-------|
| {{site.data.keyword.IBM_notm}} supported | Products that are supported by {{site.data.keyword.cloud_notm}}. |
| Third party supported | Products that are provided by individual service entities. |
| Community supported | Products that are provided by open source communities. |
{: caption="Table 2. Options for filtering software by support type" caption-side="top"}
{: #support-type-software}
{: tab-title="Support"}
{: tab-group="swfilteroptions"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the options for fitering based on filter type."}

| Option | Description |
|--------------|-------|
| HPC | Products that enable High Performance Computing (HPC) workloads on {{site.data.keyword.cloud_notm}}. For more information, see [High-performance computing on {{site.data.keyword.cloud_notm}}](https://www.ibm.com/cloud/hpc){: external} |
| SAP Certified | An infrastructure service that is certified by SAP to run production SAP workloads. For more information, see [{{site.data.keyword.ibm_cloud_sap}}](/docs/sap).|
| Satellite Enabled | A service that is enabled for use with {{site.data.keyword.cloud_notm}} Satellite. You can run apps consistently across on-premises, edge computing, and public cloud environments. For more information, see [{{site.data.keyword.cloud_notm}} {{site.data.keyword.satelliteshort}}](https://www.ibm.com/cloud/satellite){: external}. |
| Quantum Technologies | A service that is compatible with quantum technologies. For more information, see [{{site.data.keyword.IBM_notm}} Quantum services](http://cloud.ibm.com/quantum){: external}. |
{: caption="Table 2. Options for filtering software by run-time environment" caption-side="top"}
{: #supported-env-software}
{: tab-title="Works with"}
{: tab-group="swfilteroptions"}
{: class="simple-tab-table"}
{: summary="Use the buttons before the table to change the context of the table. The column headers identify the options for fitering based on filter type."}

You can also scope your view of the catalog by using the **Provider** filter to browse by individual providers, and the **Location** filter to view products available in specific regions.
{: tip}

### Searching the catalog for deployable architectures
{: #deployable-arch-search}

You can search our growing catalog of deployable architectures to find preassmbled cloud auotmation solutions that solve common enterprise business needs, for example a secure infrastructure layer for highly regulated industries, such as financial services.

The following table lists the filter options that you can use when searching the catalog for deployable architectures.

| Option | Description |
|-----|-----|
| AI / Machine Learning | Products that enable systems to learn from data rather than through explicit programming |
| Analytics | Products that facilitate the analysis of data, typically large sets of business data, by the use of mathematics, statistics, and other means |
| Blockchain | Products that facilitate the process of recording transactions and tracking assets in a business network |
| Compute | Infrastructure resources that serve as the basis for building apps in the cloud |
| Containers | A standard unit of software that packages up code and all its dependencies so the app runs quickly and reliably from one computing environment to another |
| Converged infrastructure | A way of structuring an information technology (IT) system by grouping multiple components into a single optimized computing package, components of which may include servers; data storage devices; networking equipment; and software for IT infrastructure management, automation and orchestration |
| Databases | Products that provide some form of access to a database without the need for setting up physical hardware, installing software, or configuring for performance |
| Developer tools | Products that support developing, testing, and debugging software |
| Enterprise applications | Bundle of compatible products that deliver enterprise-grade app solutions for information sharing, automation, and agility |
| Integration | Products that facilitate the connection of data, apps, APIs, and devices across an organization to be more efficient, productive, and agile |
| Internet of Things | Products that support receiving and transferring data over wireless networks without human intervention |
| Logging and monitoring | Products that support storing, searching, analyzing, and monitoring log data and events. And, products that support reviewing and managing the operational workflow and processes being logged |
| Mobile | Products with specific or special utility for users creatings things to be used on mobile devices |
| Networking | Products that support or augment the linking of computers so they can operate interactively |
| Security | Products that provide the protection of stored data from theft, leakage, and deletion |
| Storage  | Products that support data to be created, read, updated, and deleted |
{: caption="Table 3. Options for filtering by category" caption-side="top"}

You can also scope your view of the catalog by using the **Provider** filter to browse by individual providers and the **Industry** filter to view products catered for certain industries.
{: tip}



## Pricing and billing
{: #pricing-billing}

You can view the pricing details for each service when you're browsing the catalog. If you choose a service plan with a paid plan, you can estimate your costs by using the cost estimator tool. For more information, see [Estimating your costs](/docs/billing-usage?topic=billing-usage-cost).

{{site.data.keyword.Bluemix_notm}} billing provides multiple services that ensure the {{site.data.keyword.Bluemix_notm}} platform can securely manage pricing, accounts, usage, and more.

### Account management
{: #account-mgmt}

Account management maintains the billing relationship with the customer. Each account is a billing entity that represents a customer. This service controls account lifecycle, subscription, user relationship, and organization.

### Usage metering
{: #metering}

With usage metering, service providers can submit metrics that are collected for resource instances that are created by {{site.data.keyword.Bluemix_notm}} users. Third-party service providers that deliver an integrated billing service are required to submit usage for all active service instances every hour.

### Usage reports
{: #usage}

Usage reports return the summary for the account for the specified month. Account billing managers are authorized to access the reports.

## Managing security and compliance
{: #account-security-compliance}

The {{site.data.keyword.compliance_full}} offers a single location where you can validate that your resources are meeting continuous security and compliance.

You can create profiles and config rules to ensure that specific areas of your business adhere to your defined requirements or industry regulations. From the {{site.data.keyword.compliance_short}} dashboard, you can download detailed reports that you can use to provide evidence to stakeholders or external auditors. The {{site.data.keyword.compliance_short}} also offers security insights that you can use to detect potential threats when observing your account activity. For more information, see [Getting started with {{site.data.keyword.compliance_short}}](/docs/security-compliance?topic=security-compliance-getting-started).

## Creating resources
{: #provisioning-layer}

The resource controller is the next-generation {{site.data.keyword.Bluemix_notm}} platform provisioning layer that manages the lifecycle of {{site.data.keyword.Bluemix_notm}} resources in your account. Resources are created globally in an account scope. The resource controller supports the creation of resources both synchronously and asynchronously. Examples of resources include databases, accounts, processors, memory, and storage limits.

In general, resources that are tracked by the provisioning layer are intended to associate usage metrics and billing, but that isn’t always the case. In some cases, the resource might be associated with the provisioning layer to ensure that its lifecycle can be managed along with the account lifecycle. The resource controller uses {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) for authentication and authorization of actions that are taken against the provisioning layer.

The resource controller provides common APIs to control the lifecycle of resources from creating an instance to creating access credentials to removing access to deleting an instance.

## Managing your resources
{: #resource-manager}

A collection of resources is managed by [resource groups](/docs/account?topic=account-rgs). A resource group is associated with your account. All {{site.data.keyword.Bluemix_notm}} resources must be assigned to a resource group. When you create an account, a default resource group is created for you. All {{site.data.keyword.Bluemix_notm}} IAM-enabled resources must be created within a resource group. If you have a Lite account, you can have only one resource group, but with a a Pay-As-You-Go or Subscription account, you can create more than one resource group. If an account is suspended, the corresponding resource group is suspended as well, and all resources within the resource group are suspended.

## Managing Infrastructure as Code (IaC) deployments with projects
{: #projects}

{{site.data.keyword.cloud_notm}} [projects](#x2035151){: term} are a named collection of configurations that are used to manage related resources and Infrastructure as Code (IaC) deployments across accounts. They enable teams to configure, deploy, and monitor deployments by using DevOps best practices. If you select a deployable architecture from the catalog, you can add it to a project to configure and deploy it into your different environments. For more information, see [Learn about IaC deployments with projects](/docs/secure-enterprise?topic=secure-enterprise-understanding-projects).

## Searching and tagging resources
{: #search-and-tag}

The search service is a global and shared resource properties repository that is integrated within the {{site.data.keyword.Bluemix_notm}} platform. It is used for storing and searching a cloud resource's attributes, and it categorizes and classifies resources. Resources are uniquely identified by a [Cloud Resource Name (CRN)](/docs/account?topic=account-crn) identifier. The properties of a resource include tags and system properties. Both properties are defined within an {{site.data.keyword.Bluemix_notm}} billing account, and span across many regions.

This service also manages tags that are associated with a resource. You can create, delete, search, attach, or detach tags with the Tagging API. Tags are uniquely identified by a CRN identifier. Tags have a name, which must be unique within a billing account. You can create tags in key:value pairs or label format.

## Monitoring your resources
{: #resources_observability}

Observability offers a single location where you can monitor and observe your applications and services in {{site.data.keyword.Bluemix_notm}}.

With the {{site.data.keyword.la_full}} service, you can add log management capabilities to your {{site.data.keyword.Bluemix_notm}} architecture and you can manage system and application logs. It offers advanced features to monitor and troubleshoot, define alerts, and design custom dashboards. For more information, see [Getting started with {{site.data.keyword.la_full_notm}}](/docs/log-analysis?topic=log-analysis-getting-started).

You can gain operational visibility into the performance and health of your applications, services, and platforms with the {{site.data.keyword.mon_full_notm}} service. It offers a full stack telemetry with advanced features to monitor and troubleshoot, define alerts, and design custom dashboards. For more information, see [Getting started with {{site.data.keyword.monitoringlong_notm}}](/docs/monitoring?topic=monitoring-getting-started#getting-started).

## Monitoring your account
{: #account_observability}

Use the {{site.data.keyword.at_full}} service to monitor the activity of your {{site.data.keyword.Bluemix_notm}} account, investigate abnormal activity and critical actions, and comply with regulatory audit requirements. In addition, you can be alerted on actions as they happen. The events that are collected comply with the Cloud Auditing Data Federation (CADF) standard. For more information, see [Getting started with {{site.data.keyword.at_full_notm}}](/docs/activity-tracker?topic=activity-tracker-getting-started).


## Viewing status
{: #status-service}

The {{site.data.keyword.Bluemix_notm}} Status page is the central place to find all unplanned incidents, planned maintenance, announcements, and security bulletin notifications about key events that affect the {{site.data.keyword.Bluemix_notm}} platform. You can filter these categories by selecting specific locations, components, types of ongoing events, or by using keyword searches. For more information, see [Viewing cloud status](/docs/get-support?topic=get-support-viewing-cloud-status).


## Notification preferences
{: #notification-preference}

Depending on your {{site.data.keyword.Bluemix_notm}} account type, you can choose to receive email notifications about {{site.data.keyword.Bluemix_notm}} platform-related items and resource-related items from the [Notification preferences page](https://cloud.ibm.com/user/notifications){: external}. Platform-related items include announcements, billing and usage, and ordering. Resource-related items include incidents, maintenance, security bulletins, and resource activity. For more information, see [Setting email preferences for notifications](/docs/account?topic=account-email-prefs).
