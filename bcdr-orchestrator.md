---

copyright:
  years: 2021
lastupdated: "2021-11-17"

keywords: DR management, disaster recovery management, automate disaster recovery, DR automation, resiliency orchestrator

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# {{site.data.keyword.cloud_notm}} Resiliency Orchestrator
{: #cloud-resiliency-orchestrator}

{{site.data.keyword.IBM}} Cloud Resiliency Orchestration (CRO) offers a unified disaster recovery (DR) management approach that delivers real-time DR readiness validation and automated DR testing and recovery.

The Orchestration Server enables DR monitoring, reporting, testing, and workflow automation of complex IT infrastructure and applications. Built-in automation and analytics deliver faster, more cost-effective DR to help keep daily business operations running and to proactively avoid disruptions that lead to lost revenue, brand damage, and dissatisfied customers.

{{site.data.keyword.IBM_notm}} CRO can reduce DR test times and DR failover by up to 80 percent, resulting in a more cost-effective DR experience that is smarter, tailored, and more agile than ever before. Additionally, {{site.data.keyword.IBM_notm}} CRO provides DR process orchestration functions and drives other platform and function orchestrators at different layers.

![Orchestrator functions diagram](images/BCDR-Architecture-Diagram-image14.svg "Orchestrator functions diagram"){: caption="Figure 1. Orchestrator functions diagram" caption-side="bottom"}

## How do we maintain the disaster recovery posture in {{site.data.keyword.cloud_notm}}?
{: #maintain-dr-posture}

{{site.data.keyword.IBM_notm}} CRO handles the complete lifecycle of the DR process to ensure that the recovery of the application on the cloud can be done quickly and with confidence. This lifecycle is defined by the following.

### Discovery
{: #discovery}

{{site.data.keyword.IBM_notm}} CRO interfaces with the infrastructure and applications on the source – be it on premises data center, private cloud, or public cloud, and discovers and builds the full stack of the application including its dependencies and the recovery order. It performs this discovery by directly talking to the underlying infrastructure like the hypervisors, OS, databases, storage, and more, or by ingesting the data that is already available in other configuration management databases or discovery tools. These discovered application stacks form the building blocks on which {{site.data.keyword.IBM_notm}} CRO operates.


### Provision
{: #provision}

After these application stacks are created in {{site.data.keyword.IBM_notm}} CRO, it provisions storage, network, and in certain cases the server itself, and sets up the replication with the appropriate replication interval based on the required [recovery time objective](#x3167918){: term} (RTO) and [recovery point objective](#x3429911){: term} (RPO). It has the intelligence to provision not just for a virtual machine replication DR methodology, but it can also provision servers with databases and replication, like Oracle Dataguard, for situations where an application consistent copy on the DR is needed instead of a crash consistent copy.

### Monitor
{: #monitor}

In DR steady-state, where the data is getting replicated to the DR, {{site.data.keyword.IBM_notm}} CRO constantly monitors the replication, data lag, availability of the servers and application on the production, and more, and raises alerts whenever the DR SLAs are not met, exceeded, or when the application is not available in the production. It also has the capability to perform automated responses for these alerts so that pre-defined corrective actions can be performed.

### Disaster recovery test
{: #dr-test-2}

{{site.data.keyword.IBM_notm}} CRO fully automates the DR test process including provisioning the server, attaching the volumes, bringing up the servers, configuring the network, starting the databases and applications, performing configuration changes, and more across the full stack of the application. It understands the dependencies between the various applications and the tiers of the application and orchestrates the complete process of bringing up the servers, databases, and applications based on the recovery order specified. This greatly simplifies the entire DR test process reducing the time that is taken to perform a test. This automation of the test process is built using the Recover Automation Library (RAL) and hence eliminates the development and maintenance of the scripts, which is the traditional way of achieving automation.  

### Failover  
{: #failover-2}

The same orchestration capabilities and RALs are used to automate the complete failover process to recover the applications on the DR site. Similar to the DR test scenario, {{site.data.keyword.IBM_notm}} CRO recovers the complete application stack bringing up the servers, databases, and applications in the right order based on the dependencies and recovery order of that application. Since the entire operation is automated, the recovery process is quick, reliable, and reduces the dependencies on humans.

![Failover architecture diagram](images/BCDR-Architecture-Diagram-Failover.svg "Failover"){: caption="Figure 2. An architecture diagram for failover" caption-side="bottom"}

- Replication is enabled. The Site Recovery Extension Mobility service is automatically installed on the virtual machine (VM).
- The VM is registered with Site Recovery.
- Continuous replication is configured for the VM.
- Data writes on the VM disks are continuously transferred to the cache storage account in the source location.

After continuous replication is working, disk writes are immediately transferred to the cache storage account. Site recovery processes the data and sends it to the target storage account. After the data is processed, recovery points are generated in the target storage account every few minutes.  

#### Failover process  
{: #failover-process}

When you initiate a failover, the VMs are created in the target resource group, target virtual network, target subnet, and the target availability set. During a failover, you can select to use any recovery point.

The following steps provide a simplified description of a failover event.

- A failover event is triggered on the target host. If possible, it notifies the source host.  
- The failover event is completed on the target host. This is a distinct step from the failover start with the purpose of allowing you to cancel a failover operation.  
- The replica VM is now the active copy.  
- When the primary site is recovered or rebuilt, replica is reestablished in reverse mode.
- A planned failover event makes the rebuilt replica in the primary site into the active copy again.

## The Dashboard
{: #the-dashboard}

The web-based central management dashboard provides a unified DR status that regularly monitors recovery posture by server, application, and business process, validating current DR readiness with clear business and operational advantages.

It manages all DR operations including DR tests, reporting, failover, and recovery for physical or virtual systems.

Clients can replicate data, applications, and operating systems from their production environment to a securely managed service-provider facility, where business applications can failover to a production-ready environment in the event of an outage at their primary facility.

Day-to-day DR operations covering monitoring and management are performed by {{site.data.keyword.IBM_notm}} Resiliency Services. In the event of a disruption, the client is notified based on their DR policies and provided with compliance reports in the dashboard.

## Open Adaptable Architecture
{: #open-adapatble}

{{site.data.keyword.IBM_notm}} Resiliency Orchestrator architecture is flexible and adaptable through the API extension.

![Open adaptable architecture](images/BCDR-Architecture-Open-Adaptable-Architecture.svg "Open adaptable architecture"){: caption="Figure 3. An architecture diagram for open adaptable architecture" caption-side="bottom"}

* **North-bound API** provides interfaces to integrate with existing web GUIs, monitoring systems, ticketing, and billing.
* **South-bound API** provides interfaces with technologies, platforms, or other platform and product orchestrators or managers.
* **West-bound API** interfaces local plug-ins by using command line or API and local developed RAL extension.
* **East-bound API** interfaces other reporting engines and user authentication systems.

## RALs concept
{: #rals}

Flexibility in the architecture is combined with a complete recovery stack leveraging on more than 400 plus predefined patterns for efficient implementation. These patterns, called Recovery Automation Libraries (RALs), are a set of pre-packaged, pre-defined, and verified procedures to apply to specific components of the DR solution that must be orchestrated by {{site.data.keyword.IBM_notm}} CRO.

The recovery stack operates on these different layers:

* **Application** Application environment, startup, shutdown
* **Database** RPO, Dump and Apply, Health
* **Network** Failover-DNS, NAT, NetScalar
* **OS** Health, bring up, shutdown
* **Replication/Storage** Health, data lag, start, stop, split/join
* **Cloud/Infrastructure** Create/start/stop instance, provision storage, network, security groups

{{site.data.keyword.IBM_notm}} CRO works with several platforms and technologies.

As you might find in the following table, few of the technologies reported are not supported on the public cloud space, but they are included here since {{site.data.keyword.IBM_notm}} CRO works in the hybrid space and provides a full management of a Hybrid DR solution.

| Platforms       | Applications        | Replication*                |
|---------------------|-------------------------|---------------------------------|
| Linux flavors       | WebSphere, WebLogic, IIS | NetApp SnapMirror               |
| Windows             | SAP                     | EMC SRDF, RecoverPoint          |
| AIX, HP UX          | {{site.data.keyword.IBM_notm}} MQ Server               | HP Continuous Access            |
| Solaris             | Oracle                  | {{site.data.keyword.IBM_notm}} Global Mirror, SVC          |
| Oracle Exadata      | MS SQL Server           | Hitachi TrueCopy/UR             |
| FlexPod             | {{site.data.keyword.IBM_notm}} Db2                 | Oracle Dataguard                |
| VMware              | PostgreSQL              | SQL Mirroring and Log Shipping, |
| Amazon Web Services | MySQL                   | Zerto Virtual Replicator        |
| Mainframes          | MS Exchange             |                                 |
| AS 400              |                         |                                 |
{: caption="Table 1. Platform and technologies that work with {{site.data.keyword.IBM_notm}} CRO" caption-side="top"}

### Why should you use it?
{: #why-use}

Tightening {{site.data.keyword.IBM_notm}} CRO technology into the DR design and recovery procedures provides a single point of control and management among all the different class of services, technologies, and hybrid-implementations.

Benefits of {{site.data.keyword.IBM_notm}} CRO include, but are not limited to the following:

Automation
:   Maximum automation of the recovery runbooks, replacing manual actions with predeveloped, and pretested software commands

DR readiness
:    Automated recovery workflows are designed to be active and always on standby, enabling fast reaction to outages and the simplicity of "push button" recovery activation.

Recovery speed
:   The recovery process is run at software speed following predesigned, pretested, frequently exercised recovery workflows that are designed to maximize automation and minimize human reliance.

Confidence
:   {{site.data.keyword.IBM_notm}} CRO helps in keeping the recovery runbooks in-sync with the changes in the production's environment and detects errors and misalignment early, so they can be caught and remedied in low-stress test activities rather than real high-stress outages.

Reporting
:   Business line owners and application owners can have detailed understanding of the recovery design points and DR readiness of their specific areas of interest. These details are captured and stored in {{site.data.keyword.IBM_notm}} CRO's own database for ease of report generation, whether ad hoc or on a schedule.

Visibility
:   {{site.data.keyword.IBM_notm}} CRO recovery workflows run live in the regulatory environment 24 x 7, constantly monitoring the status of recovery resources and report the RTO and RPO for applications that make use of these underlying resources for recovery. The regulatory DR posture therefore is reported in real-time, not as of the last DR exercise.
