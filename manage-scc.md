---
copyright:
  years: 2020, 2021
lastupdated: "2021-06-21"

keywords: security and compliance for the platform, security for IBM Cloud, compliance for IBM Cloud, goals, config rules, rules, posture

subcollection: overview

---

{:external: target="_blank" .external}
{:note: .note}
{:term: .term}
{:shortdesc: .shortdesc}
{:table: .aria-labeledby="caption"}


# Managing security and compliance in {{site.data.keyword.cloud_notm}}
{: #manage-security-compliance}

With the {{site.data.keyword.compliance_short}}, you can manage the security and compliance of the {{site.data.keyword.cloud}} platform.
{: shortdesc}

In the {{site.data.keyword.compliance_short}}, you can accomplish the following tasks:

* Monitor for controls and goals that pertain to platform services.
* Define rules that can help to standardize resource configuration.

## Monitoring security and compliance posture
{: #monitor-platform}

As a security or compliance focal, you can use [goals](#x2117978){: term} of specific platform services to help ensure that your organization is adhering to the external and internal standards for your industry. By using the {{site.data.keyword.compliance_short}} to validate the resource configurations in your account against a [profile](#x2034950){: term}, you can identify potential issues as they arise.

All of the goals for the platform are added to the {{site.data.keyword.cloud_notm}} Best Practices Controls 1.0 profile but can also be mapped to other profiles.
{: note}

To start monitoring your resources, see [Getting started with {{site.data.keyword.compliance_short}}](/docs/security-compliance?topic-security-compliance-getting-started).

### Available goals for platform services
{: #platform-available-goals}


#### Billing
{: #billing-goals}

* Check whether the EU supported setting is enabled in account settings
* Check whether the HIPAA supported setting is enabled in account settings

#### Identity and Access Management
{: #iam-goals}

* Check whether multifactor authentication (MFA) is enabled for each user at the user level
* Check whether multifactor authentication (MFA) is enabled at the account level
* Check whether multifactor authentication (MFA) is enabled for the account owner
* Check whether account has a contact email defined
* Check whether account has a contact phone number defined
* Check whether IAM users and service IDs are attached to access groups
* Check whether account access is managed only by IAM access groups
* Check whether IAM policies for service IDs are attached only to groups or roles
* Check whether IAM policies for users are attached only to groups or roles
* Check whether security questions are registered by the account owner
* Check whether authorized IP ranges are configured by the account owner
* Check whether there are no more than # IAM administrators configured per account
* Check whether the account owner does not have an IBM Cloud API key created in IAM
* Check whether an account owner has logged in to IBM Cloud in the past # days
* Check whether IBM Cloud API keys that are managed in IAM are rotated at least every # days
* Check whether user list visibility restrictions are configured in IAM settings for the account owner
* Check whether permissions for API key creation are limited and configured in IAM settings for the account owner
* Check whether permissions for service ID creation are limited and configured in IAM settings for the account owner
* Check whether account has no more than # service IDs with admin privileges
* Check whether IAM-enabled services have at least # service IDs with the IAM manager role
* Check whether IAM-enabled services have no more than # service IDs with the IAM administrator role
* Check whether IAM-enabled services have no more than # users with the IAM administrator role



## Governing resource configuration for platform services
{: #govern-platform}

As a security or compliance focal, you can use the {{site.data.keyword.compliance_short}} to define configuration rules for the platform services that you're working with in {{site.data.keyword.cloud_notm}}. 

[Config rules](#x3084914){: term} are used to enforce the configuration standards that you want to implement across your accounts. For more details about the data that you can use to create a rule, review the following table.

| Platform service | Resource kind | Property | Operator type |  Description |
|---------------|---------------|----------|---------------|-------------|
| Billing | `account-trait` | `eu_supported` | Boolean |  Indicates whether the account has the `eu_supported` flag enabled. |
| Billing | `account-trait` | `hipaa_accepted` | Boolean |  Indicates whether the account has the `hipaa_accepted` flag enabled. |
| Catalog Management | `account-settings` | `allow_ibm_provider_only` | Boolean |  Indicates whether users are restricted to installing only software provided by {{site.data.keyword.IBM_notm}} from the {{site.data.keyword.cloud_notm}} catalog. Set catalog management filters to comply with this rule. This rule cannot be combined with other provider rules. |
| Catalog Management | `account-settings` | `allow_ibm_provider` | Boolean |  Indicates whether users can install software provided by {{site.data.keyword.IBM_notm}} software from the {{site.data.keyword.cloud_notm}} catalog. Set catalog management filters to comply with this rule. |
| Catalog Management | `account-settings` | `allow_community_provider` | Boolean |  Indicates whether users can install community-provided software from the {{site.data.keyword.cloud_notm}} catalog.  Set catalog management filters to comply with this rule. |
| Catalog Management | `account-settings` | `allow_thirdparty_provider` | Boolean |  Indicates whether users can install third-party software from the {{site.data.keyword.cloud_notm}} catalog. Set catalog management filters to comply with this rule. |
| IAM Access Groups Service | `service` | `public_access_enabled` | Boolean | A boolean indicating whether the public access feature is enabled. |
| IAM Identity Service | `accountsettings` | `restrict_create_service_id` | String | Indicates whether the restriction on service ID creation is enabled. Value options include `RESTRICTED` and `NOT_RESTRICTED`. |
| IAM Identity Service | `accountsettings` | `restrict_create_platform_apikey` | String | Indicates whether the restriction on platform API key creation is enabled. Value options include `RESTRICTED` and `NOT_RESTRICTED`. |
| IAM Identity Service | `accountsettings` | `mfa` | String | Indicates the level of MFA that is required. Value options include `NONE`, `TOTP`, `TOTP4ALL`, `LEVEL1`, `LEVEL2`, and `LEVEL3`. |
{: caption="Table 1. Rule properties for platform services" caption-side="top"}

See [What is a config rule?](/docs/security-compliance?topic=security-compliance-what-is-rule) for more information. 
