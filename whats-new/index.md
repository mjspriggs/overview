---

copyright:
  years: 2015, 2021

lastupdated: "2021-07-08"

keywords: release notes, what's new in IBM Cloud, what's new for the platform, what is new, cloud updates, new features, platform

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:tip: .tip}
{:note: .note}
{:external: target="_blank" .external}

# What's new in {{site.data.keyword.Bluemix_notm}}?
{: #whatsnew}

Stay up-to-date with the new features that are available on the {{site.data.keyword.Bluemix}} platform so that you get the most out of your {{site.data.keyword.Bluemix_notm}} experience. 
{:shortdesc}

If you're looking for updates about products that are available on {{site.data.keyword.Bluemix_notm}}, check out the [Announcements page](https://www.ibm.com/cloud/blog/announcements){: external} on the {{site.data.keyword.Bluemix_notm}} blog.
{: tip}

## Support for third-party Operator bundles from {{site.data.keyword.redhat_notm}} {{site.data.keyword.openshiftshort}} registries
{: #support-operator-bundle}

New as of: 07 July 2021

Third-party providers can now onboard Operator bundles from {{site.data.keyword.redhat_notm}} {{site.data.keyword.openshiftshort}} registries to {{site.data.keyword.cloud_notm}}. The {{site.data.keyword.redhat_notm}} {{site.data.keyword.openshiftshort}} registries include Certified Operators, Marketplace Operators, and community Operators. This capability is supported by the beta release of {{site.data.keyword.cloud_notm}} Partner Center and our general availability release of private catalog capabilities. For more information, see [Onboarding a Certified Operator bundle from a Red Hat registry](/docs/third-party?topic=third-party-bundle-register).

## New invitation flow for existing {{site.data.keyword.Bluemix_notm}} users
{: #new-invitation-flow}

New as of: 01 June 2021

To enhance security and user protection, {{site.data.keyword.Bluemix}} now requires all users to accept an invitation in order to become an active user within a new account. The new invitation flow has an impact only on inviting existing {{site.data.keyword.Bluemix}} users. Previously, existing users were being automatically onboarded to each new account as they were invited. After this change, these users need to accept an invitation in their notifications, by email, or by using the CLI to onboard to a new account.

To accept invitations in the CLI, existing members of {{site.data.keyword.Bluemix}} must use the [**`ibmcloud login`**](/docs/cli?topic=cli-ibmcloud_cli#accept-invitation-to-join-a-new-account-) command. They need to target the account that they are invited to join and use the new `--accept` flag.

As an account administrator, you might want to remind your users to accept these invitations.
{: note}

## Support for third-party virtual server images with Terraform 
{: #support-vsi-image}

New as of: 07 May 2021

Third-party providers can now offer virtual server images deployed by using Terraform in {{site.data.keyword.cloud_notm}}. This capability is supported by the beta release of {{site.data.keyword.cloud_notm}} Partner Center and our previously general availability release of private catalog capabilities. For more information, see [Onboarding a virtual server image with Terraform](/docs/third-party?topic=third-party-vsimage-register).

## Delivering notifications by using webhooks
{: #deliver-notification-webhook}

New as of: 21 April 2021

You can now easily add webhooks to the notification distribution list in addition to adding email addresses. You can register a webhook with your account on the [Notification distribution list page](https://cloud.ibm.com/account/notifications-distribution-list) to receive all account notifications. Administrators can use webhooks to configure an application to receive asynchronous notifications whenever an event occurs on the {{site.data.keyword.Bluemix_notm}} platform. Any registered webhook must support HTTP POST requests and accept the notification as a JSON.

For more information, see [Setting email preferences for notifications](/docs/account?topic=account-email-prefs#adding-webhooks-to-a-distribution-list).

## Upcoming changes to the user invitation flow
{: #upcoming-invitation-flow}

New as of: 19 April 2021

Starting 01 June 2021, to enhance security and user protection, all users will be required to accept an invitation to become an active user within a new account. The new invitation flow will have an impact only on inviting existing {{site.data.keyword.Bluemix}} users. Existing users are currently being automatically onboarded to each new account as they are invited. After this change, these users will need to accept an invitation in their notifications, by email, or by using the CLI to onboard to a new account.

Concerned about how this change will impact your automation? To avoid any disruption to on-going workflows, you need to check your scripts:

* To accept invitations in the CLI, existing members of {{site.data.keyword.Bluemix}} must use the [**`ibmcloud login`**](/docs/cli?topic=cli-ibmcloud_cli#accept-invitation-to-join-a-new-account-) command. They need to target the account that they are invited to join and use the new `--accept` flag.

As an account administrator, you may want to remind your users to accept these invitations upon initial change of this behavior.
{: note}

## Support for third-party Operators deployed on {{site.data.keyword.openshiftlong_notm}}
{: #support-onboarding-operators}

New as of: 31 March 2021

Third-party providers can now offer Operators in {{site.data.keyword.cloud_notm}}. This capability is supported by the beta release of {{site.data.keyword.cloud_notm}} Partner Center and our previously general availability release of private catalog capabilities. For more information, see [Onboarding a Node-Red Operator](/docs/third-party?topic=third-party-operator-define).

## New catalog filter for Financial Services Validated services 
{: #filter-financial-services}

New as of: 31 March 2021

You can now search the {{site.data.keyword.cloud_notm}} catalog for services that are designated as Financial Services Validated. Services with this designation leverage the industry’s highest levels of encryption certification, provide preventive and compensatory controls for financial services regulatory workloads, multi-architecture support and proactive, and automated security. See [What is {{site.data.keyword.cloud_notm}} for Financial Services?](/docs/overview?topic=overview-what-is-fscloud) for more information.

## {{site.data.keyword.codeenginefull_notm}} is supported as an app deployment type
{: #codeengine-deploy-mar2021}

New as of: 26 March 2021

{{site.data.keyword.codeenginefull}} is now supported as a application deployment type when you use a starter kit in the [{{site.data.keyword.cloud_notm}} console](https://{DomainName}/developer/appservice/starter-kits). For more information, see the [Creating apps tutorial](/docs/apps?topic=apps-tutorial-starterkit).

[{{site.data.keyword.codeengineshort}}](/docs/codeengine?topic=codeengine-getting-started) is a fully managed, serverless platform that runs your containerized workloads, including web apps, micro-services, event-driven functions, or batch jobs. {{site.data.keyword.codeengineshort}} even builds container images for you from your source code. Because these workloads are all hosted within the same Kubernetes infrastructure, all of them can seamlessly work together. The {{site.data.keyword.codeengineshort}} experience is designed so that you can focus on writing code and not on the infrastructure that is needed to host it.


## Managing user login sessions
{: #user-session-settings}

New as of: 26 February 2021

You can customize the duration of working sessions for user's on your account. Customize the duration of users active settings and select the amount of time a user can be inactive before they are signed out and need to enter their credentials again. Update your accounts Identity and Access (IAM) log in sessions from [Settings page](https://cloud.ibm.com/iam/settings){: external}. For more information, see [Managing user's log in session durations](https://test.cloud.ibm.com/docs/account?topic=account-iam-work-sessions).


## Controlling access to resources by using tags
{: #controlling-access-using-tags-febr2021}

New as of: 25 February 2021

You can now create tags to control access to your resources and your team's projects can grow without requiring updates to your IAM policies. Incorporating tags into access policies gives you the ability to share a resource across multiple projects and you can change access by simply changing the tags on a resource. For more information, see [Controlling access to resources by using tags](/docs/account?topic=account-access-tags-tutorial).


## New notifications experience
{: #notification-preferences}

New as of: 8 February 2021

A more detailed [Notification preferences page](https://cloud.ibm.com/user/notifications){: external} is now available for you to customize your preferences for receiving email notifications. You receive only one email per event unless you subscribe to them, or you can subscribe to specific incidents from the Status page on an ad hoc basis. For more information, see [Setting email preferences for notifications](/docs/account?topic=account-email-prefs).

Based on which preferences the account owner or administrator sets, users in the account can view all {{site.data.keyword.Bluemix_notm}} incidents, maintenance, announcements, and security bulletins on the [Notifications page](https://cloud.ibm.com/notifications){: external}. They can filter the list by selecting a specific type of event, or by using keyword searches. For more information, see [Viewing notifications](/docs/get-support?topic=get-support-viewing-notifications).

## Managing product availability in catalogs by location
{: #catalog-location-feb2021}

New as of: 1 February 2021

As the account owner or administrator, you can manage access to products in both the {{site.data.keyword.Bluemix_notm}} catalog and the private catalogs in your account based on the location in which the products are deployed. For instance, if you want to limit access to products that are deployed in the Dallas 1 (us-south-1) zone, you can set a filter to include only those products. For more information, see [Managing catalog settings](/docs/account?topic=account-filter-account).

## Pay as you go with Committed Use pricing model
{: #paygo-commit-jan2021}

New as of: 12 January 2021

Customers with a Subscription account can use the new pricing model, {{site.data.keyword.Bluemix_notm}} Pay as you go with Committed Use. The new pricing model provides you with additional benefits as you navigate and build on {{site.data.keyword.Bluemix_notm}}.

With this pricing model, you commit to spend a certain amount and receive discounts across the entire platform. You are billed monthly based on your usage, and unlike a subscription, you continue to receive a discount even after you reach your committed amount. For more information, see [Pay as you go with Committed Use pricing model](/docs/account?topic=account-accounts#commitment-model).

## Managing features and other updates to {{site.data.keyword.cloud-shell_notm}}
{: #cloud-shell-dec2020}

New as of: 18 December 2020

* Account owners or users with {{site.data.keyword.cloud-shell_short}} administrator access can enable or disable {{site.data.keyword.cloud-shell_short}} features for an account. The available features in this release are **File upload and download** and **Web preview**. The feature settings apply only to the enabled {{site.data.keyword.cloud-shell_short}} locations. For more information, see [Enabling or disabling {{site.data.keyword.cloud-shell_short}} features for an account](/docs/account?topic=account-shell-settings#shell-features-enable).
* An account administrator can grant specific users access to {{site.data.keyword.cloud-shell_short}} and its features, even if {{site.data.keyword.cloud-shell_short}} settings are disabled at the account level. For more information, see [Assigning access to {{site.data.keyword.cloud-shell_short}} and its features at a user level](/docs/account?topic=account-shell-settings#shell-access-user).
* The following new service roles are available:
  * Cloud Operator
  * Cloud Developer
  * File Manager

  For more information, see [IAM roles and actions](/docs/account?topic=account-iam-service-roles-actions#ibm-cloud-shell).
* {{site.data.keyword.cloud-shell_notm}} now uses a Red Hat&trade; Linux&trade; bash shell instead of a x86-64 Ubuntu Linux&trade; bash shell.

For a complete list of changes, see the [{{site.data.keyword.cloud-shell_short}} release notes](/docs/cloud-shell?topic=cloud-shell-release-notes-image).

## {{site.data.keyword.cloud_notm}} CLI Version 1.3.0 is now available
{: #cli-130}

New as of: 17 December 2020

The 1.3.0 release of the {{site.data.keyword.cloud_notm}} CLI includes:
* Initial support of private endpoints in two regions: `us-east` and `us-south`.
* Anonymous usage statistics are no longer collected for those that had previously opted in to usage statistics collection. The `--usage-stats-collect` flag is removed from the `config` command.
* Improved performance of several commands involving resource groups.
* New command to toggle the Intelligent Platform Management Interface (IPMI) on and off: `sl hardware toggle-ipmi`.
* The add `--output` flag is added to the `resource service-key-create` command.
* For the `iam access-groups` command, `Public Access` is included in the output.
* Upgrade to Go language `Golang 1.15.5`.

For more details about Version 1.3.0, see the [{{site.data.keyword.cloud_notm}} CLI release notes](https://github.com/IBM-Cloud/ibm-cloud-cli-release/releases/){: external}.

For more information about the CLI, see [Getting started with the {{site.data.keyword.cloud_notm}} CLI](/docs/cli?topic=cli-getting-started).

## Enhanced payments & invoicing for new US-based Pay-As-You-Go accounts with credit card billing
{: #sltob}

New as of: 10 December 2020

We are excited to announce our latest unification project for new US-based {{site.data.keyword.Bluemix_notm}} Pay-As-You-Go accounts with credit card billing. For increased clarification and consistency, the unified experience includes the following enhancements:
 
* A single invoice that includes comprehensive usage details for all your products
* The ability to download the invoice directly from the console
* The ability to update a credit card in the console without being redirected to a different website
* A one-to-one mapping between your invoice and your usage dashboard in the console 

For more details, including a video walk-through of the enhancements, see [The Enhanced Unified Billing and Payment Experience in {{site.data.keyword.Bluemix_notm}}](https://www.ibm.com/cloud/blog/announcements/enhanced-unified-billing-and-payment-experience-in-ibm-cloud){: external}. 

## Enhancements to the {{site.data.keyword.Bluemix_notm}} Status page
{: #status-page-enhance}

New as of: 4 December 2020

You can now experience an enhanced version of the Status page in the {{site.data.keyword.Bluemix_notm}} console that offers reduced time to visibility of issues, as well as more detailed and up-to-date status information. For more information, see [Viewing cloud status](/docs/get-support?topic=get-support-viewing-cloud-status). 

## Support for U2F MFA and other MFA factors
{: #mfa-hardware}

New as of: 25 November 2020

By default, users in your account authenticate themselves by logging in with a username and password. To require users to use more secure authentication factors, the following MFA options are now available.

  * MFA for users with an IBMid: Users authenticate by using an IBMid, password, and time-based one-time passcode (TOTP). This option applies to all users or just non-federated users.
  * MFA for all users: This option applies to users who are using either an IBMid or an external identity provider (IdP). Users authenticate by using email-based MFA, TOTP MFA, or U2F MFA. The U2F MFA factor is based on the FIDO U2F standard, and it offers the highest level of security.

For more details, see [Enabling MFA for your account](/docs/account?topic=account-enablemfa).

## Enhanced Support Center
{: #support-center-enhance-oct2020}

New as of: 28 October 2020

The [Support Center](https://cloud.ibm.com/unifiedsupport/supportcenter){: external} is now updated to help improve your experience with creating and managing your support cases. You can refine the scope of your cases by routing them to a specfic resource and provide feedback on your cases. You will also find popular FAQs that are featured based on your specific issue. For more details, see [Announcing the Release of Our New Support Center Enhancements](https://www.ibm.com/cloud/blog/announcements/new-support-center-enhancements){: external}.

## Managing {{site.data.keyword.cloud-shell_notm}} settings and other updates to {{site.data.keyword.cloud-shell_notm}}
{: #cloud-shell-sept2020}

New as of: 18 September 2020

Account owners or users with {{site.data.keyword.cloud-shell_short}} administrator access can manage {{site.data.keyword.cloud-shell_short}} settings from the {{site.data.keyword.cloud_notm}} console. For more information, see [Updating {{site.data.keyword.cloud-shell_short}} settings](/docs/account?topic=account-shell-settings).

For a complete list of changes, see the [{{site.data.keyword.cloud-shell_short}} release notes](/docs/cloud-shell?topic=cloud-shell-release-notes-image).

## Restricting account access by using IAM account settings
{: #iam-acct-settings}

For increased control over which users can access your account and work with API keys and service IDs, leverage the three new settings that are available on the **Manage** > **Access (IAM)** > **Settings** page in the console.

* Restrict access to your account to only users coming from a specified IP address or range that you set. For more information, see [Allowing specific IP addresses](/docs/account?topic=account-ips).
* Block all users from creating API keys in the account except for those that you give explicit access. For more information, see [Restricting users from creating API keys](/docs/account?topic=account-allow-api-create).
* Block all users from creating service IDs in the account except for those that you give explicit access. For more information, see [Restricting users from creating service IDs](/docs/account?topic=account-restrict-service-id-create).

## Introducing {{site.data.keyword.compliance_short}}
{: #scc-aug2020}

New as of: 31 August 2020

For highly regulated industries, such as financial or healthcare services, achieving a continuously secure and compliant cloud environment is an important first step toward protecting customer and application data. But, we understand that historically this has been a difficult and manual process, potentially placing your organization at risk, which is why, we're excited to introduce the {{site.data.keyword.compliance_short}} - built directly into the {{site.data.keyword.cloud_notm}} platform.

With the {{site.data.keyword.compliance_short}}, you can embed checkpoints into your everyday workflows that not only help to monitor for security and compliance but enforce configuration standardization across your accounts. By ensuring you have automation in place that monitors for risk, you can identify security vulnerabilities quickly and work to mitigate the impact that they have to your business.

For more information, see [Getting started with {{site.data.keyword.compliance_short}}](/docs/security-compliance?topic=security-compliance-getting-started).

## {{site.data.keyword.cloud_notm}} CLI Version 1.2.0 is now available
{: #cli-120}

New as of: 20 August 2020

The 1.2.0 release of the {{site.data.keyword.cloud_notm}} CLI includes:
 * New commands under `sl loadbal` namespace to support the {{site.data.keyword.loadbalancer_full}} service.
 * Output CSV support for billing commands.
 * Validation of service instance ID input in policy commands under `iam` namespace.
 * Additional deployment capabilities with the `ibmcloud dev` command, including manual deployment to Knative and deployment to {{site.data.keyword.openshiftlong}} containers.
 * Deprecation of the `cfee` namespace.

For more information about the {{site.data.keyword.cloud_notm}} CLI, see [Getting started with the IBM Cloud CLI](/docs/cli?topic=cli-getting-started).

## Increased usage quota and other updates to {{site.data.keyword.cloud-shell_notm}}
{: #cloud-shell-aug2020}

New as of: 12 August 2020

With this update to {{site.data.keyword.cloud-shell_notm}}, the weekly usage quota was increased from 30 hours a week to 50 hours a week so that you can use {{site.data.keyword.cloud-shell_short}} even more. Also, {{site.data.keyword.cloud-shell_short}} was changed to have separate workspaces for each user and account, whereas previously each user's workspace was shared across all of their accounts. In your sessions, you'll also now have access to more command-line tools with the addition of the Operator SDK for Kubernetes, the Mercurial source content management tool, and the Bazaar version control system, as well as updates to existing tools.

For a complete list of changes, see the [{{site.data.keyword.cloud-shell_short}} release notes](/docs/cloud-shell?topic=cloud-shell-release-notes-image).

## Customizing scoped dashboards 
{: #scoped-dash-aug2020}

New as of: 10 August 2020

Create and manage customized dashboards that can be used to offer an organized and relevant workspace. You can share the dashboards with different users in your account or as a way to group resources for specific projects or teams. When you create a new dashboard, you can start from scratch with a blank template or choose one of the other available templates. For more information, see [Working with scoped dashboards](https://test.cloud.ibm.com/docs/account?topic=account-custom-dashboard).

## Audit logs for private catalogs
{: #audit-logs-catalogs}

New as of: 04 August 2020

View recorded changes to your private catalogs with the new audit logs feature. Audit logs are recorded when you create, delete, or update your private catalog. Visit your Audit logs page in the {{site.data.keyword.Bluemix_notm}} console by going to **Manage** > **Catalogs**, and selecting **Audit logs**. For more information, see [Viewing changes to your private catalogs](/docs/account?topic=account-catalog-audit-logs).

## Notification distribution list
{: #notification-distribution}
New as of: 07 July 2020

You can now create a list of up to 10 email addresses that receive account-wide notifications in the {{site.data.keyword.Bluemix_notm}} console by going to **Account**  > **Notification distribution list**. Users that are added to the distribution list are notified about any event that's affecting the account. For more information, see [Adding users to a distribution list](https://cloud.ibm.com/docs/account?topic=account-email-prefs#adding-users-to-a-distribution-list)

## CLI support for catalog filtering in {{site.data.keyword.Bluemix_notm}} enterprises
{: #enterprise-filter-cli}
New as of: 07 July 2020

You can now use the following commands to set and manage filters in accounts within an enterprise hierarchy:

* **`ibmcloud catalog filter get`**
* **`ibmcloud catalog filter create`**
* **`ibmcloud catalog filter offering`**
* **`ibmcloud catalog filter delete`**

Each command operates the same at the enterprise level by default. You can also apply the commands to specific account groups in an enterprise. For more information, see the [Catalogs management CLI plug-in](/docs/cli?topic=cli-manage-catalogs-plugin).

## Consulting services are available in the {{site.data.keyword.Bluemix_notm}} catalog
{: #catalog-consulting-svcs}
New as of: 07 July 2020

We now offer consulting services that aim to help guide you in transforming your business. Our consulting strategy combines expertise, tools, and methodologies to develop cloud strategies and implementation plans that align with your business goals. 

To check out the available consulting services, go to the [catalog](https://cloud.ibm.com/catalog){: external}, and click **Consulting**. 

## Catalog management SDKs
{: #catalog-mgmt-sdks}
New as of: 07 July 2020

Four new Software Development Kits (SDKs) for the catalog management service, which includes private catalogs and software products, are now available. 

* The {{site.data.keyword.Bluemix_notm}} Platform Services Java SDK
* The {{site.data.keyword.Bluemix_notm}} Platform Services Node.js SDK
* The {{site.data.keyword.Bluemix_notm}} Platform Services Python SDK
* The {{site.data.keyword.Bluemix_notm}} Platform Services Go SDK

For more information, see the [Catalog Management API reference](https://cloud.ibm.com/apidocs/resource-catalog/private-catalog){: external}. 

## OVA images are available in the {{site.data.keyword.Bluemix_notm}} catalog
{: #ova-vcenter-support}
New as of: 07 July 2020

With the deployment power of the {{site.data.keyword.Bluemix_notm}} Schematics service, support for third-party OVA images targeting VMware vCenter Server deployments is now available. To quickly find the available products in the [catalog](https://cloud.ibm.com/catalog){: external}, click **Software**, and select **OVA Images** from the **Software** list. 

## {{site.data.keyword.cloud-shell_notm}} is generally available
{: #cloud-shell-ga}
New as of: 24 June 2020

{{site.data.keyword.cloud-shell_notm}}, the browser-based shell environment, is now generally available (GA)! This release includes greater region support with the addition of the Tokyo (`jp-tok`) region. {{site.data.keyword.cloud-shell_short}} sessions now also support inputting and viewing double-byte characters on the command line, so you can work in languages such as Japanese, Simplified and Traditional Chinese, and more. The server image was also updated to include updates to several command line tools, in addition to the regular updates for the {{site.data.keyword.cloud_notm}} CLI and plug-ins.

To try out {{site.data.keyword.cloud-shell_notm}}, see [Getting started with {{site.data.keyword.cloud-shell_notm}}](/docs/cloud-shell?topic=cloud-shell-getting-started).

## Connect to an external identity provider for authentication
{: #external-idp}
New as of: 21 May 2020

You can now connect your external identity provider to an {{site.data.keyword.appid_full_notm}} instance, and then configure that {{site.data.keyword.appid_short}} to connect directly to {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) to federate authentication for users in your enterprise to your {{site.data.keyword.Bluemix_notm}} account.

By using this new integration between {{site.data.keyword.appid_short}} and {{site.data.keyword.Bluemix_notm}} IAM, you can simplify the log in experience for users in your enterprise and automatically add users to your account through their login, instead of having to invite or federate each user individually with IBMid. For more information, see [Enabling authentication from an external identity provider](/docs/account?topic=account-idp-integration).

## Support for catalog filtering in {{site.data.keyword.Bluemix_notm}} enterprises
{: #enterprise-catalog-filter}
New as of: 01 May 2020

You can now use filters to customize which products in the {{site.data.keyword.Bluemix_notm}} catalog are available in accounts within an enterprise hierarchy. Filters that are set at a parent account level apply to all child account groups and accounts. For more information, see [Managing products for an {{site.data.keyword.Bluemix_notm}} enterprise](/docs/account?topic=account-catalog-enterprise-restrict).   

## Unified notifications experience
{: #unified-notifications-experience}
New as of: 21 April 2020

Viewing your notifications is now easier than ever with the new unified notifications experience. The notifications page is the centralized place to view and manage all incidents, maintenance, and announcements that might affect your account. In the {{site.data.keyword.Bluemix_notm}} console, click the **Notifications** icon ![Notification icon](../../icons/Notification.svg "Notifications") on the console menu bar to view your notifications.

Additionally, you can find all infrastructure notifications on the new notifications page. To learn more about the new notifications experience, see [Viewing notifications](/docs/get-support?topic=get-support-viewing-notifications).

## New features and multi-region support for {{site.data.keyword.cloud-shell_notm}} (Beta)
New as of: 18 April 2020

This update to {{site.data.keyword.cloud-shell_notm}} (Beta) includes several new features to help you work from the command line in {{site.data.keyword.Bluemix_notm}}:
* You can now preview web apps within {{site.data.keyword.cloud-shell_short}}. By running apps on an available port, you can open a preview at a URL that only you can see, similar to a cloud version of `localhost`. 
* You can now use {{site.data.keyword.cloud-shell_short}} within the Frankfurt region in addition to the existing Dallas region. 
* Usage timeouts were changed to extend how long you can leave your sessions idle before they're closed. And, there's no longer a time limit on continuous usage.
* An update to the server image adds the GNU Automake (`automake`) and GNU Compiler Collection (`gcc`, `gcov`, and `gcov-tool`) tools to your sessions. 

For a complete list of changes, see the [{{site.data.keyword.cloud-shell_short}} release notes](/docs/cloud-shell?topic=cloud-shell-release-notes-image).

## {{site.data.keyword.cloud_notm}} CLI Version 1.0.0 is now available
(: #cli-100}

New as of: 31 March 2020

The 1.0.0 release of the {{site.data.keyword.Bluemix_notm}} CLI includes two new global options to help you more easily automate command-line scripting tasks. The new `--output json` option provides command output in a parsable JSON format, and the `--quiet` option suppresses some extra messages such as progress indicators simplify automated processing. The {{site.data.keyword.Bluemix_notm}} CLI now also includes the {{site.data.keyword.dev_cli_notm}} (`ibmcloud dev`) commands, so you can work with apps, pipelines, toolchains, and more without needing to install a separate plug-in. The Cloud Foundry CLI (`ibmcloud cf`) is no longer bundled but can still be installed separately.

For more information about the {{site.data.keyword.Bluemix_notm}} CLI, see [Getting started with the IBM Cloud CLI and Developer Tools](/docs/cli?topic=cli-getting-started).

## Customizing how access is assigned by using custom roles
New as of: 18 March 2020

Until now, you assigned access by using the available platform and service roles that have specific actions that are mapped by individual services. Sometimes, you must assign multiple roles to achieve the required access for your users. With the latest {{site.data.keyword.Bluemix_notm}} Identity and Access Management feature, you can now customize how access is assigned within individual services by creating custom roles. You can choose to organize any number of actions available for a specific service into a new role with a name of your choosing. For more information, see [Creating custom roles](/docs/account?topic=account-custom-roles).

## Updated handling of API keys for removed users
{: #api-keys-removed-users}
New as of: 26 February 2020

When you remove a user from your account, {{site.data.keyword.cloud_notm}} automatically cleans up the API keys associated with that user's identity, so you don't have to. For more information, see the [Updated handling of IBM Cloud API keys for users removed from accounts](https://www.ibm.com/cloud/blog/announcements/updated-handling-of-ibm-cloud-api-keys-for-users-removed-from-accounts){: external} blog post.

## {{site.data.keyword.cloud-shell_notm}} (Beta) is now available
{: #cloud-shell-beta}
New as of: 21 January 2020

We're introducing a new way to access {{site.data.keyword.cloud_notm}} from the command line with no installation needed - {{site.data.keyword.cloud-shell_full}}! {{site.data.keyword.cloud-shell_notm}} is a cloud-based shell environment that gives you instant command-line access through your web browser. It's preconfigured with the full {{site.data.keyword.cloud_notm}} CLI, all CLI plug-ins, and tons of tools so you have everything that you need to manage apps, resources, and infrastructure. To try out this beta release, see [Getting started with {{site.data.keyword.cloud-shell_notm}}](/docs/cloud-shell?topic=cloud-shell-getting-started).

## Improved Support Center 
{: #improved-support}
New as of: 09 January 2020

The latest enhancement to the support center offers a personalized experience to better resolve any IBM Cloud related issue. Navigate through the landing page to view incidents that are specific to your account along with a list of your open cases. Additionally, our self-help options have expanded, popular FAQs and recommended topics are populated to provide information that is relevant to your account. To check out the new experience, log in and go to the [Support Center](https://cloud.ibm.com/unifiedsupport/supportcenter){: external} . 

## Disable public access to resources
{: #disable-public}
New as of: 19 December 2019

All users and service IDs are members of the Public Access group by default, which provides unauthenticated access to the resources that the group can access. You can now disable public access at the account level for cases in which you might want to prevent policies that could publicly expose resources from being created. For more information, see [Managing public access to resources](/docs/account?topic=account-public). 

## Delete resource groups
{: #delete-rgs}
New as of: 26 November 2019

Besides the default resource group that's automatically created for you when create your {{site.data.keyword.Bluemix_notm}} account, you can now delete any resource group that doesn't contain any resources. For more information, see [Managing resource groups](/docs/account?topic=account-rgs).


## Bitnami Helm charts
{: #bitnami}
New as of: 04 November 2019

{{site.data.keyword.IBM_notm}} and VMware are partnering to provide the [Bitnami Application Catalog](https://bitnami.com/stacks){: external} to {{site.data.keyword.cloud_notm}} customers. The first set of offerings available in the {{site.data.keyword.cloud_notm}} catalog are the Bitnami Helm charts, which Bitnami has created and validated to work on the {{site.data.keyword.containerlong_notm}}. Kubernetes developers typically install Helm charts manually from the CLI by using the helm command. However, this installation process has been simplified by building an auto-installation feature in the {{site.data.keyword.cloud_notm}} catalog. Check out these offerings today by selecting **Bitnami** from the **Provider** filter.


## Apply promo codes to your account and services
{: #promo-codes}
New as of: 18 October 2019

{{site.data.keyword.Bluemix_notm}} now has promo codes that you can use to get credit toward your account and services. Promo codes are provided by {{site.data.keyword.Bluemix_notm}} sales on a limited basis to customers with billable accounts. You can apply promo codes from a new Promotions page or from the catalog when you create a resource in the {{site.data.keyword.Bluemix_notm}} console. For more information, see [Applying promo codes](/docs/billing-usage?topic=billing-usage-applying-promo-codes).

## Download access reports for specific resources
{: #access-report}
New as of: 17 October 2019

Have you ever wanted to get a quick view of all users, service IDs, access groups, and services that have access to a specific resource in your account? Well, now you can download a report that includes details about who can access your resource. From the My resources page in your account, you can select the **Export access report** option in the row for an IAM-enabled resource to get the report. For more information about the types of data available in the report and who has access to view the report, see [Exporting an access report](/docs/account?topic=account-access-report).

## Mapping actions to IAM roles 
{: #actions-iam}
New as of: 15 October 2019

When you invite a user to your account or assign an existing user IAM access, you can review each action that is mapped to a role. Click the **Actions for role** option to view a list of all actions that are mapped to a specific role when you're selecting the roles to assign in an access policy. By reviewing the action to role mappings, you can have confidence that you are always assigning the correct level of access to users in your account. For more information about this new enhancement, see [Invite User Flow and Transparent Actions](https://www.ibm.com/cloud/blog/announcements/invite-user-flow-and-transparent-actions){: external}.

## Cloud Paks and Schematics templates
{: #cloud-paks-terraform}
New as of: 3 October 2019

With the deployment power of the {{site.data.keyword.Bluemix_notm}} Schematics service, we now deliver bundled solutions through packaged software and deployable automation scripts that empower you to build, manage, and modernize your cloud architectures faster and more securely. The first release of these offerings include IBM Cloud Paks and a handful of useful Terraform-based templates. 

From the [catalog](https://cloud.ibm.com/catalog), filter by the offering type and deployment target to find what you're looking for faster. Select **Cloud Paks** and **Terraform** to check out the new offerings that are available.

## Term-based model for {{site.data.keyword.Bluemix_notm}} support subscriptions
{: #support-subscriptions}
New as of: 23 September 2019

New subscriptions for {{site.data.keyword.Bluemix_notm}} support now follow the same term-based model as subscriptions for {{site.data.keyword.Bluemix_notm}} platform services. Rather than credit being valid in monthly increments, credit is now available up front for an entire subscription term, which can be up to one year's worth of credit. You now have more flexibility to use your support credit when you need it, and the chances of incurring monthly overages are reduced. When you buy or renew a support subscription, any existing active support subscriptions are converted to this new flexible model for the remainder of their term. For more information, see [Support subscriptions](/docs/account?topic=account-accounts#support-subscriptions).

You can also now view your support subscriptions in the {{site.data.keyword.Bluemix_notm}} console so you can keep track of your available credit. For more information, see [Viewing your support costs](/docs/billing-usage?topic=billing-usage-support).

## Redirecting SoftLayer to {{site.data.keyword.Bluemix_notm}} 
{: #sl-redirect}
New as of: 12 September 2019

SoftLayer account owners who previously didn't have access to the {{site.data.keyword.Bluemix_notm}} platform can now manage their infrastructure, services, and applications from one location: [cloud.ibm.com](https://cloud.ibm.com){: external} . For more details, see [Transitioning to the {{site.data.keyword.Bluemix_notm}} experience](/docs/overview?topic=overview-ui#redirect-cloud).

## {{site.data.keyword.Bluemix_notm}} enterprises for centrally managing multiple accounts
{: #ibm-cloud-enterprises}
New as of: 25 July 2019

You can now centrally manage billing and usage for multiple accounts by creating an {{site.data.keyword.Bluemix_notm}} enterprise. With an enterprise, you can create a multitiered hierarchy of accounts by organizing related accounts into account groups. Enterprises simplify management of multiple accounts with the following key features:
   * Consolidated billing means that you can manage billing, invoicing, and payment for all accounts from a single place, the enterprise account. 
   * Subscription credit is aggregated into a credit pool and shared with all accounts in the enterprise. Not only is tracking your subscriptions easier, but you can get fewer, larger subscriptions for a better discount because the credit is shared. 
   * Top-down usage reporting gives you a unified view of usage costs from all accounts, organized according to your enterprise hierarchy. 

If you have multiple accounts, at least one of which is a Subscription account, you can create an enterprise. See [What is an enterprise?](/docs/account?topic=account-enterprise) and [Introducing IBM Cloud Enterprises](http://www.ibm.com/cloud/blog/announcements/Introducing-IBM-Cloud-Enterprises){: external}  for more information.

## Subscriptions page for tracking subscription credit spending
{: #subscriptions-page}
New as of: 18 July 2019

If you have a Subscription account, you can now view all of your subscriptions and analyze your credit spending on the Subscriptions page. You get a high-level view of the total subscription credit in your account and detailed charts that visualize trends such as your credit burndown and monthly spending. You can also view credit from any promotions in your account. For more information, see [Managing subscriptions](/docs/billing-usage?topic=billing-usage-subscriptions).

Additionally, to better reflect their usage, codes that you apply to add subscription credit to your account are now called subscription codes rather than feature codes.

## Managing SoftLayer SAML federation on {{site.data.keyword.cloud_notm}}
{: #saml-federation}
New as of: 02 July 2019

Former SoftLayer users who set up a SAML identity provider for logging in with federated IDs can now manage their configuration data in the {{site.data.keyword.cloud_notm}} console in Access (IAM) on the Identity providers page. This type of federation is deprecated, so new identity providers can't be set up currently. You can continue to update your identity provider data or choose to delete this federation in favor of switching to [federating with IBMid](/docs/account?topic=account-account-getting-started#signup-federated).

## Customize your dashboard
{: #custom}
New as of: 14 June 2019 

You can now control what's displayed on your dashboard. Customizing your dashboard includes the ability to add, remove, and rearrange the widgets. For more information, see [Customizing your dashboard](/docs/account?topic=account-custom-dashboard).

## Export usage data with associated tags
New as of: 4 April 2019 

You can now use our newest tagging capabilities to manage resources, usage, and costs in the exported usage report. When you add a tag to a resource, you can view the tag that is associated with the resource. In the {{site.data.keyword.cloud_notm}} console, go to **Manage**> **Billing and Usage**> **Usage**> **Export CSV**>  **Instances** to download your usage report. For more information on exporting tags, check out the [Export tags within your usage data to help with cost allocation](https://www.ibm.com/cloud/blog/export-your-tagged-usage-data-within-the-enhanced-ibm-cloud){: external}  blog post.

## Enabling public access to resources
New as of: 25 March 2019

You can now enable public access to objects in your {{site.data.keyword.cos_full}} buckets by using a new access group that is provided for you in your account. This new access group is called the `Public access` group, and all users and service IDs are added to it by default. You can update the policies for the access group to enable all users, even unauthenticated users, access to the resource that you specify in the policy. [Learn more about the public access group](/docs/account?topic=account-public#public).

## Multifactor authentication for users with federated IDs
New as of: 12 March 2019
{: #mfa-federated}

Account owners or users assigned the administrator role for the billing account management service can enable multifcator authentication (MFA) for all users in their account. Federated users who use their corporate or enterprise single sign-on ID can now be required to authenticate by using MFA for logging in to {{site.data.keyword.Bluemix_notm}}. For more information about this feature enhancement and what you need to know about enabling MFA for your account, see [Introducing MFA for IBM Cloud Users with Federated ID](https://www.ibm.com/cloud/blog/introducing-mfa-for-ibm-cloud-users-with-federated-id){: external} .

## New appdomain.cloud host name option
New as of: 31 December 2018
{: #appdomain}

A new host name option `*.appdomain.cloud` is available on cloud.ibm.com.

Previously, the `mybluemix.net` domain was used for hosting apps in various deployment targets, such as {{site.data.keyword.containerlong_notm}} or Cloud Foundry. Any apps that are hosted on `mybluemix.net` are not impacted.

The subdomain for Cloud Foundry apps is `cf.appdomain.cloud`. The subdomain for apps that you deploy to {{site.data.keyword.containerlong_notm}} is `containers.appdomain.cloud`.

## New Cloud Foundry API endpoints
New as of: 30 November 2018
{: #cf-api-endpoints}

The legacy `api.*.bluemix.net` Cloud Foundry API endpoints are still available for compatibility with earlier versions. However, you can update scripts and infrastructure automation to use the following new Cloud Foundry API endpoints for your region:

* api.us-south.cf.cloud.ibm.com (previously api.ng.bluemix.net)
* api.eu-gb.cf.cloud.ibm.com (previously api.eu-gb.bluemix.net)
* api.us-east.cf.cloud.ibm.com (previously api.us-east.bluemix.net)
* api.eu-de.cf.cloud.ibm.com (previously api.eu-de.bluemix.net)
* api.au-syd.cf.cloud.ibm.com (previously api.au-syd.bluemix.net)

## Enhanced support experience for {{site.data.keyword.Bluemix_notm}}
New as of: 30 November 2018 
{: #support}

With the Support Center, you can work to resolve all {{site.data.keyword.Bluemix_notm}}-related issues. The landing page provides you FAQs, so you can find the answer to your question without even contacting {{site.data.keyword.Bluemix_notm}}. You can also chat with a live support rep. Your cases can now be managed in from a single location. In the console, go to **Support** &gt; **Manage cases** to create, view, or edit cases.

You can also find the [Status page](https://cloud.ibm.com/status){: external}  from the Support Center. It is enhanced to include all unplanned incidents, planned maintenance, announcements, and security bulletin notifications about key events that affect the {{site.data.keyword.Bluemix_notm}} platform, infrastructure, and major services. Click **View cloud status** from the Support Center. To check out the new experience, log in and go to the [Support Center](https://cloud.ibm.com/unifiedsupport/supportcenter){: external} . 

## Unified login, API keys, and user and access management
New as of: 30 November 2018
{: #useraccess}

With our latest updates, you can take advantage of a simplified secure login that is available for all users regardless of your ID type. Whether you have an IBMid or a SoftLayer ID, you can quickly log in to the {{site.data.keyword.Bluemix_notm}} console from our enhanced login page. You can also make secure API calls across {{site.data.keyword.Bluemix_notm}} and automate your CLI login by using an IAM API key or an IAM access token. 

After you log in, you can now see all users, including platform and classic infrastructure users, from your Users page in the Access (IAM) UI. Depending on your access to view other users in the account, you can filter your view quickly by account users, classic infrastructure users, or Cloud Foundry org. You can also use the filters to find users quickly by name, email, or status.

Now that all of your users are in a single console, you can manage their access to all types of resources from the same place. Access starts with the user, so start by selecting a user from your list. Then, depending on which type of resource that you want to assign access to, you can choose from IAM access policies, Cloud Foundry access, or classic infrastructure permissions. If you want to assign IAM access policies, try creating an access group to streamline your access management process by adding all users to the same access group that need the same policies assigned.

For more details, check out [Outstanding User Access Improvements Help Deliver a Unified {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-access-management){: external} . 

## Find all {{site.data.keyword.Bluemix_notm}} CLI plug-in documentation in one place
New as of: 30 November 2018
{: #cli}

You can now access all of the {{site.data.keyword.Bluemix_notm}} CLI plug-in documentation in one location, making it easier for you to find any CLI command that you are looking for. Check out the References section in the [CLI documentation](/docs/cli?topic=cli-ibmcloud_cli).

## New dashboard and Resource list page
New as of: 30 November 2018
{: #dash}

With our latest update, you can now view all your platform and infrastructure services from one location. When you log in, you can check out the new dashboard right away. After you add resources to your account from the catalog, you can use your resource list to get a full view of your account resources:

* The dashboard is redesigned so that you can view a summary your resources, maintenance, status, apps, support, usage, and users.
* You can find more details about your resources by going to your resource list. You can tag your resources to organize them, or select them to update the details page.
* Now that you can see all of your resources in one place, we added a global search so that you can quickly find resources that you created and expect to find in your resource list. 
* You can also search for catalog results, so you can quickly find resources to add to your account.  

See [Manage All Your Cloud Resources on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/blogs/bluemix/2018/11/manage-all-your-cloud-resources-on-the-enhanced-ibm-cloud-platform/){: external}  for more details.

## Unified account, billing, and user profile information
New as of: 30 November 2018
{: #profile}

Your account, billing, and profile information is now simplified. You can view your account information for all of your platform and infrastructure resources in a unified console. 

* Your profile and settings area contains information about you as well as your email notification preferences for all resource types. 
* Your account information area contains information about your company or organization, account settings, and quick access for working with resource groups and Cloud Foundry orgs. You can even find best practices to help you get up and running quickly!
* Your billing and usage area of your account helps you understand your bill, make payments, monitor subscriptions, get quotes, track orders, and set spending notifications.

Check out [Bringing It All Together: A Single Account and Billing Management Experience](https://www.ibm.com/cloud/blog/announcements/ibm-cloud-account-management){: external}  for more details.

## Organize your resources with tags
New as of: 30 November 2018
{: #tag}

Tags are now available for you to add to your resources, like Cloud Object Storage, to help you manage resources and find the resources that are the most relevant to you. For example, if you have hundreds of resources and you want to differentiate between ones that are paid the same way, you could tag them with `costcenter:location01`. Or, if you have a team that is working on a couple of resources repeatedly, you can use something like `team-blue`. You can also filter the My resources page by tags to quickly organize and find the resources that you need. For more information, see [Working with tags](/docs/account?topic=account-tag) and [Platform Tagging on the Enhanced {{site.data.keyword.Bluemix_notm}} Platform](https://www.ibm.com/cloud/blog/announcements/platform-tagging-on-the-enhanced-ibm-cloud-platform){: external} . 

## Get accurate monthly costs with the cost estimator
New as of: 30 November 2018
{: #cost-estimator}

To help you decide and analyze what services you'd like to purchase, you can use the cost estimator. Now, you can go through the console and select each service you'd like to have, and add all of the costs in an easy to use tool. You can even enter projected data usages, lookups per second, writes per second, and queries per second to get a more accurate estimation of your monthly expenditures. You can use the cost estimator with each catalog service you select, or you can click the cost estimator icon ![Cost Estimator icon](../icons/calculator.svg "Cost Estimator") in the console menu to get a summary of your estimated costs. For more information, see [Estimating your costs](/docs/billing-usage?topic=billing-usage-cost).

## Updated global location names
New as of: 1 November 2018
{: #location-name-updates}

As {{site.data.keyword.cloud_notm}} continues to expand our global availability footprint, we’re updating our location naming structure to better support an understandable, consistent hierarchy of geographies, regions, and data centers around the world. If you’re familiar with our current global regions, you’ll recognize names like US South and Sydney. We’re aligning these location names to the names of the city in which the data centers physically exist.

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

## Assign account management access to others
New as of: 30 October 2018
{: #acct-mgmt-services}

With {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM), you can delegate common tasks that you complete as an account administrator to another user in your account. By creating an access policy on one or all of the available account management services, you can easily delegate responsibilities such as inviting and removing users, managing access groups, managing service IDs, maintaining private catalog services, and even monitoring billing and tracking usage. There are four individual account management services and an all services option that you can use to set up access policies:

* User Management for inviting and removing users
* IAM Access Groups for creating, editing, deleting, updating, and assigning access 
* IAM Identity Service for viewing, creating, deleting, and assigning access to service IDs and associated API keys across the account
* Global resource catalog for viewing private catalog offerings and updating the metadata and visibility for the offerings
* All account management services for access to each of the individual account management service options based on the assigned role as well as access to billing and usage tracking.

For more information on the tasks that a user can do based on which account management service they have a policy on and which role they are assigned, see [Example platform management roles and actions for account management services](/docs/account?topic=account-account-services#account-management-actions-roles). For more information about this new feature, see the [Introducing More Flexibility and Control for IBM Cloud Account Management Services Access](https://www.ibm.com/cloud/blog/announcements/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access){: external}  blog post. 

## Searching for resources
New as of: 17 July 2018
{: #forward-slash-key}

You can search for resources from anywhere in the {{site.data.keyword.cloud_notm}} console. Type the name of a resource in the search field in the console menu bar. Press the Forward Slash key (/) to activate the search.

## Dynamically add federated users to access groups
New as of: 12 July 2018
{: #add-fed-users}

You can create dynamic rules to automatically add federated users to access groups based on specific identity attributes. When your users log in with a federated ID, the data from the identity provider dynamically maps your users to an access group based on the rules that you set. For more information, see [Creating dynamic rules for access groups](/docs/account?topic=account-rules).

## Protect your service IDs and API keys
New as of: 1 June 2018
{: #protect-svcid-apikey}

To avoid a situation where your service ID or API key is deleted causing an outage or disruption, you can lock service IDs and API keys by using the UI or CLI. Locking a service ID also prevents any access policies from being changed, deleted, or assigned as well as any API keys associated with the service ID from being created or deleted. For more information, see [Locking a service ID](/docs/account?topic=account-serviceidapikeys#lockkey) and [Locking an API key](/docs/account?topic=account-userapikey).

## Upgrade your Lite account to a Subscription account
New as of: 31 May 2018
{: #upgrade-lite}

You can now upgrade your Lite account to a Subscription account directly from the {{site.data.keyword.Bluemix_notm}} console. With a Subscription account, you can use both platform and infrastructure offerings, and take advantage of discounted pricing by making a monthly spending and term commitment. You can also avoid surprises with fixed billing on a monthly payment schedule, but with the flexibility to order more or less based on your needs. For more information, see [FAQS for billing and usage](/docs/billing-usage?topic=billing-usage-billusagefaqs). 

## {{site.data.keyword.Bluemix_notm}} CLI rebranding
New as of: 15 May 2018
{: #cli-rebrand}

The {{site.data.keyword.Bluemix_notm}} CLI commands changed from **`bluemix`** and **`bx`** to **`ibmcloud`**. However, you can still use the **`bluemix`** and **`bx`** CLI commands until they are removed later. There is no short name now, just the full name **`ibmcloud`**. 

## Multi-factor authentication for your account
New as of: 02 May 2018
{: #account-mfa}

Multi-factor authentication (MFA) adds an extra layer of security to your account by requiring all users to provide a time-based one-time passcode in addition to their standard IBMid and password during login. This is also commonly known as two-factor authentication (2FA). MFA is enabled per account, and once it is turned on, all users in the account are required to log in by using the extra security measure. For more information, see the [IBM Cloud Platform now adds support for Multi-Factor Authentication](https://www.ibm.com/cloud/blog/ibm-cloud-platform-now-adds-support-multi-factor-authentication){: external}  blog post.

## Assign access quickly by using access groups
New as of: 03 April 2018
{: #access-groups}

Do you want to be able to assign access quickly by using the least number of policies possible? Now you can with access groups. Group a set of users and service IDs together and assign a single policy that applies to all members of the group. By using access groups, you can limit the time that you spend managing access to the users and service IDs in your account. Check out the blog post [New feature: Access groups](https://www.ibm.com/cloud/blog/access-groups){: external}  for more details.

## Cloud Foundry Service US East region
New as of: 15 December 2017
{: #cf-useast}

A new US East data center is now available in Washington, DC. You can reach this new region by using the `us-east.cloud.ibm.com` endpoint. For details about the services that are available for purchase in this new region, see [Services by region](/docs/overview?topic=overview-services_region).

## Support for resources in the European Union
New as of: 14 December 2017
{: #eu-resources}

If your services and data centers are located in Europe, {{site.data.keyword.Bluemix_notm}} now offers extra capabilities to protect your data in the European Union. You can request that support is provided by customer success teams that are located in Europe. This support is available 24 hours a day, 7 days a week. See [Enabling the EU supported option](/docs/account?topic=account-eu-hipaa-supported#bill_eusupported) and [Requesting support for resources in the European Union](/docs/get-support?topic=get-support-using-avatar#eusupported) for more information.

## Withdrawal of support for TLS 1.0 and 1.1
New as of: 28 November 2017
{: #nosupport-tls}

On 1 March 2018 {{site.data.keyword.Bluemix_notm}} will withdraw support for TLS 1.0 and TLS 1.1 across many of our cloud products and services as part of our commitment to offering a cloud that is secure to the core and in alignment with industry best practices for security and data privacy.

## A new way to organize resources within your account
New as of: 16 November 2017
{: #usergs}

Resource groups are a new way for you to create customizable groupings of account resources, and access to the group and the resources within it are managed by using Identity and Access Management (IAM). Everyone starts out with a default resource group. You can rename this resource group and add new service instances to it as you create them from the catalog.

For users with a Pay-As-You-Go or Subscription account, you can create extra resource groups to make managing quota and viewing billing usage for a set of resources easier. You can also group resources to make it easier for you to assign users access to more than one service at a time. To learn more about working with resource groups for your account, see [Managing resource groups](/docs/account?topic=account-rgs).

## Updates for {{site.data.keyword.Bluemix_notm}} IAM
New as of: 16 November 2017
{: #iam-nov17}

The introduction of resource groups within your {{site.data.keyword.Bluemix_notm}} account provides a new way for you to assign access. Users and service IDs can be assigned access to all services within a resource group, enabling you to quickly assign access to more than one resource at a time. You can also customize access for each user or service ID by assigning access to just some services within a resource group, or you choose to assign access to individual resources down to the service instance level. For more information about the features that you can take advantage of by using IAM, see [What features does IAM provide?](/docs/account?topic=account-iamoverview#features)

## Customize your dashboard view
New as of: 16 November 2017
{: #custom-dash}

You can view and manage all the resources in your account from your dashboard in the {{site.data.keyword.Bluemix_notm}} console. And now, you can set filters to customize your view. For example, you can filter by resource group to view the specific resources in a resource group. You can also filter by region or Cloud Foundry space. For more details, see [Managing resources on the dashboard](/docs/overview?topic=overview-ui#dashboardview).

## Support Center
New as of: 2 November 2017
{: #support-nov17}

We now have the new Support Center where you can search for information, post questions to our developer community, and manage tickets. Go to **Support > Support Center** in the {{site.data.keyword.Bluemix_notm}} console menu bar.

## Introducing {{site.data.keyword.Bluemix_notm}}
New as of: 31 October 2017
{: #meet-ibmcloud}

Bluemix is now {{site.data.keyword.Bluemix_notm}}. Besides rolling out our new name, nothing changes. You can still easily build and run your apps and services as always. Check out the [{{site.data.keyword.Bluemix_notm}} blog](https://www.ibm.com/cloud/blog/announcements/bluemix-is-now-ibm-cloud){: external}  for more details.

## Lite account
New as of: 31 October 2017
{: #new-liteacct}

A Lite account is our new account type that gives you access to try select services for free with no time restrictions. This new account also includes usage tracking and efficiency features to help you better manage your resources. To learn more about what's available, see [Account types](/docs/account?topic=account-accounts#liteaccount).

## Identity and Access Management application authentication feature
New as of: 6 October 2017
{: #app-authfeature}

Identity and Access Management (IAM) now supports service IDs, which you can think of as identities that can be used for apps to authenticate with your {{site.data.keyword.Bluemix_notm}} services. Instead of using individual user credentials, a Service ID can be created with an associated API key and access permissions in the form of a service policy that is assigned to the Service ID in order for you to control the level of access for any application authenticating with that ID.

For more information about the benefits of this feature and how to get started, see the [Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/cloud/blog/introducing-ibm-cloud-iam-service-ids-api-keys){: external} .

## {{site.data.keyword.Bluemix_notm}} global catalog
New as of: 27 July 2017
{: #gc}

Expanding on the last console update to manage your public regions from a single location in the console, {{site.data.keyword.Bluemix_notm}} now has a global catalog, making the process of selecting and deploying items that you select from the catalog a more streamlined process. Regardless of the region that you select in the console, you can now see all services that are available across all public regions from your catalog. Once you select a tile from the catalog, you can see which regions the service is available in, and select where you want to deploy it. For more information about the latest updates to the catalog, see [A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/cloud/blog/announcements/global-bluemix-catalog-makes-building-things-easier){: external} .

## {{site.data.keyword.Bluemix_notm}} console updates
New as of: 23 May 2017
{: #console-may17}

You can now manage your public regions from a single location through the updated {{site.data.keyword.Bluemix_notm}} console. The region selector offers you streamlined access to your resources, and other enhancements include higher availability and improved performance. For more information, check out [New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: external} .

## Identity and access management
New as of: 01 May 2017
{: #iam-may17}

With the latest updates and improvements, {{site.data.keyword.Bluemix_notm}} account owners or administrators can now use a new unified access control UI to take advantage of the following capabilities:
 * Manage users' fine-grained access to Kubernetes services and other services as they adopt the new access control features
 * Assign service policies and Cloud Foundry roles to users within their organizations

Additionally, {{site.data.keyword.Bluemix_notm}} platform users can create, delete, and list API keys associated with their user IDs. And platform users can use those API keys to authenticate when using APIs or CLIs.

Lastly, we enhanced our unified user management capability to ensure that in a linked IaaS-PaaS account, users are managed in a unified way with no need to add users separately in the SoftLayer Customer Portal or the {{site.data.keyword.Bluemix_notm}} console.

For more information, check out the [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: external}  blog post.

## Navigation design changes for {{site.data.keyword.Bluemix_notm}} docs
New as of: 13 April 2017
{: #docnavupdates}

With this navigation update, we think you'll understand how content is better organized throughout our docs, and will be able to find relevant content more efficiently. With fewer nested layers of content, you won't have to dig around to find the documentation you need to be successful with {{site.data.keyword.Bluemix_notm}}.

