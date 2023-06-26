---
copyright:
  years: 2015, 2023

lastupdated: "2023-06-26"

keywords: release notes, what's new in IBM Cloud, what's new for the platform, what is new, cloud updates, new features, platform release notes

subcollection: overview

content-type: release-note

---

{{site.data.keyword.attribute-definition-list}}

# Release notes for the {{site.data.keyword.cloud_notm}} platform
{: #whatsnew}

Stay up-to-date with the new features that are available on the {{site.data.keyword.Bluemix}} platform so that you get the most out of your {{site.data.keyword.Bluemix_notm}} experience.
{: shortdesc}

## June 2023
{: #june-2023}

### 6 June 2023
{: #overview-june0223}
{: release-note}

New event notifications for projects
:   You can now send out notifications when a deployment is complete or when resources are successfully destroyed. For more information, see the [available events for projects](/docs/secure-enterprise?topic=secure-enterprise-event-notifications-events&interface=ui#event-notifications-list).

Support for access management tags in the projects UI
:   You can now add, edit, and delete access management tags directly in the projects UI. Previously, you could manage these tags only by using the command-line interface (CLI) or API.

## April 2023
{: #april-2023}

### 25 April 2023
{: #overview-apr2423}
{: release-note}

Customized compliance validation
:   In addition to using default controls, you can specify a {{site.data.keyword.compliance_short}} attachment to validate deployable architectures that you're configuring in a project. For more information, see [Configuring the architecture](/docs/secure-enterprise?topic=secure-enterprise-config-project#how-to-config).

Support for deployable architectures onboarded from private or public GitHub repositories
:   You can now deploy architectures that are onboarded to the catalog from either a private or public GitHub repository. Previously, only deployable architectures onboarded from a public GitHub repository were supported.

### 17 April 2023
{: #overview-apr1723}
{: release-note}

Check out deployable architectures in the catalog
:   {{site.data.keyword.cloud_notm}} provides deployable architectures in the catalog, which are products that provide automation for the deployment of common architectural patterns that combine one or more cloud resources and are designed for scalability and modularity. Go to the catalog, and [filter by Deployable architectures](/catalog#reference_architecture) to review the growing catalog of options. For more information, see [Identifying the right infrastructure architecture](/docs/overview?topic=overview-secure-enterprise#define-architecture).

{{site.data.keyword.cloud_notm}} projects for automated IaC deployments
:   You can now configure, deploy, and monitor deployments by using DevOps best practices with projects. By using projects, you can manage Infrastructure as Code (IaC) at scale and across accounts to ensure that the configuration is always valid, secure, and compliant. [Learn more about IaC deployments with projects](/docs/secure-enterprise?topic=secure-enterprise-understanding-projects).

Onboard customized deployable architectures for your enterprise users
:   You can customize {{site.data.keyword.cloud_notm}} deployable architectures to meet your enterprise’s needs, and then leverage private catalogs to make only approved and compliant architectures available for your enterprise developers to deploy. For more information, see [Customizing an {{site.data.keyword.cloud_notm}} deployable architecture](/docs/secure-enterprise?topic=secure-enterprise-customize-from-catalog).

### 12 April 2023
{: #overview-apr1223}
{: release-note}

Selecting languages for community support
:   If you offer a community type of support for your product provided by open source communities, Partner Center now gives you the option to select the languages in which support is provided. By providing support in multiple languages, your customers can communicate their issues in their preferred language and get support more efficiently. For more information, see [Defining your support experience](/docs/sell?topic=sell-saas-support-details&interface=ui).

### 10 April 2023
{: #overview-apr1023}
{: release-note}

Checking the delivery status of email notifications and viewing email history
:   The new Communication history page provides a way for you to check the status of all email notifications that are sent you and you can verify whether the emails are delivered successfully. You can also view the last 90 days of {{site.data.keyword.cloud_notm}} email history, which can help you save time by troubleshooting any delivery issues without you having to contact {{site.data.keyword.IBM_notm}} support. For more information, see [Checking the delivery status of email notifications and viewing email history](/docs/get-support?topic=get-support-viewing-notifications#view-email-history).

### 04 April 2023
{: #overview-apr0423}
{: release-note}

Customize the look and feel of your private catalog
:   You can enhance the appearance of your private catalog to match your brand by adding a custom banner image to your private catalogs. For more information about personalizing your private catalog, see [Branding your private catalog with a custom banner](/docs/account?topic=account-restrict-by-user#customer-banner).

Add a custom provider name for your private products
:   You can make it easier for users to search for your products added to a private catalog by specifying a custom provider name. Adding a custom provider name for your private products can help users find them quickly by using the Provider filter in the catalog. For more information, see [Providing catalog entry details](/docs/account?topic=account-cm-catalog-details#cm-catalog-entry).

## March 2023
{: #march-2023}

### 29 March 2023
{: #overview-29march23}
{: release-note}

Generate a report on the MFA status of account users
:   Users that don't meet MFA requirements leave your account vulnerable. You can now identify the users in your account that don't satisfy your MFA requirements. For more information, see [Identifying a user's MFA status](/docs/account?topic=account-id-user-mfa).

An extra layer of security for users that don't use MFA
:   {{site.data.keyword.Bluemix_notm}} recommends enabling multifactor authentication (MFA) for all users in your account, but some automation scenarios might require you to exclude specific users from your MFA requirement. For users that are excluded from MFA, you can make access more secure by disabling CLI logins with only a username and password. This way, you require an API key to log in to the CLI or users can log in with `--sso`. For more information, see [Disabling MFA](/docs/account?topic=account-enablemfa#disablemfa).

## February 2023
{: #february-2023}

### 22 February 2023
{: #overview-22feb23}
{: release-note}

User-specific MFA
:   You can now enforce user-specific multifactor authentication (MFA) requirements that differ from the account default MFA setting. After you update the MFA requirement for an individual user, view a list of users that have unique MFA requirements in the account by going to Manage > Access (IAM) > Settings > Authentication. For more information, see [Enabling MFA for an individual user](/docs/account?topic=account-enablemfa&interface=ui#enabling-user).

### 20 February 2023
{: #overview-20feb23}
{: release-note}

Download and read {{site.data.keyword.cloud_notm}} docs offline
:   While digital is still the primary delivery target for {{site.data.keyword.cloud_notm}} docs, you can now print or download and read a doc set offline. Go to the menu next to the doc set title in the navigation and click **View as PDF**.

## January 2023
{: #january-2023}

### 27 January 2023
{: #overview-27jan23}
{: release-note}

New services integrating with context-based restriction
:   Services continue to integrate with the {{site.data.keyword.Bluemix_notm}} platform's context-based restrictions feature, including [{{site.data.keyword.vpc_full}} (VPC) Infrastructure Services](/docs/vpc?topic=vpc-cbr). To see a full list of services that can use context-based restrictions to define and enforce access restrictions on their resources, see [Services integrated with context-based restrictions](/docs/account?topic=account-context-restrictions-whatis#cbr-adopters).

### 25 January 2023
{: #overview-25jan23}
{: release-note}

Time-based conditions in IAM access policies
:   {{site.data.keyword.Bluemix_notm}} IAM is excited to give customers the ability to set access controls based on a specified time and date. You can now create policies that grant employees access to a resource during only their working hours, or grant automated processes temporary access for a specified duration. Implementing such limitations helps you to apply the principle of least privilege for assigning access and reduces the opportunity for attack in the event of a security breach. For more information, see [Limiting access with time-based conditions](/docs/account?topic=account-iam-time-based&interface=ui).

IAM Policy Management API V2 release
:   A new version (`v2`) of the IAM Policy Management API is now available. This version adds a new JSON schema to support a conditional policy construct and several time-based comparison operators. These operators provide the capability to restrict access based on time and date. With time-based access control, customers can establish granular policy enforcement based on a specified time period. For more information, see the [IAM Policy Management API change log](/docs/account?topic=account-api-change-log&interface=ui)

### 09 January 2023
{: #overview-09jan23}
{: release-note}

Save and share multiple estimates by using the {{site.data.keyword.cloud_notm}} Cost Estimator
:   The {{site.data.keyword.cloud_notm}} Cost Estimator now allows a customer to save multiple estimates to their account and share those estimates with users that belong to the same account. For more information, see [Estimating your costs](/docs/billing-usage?topic=billing-usage-cost).

## December 2022
{: #december-2022}

### 15 December 2022
{: #overview-dec1522}
{: release-note}

Checklist for getting started on {{site.data.keyword.cloud_notm}}
:   A new checklist is now available in the {{site.data.keyword.cloud_notm}} docs for [Getting started on {{site.data.keyword.cloud_notm}}](/docs/overview?topic=overview-get-started-checklist). This checklist outlines the tasks for you to complete to accelerate your journey to cloud by guiding you through your account setup and organization of resources.

## October 2022
{: #october-2022}

### 10 October 2022
{: #overview-10oct2022}
{: release-note}

A new way to provide the {{site.data.keyword.cloud_notm}} docs team your feedback
:   We want to hear from you! Let us know about your experience with the {{site.data.keyword.cloud_notm}} docs or API docs by submitting your feedback from the **Feedback** button. You can tell us what you love and even what you’d like to see improved, so we can work together to ensure that you always enjoy the {{site.data.keyword.cloud_notm}} documentation.

### 07 October 2022
{: #overview-07oct2022}
{: release-note}

Setting an alternative account owner
:   As the owner of an account with classic infrastructure, you can set a trusted profile as the alternative account owner. An alternative account owner ensures that you always have a secure way to manage account ownership if your account owner leaves your organization or isn't available. For more information, see [Setting an alternative account owner](/docs/account?topic=account-classic-infra-owner&interface=ui).

### 04 October 2022
{: #overview-04oct2022}
{: release-note}

Catalog integration with Virtual Private Cloud custom images
:   ISV Partners and {{site.data.keyword.cloud_notm}} customers can now import custom VPC images directly to their account or enterprise, or sell on the IBM Cloud catalog without depending on Terraform. For more information, see [Onboarding a virtual server image for VPC](/docs/account?topic=account-catalog-vsivpc-tutorial).

## September 2022
{: #september-2022}

### 29 September 2022
{: #overview-29sept2022}
{: release-note}

Enabling {{site.data.keyword.en_full_notm}} for the notification distribution list
:   You can now easily add {{site.data.keyword.en_short}} instances to the notification distribution list and receive account-wide {{site.data.keyword.cloud_notm}} notifications. With {{site.data.keyword.en_short}}, you can choose to deliver your notifications to different destinations, including email, SMS, or webhooks. When an event of interest occurs on the {{site.data.keyword.cloud_notm}} platform and an event is generated, the notification distribution list communicates with a connected {{site.data.keyword.en_short}} instance to forward a notification to the supported destination.

For more information, see [Enabling {{site.data.keyword.en_short}} for the notification distribution list](/docs/account?topic=account-add-users-distribution-list#event-notifications-distribution-list).

### 26 September 2022
{: #overview-26sept2022}
{: release-note}

Identifying inactive policies
:   To reduce the number of policies in your account and keep only the minimum access that is necessary for each user, you can now identify the infrequently used access policies on the [Inactive policies](/iam/inactive-policies) page in the console. You can determine whether to remove the inactive policies, or in some cases, you might expect an infrequently used policy. For more information, see [Managing inactive policies](/docs/account?topic=account-iam-audit-policies&interface=ui#iam-audit-policies-list).

Exporting user access reports
:   Make sure that users have only the access that they need. Export an access policy report for any user in your account to view all of the access policies that they are assigned. For more information, see [Exporting user access policy reports](/docs/account?topic=account-iam-audit-policies&interface=ui#audit-user-access).

### 22 September 2022
{: #overview-22sept2022}
{: release-note}

A new way to provide {{site.data.keyword.cloud_notm}} your feedback
:   We want to hear from you! Let us know about your experience with the {{site.data.keyword.cloud_notm}} console by submitting your feedback from the **Help** > **Send feedback** option in the console menu bar. You can tell us what you love and even what you’d like to see improved, so we can work together to ensure that you always enjoy developing on {{site.data.keyword.cloud_notm}}.

### 21 September 2022
{: #overview-21sept2022}
{: release-note}

Getting help in the console
:   You can now find the documentation and Support Center help options from a single menu item in the {{site.data.keyword.cloud_notm}} console menu bar. Check out the new **Help** option from the console menu bar that now includes your links for [Docs](/docs), the [Support Center](https://cloud.ibm.com/unifiedsupport/supportcenter), a form to give us feedback, and available guided tours.

### 16 September 2022
{: #overview-16september2022}
{: release-note}

Attaching tags on service IDs
:   In addition to tagging resources, you can now attach user tags and access management tags on service IDs. User tags help you group service IDs for usage reports, and you can use access management tags to control access to your service IDs. For more information, see [Working with tags](/docs/account?topic=account-tag&interface=ui).

Specifying a user onboarding strategy
:   If you’re [Enabling and connecting your identity provider](/docs/account?topic=account-idp-integration#idp-console), you can now specify how you want to onboard users to the account upon first-time login. This way, you can add each user to your account when they log in the first time, add users to your account only if they log in and don't select a trusted profile, or never add users to your account and provide access only by using trusted profiles. For more information about trusted profiles, see [Creating trusted profiles](/docs/account?topic=account-create-trusted-profile).

### 02 September 2022
{: #overview-02september2022}
{: release-note}

Increased policy limit
:   The shared limit for IAM policies and context-based restrictions has increased from 2010 to 4020 so that you don't need to [request an increase to the limit in your account](/docs/account?topic=account-account-limits&interface=cli#limit-increase) as you grow your organizational capacity. For more information, see [Known issues and limitations](/docs/account?topic=account-known-issues#iam_limits).

## August 2022
{: #august-2022}

### 31 August 2022
{: #overview-31aug2022}
{: release-note}

Choose from dark or light themes in the console
:   Enjoy a customized experience in the console that matches your preferences. By default, the console uses the mode that you already have set for your device. We'd like you to be able to experience {{site.data.keyword.cloud_notm}} using a theme of your choosing. Use the Avatar icon from the console menu bar to find the options for changing your theme.

## July 2022
{: #july-2022}

### 21 July 2022
{: #overview-21july2022}
{: release-note}

Monitoring context-based restrictions
:   To help you predict how context-based restrictions might affect users, applications, and workflows, {{site.data.keyword.cloud_notm}} is excited to release report-only mode for rules. You can enable context-based restrictions during creation, or choose to set the rule to report-only mode. Using {{site.data.keyword.cloudaccesstrailshort}}, you can monitor the impact of enabled rules, or view report-only rules to see how they will affect your users, applications, and workflows without enforcing the rule. For more information, see [Monitoring context-based restrictions](/docs/account?topic=account-cbr-monitor).

### 08 July 2022
{: #overview-08july2022}
{: release-note}

Streamlined process for updating published support information in Partner Center
:   You can update support information for your published products by editing your already approved support information and then requesting an approval. After your changes are approved, you can publish the updates. For more information, see [Updating your product's support information](/docs/sell?topic=sell-saas-support-details#service-support-include-update-support-details).

## June 2022
{: #june-2022}

### 23 June 2022
{: #overview-23june2022}
{: release-note}

Onboarding software to sell on {{site.data.keyword.cloud_notm}} by using the API
:   To sell your products on {{site.data.keyword.cloud_notm}}, you can now onboard and publish by using the Partner Center Sell API, in addition to using the Partner Center experience in the console. For more information, see [Partner Center Sell API](/apidocs/partner-center-sell).

### 22 June 2022
{: #overview-22june2022}
{: release-note}

Identify inactive identities
:   You can create a report in the [IBM Cloud console](/iam/inactive-identities) to identify which users, service IDs, trusted profiles, and API keys in your account are inactive. Removing access for inactive identities can reduce the risk of unauthorized access to your {{site.data.keyword.cloud}} resources and help you manage access more efficiently. For more information, see [Identifying inactive identities](/docs/account?topic=account-id-inactive-identities).

Updated process for assigning access
:   Assigning IAM, Classic Infrastructure, and {{site.data.keyword.ibmcf_notm}} access just got more streamlined. When assigning access, each service that you select has an in-context description. You can also find all IAM access policy and access group information for an identity under a single tab. Check out the updated process by assigning access to any user, service ID, or trusted profile.

Assign a policy for All IAM Account Management services
:   You can now assign an access policy for All IAM Account Management services, which includes the IAM Identity service, IAM Access Management service, IAM User Management service, IAM Access Groups service, and future IAM services. By assigning an access policy for a group of services, you decrease the number of policies in your account and reduce the time and effort to manage access.

### 13 June 2022
{: #overview-13june2022}
{: release-note}

Updated process for onboarding services in Partner Center
:   Partner Center has made it easier to provide required support information. The process has improved the approval process for publishing your product, and it has added consistency to all third-party product information which helps customers find the help that they need.

For more information, see [Defining your support experience](/docs/sell?topic=sell-saas-support-details).

## May 2022
{: #may-2022}

### 04 May 2022
{: #overview-may2022}
{: release-note}

Required access to view service credentials
:    When the credential level access can't be determined by comparing the access of the user and the credential, the credential is redacted. Services that support access control on resources that are allocated in the context of a service instance, such as Cloud Object Storage buckets, now require the user to have the resource-controller.credential.retrieve_all action to view service credentials.

To determine if your service is affected, review your service's documentation. For more information about the required access to view service credentials, see [Viewing a credential](/docs/account?topic=account-service_credentials&interface=ui#viewing-credentials-ui). 

## April 2022
{: #april-2022}

### 5 April 2022
{: #overview-apr0522}
{: release-note}

Onboarding virtual server images for {{site.data.keyword.powerSys_notm}}
:   You can now onboard virtual server images for {{site.data.keyword.powerSys_notm}} to private catalogs and the {{site.data.keyword.cloud_notm}} catalog. For more information about onboarding to the {{site.data.keyword.cloud_notm}}, see [Registering a virtual server image for Power Systems in IBM Cloud Partner Center](/docs/sell?topic=sell-vsipower-register). For more information about onboarding to your private catalog, see [Onboarding a virtual server image for Power Systems to a private catalog](/docs/sell?topic=sell-vsipower-onboard).

Upload translations of your software by using the CLI
:   You can now download and upload translations of your software by using the CLI. For more information, see [Translating product details by using the CLI](/docs/account?topic=account-translate-product-details).

### 4 April 2022
{: #overview-apr0422}
{: release-note}

Adding custom service parameters for your service
:  If the provisioning process of your product requires additional information from your customers, you can now add custom input fields for your product in {{site.data.keyword.cloud_notm}} Partner Center. For more information, see [Adding custom service parameters for your service in Partner Center](/docs/sell?topic=sell-service-add-custom-parameters).

## March 2022
{: #march-2022}

### 25 March 2022
{: #overview-mar2522}
{: release-note}

Trusted profiles are now members of access groups
:   You can now add trusted profiles as members of access groups like other IAM identities, such as users and service IDs. For more information, see [Creating trusted profiles](/docs/account?topic=account-create-trusted-profile) and [Setting up access groups](/docs/account?topic=account-groups).

### 1 March 2022
{: #overview-mar0122}
{: release-note}

Use feature and subscription codes to create new accounts
:   When you [register for a new {{site.data.keyword.cloud_notm}} account](/registration){: external}, you can use a feature code that you received from participating in a special event or a subscription code that you received by email. Instead of verifying your identity by entering your credit card information, click the option to **Register with a code** to complete the set up of your new account.

## February 2022
{: #february-2022}

### 28 February 2022
{: #overview-feb2822}
{: release-note}

365 days of status history is now available
:   You can now easily view events that were completed in the past year on the {{site.data.keyword.cloud_notm}} Status page. Previously, you could view only the history of completed events from the past month. For more information about the {{site.data.keyword.cloud_notm}} Status page, see [Viewing cloud status](/docs/get-support?topic=get-support-viewing-cloud-status).

### 7 February 2022
{: #overview-feb0722}
{: release-note}

Support for onboarding third-party services in Partner Center
:   Onboarding new services in the resource management console is no longer supported. You must use Partner Center to onboard new services to the {{site.data.keyword.cloud_notm}} console. You can continue to manage existing services in the resource management console.

## December 2021
{: #december-2021}

### 17 December 2021
{: #overview-dec1721}
{: release-note}

Restricting domains for account invitations
:   You can now restrict membership to your account based on the domain of the users by creating an allowlist. This way, only users with a specific domain or domains can be invited to the account. For more information, see [Restricting domains for account invitations](/docs/account?topic=account-restrict-acct-invite).

## November 2021
{: #november-2021}

### 8 November 2021
{: #overview-nov0821}
{: release-note}

Data centers closed in 2021
:   The following list shows the locations with the associated data centers and specific PODs that were closed by 08 November 2021.

    - Dallas: DAL05 – POD2
    - Houston: HOU02
    - Melbourne: MEL01
    - Oslo: OSL01
    - Washington DC: WDC01 – POD3 and POD4

    For more information about upcoming data center closures, see [Data center consolidations](/docs/get-support?topic=get-support-dc-closure).

### 1 November 2021
{: #overview-nov0121}
{: release-note}

Accessing Partner Center from the {{site.data.keyword.cloud_notm}} catalog
:   As a third-party provider, you can now click **Sell on {{site.data.keyword.cloud_notm}}** to access Partner Center directly from the {{site.data.keyword.cloud_notm}} catalog. For more information, see the [catalog](/catalog){: external}.

## October 2021
{: #october-2021}

### 25 October 2021
{: #overview-oct2521}
{: release-note}

Securing IBM Cloud accounts
:   Our focus is to provide the most secure public cloud. That's why we will be verifying user identities and securing accounts through credit card verification when creating new accounts starting 25 October 2021. Don't worry, we won't charge you for signing up, and you can still try {{site.data.keyword.cloud_notm}} for free. For more information, see [Securing {{site.data.keyword.cloud_notm}} accounts](https://www.ibm.com/cloud/blog/announcements/securing-ibm-cloud-accounts).{: external}

### 05 October 2021
{: #overview-oct0521}
{: release-note}

Suspending and deprecating private products
:   As a private catalog owner, you can now suspend or deprecate software that's in your private catalogs. When you suspend a version of software, it's immediately removed from your private catalog. When you deprecate software, it remains available to users with access to the private catalog for 90 days. After 90 days, it's permanently removed.

   For more information, see [Deprecating a private product](/docs/account?topic=account-deprecate-product) and [Suspending a version of a private product](/docs/account?topic=account-suspend-product).

Suspending and deprecating third-party software
:   As a third-party provider, you can now suspend and deprecate published software from the {{site.data.keyword.cloud_notm}} catalog to meet the needs of your product's lifecycle. When you suspend a product or version, it is immediately removed from the catalog. When you deprecate a product or version, it remains available for use in the catalog for 90 days. After 90 days, it's permanently removed.

   For more information, see [Deprecating software from the {{site.data.keyword.cloud_notm}} catalog](/docs/sell?topic=sell-deprecate-product) and [Suspending your product from the {{site.data.keyword.cloud_notm}} catalog](/docs/sell?topic=sell-suspend-product).

Filtering the {{site.data.keyword.cloud_notm}} catalog by specific providers
:   The latest enhancements to {{site.data.keyword.cloud_notm}} catalog include support for filtering products by provider name. If you're looking for a specific provider's products or curious about how many products that a provider offers, you can use the **Provider** filter to narrow down your search. To explore the filter updates, see the [catalog](/catalog){: external}.

## September 2021
{: #september-2021}

### 27 September 2021
{: #overview-sept2721}
{: release-note}

Securing your resources with context-based restrictions
:   You can now use context-based restrictions to configure and enforce access restrictions for {{site.data.keyword.Bluemix_notm}} resources. The access restrictions are based on the network location where an access request is created. These restrictions work in tandem with traditional IAM access policies, which are based on identity, to provide an extra layer of protection. Since both IAM access and context-based restrictions must enforce access, context-based restrictions offer protection even in the face of compromised or mismanaged credentials.

   You can create context-based restrictions by defining one or more network zones, which contain allowed network locations, and then associating the zones with the cloud resource through a context-based restrictions rule. Network zones can be defined in terms of IP address constructs, VPCs, and service references, which grant access to a resource from another cloud service.

   For more information, see [What are content-based restrictions?](/docs/account?topic=account-context-restrictions-whatis)

### 24 September 2021
{: #overview-sept2421}
{: release-note}

Assigning access policies based on resource location
:   For supporting services, like {{site.data.keyword.registryshort}}, you can now scope access to more granular locations in your policies, such as geography, country, metro, satellite location.

### 20 September 2021
{: #overview-sep2021}
{: release-note}

Checking the root cause of an incident
:   You can now visit the {{site.data.keyword.Bluemix_notm}} [Incident reports page](/status/incident-reports){: external} to check the health of an {{site.data.keyword.Bluemix_notm}} service. You can find Customer Incident Reports (CIR) on the page, which provide Root Cause Analysis (RCA) for past major outages. You are able to view and download the incident reports from the page about any events that affect {{site.data.keyword.Bluemix_notm}} availability. These reports are in PDF file formats and available for 5 years starting from the date when the event happened.

   For more information, see [Checking Incident reports](/docs/get-support?topic=get-support-viewing-cloud-status#status-incident-report).

### 01 September 2021
{: #overview-sep0121}
{: release-note}

Update to the latest CLI version
:   The {{site.data.keyword.cloud_notm}} CLI team is deprecating the current CLI plugin repo infrastructure for downloading and updating the CLI binary files and plugins. The CLI is migrating to a new infrastructure that works with {{site.data.keyword.cloud_notm}} CLI version 2.0.0 or newer. Ensure that you update all instances of the {{site.data.keyword.cloud_notm}} CLI before 1 October 2021 to avoid disruptions for downloading or updating the plugins. No impact is expected for users who don't need to update any plugins or the CLI.

## August 2021
{: #overview-aug2021}

### 05 August 2021
{: #overview-aug0521}
{: release-note}

Delivering notifications by using Microsoft Teams webhooks
:   Adding Microsoft Teams webhooks to your distribution list is available for receiving account-related {{site.data.keyword.cloud_notm}} notifications. To create a webhook, you need to add an incoming webhook to a Teams channel and a unique URL that maps to the selected channel.
With this webhook integration, you can easily receive the notifications in a selected Microsoft Teams channel in which you added the incoming webhook.

   For more information, see [Adding Microsoft Teams webhooks to a distribution list](/docs/account?topic=account-adding-webhooks-to-a-distribution-list#add-microsoft-teams-webhooks-to-a-distribution-list).


### 04 August 2021
{: #overview-aug0421}
{: release-note}

Support for third-party Operator bundles from GitHub
:   Third-party providers can now onboard Operator bundles from GitHub repositories to {{site.data.keyword.cloud_notm}} by using TGZ files. Previously, the ability to onboard Operator bundles was limited to Operator bundles in {{site.data.keyword.openshiftshort}} registries. This capability is supported by the beta release of {{site.data.keyword.cloud_notm}} Partner Center and our general availability release of private catalog capabilities. For more information, see [Onboarding a Node-RED Operator](/docs/third-party?topic=third-party-operator-register).

Software onboarding enhancements: progress indicators
:   When you onboard software to the {{site.data.keyword.cloud_notm}} catalog or private catalogs in your account, you'll find new indicators in the console that you can use to track your progress with configuring and validating your product. For more information, see [Onboarding software to your account](/docs/account?topic=account-create-private-catalog&interface=ui).


### 03 August 2021
{: #overview-aug0321}
{: release-note}

Filtering the {{site.data.keyword.cloud_notm}} catalog by product type
:   When you navigate to the {{site.data.keyword.cloud_notm}} catalog, your view by default includes all types of products: services, software, and professional services. To help you quickly find the product that you're looking for, you can now filter the products to view services only, software only, or professional services only. For more information, see [{{site.data.keyword.cloud_notm}} catalog](/docs/overview?topic=overview-whatis-platform#catalog).


## July 2021
{: #overview-jul-2021}

### 27 July 2021
{: #overview-jul2721}
{: release-note}

Assigning access to federated users and compute resources by using trusted profiles
:   You can use trusted profiles to automatically grant federated users in your account access to resources with conditions based on SAML attributes from your corporate directory. You can also use trusted profiles to manage the authorization of applications that are running in compute resources, such as {{site.data.keyword.containerlong_notm}}, to access other {{site.data.keyword.cloud_notm}} services without the need for service IDs or API keys. For more information, see [Creating trusted profiles](/docs/account?topic=account-create-trusted-profile#federated-users-steps).

### 15 July 2021
{: #overview-jul1521}
{: release-note}

Scoping support cases to what matters to you
:   When you create a case in the {{site.data.keyword.Bluemix_notm}} Support Center, you now have options to narrow the subject of your case to a specific topic that's most closely related to the issue you're experiencing. As a result, you can ensure that your support case gets routed to the appropriate support engineer and resolved as efficiently as possible. For more information, see [Creating support cases](/docs/get-support?topic=get-support-open-case#creating-support-case).


### 14 July 2021
{: #overview-jul1421}
{: release-note}

Delivering notifications by using Slack webhooks
:   In addition to generic webhooks, you can now add Slack webhooks to your distribution list and receive account-wide {{site.data.keyword.cloud_notm}} notifications through them. To create a webhook, you need to set up an app in Slack and a unique URL.
With this new webhook integration, you can easily receive the notifications in a selected Slack channel in which you installed your app.

   For more information on Slack webhooks, see [Adding Slack webhooks to a distribution list](/docs/account?topic=account-adding-webhooks-to-a-distribution-list#adding-slack-webhooks-to-a-distribution-list).


### 07 July 2021
{: #overview-jul0721}
{: release-note}

Service-level discounts for accounts with the Pay as you go with Committed Use billing model
:   If you have an account with the Pay as you go with Committed Use billing model, you might be eligible to receive service-level discounts. You can apply service-level discounts to commitments in addition to the platform-level discount.
:   Service-level discounts are provided by {{site.data.keyword.Bluemix_notm}} Sales to customers with the Pay as you go with Committed Use billing model. For more information, see [Service-level discounts](/docs/billing-usage?topic=billing-usage-committed-use#service-discount-commit).


Support for third-party Operator bundles from {{site.data.keyword.openshiftshort}} registries
:   Third-party providers can now onboard Operator bundles from {{site.data.keyword.openshiftshort}} registries to {{site.data.keyword.cloud_notm}}. The {{site.data.keyword.openshiftshort}} registries include Certified Operators, Marketplace Operators, and community Operators. This capability is supported by the beta release of {{site.data.keyword.cloud_notm}} Partner Center and our general availability release of private catalog capabilities. For more information, see [Onboarding a Certified Operator bundle from a Red Hat registry](/docs/third-party?topic=third-party-bundle-register).

## June 2021
{: #overview-jun-2021}

### 01 June 2021
{: #overview-jun0121}
{: release-note}

New invitation flow for existing {{site.data.keyword.Bluemix_notm}} users
:   To enhance security and user protection, {{site.data.keyword.Bluemix}} now requires all users to accept an invitation in order to become an active user within a new account. The new invitation flow has an impact only on inviting existing {{site.data.keyword.Bluemix}} users. Previously, existing users were being automatically onboarded to each new account as they were invited. After this change, these users need to accept an invitation in their notifications, by email, or by using the CLI to onboard to a new account.
:   To accept invitations in the CLI, existing members of {{site.data.keyword.Bluemix}} must use the [**`ibmcloud login`**](/docs/cli?topic=cli-ibmcloud_cli#accept-invitation-to-join-a-new-account-) command. They need to target the account that they are invited to join and use the new `--accept` flag.

As an account administrator, you might want to remind your users to accept these invitations.
{: note}

## May 2021
{: #overview-may-2021}

### 07 May 2021
{: #overview-may0721}
{: release-note}

Support for third-party virtual server images with Terraform
:   Third-party providers can now offer virtual server images deployed by using Terraform in {{site.data.keyword.cloud_notm}}. This capability is supported by the beta release of {{site.data.keyword.cloud_notm}} Partner Center and our previously general availability release of private catalog capabilities. For more information, see [Onboarding a virtual server image with Terraform](/docs/third-party?topic=third-party-vsimage-register).


## April 2021
{: #overview-apr-2021}

### 21 April 2021
{: #overview-apr2121}
{: release-note}

Delivering notifications by using webhooks
:   You can now easily add webhooks to the notification distribution list in addition to adding email addresses. You can register a webhook with your account on the [Notification distribution list page](https://cloud.ibm.com/account/notifications-distribution-list) to receive all account notifications. Administrators can use webhooks to configure an application to receive asynchronous notifications whenever an event occurs on the {{site.data.keyword.Bluemix_notm}} platform. Any registered webhook must support HTTP POST requests and accept the notification as a JSON.

   For more information, see [Adding webhooks to a distribution list](/docs/account?topic=account-adding-webhooks-to-a-distribution-list).


### 19 April 2021
{: #overview-apr1921}
{: release-note}

Upcoming changes to the user invitation flow
:   Starting June 01 2021, to enhance security and user protection, all users will be required to accept an invitation to become an active user within a new account. The new invitation flow will have an impact only on inviting existing {{site.data.keyword.Bluemix}} users. Existing users are currently being automatically onboarded to each new account as they are invited. After this change, these users will need to accept an invitation in their notifications, by email, or by using the CLI to onboard to a new account.

   Concerned about how this change will impact your automation? To avoid any disruption to on-going workflows, you need to check your scripts:

   * To accept invitations in the CLI, existing members of {{site.data.keyword.Bluemix}} must use the [**`ibmcloud login`**](/docs/cli?topic=cli-ibmcloud_cli#accept-invitation-to-join-a-new-account-) command. They need to target the account that they are invited to join and use the new `--accept` flag.

   As an account administrator, you may want to remind your users to accept these invitations upon initial change of this behavior.
   {: note}

## March 2021
{: #overview-mar-2021}

### 31 March 2021
{: #overview-mar3121}
{: release-note}

Support for third-party Operators deployed on {{site.data.keyword.openshiftlong_notm}}
:   Third-party providers can now offer Operators in {{site.data.keyword.cloud_notm}}. This capability is supported by the beta release of {{site.data.keyword.cloud_notm}} Partner Center and our previously general availability release of private catalog capabilities. For more information, see [Onboarding a Node-Red Operator](/docs/third-party?topic=third-party-operator-define).

New catalog filter for Financial Services Validated services
:   You can now search the {{site.data.keyword.cloud_notm}} catalog for services that are designated as Financial Services Validated. Services with this designation leverage the industry’s highest levels of encryption certification, provide preventive and compensatory controls for financial services regulatory workloads, multi-architecture support and proactive, and automated security. See [What is {{site.data.keyword.cloud_notm}} for Financial Services?](/docs/overview?topic=overview-what-is-fscloud) for more information.


### 26 March 2021
{: #overview-mar2621}
{: release-note}

{{site.data.keyword.codeenginefull_notm}} is supported as an app deployment type
:   {{site.data.keyword.codeenginefull}} is now supported as an application deployment type when you use a starter kit in the {{site.data.keyword.cloud_notm}} console. For more information, see the [Creating apps tutorial](/docs/apps?topic=apps-tutorial-starterkit).

   [{{site.data.keyword.codeengineshort}}](/docs/codeengine?topic=codeengine-getting-started) is a fully managed, serverless platform that runs your containerized workloads, including web apps, micro-services, event-driven functions, or batch jobs. {{site.data.keyword.codeengineshort}} even builds container images for you from your source code. Because these workloads are all hosted within the same Kubernetes infrastructure, all of them can seamlessly work together. The {{site.data.keyword.codeengineshort}} experience is designed so that you can focus on writing code and not on the infrastructure that is needed to host it.

Duplicate access group names
:   Access groups must use unique names. You can't create or update IAM access groups to use the same name.

## February 2021
{: #overview-feb-2021}

### 26 February 2021
{: #overview-feb2621}
{: release-note}

Managing user login sessions
:   You can customize the duration of working sessions for user's on your account. Customize the duration of users active settings and select the amount of time a user can be inactive before they are signed out and need to enter their credentials again. Update your accounts Identity and Access (IAM) log in sessions from [Settings page](https://cloud.ibm.com/iam/settings){: external}. For more information, see [Managing user's log in session durations](/docs/account?topic=account-iam-work-sessions).


### 25 February 2021
{: #overview-feb2521}
{: release-note}

Controlling access to resources by using tags
:   You can now create tags to control access to your resources and your team's projects can grow without requiring updates to your IAM policies. Incorporating tags into access policies gives you the ability to share a resource across multiple projects and you can change access by simply changing the tags on a resource. For more information, see [Controlling access to resources by using tags](/docs/account?topic=account-access-tags-tutorial).


### 08 February 2021
{: #overview-feb0821}
{: release-note}

New notifications experience
:   A more detailed [Notification preferences page](https://cloud.ibm.com/user/notifications){: external} is now available for you to customize your preferences for receiving email notifications. You receive only one email per event unless you subscribe to them, or you can subscribe to specific incidents from the Status page on an ad hoc basis. For more information, see [Setting email preferences for notifications](/docs/account?topic=account-email-prefs).

   Based on which preferences the account owner or administrator sets, users in the account can view all {{site.data.keyword.Bluemix_notm}} incidents, maintenance, announcements, and security bulletins on the [Notifications page](https://cloud.ibm.com/notifications){: external}. They can filter the list by selecting a specific type of event, or by using keyword searches. For more information, see [Viewing notifications](/docs/get-support?topic=get-support-viewing-notifications).


### 01 February 2021
{: #overview-feb0121}
{: release-note}

Managing product availability in catalogs by location
:   As the account owner or administrator, you can manage access to products in both the {{site.data.keyword.Bluemix_notm}} catalog and the private catalogs in your account based on the location in which the products are deployed. For instance, if you want to limit access to products that are deployed in the Dallas 1 (us-south-1) zone, you can set a filter to include only those products. For more information, see [Managing catalog settings](/docs/account?topic=account-filter-account).

## January 2021
{: #overview-jan-2021}

### 11 January 2021
{: #overview-jan1121}

Pay as you go with Committed Use pricing model
:   Customers with a Subscription account can use the new pricing model, {{site.data.keyword.Bluemix_notm}} Pay as you go with Committed Use. The new pricing model provides you with additional benefits as you navigate and build on {{site.data.keyword.Bluemix_notm}}.

   With this pricing model, you commit to spend a certain amount and receive discounts across the entire platform. You are billed monthly based on your usage, and unlike a subscription, you continue to receive a discount even after you reach your committed amount. For more information, see [Pay as you go with Committed Use pricing model](/docs/account?topic=account-accounts#commitment-model).

## December 2020
{: #overview-dec-2020}

### 18 December 2020
{: #overview-dec1820}
{: release-note}

Managing features and other updates to {{site.data.keyword.cloud-shell_notm}}
:   Account owners or users with {{site.data.keyword.cloud-shell_short}} administrator access can enable or disable {{site.data.keyword.cloud-shell_short}} features for an account. The available features in this release are **File upload and download** and **Web preview**. The feature settings apply only to the enabled {{site.data.keyword.cloud-shell_short}} locations. For more information, see [Enabling or disabling {{site.data.keyword.cloud-shell_short}} features for an account](/docs/account?topic=account-shell-settings#shell-features-enable).
:   An account administrator can grant specific users access to {{site.data.keyword.cloud-shell_short}} and its features, even if {{site.data.keyword.cloud-shell_short}} settings are disabled at the account level. For more information, see [Assigning access to {{site.data.keyword.cloud-shell_short}} and its features at a user level](/docs/account?topic=account-shell-settings#shell-access-user).
:   The following new service roles are available:
   * Cloud Operator
   * Cloud Developer
   * File Manager

   For more information, see [IAM roles and actions](/docs/account?topic=account-iam-service-roles-actions#ibm-cloud-shell).
:   {{site.data.keyword.cloud-shell_notm}} now uses a Red Hat&trade; Linux&trade; bash shell instead of a x86-64 Ubuntu Linux&trade; bash shell.

   For a complete list of changes, see the [{{site.data.keyword.cloud-shell_short}} release notes](/docs/cloud-shell?topic=cloud-shell-release-notes-image).


### 17 December 2020
{: #overview-dec1720}
{: release-note}

{{site.data.keyword.cloud_notm}} CLI Version 1.3.0 is now available
:   The 1.3.0 release of the {{site.data.keyword.cloud_notm}} CLI includes:
   * Initial support of private endpoints in two regions: `us-east` and `us-south`.
   * Anonymous usage statistics are no longer collected for those that had previously opted in to usage statistics collection. The `--usage-stats-collect` flag is removed from the `config` command.
   * Improved performance of several commands involving resource groups.
   * New command to toggle the Intelligent Platform Management Interface (IPMI) on and off: `sl hardware toggle-ipmi`.
   * The add `--output` flag is added to the `resource service-key-create` command.
   * For the `iam access-groups` command, `Public Access` is included in the output.
   * Upgrade to Go language `Golang 1.15.5`.

   For more details about Version 1.3.0, see the [{{site.data.keyword.cloud_notm}} CLI release notes](https://github.com/IBM-Cloud/ibm-cloud-cli-release/releases/){: external}.

   For more information about the CLI, see [Getting started with the {{site.data.keyword.cloud_notm}} CLI](/docs/cli?topic=cli-getting-started).


### 10 December 2020
{: #overview-dec1020}
{: release-note}

Enhanced payments & invoicing for new US-based Pay-As-You-Go accounts with credit card billing
:   We are excited to announce our latest unification project for new US-based {{site.data.keyword.Bluemix_notm}} Pay-As-You-Go accounts with credit card billing. For increased clarification and consistency, the unified experience includes the following enhancements:
   * A single invoice that includes comprehensive usage details for all your products
   * The ability to download the invoice directly from the console
   * The ability to update a credit card in the console without being redirected to a different website
   * A one-to-one mapping between your invoice and your usage dashboard in the console

   For more details, including a video walk-through of the enhancements, see [The Enhanced Unified Billing and Payment Experience in {{site.data.keyword.Bluemix_notm}}](https://www.ibm.com/cloud/blog/announcements/enhanced-unified-billing-and-payment-experience-in-ibm-cloud){: external}.


### 04 December 2020
{: #overview-dec0420}
{: release-note}

Enhancements to the {{site.data.keyword.Bluemix_notm}} Status page
:   You can now experience an enhanced version of the Status page in the {{site.data.keyword.Bluemix_notm}} console that offers reduced time to visibility of issues, as well as more detailed and up-to-date status information. For more information, see [Viewing cloud status](/docs/get-support?topic=get-support-viewing-cloud-status).

## November 2020
{: #overview-nov-2020}

### 30 November 2020
{: #overview-nov3020}
{: release-note}

Data centers closed in 2020
:   The following list shows the locations with the associated data centers and specific PODs that were closed by 30 November 2020.

    - Dallas: DAL07
    - Seattle: SEA01
    - Legacy Planet: D2 (colocation in Dallas), D6 and D7 (Dallas), H2 (Houston)

    For more information about upcoming data center closures, see [Data center consolidations](/docs/get-support?topic=get-support-dc-closure).

### 25 November 2020
{: #overview-nov2520}
{: release-note}

Support for U2F MFA and other MFA factors
:   By default, users in your account authenticate themselves by logging in with a username and password. To require users to use more secure authentication factors, the following MFA options are now available.
   * MFA for users with an IBMid: Users authenticate by using an IBMid, password, and time-based one-time passcode (TOTP). This option applies to all users or just non-federated users.
   * MFA for all users: This option applies to users who are using either an IBMid or an external identity provider (IdP). Users authenticate by using email-based MFA, TOTP MFA, or U2F MFA. The U2F MFA factor is based on the FIDO U2F standard, and it offers the highest level of security.

   For more details, see [Enabling MFA for your account](/docs/account?topic=account-enablemfa).

## October 2020
{: #overview-oct-2020}

### 28 October 2020
{: #overview-oct2820}
{: release-note}

Enhanced Support Center
:   The [Support Center](https://cloud.ibm.com/unifiedsupport/supportcenter){: external} is now updated to help improve your experience with creating and managing your support cases. You can refine the scope of your cases by routing them to a specfic resource and provide feedback on your cases. You will also find popular FAQs that are featured based on your specific issue. For more details, see [Announcing the Release of Our New Support Center Enhancements](https://www.ibm.com/cloud/blog/announcements/new-support-center-enhancements){: external}.

## September 2020
{: #overview-sept-2020}

### 18 September 2020
{: #overview-sep1820}
{: release-note}

Managing {{site.data.keyword.cloud-shell_notm}} settings and other updates to {{site.data.keyword.cloud-shell_notm}}
:   Account owners or users with {{site.data.keyword.cloud-shell_short}} administrator access can manage {{site.data.keyword.cloud-shell_short}} settings from the {{site.data.keyword.cloud_notm}} console. For more information, see [Updating {{site.data.keyword.cloud-shell_short}} settings](/docs/account?topic=account-shell-settings).

   For a complete list of changes, see the [{{site.data.keyword.cloud-shell_short}} release notes](/docs/cloud-shell?topic=cloud-shell-release-notes-image).

Restricting account access by using IAM account settings
:   For increased control over which users can access your account and work with API keys and service IDs, leverage the three new settings that are available on the **Manage** > **Access (IAM)** > **Settings** page in the console.

   * Restrict access to your account to only users coming from a specified IP address or range that you set. For more information, see [Allowing specific IP addresses](/docs/account?topic=account-ips).
   * Block all users from creating API keys in the account except for those that you give explicit access. For more information, see [Restricting users from creating API keys](/docs/account? topic=account-allow-api-create).
   * Block all users from creating service IDs in the account except for those that you give explicit access. For more information, see [Restricting users from creating service IDs](/docs/account?topic=account-restrict-service-id-create).

## August 2020
{: #overview-aug-2020}

### 31 August 2020
{: #overview-aug3120}
{: release-note}

Introducing {{site.data.keyword.compliance_short}}
:   For highly regulated industries, such as financial or healthcare services, achieving a continuously secure and compliant cloud environment is an important first step toward protecting customer and application data. But, we understand that historically this has been a difficult and manual process, potentially placing your organization at risk, which is why, we're excited to introduce the {{site.data.keyword.compliance_short}} - built directly into the {{site.data.keyword.cloud_notm}} platform.

   With the {{site.data.keyword.compliance_short}}, you can embed checkpoints into your everyday workflows hat not only help to monitor for security and compliance but enforce configuration standardization across our accounts. By ensuring you have automation in place that monitors for risk, you can identify security vulnerabilities quickly and work to mitigate the impact that they have to your business.

   For more information, see [Getting started with {{site.data.keyword.compliance_short}}](/docs/security-compliance?topic=security-compliance-getting-started).


### 20 August 2020
{: #overview-aug2020}
{: release-note}

{{site.data.keyword.cloud_notm}} CLI Version 1.2.0 is now available
:   The 1.2.0 release of the {{site.data.keyword.cloud_notm}} CLI includes:
   * New commands under `sl loadbal` namespace to support the {{site.data.keyword.loadbalancer_full}} service.
   * Output CSV support for billing commands.
   * Validation of service instance ID input in policy commands under `iam` namespace.
   * Additional deployment capabilities with the `ibmcloud dev` command, including manual deployment to Knative and deployment to {{site.data.keyword.openshiftlong}} containers.
   * Deprecation of the `cfee` namespace.

   For more information about the {{site.data.keyword.cloud_notm}} CLI, see [Getting started with the IBM Cloud CLI](/docs/cli?topic=cli-getting-started).


### 12 August 2020
{: #overview-aug1220}
{: release-note}

Increased usage quota and other updates to {{site.data.keyword.cloud-shell_notm}}
:   With this update to {{site.data.keyword.cloud-shell_notm}}, the weekly usage quota was increased from 30 hours a week to 50 hours a week so that you can use {{site.data.keyword.cloud-shell_short}} even more. Also, {{site.data.keyword.cloud-shell_short}} was changed to have separate workspaces for each user and account, whereas previously each user's workspace was shared across all of their accounts. In your sessions, you'll also now have access to more command-line tools with the addition of the Operator SDK for Kubernetes, the Mercurial source content management tool, and the Bazaar version control system, as well as updates to existing tools.

   For a complete list of changes, see the [{{site.data.keyword.cloud-shell_short}} release notes](/docs/cloud-shell?topic=cloud-shell-release-notes-image).


### 10 August 2020
{: #overview-aug1020}
{: release-note}

Customizing scoped dashboards
:   Create and manage customized dashboards that can be used to offer an organized and relevant workspace. You can share the dashboards with different users in your account or as a way to group resources for specific projects or teams. When you create a new dashboard, you can start from scratch with a blank template or choose one of the other available templates. For more information, see [Working with scoped dashboards](/docs/account?topic=account-custom-dashboard).


### 04 August 2020
{: #overview-aug0420}
{: release-note}

Audit logs for private catalogs
:   View recorded changes to your private catalogs with the new audit logs feature. Audit logs are recorded when you create, delete, or update your private catalog. Visit your Audit logs page in the {{site.data.keyword.Bluemix_notm}} console by going to **Manage** > **Catalogs**, and selecting **Audit logs**. For more information, see [Viewing changes to your private catalogs](/docs/account?topic=account-catalog-audit-logs).

## July 2020
{: #overview-jul-2020}

### 07 July 2020
{: #overview-jul0720}
{: release-note}

Notification distribution list
:   You can now create a list of up to 10 email addresses that receive account-wide notifications in the {{site.data.keyword.Bluemix_notm}} console by going to **Account**  > **Notification distribution list**. Users that are added to the distribution list are notified about any event that's affecting the account. For more information, see [Adding users to a distribution list](/docs/account?topic=account-email-prefs#adding-users-to-a-distribution-list)

CLI support for catalog filtering in {{site.data.keyword.Bluemix_notm}} enterprises
:   You can now use the following commands to set and manage filters in accounts within an enterprise hierarchy:
   * **`ibmcloud catalog filter get`**
   * **`ibmcloud catalog filter create`**
   * **`ibmcloud catalog filter offering`**
   * **`ibmcloud catalog filter delete`**

   Each command operates the same at the enterprise level by default. You can also apply the commands to specific account groups in an enterprise. For more information, see the [Catalogs management CLI plug-in](/docs/cli?topic=cli-manage-catalogs-plugin).

Professional services are available in the {{site.data.keyword.Bluemix_notm}} catalog
:   We now offer professional services that aim to help guide you in transforming your business. This strategy combines expertise, tools, and methodologies to develop cloud strategies and implementation plans that align with your business goals.

   To explore what's available, go to the [catalog](https://cloud.ibm.com/catalog){: external}, and click **Professional services**.

Catalog management SDKs
:   Four new Software Development Kits (SDKs) for the catalog management service, which includes private catalogs and software products, are now available.
   * The {{site.data.keyword.Bluemix_notm}} Platform Services Java SDK
   * The {{site.data.keyword.Bluemix_notm}} Platform Services Node.js SDK
   * The {{site.data.keyword.Bluemix_notm}} Platform Services Python SDK
   * The {{site.data.keyword.Bluemix_notm}} Platform Services Go SDK

   For more information, see the [Catalog Management API reference](/apidocs/resource-catalog/private-catalog){: external}.

OVA images are available in the {{site.data.keyword.Bluemix_notm}} catalog
:   With the deployment power of the {{site.data.keyword.Bluemix_notm}} Schematics service, support for third-party OVA images targeting VMware vCenter Server deployments is now available. To quickly find the available products in the [catalog](https://cloud.ibm.com/catalog){: external}, click **Software**, and select **OVA Images** from the **Software** list.

## June 2020
{: #overview-jun-2020}

### 24 June 2020
{: #overview-jun2420}
{: release-note}

{{site.data.keyword.cloud-shell_notm}} is generally available
:   {{site.data.keyword.cloud-shell_notm}}, the browser-based shell environment, is now generally available (GA)! This release includes greater region support with the addition of the Tokyo (`jp-tok`) region. {{site.data.keyword.cloud-shell_short}} sessions now also support inputting and viewing double-byte characters on the command line, so you can work in languages such as Japanese, Simplified and Traditional Chinese, and more. The server image was also updated to include updates to several command line tools, in addition to the regular updates for the {{site.data.keyword.cloud_notm}} CLI and plug-ins.

   To try out {{site.data.keyword.cloud-shell_notm}}, see [Getting started with {{site.data.keyword.cloud-shell_notm}}](/docs/cloud-shell?topic=cloud-shell-getting-started).


## May 2020
{: #overview-may-2020}

### 21 May 2020
{: #overview-may2120}
{: release-note}

Connect to an external identity provider for authentication
:   You can now connect your external identity provider to an {{site.data.keyword.appid_full_notm}} instance, and then configure that {{site.data.keyword.appid_short}} to connect directly to {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) to federate authentication for users in your enterprise to your {{site.data.keyword.Bluemix_notm}} account.

   By using this new integration between {{site.data.keyword.appid_short}} and {{site.data.keyword.Bluemix_notm}} IAM, you can simplify the log in experience for users in your enterprise and automatically add users to your account through their login, instead of having to invite or federate each user individually with IBMid. For more information, see [Enabling authentication from an external identity provider](/docs/account?topic=account-idp-integration).


### 01 May 2020
{: #overview-may0120}
{: release-note}

Support for catalog filtering in {{site.data.keyword.Bluemix_notm}} enterprises
:   You can now use filters to customize which products in the {{site.data.keyword.Bluemix_notm}} catalog are available in accounts within an enterprise hierarchy. Filters that are set at a parent account level apply to all child account groups and accounts. For more information, see [Managing products for an {{site.data.keyword.Bluemix_notm}} enterprise](/docs/secure-enterprise?topic=secure-enterprise-catalog-enterprise-restrict).


## April 2020
{: #overview-apr-2020}

### 21 April 2020
{: #overview-apr2120}
{: release-note}

Unified notifications experience
:   Viewing your notifications is now easier than ever with the new unified notifications experience. The notifications page is the centralized place to view and manage all incidents, maintenance, and announcements that might affect your account. In the {{site.data.keyword.Bluemix_notm}} console, click the **Notifications** icon ![Notification icon](../../icons/Notification.svg "Notifications") on the console menu bar to view your notifications.

   Additionally, you can find all infrastructure notifications on the new notifications page. To learn more about the new notifications experience, see [Viewing notifications](/docs/get-support?topic=get-support-viewing-notifications).


### 18 April 2020
{: #overview-apr1820}
{: release-note}

New features and multi-region support for {{site.data.keyword.cloud-shell_notm}} (Beta)
:   This update to {{site.data.keyword.cloud-shell_notm}} (Beta) includes several new features to help you work from the command line in {{site.data.keyword.Bluemix_notm}}:
   * You can now preview web apps within {{site.data.keyword.cloud-shell_short}}. By running apps on an available port, you can open a preview at a URL that only you can see, similar to a cloud version of `localhost`.
   * You can now use {{site.data.keyword.cloud-shell_short}} within the Frankfurt region in addition to the existing Dallas region.
   * Usage timeouts were changed to extend how long you can leave your sessions idle before they're closed. And, there's no longer a time limit on continuous usage.
   * An update to the server image adds the GNU Automake (`automake`) and GNU Compiler Collection (`gcc`, `gcov`, and `gcov-tool`) tools to your sessions.

   For a complete list of changes, see the [{{site.data.keyword.cloud-shell_short}} release notes](/docs/cloud-shell?topic=cloud-shell-release-notes-image).


## March 2020
{: #overview-mar-2020}

### 31 March 2020
{: #overview-mar3120}
{: release-note}

{{site.data.keyword.cloud_notm}} CLI Version 1.0.0 is now available
:   The 1.0.0 release of the {{site.data.keyword.Bluemix_notm}} CLI includes two new global options to help you more easily automate command-line scripting tasks. The new `--output json` option provides command output in a parsable JSON format, and the `--quiet` option suppresses some extra messages such as progress indicators simplify automated processing. The {{site.data.keyword.Bluemix_notm}} CLI now also includes the {{site.data.keyword.dev_cli_notm}} (`ibmcloud dev`) commands, so you can work with apps, pipelines, toolchains, and more without needing to install a separate plug-in. The Cloud Foundry CLI (`ibmcloud cf`) is no longer bundled but can still be installed separately.

   For more information about the {{site.data.keyword.Bluemix_notm}} CLI, see [Getting started with the IBM Cloud CLI and Developer Tools](/docs/cli?topic=cli-getting-started).


### 18 March 2020
{: #overview-mar1820}
{: release-note}

Customizing how access is assigned by using custom roles
:   Until now, you assigned access by using the available platform and service roles that have specific actions that are mapped by individual services. Sometimes, you must assign multiple roles to achieve the required access for your users. With the latest {{site.data.keyword.Bluemix_notm}} Identity and Access Management feature, you can now customize how access is assigned within individual services by creating custom roles. You can choose to organize any number of actions available for a specific service into a new role with a name of your choosing. For more information, see [Creating custom roles](/docs/account?topic=account-custom-roles).

## February 2020
{: #overview-feb-2020}

### 26 February 2020
{: #overview-feb2620}
{: release-note}

Updated handling of API keys for removed users
:   When you remove a user from your account, {{site.data.keyword.cloud_notm}} automatically cleans up the API keys associated with that user's identity, so you don't have to. For more information, see the [Updated handling of IBM Cloud API keys for users removed from accounts](https://www.ibm.com/cloud/blog/announcements/updated-handling-of-ibm-cloud-api-keys-for-users-removed-from-accounts){: external} blog post.


## January 2020
{: #overview-jan-2020}

### 21 January 2020
{: #overview-jan2120}
{: release-note}

{{site.data.keyword.cloud-shell_notm}} (Beta) is now available
:   We're introducing a new way to access {{site.data.keyword.cloud_notm}} from the command line with no installation needed - {{site.data.keyword.cloud-shell_full}}! {{site.data.keyword.cloud-shell_notm}} is a cloud-based shell environment that gives you instant command-line access through your web browser. It's preconfigured with the full {{site.data.keyword.cloud_notm}} CLI, all CLI plug-ins, and tons of tools so you have everything that you need to manage apps, resources, and infrastructure. To try out this beta release, see [Getting started with {{site.data.keyword.cloud-shell_notm}}](/docs/cloud-shell?topic=cloud-shell-getting-started).


### 09 January 2020
{: #overview-jan0920}
{: release-note}

Improved Support Center
:   The latest enhancement to the support center offers a personalized experience to better resolve any IBM Cloud related issue. Navigate through the landing page to view incidents that are specific to your account along with a list of your open cases. Additionally, our self-help options have expanded, popular FAQs and recommended topics are populated to provide information that is relevant to your account. To check out the new experience, log in and go to the [Support Center](https://cloud.ibm.com/unifiedsupport/supportcenter){: external} .

## December 2019
{: #overview-dec-2019}

### 19 December 2019
{: #overview-dec1919}
{: release-note}

Disable public access to resources
:   All users and service IDs are members of the Public Access group by default, which provides unauthenticated access to the resources that the group can access. You can now disable public access at the account level for cases in which you might want to prevent policies that could publicly expose resources from being created. For more information, see [Managing public access to resources](/docs/account?topic=account-public).


## November 2019
{: #overview-nov-2019}

### 26 November 2019
{: #overview-nov2619}
{: release-note}

Delete resource groups
:   Besides the default resource group that's automatically created for you when create your {{site.data.keyword.Bluemix_notm}} account, you can now delete any resource group that doesn't contain any resources. For more information, see [Managing resource groups](/docs/account?topic=account-rgs).


### 04 November 2019
{: #overview-nov0419}
{: release-note}

Bitnami Helm charts
:   {{site.data.keyword.IBM_notm}} and VMware are partnering to provide the [Bitnami Application Catalog](https://bitnami.com/stacks){: external} to {{site.data.keyword.cloud_notm}} customers. The first set of offerings available in the {{site.data.keyword.cloud_notm}} catalog are the Bitnami Helm charts, which Bitnami has created and validated to work on the {{site.data.keyword.containerlong_notm}}. Kubernetes developers typically install Helm charts manually from the CLI by using the helm command. However, this installation process has been simplified by building an auto-installation feature in the {{site.data.keyword.cloud_notm}} catalog. Check out these offerings today by selecting **Bitnami** from the **Provider** filter.


## October 2019
{: #overview-oct-2019}

### 18 October 2019
{: #overview-oct1819}
{: release-note}

Apply promo codes to your account and services
:   {{site.data.keyword.Bluemix_notm}} now has promo codes that you can use to get credit toward your account and services. Promo codes are provided by {{site.data.keyword.Bluemix_notm}} sales on a limited basis to customers with billable accounts. You can apply promo codes from a new Promotions page or from the catalog when you create a resource in the {{site.data.keyword.Bluemix_notm}} console. For more information, see [Applying promo codes](/docs/billing-usage?topic=billing-usage-applying-promo-codes).

Download access reports for specific resources
:   Have you ever wanted to get a quick view of all users, service IDs, access groups, and services that have access to a specific resource in your account? Well, now you can download a report that includes details about who can access your resource. From the My resources page in your account, you can select the **Export access report** option in the row for an IAM-enabled resource to get the report. For more information about the types of data available in the report and who has access to view the report, see [Exporting an access report](/docs/account?topic=account-access-report).


### 15 October 2019
{: #overview-oct1519}
{: release-note}

Mapping actions to IAM roles
:   When you invite a user to your account or assign an existing user IAM access, you can review each action that is mapped to a role. Click the **Actions for role** option to view a list of all actions that are mapped to a specific role when you're selecting the roles to assign in an access policy. By reviewing the action to role mappings, you can have confidence that you are always assigning the correct level of access to users in your account. For more information about this new enhancement, see [Invite User Flow and Transparent Actions](https://www.ibm.com/cloud/blog/announcements/invite-user-flow-and-transparent-actions){: external}.


### 03 October 2019
{: #overview-oct0319}
{: release-note}

Cloud Paks and Schematics templates
:   With the deployment power of the {{site.data.keyword.Bluemix_notm}} Schematics service, we now deliver bundled solutions through packaged software and deployable automation scripts that empower you to build, manage, and modernize your cloud architectures faster and more securely. The first release of these offerings include IBM Cloud Paks and a handful of useful Terraform-based templates.

   From the [catalog](https://cloud.ibm.com/catalog), filter by the offering type and deployment target to find what you're looking for faster. Select **Cloud Paks** and **Terraform** to check out the new offerings that are available.

## September 2019
{: #overview-sep-2019}

### 23 September 2019
{: #overview-sep2319}
{: release-note}

Term-based model for {{site.data.keyword.Bluemix_notm}} support subscriptions
:   New subscriptions for {{site.data.keyword.Bluemix_notm}} support now follow the same term-based model as subscriptions for {{site.data.keyword.Bluemix_notm}} platform services. Rather than credit being valid in monthly increments, credit is now available up front for an entire subscription term, which can be up to one year's worth of credit. You now have more flexibility to use your support credit when you need it, and the chances of incurring monthly overages are reduced. When you buy or renew a support subscription, any existing active support subscriptions are converted to this new flexible model for the remainder of their term. For more information, see [Support subscriptions](/docs/account?topic=account-accounts#support-subscriptions).

   You can also now view your support subscriptions in the {{site.data.keyword.Bluemix_notm}} console so you can keep track of your available credit. For more information, see [Viewing your support costs](/docs/billing-usage?topic=billing-usage-support).


### 12 September 2019
{: #overview-sep1219}
{: release-note}

Redirecting SoftLayer to {{site.data.keyword.Bluemix_notm}}
:   SoftLayer account owners who previously didn't have access to the {{site.data.keyword.Bluemix_notm}} platform can now manage their infrastructure, services, and applications from one location: [cloud.ibm.com](https://cloud.ibm.com){: external}.


## July 2019
{: #overview-jul-2019}

### 25 July 2019
{: #overview-jul2519}
{: release-note}

{{site.data.keyword.Bluemix_notm}} enterprises for centrally managing multiple accounts
:   You can now centrally manage billing and usage for multiple accounts by creating an {{site.data.keyword.Bluemix_notm}} enterprise. With an enterprise, you can create a multitiered hierarchy of accounts by organizing related accounts into account groups. Enterprises simplify management of multiple accounts with the following key features:
   * Consolidated billing means that you can manage billing, invoicing, and payment for all accounts from a single place, the enterprise account.
   * Subscription credit is aggregated into a credit pool and shared with all accounts in the enterprise. Not only is tracking your subscriptions easier, but you can get fewer, larger subscriptions for a better discount because the credit is shared.
   * Top-down usage reporting gives you a unified view of usage costs from all accounts, organized according to your enterprise hierarchy.

   If you have multiple accounts, at least one of which is a Subscription account, you can create an enterprise. See [What is an enterprise?](/docs/secure-enterprise?topic=secure-enterprise-what-is-enterprise) and [Introducing IBM Cloud Enterprises](https://www.ibm.com/cloud/blog/announcements/introducing-ibm-cloud-enterprises){: external}  for more information.

Subscriptions page for tracking subscription credit spending
:   If you have a Subscription account, you can now view all of your subscriptions and analyze your credit spending on the Subscriptions page. You get a high-level view of the total subscription credit in your account and detailed charts that visualize trends such as your credit burndown and monthly spending. You can also view credit from any promotions in your account. For more information, see [Managing subscriptions](/docs/billing-usage?topic=billing-usage-subscriptions).

   Additionally, to better reflect their usage, codes that you apply to add subscription credit to your account are now called subscription codes rather than feature codes.


### 02 July 2019
{: #overview-jul0219}
{: release-note}

Managing SoftLayer SAML federation on {{site.data.keyword.cloud_notm}}
:   Former SoftLayer users who set up a SAML identity provider for logging in with federated IDs can now manage their configuration data in the {{site.data.keyword.cloud_notm}} console in Access (IAM) on the Identity providers page. This type of federation is deprecated, so new identity providers can't be set up currently. You can continue to update your identity provider data or choose to delete this federation in favor of switching to [federating with IBMid](/docs/account?topic=account-account-getting-started#signup-federated).

## June 2019
{: #overview-jun-2019}

### 14 June 2019
{: #overview-jun1419}
{: release-note}

Customize your dashboard
:   You can now control what's displayed on your dashboard. Customizing your dashboard includes the ability to add, remove, and rearrange the widgets. For more information, see [Customizing your dashboard](/docs/account?topic=account-custom-dashboard).

## April 2019
{: #overview-apr-2019}

### 04 April 2019
{: #overview-apr0419}
{: release-note}

Export usage data with associated tags
:   You can now use our newest tagging capabilities to manage resources, usage, and costs in the exported usage report. When you add a tag to a resource, you can view the tag that is associated with the resource. In the {{site.data.keyword.cloud_notm}} console, go to **Manage**> **Billing and Usage**> **Usage**> **Export CSV**>  **Instances** to download your usage report. For more information on exporting tags, check out the [Export tags within your usage data to help with cost allocation](https://www.ibm.com/cloud/blog/export-your-tagged-usage-data-within-the-enhanced-ibm-cloud){: external} blog post.


## March 2019
{: #overview-mar-2019}

### 25 March 2019
{: #overview-mar2519}
{: release-note}

Enabling public access to resources
:   You can now enable public access to objects in your {{site.data.keyword.cos_full}} buckets by using a new access group that is provided for you in your account. This new access group is called the `Public access` group, and all users and service IDs are added to it by default. You can update the policies for the access group to enable all users, even unauthenticated users, access to the resource that you specify in the policy. [Learn more about the public access group](/docs/account?topic=account-public#public).

### 12 March 2019
{: #overview-mar1219}
{: release-note}

Multifactor authentication for users with federated IDs
:   Account owners or users assigned the administrator role for the billing account management service can enable multifcator authentication (MFA) for all users in their account. Federated users who use their corporate or enterprise single sign-on ID can now be required to authenticate by using MFA for logging in to {{site.data.keyword.Bluemix_notm}}. For more information about this feature enhancement and what you need to know about enabling MFA for your account, see [Introducing MFA for IBM Cloud Users with Federated ID](https://www.ibm.com/cloud/blog/introducing-mfa-for-ibm-cloud-users-with-federated-id){: external} .

## December 2018
{: #overview-dec-2018}

### 31 December 2018
{: #overview-dec2118}
{: release-note}

New appdomain.cloud host name option
:   A new host name option `*.appdomain.cloud` is available on cloud.ibm.com.

   Previously, the `mybluemix.net` domain was used for hosting apps in various deployment targets, such as {{site.data.keyword.containerlong_notm}} or Cloud Foundry. Any apps that are hosted on `mybluemix.net` are not impacted.

   The subdomain for Cloud Foundry apps is `cf.appdomain.cloud`. The subdomain for apps that you deploy to {{site.data.keyword.containerlong_notm}} is `containers.appdomain.cloud`.


## November 2018
{: #overview-nov-2018}

### 30 November 2018
{: #overview-nov3018}
{: release-note}

New Cloud Foundry API endpoints
:   The legacy `api.*.bluemix.net` Cloud Foundry API endpoints are still available for compatibility with earlier versions. However, you can update scripts and infrastructure automation to use the following new Cloud Foundry API endpoints for your region:
   * api.us-south.cf.cloud.ibm.com (previously api.ng.bluemix.net)
   * api.eu-gb.cf.cloud.ibm.com (previously api.eu-gb.bluemix.net)
   * api.us-east.cf.cloud.ibm.com (previously api.us-east.bluemix.net)
   * api.eu-de.cf.cloud.ibm.com (previously api.eu-de.bluemix.net)
   * api.au-syd.cf.cloud.ibm.com (previously api.au-syd.bluemix.net)

Enhanced support experience for {{site.data.keyword.Bluemix_notm}}
:   With the Support Center, you can work to resolve all {{site.data.keyword.Bluemix_notm}}-related issues. The landing page provides you FAQs, so you can find the answer to your question without even contacting {{site.data.keyword.Bluemix_notm}}. You can also chat with a live support rep. Your cases can now be managed in from a single location. In the console, go to **Support** &gt; **Manage cases** to create, view, or edit cases.

   You can also find the [Status page](https://cloud.ibm.com/status){: external} from the Support Center. It is enhanced to include all unplanned incidents, planned maintenance, announcements, and security bulletin notifications about key events that affect the {{site.data.keyword.Bluemix_notm}} platform, infrastructure, and major services. Click **View cloud status** from the Support Center. To check out the new experience, log in and go to the [Support Center](https://cloud.ibm.com/unifiedsupport/supportcenter){: external} .

Unified login, API keys, and user and access management
:   With our latest updates, you can take advantage of a simplified secure login that is available for all users regardless of your ID type. Whether you have an IBMid or a SoftLayer ID, you can quickly log in to the {{site.data.keyword.Bluemix_notm}} console from our enhanced login page. You can also make secure API calls across {{site.data.keyword.Bluemix_notm}} and automate your CLI login by using an IAM API key or an IAM access token.

   After you log in, you can now see all users, including platform and classic infrastructure users, from your Users page in the Access (IAM) UI. Depending on your access to view other users in the account, you can filter your view quickly by account users, classic infrastructure users, or Cloud Foundry org. You can also use the filters to find users quickly by name, email, or status.

   Now that all of your users are in a single console, you can manage their access to all types of resources from the same place. Access starts with the user, so start by selecting a user from your list. Then, depending on which type of resource that you want to assign access to, you can choose from IAM access policies, Cloud Foundry access, or classic infrastructure permissions. If you want to assign IAM access policies, try creating an access group to streamline your access management process by adding all users to the same access group that need the same policies assigned.

   For more details, check out [Outstanding User Access Improvements Help Deliver a Unified {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-access-management){: external}.

Find all {{site.data.keyword.Bluemix_notm}} CLI plug-in documentation in one place
:   You can now access all of the {{site.data.keyword.Bluemix_notm}} CLI plug-in documentation in one location, making it easier for you to find any CLI command that you are looking for. Check out the References section in the [CLI documentation](/docs/cli?topic=cli-ibmcloud_cli).

New dashboard and Resource list page
:   With our latest update, you can now view all your platform and infrastructure services from one location. When you log in, you can check out the new dashboard. After you add resources to your account from the catalog, you can use your resource list to get a full view of your account resources:
   * The dashboard is redesigned so that you can view a summary your resources, maintenance, status, apps, support, usage, and users.
   * You can find more details about your resources by going to your resource list. You can tag your resources to organize them, or select them to update the details page.
   * Now that you can see all of your resources in one place, we added a global search so that you can quickly find resources that you created and expect to find in your resource list.
   * You can also search for catalog results, so you can quickly find resources to add to your account.

   See [Manage All Your Cloud Resources on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/manage-all-your-cloud-resources-on-the-enhanced-ibm-cloud-platform/){: external} for more details.

Unified account, billing, and user profile information
:   Your account, billing, and profile information is now simplified. You can view your account information for all of your platform and infrastructure resources in a unified console.
:   Your profile and settings area contains information about you as well as your email notification preferences for all resource types.
:   Your account information area contains information about your company or organization, account settings, and quick access for working with resource groups and Cloud Foundry orgs. You can even find best practices to help you get up and running quickly!
:   Your billing and usage area of your account helps you understand your bill, make payments, monitor subscriptions, get quotes, track orders, and set spending notifications.

   Check out [Bringing It All Together: A Single Account and Billing Management Experience](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-account-management){: external} for more details.

Organize your resources with tags
:   Tags are now available for you to add to your resources, like Cloud Object Storage, to help you manage resources and find the resources that are the most relevant to you. For example, if you have hundreds of resources and you want to differentiate between ones that are paid the same way, you could tag them with `costcenter:location01`. Or, if you have a team that is working on a couple of resources repeatedly, you can use something like `team-blue`. You can also filter the My resources page by tags to quickly organize and find the resources that you need. For more information, see [Working with tags](/docs/account?topic=account-tag) and [Platform Tagging on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/platform-tagging-on-the-enhanced-ibm-cloud-platform){: external}.

Get accurate monthly costs with the cost estimator
:   To help you decide and analyze what services you'd like to purchase, you can use the cost estimator. Now, you can go through the console and select each service you'd like to have, and add all of the costs in an easy to use tool. You can even enter projected data usages, lookups per second, writes per second, and queries per second to get a more accurate estimation of your monthly expenditures. You can use the cost estimator with each catalog service you select, or you can click the Cost Estimator icon ![Cost Estimator icon](../icons/calculator.svg "Cost Estimator") in the console menu to get a summary of your estimated costs. For more information, see [Estimating your costs](/docs/billing-usage?topic=billing-usage-cost).


### 01 November 2018
{: #overview-nov0118}
{: release-note}

Updated global location names
:   As {{site.data.keyword.cloud_notm}} continues to expand our global availability footprint, we’re updating our location naming structure to better support an understandable, consistent hierarchy of geographies, regions, and data centers around the world. If you’re familiar with our current global regions, you’ll recognize names like US South and Sydney. We’re aligning these location names to the names of the city in which the data centers physically exist.

   For now, the programmatic IDs are not changing, so there’s no impact from an API perspective. The following table shows the old and new location names. For more information and a comprehensive list of data centers and regions, see [Service availability](/docs/overview?topic=overview-services_region).

   | Previous Location Display Name | New Location Display Name | Code     |
   |--------------------------------|---------------------------|----------|
   | US South                       | Dallas                    | us-south |
   | US East                        | Washington DC             | us-east  |
   | United Kingdom                 | London                    | eu-gb    |
   | Germany                        | Frankfurt                 | eu-de    |
   | Sydney                         | Sydney                    | au-syd   |
   | AP North                       | Tokyo                     | jp-tok   |
   {: caption="Table 1. New location names" caption-side="top"}

## October 2018
{: #overview-oct-2018}

### 30 October 2018
{: #overview-oct3018}
{: release-note}

Assign account management access to others
:   With {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM), you can delegate common tasks that you complete as an account administrator to another user in your account. By creating an access policy on one or all of the available account management services, you can easily delegate responsibilities such as inviting and removing users, managing access groups, managing service IDs, maintaining private catalog services, and even monitoring billing and tracking usage. There are four individual account management services and an all services option that you can use to set up access policies:
   * User Management for inviting and removing users
   * IAM Access Groups for creating, editing, deleting, updating, and assigning access
   * IAM Identity Service for viewing, creating, deleting, and assigning access to service IDs and associated API keys across the account
   * Global resource catalog for viewing private catalog offerings and updating the metadata and visibility for the offerings
   * All account management services for access to each of the individual account management service options based on the assigned role as well as access to billing and usage tracking.

   For more information on the tasks that a user can do based on which account management service they have a policy on and which role they are assigned, see [Example platform management roles and actions for account management services](/docs/account?topic=account-account-services#account-management-actions-roles). For more information about this new feature, see the [Introducing More Flexibility and Control for IBM Cloud Account Management Services Access](https://www.ibm.com/cloud/blog/announcements/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access){: external} blog post.


## July 2018
{: #overview-jul-2018}

### 17 July 2018
{: #overview-jul1718}
{: release-note}

Searching for resources
:   You can search for resources from anywhere in the {{site.data.keyword.cloud_notm}} console. Type the name of a resource in the search field in the console menu bar. Press the Forward Slash key (/) to activate the search.


### 12 July 2018
{: #overview-jul1218}
{: release-note}

Dynamically add federated users to access groups
:   You can create dynamic rules to automatically add federated users to access groups based on specific identity attributes. When your users log in with a federated ID, the data from the identity provider dynamically maps your users to an access group based on the rules that you set. For more information, see [Creating dynamic rules for access groups](/docs/account?topic=account-rules).

## June 2018
{: #overview-jun-2018}

### 01 June 2018
{: #overview-jun0118}
{: release-note}

Protect your service IDs and API keys
:   To avoid a situation where your service ID or API key is deleted causing an outage or disruption, you can lock service IDs and API keys by using the UI or CLI. Locking a service ID also prevents any access policies from being changed, deleted, or assigned as well as any API keys associated with the service ID from being created or deleted. For more information, see [Locking a service ID](/docs/account?topic=account-serviceidapikeys#lockkey) and [Locking an API key](/docs/account?topic=account-userapikey).


## May 2018
{: #overview-may-2018}

### 31 May 2018
{: #overview-may3118}
{: release-note}

Upgrade your Lite account to a Subscription account
:   You can now upgrade your Lite account to a Subscription account directly from the {{site.data.keyword.Bluemix_notm}} console. With a Subscription account, you can use both platform and infrastructure offerings, and take advantage of discounted pricing by making a monthly spending and term commitment. You can also avoid surprises with fixed billing on a monthly payment schedule, but with the flexibility to order more or less based on your needs. For more information, see [FAQS for billing and usage](/docs/billing-usage?topic=billing-usage-billusagefaqs).


### 15 May 2018
{: #overview-may1518}
{: release-note}

{{site.data.keyword.Bluemix_notm}} CLI rebranding
:   The {{site.data.keyword.Bluemix_notm}} CLI commands changed from **`bluemix`** and **`bx`** to **`ibmcloud`**. However, you can still use the **`bluemix`** and **`bx`** CLI commands until they are removed later. There is no short name now, just the full name **`ibmcloud`**.


### 02 May 2018
{: #overview-may0218}
{: release-note}

Multi-factor authentication for your account
:   Multi-factor authentication (MFA) adds an extra layer of security to your account by requiring all users to provide a time-based one-time passcode in addition to their standard IBMid and password during login. This is also commonly known as two-factor authentication (2FA). MFA is enabled per account, and once it is turned on, all users in the account are required to log in by using the extra security measure. For more information, see the [IBM Cloud Platform now adds support for Multi-Factor Authentication](https://www.ibm.com/cloud/blog/ibm-cloud-platform-now-adds-support-multi-factor-authentication){: external} blog post.

## April 2018
{: #overview-apr-2018}

### 03 April 2018
{: #overview-apr0318}
{: release-note}

Assign access quickly by using access groups
:   Do you want to be able to assign access quickly by using the least number of policies possible? Now you can with access groups. Group a set of users and service IDs together and assign a single policy that applies to all members of the group. By using access groups, you can limit the time that you spend managing access to the users and service IDs in your account. Check out the blog post [New feature: Access groups](https://www.ibm.com/cloud/blog/access-groups){: external} for more details.

## December 2017
{: #overview-dec-2017}

### 15 December 2017
{: #overview-dec1517}
{: release-note}

Cloud Foundry Service US East region
:   A new US East data center is now available in Washington, DC. You can reach this new region by using the `us-east.cloud.ibm.com` endpoint. For details about the services that are available for purchase in this new region, see [Services by region](/docs/overview?topic=overview-services_region).


### 14 December 2017
{: #overview-dec1417}
{: release-note}

Support for resources in the European Union
:   If your services and data centers are located in Europe, {{site.data.keyword.Bluemix_notm}} now offers extra capabilities to protect your data in the European Union. You can request that support is provided by customer success teams that are located in Europe. This support is available 24 hours a day, 7 days a week. See [Enabling the EU supported option](/docs/account?topic=account-eu-hipaa-supported#bill_eusupported) and [Requesting support for resources in the European Union](/docs/get-support?topic=get-support-using-avatar#eusupported) for more information.


## November 2017
{: #overview-nov-2017}

### 28 November 2017
{: #overview-nov2817}
{: release-note}

Withdrawal of support for TLS 1.0 and 1.1
:   On 1 March 2018 {{site.data.keyword.Bluemix_notm}} will withdraw support for TLS 1.0 and TLS 1.1 across many of our cloud products and services as part of our commitment to offering a cloud that is secure to the core and in alignment with industry best practices for security and data privacy.

### 16 November 2017
{: #overview-nov1617}
{: release-note}

A new way to organize resources within your account
:   Resource groups are a new way for you to create customizable groupings of account resources, and access to the group and the resources within it are managed by using Identity and Access Management (IAM). Everyone starts out with a default resource group. You can rename this resource group and add new service instances to it as you create them from the catalog.

   For users with a Pay-As-You-Go or Subscription account, you can create extra resource groups to make managing quota and viewing billing usage for a set of resources easier. You can also group resources to make it easier for you to assign users access to more than one service at a time. To learn more about working with resource groups for your account, see [Managing resource groups](/docs/account?topic=account-rgs).

Updates for {{site.data.keyword.Bluemix_notm}} IAM
:   The introduction of resource groups within your {{site.data.keyword.Bluemix_notm}} account provides a new way for you to assign access. Users and service IDs can be assigned access to all services within a resource group, enabling you to quickly assign access to more than one resource at a time. You can also customize access for each user or service ID by assigning access to just some services within a resource group, or you choose to assign access to individual resources down to the service instance level. For more information about the features that you can take advantage of by using IAM, see [What features does IAM provide?](/docs/account?topic=account-iamoverview#features)

Customize your dashboard view
:   You can view and manage all the resources in your account from your dashboard in the {{site.data.keyword.Bluemix_notm}} console. And now, you can set filters to customize your view. For example, you can filter by resource group to view the specific resources in a resource group. You can also filter by region or Cloud Foundry space. For more details, see [Managing resources on the dashboard](/docs/overview?topic=overview-ui#dashboardview).

### 02 November 2017
{: #overview-nov0217}
{: release-note}

Support Center
:   We now have the new Support Center where you can search for information, post questions to our developer community, and manage tickets. Go to **Support > Support Center** in the {{site.data.keyword.Bluemix_notm}} console menu bar.


## October 2017
{: #overview-oct-2017}

### 31 October 2017
{: #overview-oct3117}
{: release-note}

Introducing {{site.data.keyword.Bluemix_notm}}
:   Bluemix is now {{site.data.keyword.Bluemix_notm}}. Besides rolling out our new name, nothing changes. You can still easily build and run your apps and services as always. Check out the [{{site.data.keyword.Bluemix_notm}} blog](https://www.ibm.com/cloud/blog/announcements/bluemix-is-now-ibm-cloud){: external}  for more details.

Lite account
:   A Lite account is our new account type that gives you access to try select services for free with no time restrictions. This new account also includes usage tracking and efficiency features to help you better manage your resources. To learn more about what's available, see [Account types](/docs/account?topic=account-accounts#liteaccount).


### 06 October 2017
{: #overview-oct0617}
{: release-note}

Identity and Access Management application authentication feature
:   Identity and Access Management (IAM) now supports service IDs, which you can think of as identities that can be used for apps to authenticate with your {{site.data.keyword.Bluemix_notm}} services. Instead of using individual user credentials, a Service ID can be created with an associated API key and access permissions in the form of a service policy that is assigned to the Service ID in order for you to control the level of access for any application authenticating with that ID.

   For more information about the benefits of this feature and how to get started, see the [Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/cloud/blog/introducing-ibm-cloud-iam-service-ids-api-keys){: external}.

## July 2017
{: #overview-jul-2017}

### 27 July 2017
{: #overview-jul2717}
{: release-note}

{{site.data.keyword.Bluemix_notm}} global catalog
:   Expanding on the last console update to manage your public regions from a single location in the console, {{site.data.keyword.Bluemix_notm}} now has a global catalog, making the process of selecting and deploying items that you select from the catalog a more streamlined process. Regardless of the region that you select in the console, you can now see all services that are available across all public regions from your catalog. Once you select a tile from the catalog, you can see which regions the service is available in, and select where you want to deploy it. For more information about the latest updates to the catalog, see [A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/cloud/blog/announcements/global-bluemix-catalog-makes-building-things-easier){: external}.


## May 2017
{: #overview-may-2017}

### 23 May 2017
{: #overview-may2317}
{: release-note}

{{site.data.keyword.Bluemix_notm}} console updates
:   You can now manage your public regions from a single location through the updated {{site.data.keyword.Bluemix_notm}} console. The region selector offers you streamlined access to your resources, and other enhancements include higher availability and improved performance. For more information, check out [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: external}.


### 01 May 2017
{: #overview-may0117}
{: release-note}

Identity and access management
:   With the latest updates and improvements, {{site.data.keyword.Bluemix_notm}} account owners or administrators can now use a new unified access control UI to take advantage of the following capabilities:
   * Manage users' fine-grained access to Kubernetes services and other services as they adopt the new access control features
   * Assign service policies and Cloud Foundry roles to users within their organizations

   Additionally, {{site.data.keyword.Bluemix_notm}} platform users can create, delete, and list API keys associated with their user IDs. And platform users can use those API keys to authenticate when using APIs or CLIs.

   Lastly, we enhanced our unified user management capability to ensure that in a linked IaaS-PaaS account, users are managed in a unified way with no need to add users separately in the SoftLayer Customer Portal or the {{site.data.keyword.Bluemix_notm}}console.

   For more information, check out the [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: external} blog post.


## April 2017
{: #overview-apr-2017}

### 13 April 2017
{: #overview-apr1317}
{: release-note}

Navigation design changes for {{site.data.keyword.Bluemix_notm}} docs
:   With this navigation update, we think you'll understand how content is better organized throughout our docs, and will be able to find relevant content more efficiently. With fewer nested layers of content, you won't have to dig around to find the documentation you need to be successful with {{site.data.keyword.Bluemix_notm}}.
