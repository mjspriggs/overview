---

copyright:
  years: 2015, 2022
lastupdated: "2022-10-18"

keywords: ui, platform, console, using the console

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# Navigating the {{site.data.keyword.cloud_notm}} console
{: #ui}

The [{{site.data.keyword.cloud}} console](https://cloud.ibm.com){: external} is the user interface that you use to manage all your {{site.data.keyword.cloud_notm}} resources. You can create a free account, log in, access documentation, access the catalog, view pricing information, get support, or check the status of {{site.data.keyword.cloud_notm}} components. After you log in, the menu bar contains a **Menu** icon ![Menu icon](../icons/icon_hamburger.svg "Menu") and more links.
{: shortdesc}

## Watch a tour
{: #video-ui}

![Introducing {{site.data.keyword.cloud_notm}}](https://video.ibm.com/embed/recorded/128452443){: video output="iframe" data-script="#video-transcript-ui" id="watsonmediaplayer" width="560" height="315" scrolling="no" allowfullscreen webkitallowfullscreen mozAllowFullScreen frameborder="0" style="border: 0 none transparent;"}


### Video transcript
{: #video-transcript-ui}
{: notoc}

Welcome to {{site.data.keyword.cloud_notm}}, your open, secure, and enterprise-ready cloud platform with over 350 unique products for you to start building the solutions that you need today! Just log in, and you're ready to start building in the cloud.

From the global navigation, you can explore how to get started with key technologies in {{site.data.keyword.cloud_notm}}. Choose from technologies including serverless computing with Functions [Click Menu icon > Functions], container-based deployments on Kubernetes [Click Kubernetes to expand the options] or Red Hat OpenShift [Click OpenShift to expand the options], and VPC infrastructure [Click VPC Infrastructure to expand the options]. Developers can start with API management tools, app development starter kits, DevOps toolchains, and more to expedite and automate your app development.

You can get started creating resources through any of these guided journeys [Click Kubernetes > Clusters].

Or, if you want to explore everything that {{site.data.keyword.cloud_notm}} has to offer, go to the catalog to browse over 350 unique products [Click Catalog menu item]. Choose from our broad portfolio of managed services [Click Services], explore software products to take advantage of simplified installation [Click Software], or consult with {{site.data.keyword.cloud_notm}} experts [Click Consulting]. If you're just here to try it out, filter the catalog by products that offer Lite plans, which are free to use [Click Services, and select the Lite pricing plan option].

When you're working in {{site.data.keyword.cloud_notm}} [Click IBM Cloud menu option], check out your dashboard to get a high-level overview of your account's resources, users, support cases, compliance monitoring, and usage, with quick links out to each area. You can tailor the information that's displayed to only what you need by creating custom dashboards and adding widgets for specific resources, team notes, management tasks, and more [Click the Actions menu icon > Create dashboard > Management > Create].

For any account management tasks that you need to take care of, go to Manage > Account [Click Manage menu option > Account]. Here you can create and manage your resource groups, Cloud Foundry orgs, create tags to organize resources, manage your account settings, and more.

From the same Manage menu, you can go to Billing and usage [Click Manage menu option > Billing and usage] to view your usage, view invoices, and set spending notifications to help keep track of your costs.

Then, through the Manage > Access (IAM) option [Click Manage menu item > Access (IAM)], you can invite users to your account and manage their access to account resources including IAM-enabled, Cloud Foundry, and classic infrastructure resources.

In a connected world, security is more important than ever, and we've built it right into the platform [Click Menu icon > Security and Compliance]. With the {{site.data.keyword.cloud_notm}} Security and Compliance Center [Click Dashboard], you can set up a unified dashboard to monitor security and compliance, govern configuration, and gain insights into threats.

If you prefer to work from the command line [Click IBM Cloud Shell menu item], you can manage your {{site.data.keyword.cloud_notm}} account and resources right from your browser with {{site.data.keyword.cloud-shell_notm}}. Just open {{site.data.keyword.cloud-shell_short}} to start using the {{site.data.keyword.cloud_notm}} CLI and tons of other plug-ins, tools, and runtimes with no installation needed.

If you run into any questions as you're working in {{site.data.keyword.cloud_notm}}, visit the Support Center [Click Support menu option], where you'll find FAQs and common tasks that can help you to resolve your issue quickly without even having to contact {{site.data.keyword.cloud_notm}}. However, if you do need to get in touch with us or open a support case, those options are also available to you.

For in-depth information about how to get up and running in {{site.data.keyword.cloud_notm}}, visit the docs [Click Docs menu item > Develop tab]. Explore key topics by use case or browse through our library of tutorials that range from quick start guides to advanced solution tutorials [Click Deploy tab > Tutorials tab].

For more guidance, check out the full product docs [Click All product docs tab] or API & SDK reference libraries [Click API & SDK reference tab]. Or, browse our FAQ library to get answers to common questions about {{site.data.keyword.cloud_notm}}'s products and services [Click FAQs tab, and expand the What is Master Data Management? entry].

Now that you know how to navigate through the {{site.data.keyword.cloud_notm}} user interface to get your account set up, create resources from the catalog, and find help through support and docs, it's time get coding or building your infrastructure!


## Using the console
{: #consoleoptions}

When you log in to {{site.data.keyword.cloud_notm}}, your dashboard is displayed, which shows widgets that summarize the status of your account. If you're interested in customizing your dashboard, see [Working with scoped dashboards](/docs/account?topic=account-custom-dashboard).

You can navigate the console by using the options from the console menu bar. Use the following options to explore the console:

* Use the **Catalog** link to explore over 350 products that offer options for compute, networking, security management, end-to-end developer solutions, and more.
* Click the **Help** icon ![Help icon](../icons/help.svg "Help") > **Docs** to access the product documentation.
* Click the **Help** icon ![Help icon](../icons/help.svg "Help") > **Support center** to go to the [Support Center](https://cloud.ibm.com/unifiedsupport/supportcenter){: external} page
* From the **Manage** menu, you can access your account, billing and usage, and Identity and Access Management options.
* Click the **{{site.data.keyword.cloud-shell_notm}}** icon ![{{site.data.keyword.cloud-shell_notm}} icon](../icons/terminal-cloud-shell.svg "Cloud Shell") to open a browser-based shell environment that you can use to work with your {{site.data.keyword.cloud_notm}} resources.
* Click the **Cost estimator** icon ![Cost estimator icon](../icons/calculator.svg "Cost Estimator") to open the cost estimator.
* Click the **Notifications** icon ![Notifications icon](../icons/Notification.svg "Notifications") to view and control all incidents, maintenance, and announcements that are likely to affect your account.
* Click the **Avatar** icon ![Avatar icon](../icons/i-avatar-icon.svg "Avatar") to access your profile, guided tours, console theme options, and more.

In addition to the console, [command-line interfaces (CLIs)](/docs/cli?topic=cli-getting-started), APIs, and SDKs are available for interacting with you cloud account and resources. [Terraform](/docs/ibm-cloud-provider-for-terraform?topic=ibm-cloud-provider-for-terraform-getting-started) support is also available through use of the {{site.data.keyword.cloud_notm}} Provider plug-in for managing cloud resources at enterprise scale through templates and scripting.
