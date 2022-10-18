---

copyright:
  years: 2016, 2022
lastupdated: "2022-10-18"

keywords: glossary, IBM Cloud glossary, terms, definitions

subcollection: overview

---

{:shortdesc: .shortdesc}
{:external: target="_blank" .external}

# Glossary terms for {{site.data.keyword.cloud_notm}}
{: #glossary}

This glossary provides terms and definitions for {{site.data.keyword.cloud}}.
{: shortdesc}

The following cross-references are used in this glossary:

- *See* refers you from a nonpreferred term to the preferred term or from an abbreviation to the spelled-out form.
- *See also* refers you to a related or contrasting term.

## A
{: #glossa}

### access control list
{: #x2012793}

A list that statelessly manages inbound and outbound traffic for a subnet through the use of rules. An access control list helps provide security at the subnet level.

### access group
{: #x2160811}

A set of users and service IDs organized into a group that is used as the subject of an access policy for assigning all group members the same access.

### access policy
{: #x2853407}

A method for granting users, service IDs, and access groups access to account resources. An access policy includes a subject, target, and role.

### access token
{: #x2113001}

A value used by the consumer to gain access to the protected resources on behalf of the user, instead of using the user's service provider credentials.

### account
{: #x2012863}

A unit within the representation of an organizational structure. It can include resources, such as servers, access controls, and configurations. See also [enterprise account](#x9863395).

### account group
{: #x8622525}

An organizational unit for accounts within an enterprise. An account group can contain accounts or other account groups. See also [enterprise](#x2026915).

### accuracy
{: #x3125742}

A measure of the correctness of the decisions and predictions that are made by machine learning models, which are often part of AI systems. See also [precision](#x2003831), [recall](#x2154357).

### accuracy analysis
{: #x7881108}

Analyzing machine learning model scores to determine whether changes are needed to improve accuracy.

### action
{: #x2012974}

- A task that is performed in the context of a service.
- A code snippet that can be explicitly invoked, or run in response to an event. See also [feed](#x3129185), [invoke](#x2057232).

### adjudication
{: #x3096333}

An iterative process for resolving annotation conflicts by comparing the annotations added to the same document by different human annotators.

### affinity
{: #x2149238}

Two or more container group instances running on the same network node. See also [anti-affinity](#x8888040).

### allowlist
{: #x3954001}

A list of items, such as usernames, email addresses, or IP addresses, that are granted access to a certain system or function. When an allowlist is used for access control, all entities are denied access, except for those that are included in the allowlist. See also [blocklist](#x3954055).

### analysis engine
{: #x3461204}

A program that analyzes artifacts, such as documents, and infers information about them, and which implements the UIMA Analysis Engine interface specification. Analysis engines are constructed from building blocks called annotators. An analysis engine can contain a single annotator, which is referred to as a primitive analysis engine, or multiple annotators, which is referred to as an aggregate analysis engine.

### annotation
{: #x2013712}

Information about a span of text. For example, an annotation might indicate that a span of text represents a company name.

### annotation process manager
{: #x9825807}

A role that is responsible for managing the full annotation lifecycle activities within a workspace. The project manager that is added to a workspace typically performs the activities of an annotation process manager.

### annotation set
{: #x9504010}

- In human annotation, a collection of documents that are extracted from the corpus that allow the workload to be shared by multiple human annotators.
- In machine-based annotation, a collection of documents that can be used as blind data, training data, or test data.

### anti-affinity
{: #x8888040}

Two or more container group instances that run on different network nodes to ensure higher availability for an app. See also [affinity](#x2149238).

### API
{: #x2008805}

See [application programming interface](#x2000186).

### API key
{: #x8051010}

A unique code that is passed to an API to identify the calling application or user. An API key is used to track and control how the API is being used, for example, to prevent malicious use or abuse of the API.

### API operation
{: #x9826953}

A unit of a REST API that can be invoked. An API operation comprises an HTTP verb and a URL path that is subordinate to the context root of the API.

### API resource
{: #x7103848}

A unit of a REST API that can be invoked. An API resource comprises an HTTP verb and a unique URL path that is subordinate to the context root of the API.

### app
{: #x4281528}

A web or mobile device application. See also [mobile application](#x4258535), [web application](#x2116500).

### application programming interface (API)
{: #x2000186}

An interface that allows an application program that is written in a high-level language to use specific data or functions of the operating system or another program.

### artifact
{: #x2262995}

An entity that is used or produced by a software or systems development process. Examples of artifacts include designs, requirements, source files, plans, scripts, simulations, models, test plans, and binary executable files. In an HTTP context, artifacts have a URI and are called resources.

### assembly
{: #x2260813}

An application programming interface that provides rich functionality for interacting with an application. The assembly  makes side calls to external services and then transforms and aggregates the response before a response is relayed to the calling application.

### asset
{: #x2172042}

Tangible or intangible goods, services, or property represented as an entity that is traded on a blockchain network.

### attribute
{: #x2000252}

A characteristic or trait of an entity that describes the entity; for example, the telephone number of an employee is one of the employee attributes.

### authentication (AuthN)
{: #x2014567}

The process of validating the identity of a user or server.

### AuthN
{: #x7470446}

See [authentication](#x2014567).

### authorization (AuthZ)
{: #x2014653}

In computer security, the right granted to a user to communicate with or make use of a computer system.

### AuthZ
{: #x7470448}

See [authorization](#x2014653).

### availability zone
{: #x7018171}

A location within a region that IBM Cloud Kubernetes Service runs in.


## B
{: #glossb}

### bare metal server
{: #x6778472}

A dedicated, fully-customizable physical server that can be used for virtualization or web hosting.

### base image
{: #x5366487}

An image that has no parent image. See also [image](#x2024928), [parent image](#x8439210).

### beta product
{: #x10127356}

A product that IBM makes available solely for evaluation and testing purposes. There are no warranties, SLAs or support provided and beta products are not intended for production use.

### bias detection
{: #x9721361}

The process of calculating fairness to metrics to detect when AI models are delivering unfair outcomes based on certain attributes.

### billing option
{: #x6526863}

The method by which a client is billed for cloud service usage. Examples include paying in advance, such as with subscriptions, and payment in arrears, as in Pay-As-You-Go accounts.

### billing unit
{: #x9308099}

The highest level billing entity within an enterprise. Each account or account group is linked to a billing unit, which manages all associated contracts, invoices, orders, and payments. A billing unit can contain one or more credit pools. See also [credit pool](#x9796950), [enterprise](#x2026915).

### bind
{: #x2000361}

To establish a connection between software components on a network using an agreed-to protocol. In web services, the bind operation occurs when the service requester invokes or initiates an interaction with the service at run time using the binding details in the service description to locate, contact, and invoke the service.

### blind data
{: #x7881128}

A set of documents annotated with the ground truth, such as question and answer pairs, semantic annotation, and passage judgment. Blind data is never released or seen by developers and is used to test the system periodically to evaluate performance on unseen data. See also [testing data](#x7736833), [training data](#x2860199).

### block
{: #x2000384}

A unit that contains ordered transactions in a blockchain network. Blocks are immutable and contain the cryptographic hash of the previous block to create a chain of blocks. This iterative process confirms the integrity of the previous block, all the way back to the initial block. See also [genesis block](#x9076628).

### blocklist
{: #x3954055}

A list of items, such as usernames, email addresses, or IP addresses, that are denied access to a certain system or function. When a blocklist is used for access control, all entities are allowed access, except for those that are included in the blocklist. See also [allowlist](#x3954001).

### BLU Acceleration
{: #x7470463}

A collection of IBM Db2 technologies designed to work primarily with read-mostly business intelligence query processing. BLU Acceleration consists of four major database design advances: dynamic in-memory columnar processing, actionable compression, parallel vector processing, and data skipping.

### blue-green deployment
{: #x7807335}

A deployment technique that enables continuous delivery and minimizes downtime by running two nearly identical production environments called Blue and Green. While one of the environments (for example, Blue) is the live production environment, the other (for example, Green) can be used for final testing and deployment. After the application is deployed in Green, Green becomes the production environment and Blue becomes idle. See also [red-black deployment](#x8439181).

### boilerplate
{: #x7233930}

A template that includes one application and its associated runtime environment and predefined services for a particular domain.

### borderless
{: #x8439189}

Pertaining to an open, non-proprietary development platform that includes public cloud, dedicated cloud, and local cloud deployment models. See also [dedicated cloud](#x8439199), [local cloud](#x8439194), [public cloud](#x4585370).

### bucket
{: #x2072079}

A container for storing unstructured data.

### buildpack
{: #x7233925}

A collection of scripts that provide framework and runtime support for apps.

### business continuity
{: #x3026801}

The capability of a business to withstand outages and to operate mission-critical services normally and without interruption in accordance with predefined service-level agreements.


## C
{: #glossc}

### CA
{: #x2015942}

See [certificate authority](#x2016383).

### certificate authority (CA)
{: #x2016383}

A trusted third-party organization or company that issues the digital certificates. The certificate authority typically verifies the identity of the individuals who are granted the unique certificate. See also [intermediate certificate](#x3753781), [Secure Sockets Layer](#x2038004), [trusted root](#x2042234).

### certificate signing request (CSR)
{: #x3530521}

An electronic message that an organization sends to a certificate authority (CA) to obtain a certificate. The request includes a public key and is signed with a private key; the CA returns the certificate after signing with its own private key.

### chaincode
{: #x9829545}

Executable code that contains business logic agreed to by a set of organizations on a channel. A chaincode, and the smart contracts it contains, is installed on peers, instantiated on a channel, and governs access to the ledger data that is generated through invocations of the chaincode. See also [transaction](#x2005321).

### channel
{: #x2016483}

A private subset of a larger  blockchain network with specific rules and a separate ledger that only channel members can access.

### CLI
{: #x2008863}

See [command-line interface](#x2051424).

### client
{: #x2000644}

- An entity that acts on behalf of a user by connecting to a peer to communicate with the blockchain.
- A software program or computer that requests services from a server. See also [host](#x2002243).

### client secret
{: #x7024948}

A piece of information that is used with an application key to verify the identity of an application. An API can be configured to require that client applications supply their application secret with their application key. The application secret functions effectively as a password known only to the application. The application secret is passed by the client using an HTTP query parameter.

### cloud computing
{: #x3877850}

A computing platform where users can have access to applications or computing resources, as services, from anywhere through their connected devices. A simplified user interface or application programming interface (API), or both, makes the infrastructure supporting such services transparent to users.

### cloud portability
{: #x4585297}

The ability to move applications and services across public or private cloud computing environments, or from different cloud providers.

### cloud provider
{: #x4585302}

An organization that provides cloud computing resources.

### cloud resource name (CRN)
{: #x9494304}

A globally unique identifier for a specific cloud resource. The value is segmented hierarchically by version, instance, type, location, and scope, separated by colons.

### command-line interface (CLI)
{: #x2051424}

A computer interface in which the input and output are text based.

### community
{: #x3103004}

A collection of consumer organizations. It is used as a grouping construct when publishing APIs. Communities are used to restrict the visibility and accessibility of APIs.

### component
{: #x2017871}

In source control management, a grouping of related artifacts in a stream or repository workspace. A component can contain any number of folders and files.

### compute
{: #x3723424}

Infrastructure or resources that serve as the basis for building apps in the cloud.

### config rule
{: #x9963852}

See [configuration rule](#x3084914).

### configuration rule (config rule)
{: #x3084914}

A JSON document that defines the configuration of resources and validates the compliance based on security requirements when a resource is created or modified.

### confusion matrix
{: #x2916277}

A table that provides a detailed numeric breakdown of annotated document sets. The table is used to compare the annotations that were added by a machine learning model to the annotations in the ground truth. The table reports the number of false positives, false negatives, true positives, and true negatives.

### connection
{: #x2000863}

In data communication, an association established between entities for conveying information.

### consensus
{: #x8888385}

The process of participants in a blockchain agreeing to a transaction and validating it through the peer network. Consensus ensures that shared ledgers are exact copies, and lowers the risk of fraudulent transactions since tampering would have to occur across many places at the exact same time.

### consumer
{: #x2263174}

A member in a blockchain network that uses the network to invoke transactions against the distributed ledger.

### container
{: #x2010901}

A system construct that allows users to simultaneously run separate logical operating system instances. Containers use layers of file systems to minimize image sizes and promote reuse. See also [image](#x2024928), [layer](#x2028320), [registry](#x2064940).

### context
{: #x2018372}

Environmental or conditional information that can be used to define when rules that restrict access to resources should be applied. A context can be a set of properties or attributes like client IP addresses, office hours, time of day, or multi-factor authentication.

### context-based restriction
{: #x10127184}

An access management method that defines and enforces access for resources based on the network location of the access request.

### control
{: #x2018434}

A technical, administrative, or physical safeguard designed to meet a set of defined security and privacy requirements. Controls exist to prevent, detect, or lessen the ability of a threat to exploit a vulnerability.

### coreference
{: #x9440294}

A relationship between two words or phrases in which both refer to the same person or thing and one stands as a linguistic antecedent of the other. For example, there is a coreference between the two pronouns in the phrase "She taught herself" but not in the phrase "She taught her". A coreference links two equivalent entities in the same text.

### coreference chain
{: #x9504031}

A list of entities that were annotated as coreferences. When a mention is annotated as a coreference, the system creates a coreference chain.  The coreference chain provides a way to view all of the mentions in context and verify that all of the occurrences belong together under the same entity type.

### corpus
{: #x3954167}

A collection of source documents that are used to train a machine learning model.

### credential
{: #x2018813}

Information acquired during authentication that describes a user, group associations, or other security-related identity attributes, and that is used to perform services such as authorization, auditing, or delegation. For example, a user ID and password are credentials that allow access to network and system resources.

### credit pool
{: #x9796950}

Within an enterprise billing unit, a consolidation of credit from all sources, including subscriptions and promotions, that is shared among accounts. See also [billing unit](#x9308099).

### CRN
{: #x10111475}

See [cloud resource name](#x9494304).

### crypto unit
{: #x9860404}

A single unit that represents a hardware security module and the corresponding software stack that is dedicated to the hardware security module for cryptography.

### CSR
{: #x2140147}

See [certificate signing request](#x3530521).

### curate
{: #x7883684}

To select, collect, preserve, and maintain content relevant to a specific topic. Curation establishes, maintains, and adds value to data; it transforms data into trusted information and knowledge.

### custom domain
{: #x5728384}

The customized portion of the URL selected by the user to direct requests to the application. A custom domain makes up part of the route. A custom domain can be a shared domain, a shared subdomain, or a shared domain and host. See also [domain](#x2021210), [host](#x2002243), [route](#x2037338), [subdomain](#x2040080), [Uniform Resource Locator](#x2042491).


## D
{: #glossd}

### daemon
{: #x2019215}

A program that runs unattended to perform continuous or periodic functions, such as network control.

### dashboard
{: #x2363941}

A user interface component that provides a comprehensive summary of pertinent information from various sources to the user.

### data center (DC)
{: #x2439906}

The physical location of the servers that provide cloud services.

### data encryption key
{: #x4791827}

A cryptographic key used to encrypt data that is stored in an application.

### data store
{: #x2052849}

A place, such as a database system, file, or directory, where data is stored.

### DC
{: #x2052913}

See [data center](#x2439906).

### DEA
{: #x2019805}

See [Droplet Execution Agent](#x7470348).

### dedicated cloud
{: #x8439199}

A private cloud computing environment that provides infrastructure with single-tenant hardware. See also [borderless](#x8439189).

### deployment
{: #x2104544}

A process that retrieves the output of a build, packages the output with configuration properties, and installs the package in a pre-defined location so that it can be tested or run. See also [stage](#x2067189).

### DevOps
{: #x5784896}

A software methodology that integrates application development and IT operations so that teams can deliver code faster to production and iterate continuously based on market feedback.

### DevSecOps
{: #x9892260}

A methodology that integrates security practices with the software development and operations lifecycle. The goal of the merge is to prioritize the balance of development speed and security.

### dictionary
{: #x2001532}

A collection of words that can be used to pre-annotate documents. A new annotation is created for each word in the document text that matches a term in the dictionary. A machine learning model can be configured with one or more independent dictionaries, which are typically domain-specific, such a dictionary for pharmaceuticals and a dictionary for wealth management. See also [lemma](#x2763345), [surface form](#x3271760).

### dictionary pre-annotator
{: #x9825820}

A component that identifies mentions in text that match a specific set of words. By using domain-specific terminology to pre-annotate text, dictionary pre-annotators can accelerate a human annotator's ability to prepare a set of ground truth documents.

### disaster recovery (DR)
{: #x2113280}

The ability of IT services to recover from rare but major incidents and non-transient, wide-scale failures, such as service disruption that affects an entire geographical area. The impact of such an incident exceeds the ability of the high availability design to handle it. See also high availability, recovery time objective, recovery point objective. See also [high availability](#x2284708), [recovery point objective](#x3429911), [recovery time objective](#x3167918).

### Dockerfile
{: #x9860414}

A text file that contains instructions to build a Docker image.

### document set
{: #x9825825}

A collection of documents. Documents that are imported together become a document set. Annotated documents that are grouped together for training purposes are generated as document sets.

### domain
{: #x2021210}

Part of a naming hierarchy that specifies the route. For example, example.com. In IBM Cloud, domains are associated with orgs. Domain objects are not directly bound to apps. See also [custom domain](#x5728384), [host](#x2002243), [organization](#x2032585), [route](#x2037338), [subdomain](#x2040080), [Uniform Resource Locator](#x2042491).

### DR
{: #x2021360}

See [disaster recovery](#x2113280).

### droplet
{: #x7470343}

An archive within Cloud Foundry that contains an application and its runtime and framework dependencies, prior to deployment to the cloud.

### Droplet Execution Agent (DEA)
{: #x7470348}

The Cloud Foundry component that is responsible for deploying applications.

### dynamic secret
{: #x9968958}

A unique value, such as a password or an API key, that is created dynamically and leased to an application that requires access to a protected resource. After a dynamic secret reaches the end of its lease, access to the protected resource is revoked and the secret is deleted automatically. See also [secret](#x2789492), [secrets engine](#x9968967).


## E
{: #glosse}

### endorse
{: #x2455719}

To validate a chaincode transaction that was made by another member of a blockchain network.

### endorsement
{: #x3450292}

A collection of digital signatures from endorsing peers that establish that a transaction satisfies an endorsement policy.

### endorsement policy
{: #x8911635}

A policy that defines the peer nodes on a channel that must execute transactions that are attached to a specific chaincode application, and the required combination of endorsements. For example, a policy could require that a transaction be endorsed by a minimum number of endorsing peers, a minimum percentage of endorsing peers, or by all endorsing peers that are assigned to a specific chaincode application.

### endpoint
{: #x2026820}

The address of an API or service in an environment. An API exposes an endpoint and at the same time invokes the endpoints of other services. See also [route](#x2037338).

### enterprise
{: #x2026915}

A hierarchical structure of accounts with centralized account and billing management in a cloud environment. See also [account group](#x8622525), [billing unit](#x9308099).

### enterprise account
{: #x9863395}

A unique account within an enterprise that manages users and access for account organization and enterprise billing. See also [account](#x2012863).

### entitlement
{: #x2213075}

In software licensing, the maximum allowed allocation of capacity as determined by a license agreement.

### entity
{: #x2026945}

- A person, object, or concept about which information is stored.
- A mention that is annotated by an entity type.
- A set of details that are held about a real-world object such as a person, location, or bank account. An entity is a kind of item.

### entity type
{: #x2760649}

The type of entity that a mention represents without consideration for context. For example, the mention IBM might be annotated by the entity type ORGANIZATION. In an entity-relationship model, an entity type is the thing that is being modeled or the thing that a mention refers to, such as the name of a person or place. Different entity types have different sets of attributes such as "surname" or "home town", and are connected through relationships like "lives in". An entity type exists independently and can be uniquely identified.

### envelope encryption
{: #x9860393}

The process of encrypting data with a data encryption key and then encrypting the key with a root key that can be fully managed.

### evidence
{: #x5633626}

The collected raw data to support an assessment for auditing purposes.

### experimental product
{: #x10127361}

A product that IBM makes available solely for evaluation and testing purposes, and might be unstable or not compatible with previous versions. An experimental product can be discontinued with short notice. There are no warranties, SLAs or support provided, and experimental products are not intended for production use.

### explainability
{: #x9758663}

The ability of human users to trace, audit, and understand predictions that are made in applications that use AI systems.


## F
{: #glossf}

### F1 score
{: #x9825839}

A measure of a test's accuracy that considers both precision and recall to compute the score. The F1 score can be interpreted as a weighted average of the precision and recall values. An F1 score reaches its best value at 1 and worst value at 0.

### false negative
{: #x2208339}

An answer or annotation that is correct, but was predicted to be incorrect.

### false positive
{: #x8979862}

An answer or annotation that is incorrect, but was predicted to be correct.

### feature
{: #x2022596}

A data member or attribute of a type.

### feature code
{: #x2210744}

A code that is applied to free accounts to unlock extra product resources and capabilities.

### Federal Risk and Authorization Management Program (FedRAMP)
{: #x10109081}

A United States government program that provides a standardized, risk-based approach for the adoption and use of cloud services by the US federal government. FedRAMP empowers agencies to use modern cloud technologies with an emphasis on security and protection of federal information, and helps accelerate the adoption of secure cloud solutions.

### federate
{: #x2763229}

To merge two or more entities. For example, a company's registered domain could be federated with an IBMid.

### FedRAMP
{: #x10109085}

See [Federal Risk and Authorization Management Program](#x10109081).

### feed
{: #x3129185}

A piece of code that configures an external event source to fire trigger events. See also [action](#x2012974).

### file share
{: #x2022902}

In the IBM Cloud environment, a persistent storage system where users store and share files. In IBM Cloud Kubernetes Service, users can mount Docker volumes on file shares.

### fire
{: #x2239904}

To activate a trigger.

### Fleiss Kappa score
{: #x9825844}

A measure of how consistently the same annotation was applied by multiple human annotators across overlapping documents. The Fleiss Kappa score reaches its best value at 1 and worst value at 0.

### floating IP address
{: #x6326428}

A public, routable IP address that makes use of 1-to-1 network address translation (NAT) so that a server can communicate with the public internet and private subnet within a cloud environment. Floating IP addresses are associated to an instance, for example, a virtual server instance, a load balancer, or a VPN gateway, by means of a virtual network interface card (vNIC).

### framework
{: #x2023472}

An architecture for an application that provides a standard structure for an application, and general, extensible functionality.  A framework enables and simplifies consistent implementation of complex technologies for application development.

### functional identifier
{: #x5951030}

An ID created through a federated identity provider that represents a program, application, or service that is assigned the minimum level of access required to complete the function for which it is created.


## G
{: #glossg}

### GA
{: #x2117930}

See [general availability](#x2117947).

### GB-hour
{: #x7470477}

The cumulative amount of memory (in gigabytes) that is running for all application instances for a particular buildpack per hour.

### general availability (GA)
{: #x2117947}

Date when a product is widely available for sale and delivery to customers or channels, usually across multiple geographies.

### genesis block
{: #x9076628}

The configuration block that initializes a blockchain network or channel, and also serves as the first block on a chain. See also [block](#x2000384).

### globally unique identifier (GUID)
{: #x2390455}

An algorithmically determined number that uniquely identifies an entity within a system.

### goal
{: #x2117978}

The verification of the way in which a control is met through hardware, software, or a service; or by a policy, process, procedure, or compliance artifact.

### gossip
{: #x9825999}


A method of sharing network information among peers in which each peer forwards messages to a random selection of the current peers in the network.

### Gossip Data Dissemination Protocol
{: #x9829550}

A protocol for secure, reliable, and scalable communication of information in an network by passing messages among peers.

### ground truth
{: #x7736823}

The set of vetted data, consisting of annotations added by human annotators, that is used to adapt a machine learning model to a particular domain. Ground truth is used to train machine learning models, measure model performance (precision and recall), and calculate headroom to decide where to focus development efforts for improving performance. Accuracy of ground truth is essential since inaccuracies in the ground truth will correlate to inaccuracies in the components that use it.

### GUID
{: #x2390457}

See [globally unique identifier](#x2390455).


## H
{: #glossh}

### HA
{: #x2404289}

See [high availability](#x2284708).

### hardware security module (HSM)
{: #x6704988}

A physical appliance that provides on-demand encryption, key management, and key storage as a managed service.

### hardware virtual machine mode (HVM)
{: #x9736811}

Hardware-assisted full virtualization. A virtual machine uses resources from the host computer to operate as a complete hardware environment. The host operating system is unaware of the virtual client.

### Hash-Based Message Authentication Code (HMAC)
{: #x6652268}

A cryptographic code that uses a cryptic hash function and a secret key.

### headroom analysis
{: #x7881218}

The process of determining how much improvement in accuracy, precision, or recall can be expected by addressing some class of problems that are identified while performing accuracy analysis.

### health check
{: #x4571658}

A process that monitors system resources and conditions to determine whether the system is running efficiently. The health check can be configured to report potential problems and to display warnings and fail levels before the integrity of the system is compromised.

### heavy API call
{: #x7690468}

A client operation that writes, deletes, or inserts data. Heavy API calls consume more resources than light API calls because they are affecting the data. See also [light API call](#x7690463).

### high availability (HA)
{: #x2284708}

The ability of IT services to withstand all outages and continue providing processing capability according to some predefined service level. Covered outages include both planned events, such as maintenance and backups, and unplanned events, such as software failures, hardware failures, power failures, and disasters. See also [disaster recovery](#x2113280).

### HMAC
{: #x3560783}

See [Hash-Based Message Authentication Code](#x6652268).

### host
{: #x2002243}

A computer that is connected to a network and that provides an access point to that network. The host can be a client, a server, or both a client and server simultaneously. See also [client](#x2000644), [custom domain](#x5728384), [domain](#x2021210), [route](#x2037338), [subdomain](#x2040080), [Uniform Resource Locator](#x2042491).

### HSM
{: #x2009137}

See [hardware security module](#x6704988).

### HTTP method
{: #x2024674}

An action that is used by the Hypertext Transfer Protocol. HTTP methods include GET, POST, and PUT.

### HTTPS
{: #x2193603}

See [Hypertext Transfer Protocol Secure](#x2237225).

### human annotator
{: #x9504052}

A subject matter expert who reviews, modifies, and augments the results of pre-annotation by identifying mentions, entity type relationships, and mention coreferences. By examining text in context, a human annotator helps determine ground truth and improve the accuracy of the machine learning model.

### HVM
{: #x9736815}

See [hardware virtual machine mode](#x9736811).

### hybrid cloud
{: #x4585327}

A cloud computing environment that consists of multiple public and private resources.

### Hyperledger fabric
{: #x8889858}

The implementation of the Linux Hyperledger project. See also [Linux Hyperledger project](#x8888396).

### Hypertext Transfer Protocol Secure (HTTPS)
{: #x2237225}

An Internet protocol that is used by web servers and web browsers to transfer and display hypermedia documents securely across the Internet.


## I
{: #glossi}

### IaaS
{: #x4585337}

See [infrastructure as a service](#x4585332).

### IAM
{: #x2193801}

See [identity and access management](#x7547040).

### IBM Cloud
{: #x7301758}

An open-standards, cloud-based platform for building, managing, and running apps of all types, such as web, mobile, big data, and smart devices. Capabilities include Java, mobile back-end development, and application monitoring, as well as features from ecosystem partners and open source&mdash;all provided as-a-service in the cloud.

### identity and access management (IAM)
{: #x7547040}

The process of controlling access of authorized users to data and applications,  while helping companies comply with various regulatory requirements.

### identity provider (IdP)
{: #x2714740}

A service that creates, maintains, and manages identity information, account authentication and credential management services for one or more systems. For example, a user registry for one or more hosts; or a built-in user registry for an application.

### IdP
{: #x7027913}

See [identity provider](#x2714740).

### image
{: #x2024928}

A file system and its execution parameters that are used within a container runtime to create a container. The file system consists of a series of layers, combined at runtime, that are created as the image is built by successive updates. The image does not retain state as the container executes. See also [base image](#x5366487), [container](#x2010901), [layer](#x2028320), [namespace](#x2031005), [parent image](#x8439210), [private image repository](#x8439215), [registry](#x2064940).

### imprint mode
{: #x9860399}

An operational mode in which crypto units are assigned to a user.

### infrastructure as a service (IaaS)
{: #x4585332}

The delivery of a computer infrastructure, including server functionality, networking functionality, data center functionality, and storage functionality as an outsourced service.

### input/output operations per second (IOPS)
{: #x3858854}

A standard computing benchmark used to determine the best configuration settings for servers.

### instance
{: #x2002531}

An entity that consists of resources that are reserved for a particular application or a service.

### instantiate
{: #x2056692}

The process of starting and initializing a smart contract on a blockchain channel. After instantiation, peers on the channel that have the smart contract installed can accept smart contract invocations.

### inter-annotator agreement
{: #x9721455}

A measure of how similarly a document in two or more document sets is annotated.

### intermediate certificate
{: #x3753781}

A subordinate certificate that is issued by the trusted root certificate authority (CA) specifically to issue end-entity server certificates. The result is a certificate chain that begins at the trusted root CA, passes through the intermediate certificate, and ends with the SSL certificate issued to the organization. See also [certificate authority](#x2016383), [trusted root](#x2042234).

### Internet of Things (IoT)
{: #x6714341}

The global network of endpoints that can capture or generate data. For example, a smartphone, smart watch and back-end server might all communicate with each other, sending data back and forth, or even to additional devices within the network.

### Internet Small Computer System Interface (iSCSI)
{: #x2119615}

An IP-based standard for linking data storage devices over a network and transferring data by carrying SCSI commands over IP networks.

### invoke
{: #x2057232}

To activate an action. See also [action](#x2012974).

### IOPS
{: #x3858859}

See [input/output operations per second](#x3858854).

### IoT
{: #x6714346}

See [Internet of Things](#x6714341).

### iSCSI
{: #x6515438}

See [Internet Small Computer System Interface](#x2119615).


## J
{: #glossj}

### JAR file
{: #x2406009}

A Java archive file.

### JavaScript Object Notation (JSON)
{: #x3292165}

A lightweight data-interchange format that is based on the object-literal notation of JavaScript. JSON is programming-language neutral but uses conventions from various languages.

### JSON
{: #x4267096}

See [JavaScript Object Notation](#x3292165).


## K
{: #glossk}

### knowledge graph
{: #x7904177}

A model that consolidates typed entities, their relationships, their properties, and hierarchical taxonomies to represent an organization of concepts for a given domain. After the knowledge graph store is loaded with inputs from structured and unstructured data sources, users and applications can access the knowledge graph to explore key elements of knowledge for a specific domain, explore interactions, and discover additional relationships.


## L
{: #glossl}

### label
{: #x2028176}

A user-defined identifier attached to a grouping of resources that are contained in an instance. Labels are visible only at an instance.

### layer
{: #x2028320}

A changed version of a parent image. Images consist of layers, where the changed version is layered on top of the parent image to create the new image. See also [container](#x2010901), [image](#x2024928).

### LBaaS
{: #x8688464}

See [load balancer as a service](#x9829528).

### LDAP
{: #x2481619}

See [Lightweight Directory Access Protocol](#x2028538).

### lemma
{: #x2763345}

The normalized or canonical form of a word. Typically, the lemma is the underived and uninflected form of a noun or a verb. For example, the lemma of the terms 'organizing' and 'organized' is 'organize' See also [dictionary](#x2001532), [surface form](#x3271760).

### light API call
{: #x7690463}

A client operation that only reads data. Light API calls use fewer resources than heavy API calls because they are performing a single function. See also [heavy API call](#x7690468).

### Lightweight Directory Access Protocol (LDAP)
{: #x2028538}

An open protocol that uses TCP/IP to provide access to directories that support an X.500 model and that does not incur the resource requirements of the more complex X.500 Directory Access Protocol (DAP). For example, LDAP can be used to locate people, organizations, and other resources in an Internet or intranet directory.

### Linux Hyperledger project
{: #x8888396}

An open source, collaborative effort to advance blockchain technology by identifying and addressing important features for a cross-industry open standard for distributed ledgers that can transform the way business transactions are conducted globally. Hyperledger serves as the foundation code for the IBM Blockchain products, services, and solutions. See also [Hyperledger fabric](#x8889858).

### load balancer
{: #x2788902}

Software or hardware that distributes workload across a set of servers to ensure that servers are not overloaded. The load balancer also directs users to another server if the initial server fails.

### load balancer as a service (LBaaS)
{: #x9829528}

A service that provides the ability to distribute traffic among instances in a virtual private cloud.

### local cloud
{: #x8439194}

A cloud computing environment within the client's data center. The local cloud is on-premises, providing improved latency and security. See also [borderless](#x8439189).

### logical unit number (LUN)
{: #x2163327}

In the Small Computer System Interface (SCSI) standard, a unique identifier used to differentiate devices, each of which is a logical unit (LU).

### LoopBack data source
{: #x9826958}

A JavaScript object that represents a back-end service such as a database, REST API (to be consumed), or SOAP web service. Data sources are backed by connectors that then communicate directly with the database or other back-end services.

### LoopBack model
{: #x8940739}

A model that provides a remote (REST) API that clients use to perform operations and interact with backend systems. The model consists of application data, validation rules, data access capabilities, and business logic. Every LoopBack application by default has a set of built-in models: user, application, email, and several models for access control.

### LUN
{: #x2119712}

See [logical unit number](#x2163327).


## M
{: #glossm}

### machine learning (ML)
{: #x8397498}

A method of data analysis that iteratively learns from past data and independently adapts when exposed to new data. The mathematical model at the core of machine learning is built from ground truth inputs. Through training and refinement of example input data, the model can deliver accurate, repeatable results when it analyzes new data.

### machine learning annotator
{: #x8672606}

See [machine learning model](#x7579194).


### machine learning model
{: #x7579194}

A component that identifies entities and entity relationships according to a statistical model that is based on ground truth. The model applies past experience, such as training data, to determine or predict the correct outcome of future experiences based on characteristics of the data. These past experiences are captured in the form of a model by calculating feature scores for each candidate answer or evidence and combining that with known outcomes.

### Managed Service Provider (MSP)
{: #x6418711}

An IBM Business Partner that provides IT services on a contractual basis to maintain clients' computers, networks or software. They manage services on-site at the clients' data center, remotely in the clients' data center, or in a third-party data center.

### master key
{: #x2908413}

An encryption key that is used to protect a crypto unit. The master key provides full control of the hardware security module and ownership of the root of trust that encrypts the chain keys, including the root key and standard key.

### MBaaS
{: #x7044865}

See [mobile backend as a service](#x7044858).

### member
{: #x2003073}

A participant that is enrolled in a blockchain network. A member can be as large as a multi-national corporation or as small as an individual.

### membership service provider
{: #x10127293}

A component that defines the organizations that can transact on a blockchain network. The membership service provider turns identities into permissions by defining them as administrators of an organization. It also contains the public certificate for the root of trust of the organization.
context: Typically, a single membership service provider is used to represent a single blockchain organization.

### mention
{: #x6834461}

A span of text that is considered relevant ina domain data. For example, in a type system about automotive vehicles, occurrences of terms such as "airbag", "Ford Explorer", and "child restraint system" might be relevant mentions.

### ML
{: #x9766880}

See [machine learning](#x8397498).

### mobile app
{: #x7636517}

See [mobile application](#x4258535).

### mobile application (mobile app)
{: #x4258535}

An application that has been designed for a mobile platform. Similar to web applications, mobile apps provide some function beyond static display of information, for example, allowing the user to filter news in near real-time. See also [app](#x4281528).

### mobile backend as a service (MBaaS)
{: #x7044858}

A computing model that connects mobile applications to cloud computing services and provides features such as user management, push notifications, and integration with social networks through a unified API and SDK.

### mobile cloud
{: #x4585344}

An infrastructure in which the storage and processing of data for applications is offloaded from a mobile device into the cloud. With mobile cloud computing, applications are not limited to a specific carrier, but are accessed through the Web.

### MSP
{: #x2330266}

See [Managed Service Provider](#x6418711).

### multizone region (MZR)
{: #x9774820}

A region that is spread across data centers in multiple zones to increase fault tolerance. See also [zone](#x2070723).

### MZR
{: #x9774831}

See [multizone region](#x9774820).


## N
{: #glossn}

### named entity
{: #x3271173}

A concept in a domain that falls in to a well defined category, such as names of organizations, locations, authors, or diseases.

### namespace
{: #x2031005}

A collection of repositories that store images in a registry. A namespace is associated with an IBM Cloud account, which can include multiple namespaces. See also [image](#x2024928), [private image repository](#x8439215).

### NAT
{: #x2245519}

See [network address translation](#x2031199).

### natural language processing (NLP)
{: #x2031058}

A field of artificial intelligence and linguistics that studies the problems inherent in the processing and manipulation of natural language, with an aim to increase the ability of computers to understand human languages.

### network address translation (NAT)
{: #x2031199}

An addressing method that is used to enable one IP address to communicate with several other IP addresses, such as those on a private subnet, by means of a lookup table. Network address translation has two main types: 1-to-1 and many-to-1.

### Network File System (NFS)
{: #x2031282}

A protocol that allows a computer to access files over a network as if they were on its local disks.

### NFS
{: #x2031508}

See [Network File System](#x2031282).

### NLP
{: #x2482021}

See [natural language processing](#x2031058).

### node
{: #x2003286}

- A physical component of the blockchain network infrastructure, namely a peer, Certificate Authority (CA), or ordering node.
- A member of a cluster that runs as a container or virtual machine on shared hardware.


## O
{: #glosso}

### OAuth
{: #x6013335}

An HTTP-based authorization protocol that gives applications scoped access to a protected resource on behalf of the resource owner, by creating an approval interaction between the resource owner, client, and resource server.

### OCI container image
{: #x9860419}

A container image that is compliant with the OCI Image Format Specification

### on-prem
{: #x6969434}

See [on-premises](#x4561212).

### on-premises (on-prem)
{: #x4561212}

Pertaining to software that is installed and run on the local computers of a user or organization.

### ontology
{: #x3069177}

An explicit formal specification of the representation of the objects, concepts, and other entities that can exist in some area of interest and the relationships among them.

### orderer node
{: #x9826016}

See [ordering node](#x9884023).


### ordering node
{: #x9884023}

A node that collects transactions from network members, orders the transactions and bundles them into blocks.

### ordering service
{: #x9826021}

A service that provides a shared communication channel to clients and peers for the broadcast of messages that contain transactions.

### org
{: #x7470494}

See [organization](#x2032585).

### organization
{: #x2032585}

- The entity that owns APIs or applications that use APIs.    A provider organization owns APIs and associated plans, and can additionally own applications. A consumer organization owns only applications. An organization has at least one owner. An organization can be a project team, department, or division.
- The grouping methodology for users in IBM Cloud. Orgs are used to manage quotas. Users in an org share memory and service instance quotas. See also [domain](#x2021210), [space](#x2039442).

### origin server
{: #x2210603}

A server that processes and responds to incoming requests from clients, and is typically used with a caching server.

### out-of-band
{: #x2032717}

Pertaining to data transferred through a stream that is independent from the main data stream.


## P
{: #glossp}

### PaaS
{: #x2029790}

See [platform as a service](#x2029786).

### paravirtualized mode
{: #x9736806}

A lightweight virtualization technique. While in paravirtualized mode, a virtual machine does not require virtualization extensions from the host computer, thus allowing virtualization on hardware systems that do not support hardware-assisted virtualization.

### parent image
{: #x8439210}

An image that provides a base for another image. For example, Ubuntu Linux is the parent image of the IBM Liberty image. See also [base image](#x5366487), [image](#x2024928).

### part of speech (POS)
{: #x3271709}

A grammatical category, such as noun or verb, based on the syntactic function of a lexical item.

### path
{: #x2011343}

The route through which users access REST APIs. A path consists of one or more HTTP operations such as GET or POST.

### payload logging
{: #x9758658}

The capture of payload data and deployment output to monitor ongoing health of AI in business applications.

### payment method
{: #x2281605}

The method by which a client pays an invoice, such as credit card, check, or wire transfer.

### PEAR
{: #x3566452}

See [processing engine archive](#x2959092).

### peer
{: #x2033450}

A blockchain network entity that maintains a ledger with an installed chaincode for performing read and write operations on the ledger. A peer is owned and maintained by an organization.

### performance
{: #x2033492}

The measurement of a Watson system in terms of accuracy, precision, and recall, for example, when answering questions, discovering relationships, or annotating text.

### plan
{: #x2283517}

The packaging construct by which APIs are made available to consumers. A plan makes available a collection of resources or operations from one or more APIs, and is published to communities of application developers.

### platform as a service (PaaS)
{: #x2029786}

The delivery of a computing platform, including applications, optimized middleware, development tools, and Java and Web 2.0 runtime environments, in a cloud-based environment.

### pod
{: #x8461823}

A group of containers that are running on a Kubernetes cluster. A pod is a runnable unit of work, which can be a either a stand-alone application or a microservice.

### point of presence (PoP)
{: #x5458832}

A physical location that stores servers and routers in a network cloud.

### policy
{: #x2011359}

A piece of configuration that controls some aspect of processing in the gateway during the handling of an API invocation. Policies are the building blocks of assembly flows and provide the means to configure capability, such as security, logging, caching, routing of requests to target services, and transformation of data from one format to another. Policies can be configured in the context of an API or in the context of a plan.

### PoP
{: #x7234683}

See [point of presence](#x5458832).

### POS
{: #x2034149}

See [part of speech](#x3271709).

### pre-annotation
{: #x9825866}

The process of annotating a set of documents prior to human annotation. Documents can be pre-annotated by using a rule-based model, a machine-learning model, IBM Watson Natural Language Understanding, or a dictionary. Pre-annotation can help human annotators more quickly prepare a set of ground truth documents.

### precision
{: #x2003831}

A measurement that specifies the proportion of results that are relevant. Precision, which is a positive predictive value, is determined by the number of correct positive results divided by the number of all positive results. Accuracy is best measured by using both precision and recall. See also [accuracy](#x3125742), [recall](#x2154357).

### private cloud
{: #x4585362}

A cloud computing environment in which access is limited to members of an enterprise and partner networks. See also [public cloud](#x4585370).

### private image repository
{: #x8439215}

The combination of an organization's IBM Cloud registry and its namespace. The private image repository is used when referencing an image in a command. See also [image](#x2024928), [namespace](#x2031005).

### private key
{: #x2034701}

An algorithmic pattern used to encrypt messages that only the corresponding public key can decrypt. The private key is also used to decrypt messages that were encrypted by the corresponding public key. The private key is kept on the user system and is protected by a password.

### private resource
{: #x9439035}

An entry that is visible only to account owners and their included accounts. When resources are created, they are private by default. See also [public resource](#x9439040).

### private service
{: #x7690456}

A service that is visible only to members of a specified IBM Cloud organization.

### processing engine archive (PEAR)
{: #x2959092}

A .pear archive file that includes an Unstructured Information Management Architecture (UIMA) analysis engine and all of the resources that are required to use it for custom analysis.

### profile
{: #x2034950}

- A collection of controls used to evaluate whether technology and services are configured in compliance with security policies. See also [rule](#x2037526), [scope](#x2037763).
- A specification of a resource's capacities and capabilities. Different profiles are optimized for different workloads and use cases. A resource's pricing model might depend on its profile.

### promo code
{: #x8440874}

A code used to apply limited time credits to Pay-As-You-Go and Subscription accounts.

### proxy
{: #x2267627}

An application programming interface that forwards requests to a user-defined backend resource and relays responses back to the calling application.

### public cloud
{: #x4585370}

A cloud computing environment in which access to standardized resources, such as infrastructure, multi-tenant hardware, and services, is available to subscribers on a pay-per-use basis. See also [borderless](#x8439189), [private cloud](#x4585362).

### public gateway
{: #x9594389}

The connection of a subnet, with all virtual server instances attached, to the internet. A public gateway uses a many-to-1 network address translation (NAT), which means that thousands of virtual server instances with private addresses can use one public IP address to talk to the public internet.

### public resource
{: #x9439040}

An entry that is visible to everyone in the IBM Cloud catalog. Public resources can be built by any provider (IBM or third party providers). See also [private resource](#x9439035).

### publish
{: #x2116130}

The process of moving an application or product from staging so that the plans and APIs included within it are available for application developers to access and use.

### push
{: #x2035465}

To send information from a server to a client. When a server pushes content, it is the server that initiates the transaction, not a request from the client.

### push notification
{: #x5599582}

An alert indicating a change or update on a mobile app icon.


## Q
{: #glossq}

### quick start
{: #x2277549}

 A pre-built cloud solution template used to automatically create resources and applications.

### quota
{: #x2437020}

The number of resources that can be consumed at an account or service instance level.


## R
{: #glossr}

### Raft
{: #x10127298}

A crash fault tolerant ordering service implementation based on the etcd library of the Raft protocol. Raft follows a leader-and-follower model, where a leader node is elected per channel, and its decisions are replicated by the followers.

### read-mostly
{: #x7470468}

Pertaining to data that changes dynamically.

### recall
{: #x2154357}

A measurement that specifies the percentage of relevant results returned, out of all available relevant results. Recall, which is a measure of sensitivity, is determined by the number of correct positive results divided by the number of positive results that should have been returned. Accuracy is best measured by using both precision and recall. See also [accuracy](#x3125742), [precision](#x2003831).

### recovery point objective (RPO)
{: #x3429911}

In disaster recovery planning, the point at which data is restored to in the event of a disaster. See also [disaster recovery](#x2113280).

### recovery time objective (RTO)
{: #x3167918}

The maximum duration of time within which an application should be restored after any type of disaster. See also [disaster recovery](#x2113280).

### red-black deployment
{: #x8439181}

A deployment technique that drives continuous delivery by enabling synchronized test, development, and deployment. Initially, development is done on an inactive environment (black) while the active environment continues to take traffic (red). Once deployment starts, both environments go live (red-red) until routing is disabled on the formerly active, previous version environment, then subsequently removed (black) while the new environment serves as the only active environment. See also [blue-green deployment](#x7807335).

### region
{: #x2091391}

A defined geographic territory. A region could be a specific postal code area, a town, a city, a state, a group of states, or even a group of countries. Each region can itself be a set of other regions or a set of postal codes that form the region.

### registry
{: #x2064940}

A storage and distribution service that contains public or private images that are used to create containers. See also [container](#x2010901), [image](#x2024928).

### relation
{: #x2064959}

Typically a verb that reflects how entities are related to one another. For example, "lives in" is a relation between a person and a town. A relation links two different entities in the same sentence.

### relation type
{: #x3157818}

A binary, unidirectional relationship between two entities. For example, Mary employedBy IBM is a valid relationship; IBM employedBy Mary is not.

### Representational State Transfer (REST)
{: #x3220976}

A software architectural style that guides the design and development of the architecture for the World Wide Web. REST defines a set of constraints for  the architecture of  Internet-scale distributed hypermedia systems, such as the Web.

### resource
{: #x2004267}

A physical or logical component that can be provisioned or reserved for an application or service instance. Examples of resources can include storage, processors, memory, clusters, and VMs.

### resource group
{: #x2161955}

The environment, and constraints, in which contained resource instances adhere to. A user can be associated with a resource group to enable collaboration.

### REST
{: #x3220987}

See [Representational State Transfer](#x3220976).

### role
{: #x2065412}

- An attribute that provides a context-sensitive meaning of a mention. For example, in the phrase "I went to IBM today", IBM is the mention, Organization is the entity type, and Facility is the role of the entity type.
- A set of permissions or access rights.

### root key
{: #x6946961}

A symmetric wrapping key that is used for encrypting and decrypting other keys that are stored in a data service.

### route
{: #x2037338}

The URL that is used to direct requests to an application. A route is made up of an optional host (or subdomain) and a domain that are specified when an application is pushed. For example, in the route myapp.example.com, myapp is the host and example.com is the domain. A route can be associated with one or more applications. Unless a custom domain is specified, IBM Cloud uses a default shared domain in the route to an application. See also [custom domain](#x5728384), [domain](#x2021210), [endpoint](#x2026820), [host](#x2002243), [subdomain](#x2040080), [Uniform Resource Locator](#x2042491).

### RPO
{: #x3429916}

See [recovery point objective](#x3429911).

### RTO
{: #x3169555}

See [recovery time objective](#x3167918).

### rule
{: #x2037526}

- A set of conditional statements that are used to determine whether a build can be promoted. See also [profile](#x2034950), [scope](#x2037763).
- The set of allowed contexts that are associated with an IBM Cloud resource. The defined contexts dictate a user's or service's access to that resource.

### rule set
{: #x2065665}

A set of rules that define patterns for annotating text. If a pattern applies, then the actions of the rule are performed on the matched annotations. A rule typically specifies the condition that must match, an optional quantifier, a list of additional constraints that the matched text must fulfill, and the actions to be taken when a match occurs, such as creating a new annotation or modifying an existing annotation.

### runtime
{: #x2391929}

The set of resources used to run the application. See also [starter](#x7470511).


## S
{: #glosss}

### SaaS
{: #x4585391}

See [software as a service](#x4585386).

### sandbox catalog
{: #x9826969}

A catalog in which approvals for publishing and lifecycle actions are bypassed so that it can be used for testing APIs under development.

### scale
{: #x2004442}

To increase platform (or system) capacity by adding more application or service instances

### SCM
{: #x2116206}

See [source control management](#x3579285).

### scope
{: #x2037763}

A grouping of resources that can be validated or evaluated for security and compliance. See also [profile](#x2034950), [rule](#x2037526).

### secret
{: #x2789492}

A type of sensitive information, such as a password or an API key, that is used by an application to access a protected resource. See also [dynamic secret](#x9968958).

### secret group
{: #x9968962}

The environment and constraints that contained secrets in an instance must adhere to. A user can be associated with a secret group to enable access and collaboration.

### secrets engine
{: #x9968967}

A component that serves as a back end for a specific type of secret, such as a password or an API key, within a secrets management service. Depending on its type, a secrets engine can store data, generate secrets on demand, and more. See also [dynamic secret](#x9968958).

### Secure Shell (SSH)
{: #x3574365}

A network protocol for secure data exchange between two networked devices. The client can use public-key and private-key authentication, or password authentication, to access the remote server.

### Secure Sockets Layer (SSL)
{: #x2038004}

A security protocol that provides communication privacy. With SSL, client/server applications can communicate in a way that is designed to prevent eavesdropping, tampering, and message forgery. See also [certificate authority](#x2016383).

### security definition
{: #x2135207}

A specification of the settings for a particular aspect of API security; for example, the user registry that authenticates access to the API.

### security group
{: #x2066040}

A resource that provides rules to filter IP traffic to resources in a virtual private cloud. Rules are stateful, such that packets in response to allowed packets are automatically permitted.

### select availability
{: #x9773835}

A production-ready product that is available for sale and accessible to select customers.

### service
{: #x2038343}

A cloud extension that provides ready-for-use functionality, such as database, messaging, and web software for running code, or application management or monitoring capabilities. Services usually do not require installation or maintenance and can be combined to create applications.

### service binding
{: #x5333865}

An association between an application and a service instance that contains the application credentials that are used to communicate with the service instance.

### service credential
{: #x8878996}

A set of API endpoint information and enrollIDs or secrets that are used to interact with network resources, such as CAs, orderers, and peers, in a blockchain network.

### service endpoint
{: #x2871419}

The physical address of a service which implements one or more interfaces.

### service ID
{: #x9148163}

An identity that authenticates a service or an application to a cloud environment and other services. A service ID can be assigned access policies and used to enable an application that is deployed to a cloud environment access to cloud services.

### session
{: #x2004539}

The period of time after an app is started on a mobile device and the quality assurance product is notified to begin collecting app behavior, issues, and problems.

### signature key
{: #x8250375}

An encryption key that is used by the crypto unit administrator to sign commands that are issued to the crypto unit.

### signCert
{: #x9826026}

A certificate that any entity, such as an organization or admin, attaches to their proposals or proposal responses. These signCerts are unique to an entity and are checked by the ordering service to make sure they match the signCert on file for that entity.

### single-campus multizone region (single-campus MZR)
{: #x10127487}

A region that consists of multiple zones that are hosted on data centers that are located within a single building or campus. Dependencies such as power, cooling, networking, and physical security might overlap but are not identical between any two zones to increase fault tolerance. See also [zone](#x2070723).

### single-campus MZR
{: #x10127585}

See [single-campus multizone region](#x10127487).

### single-page application (SPA)
{: #x9829514}

An application that works inside a browser and does not require page reloading during use.

### single sign-on (SSO)
{: #x2213318}

An authentication process in which a user can access more than one system or application by entering a single user ID and password.

### smart contract
{: #x8888420}

A set of business terms that are embedded into a blockchain and executed with transactions. A smart contract can also include a digital representation of a set of business rules and defines conditions under which transfers occur. A smart contract is implemented using chaincode.

### SoE
{: #x9858636}

See [system of engagement](#x6528306).

### software as a service (SaaS)
{: #x4585386}

A model of software deployment whereby software including business processes, enterprise applications, and collaboration tools, are provided as a service to customers through the cloud.

### SOLO
{: #x9825888}

A consensus plugin implementation for Hyperledger Fabric that results in a single ordering service node in the blockchain network.

### SOR
{: #x2214822}

See [system of record](#x6735061).

### source control management (SCM)
{: #x3579285}

An aspect of software configuration management that involves managing changes to collections of files.

### SPA
{: #x2151882}

See [single-page application](#x9829514).

### space
{: #x2039442}

A sub-group within an IBM Cloud org. Users who are members of an org are given access to one or more of its spaces, with permissions associated with a particular role (such as developer, manager, or auditor). Any member of the space can view apps, but only members with the developer role can create apps and add service instances to the space. Apps and service instances are associated with spaces. See also [organization](#x2032585).

### SSH
{: #x4318877}

See [Secure Shell](#x3574365).

### SSL
{: #x2483907}

See [Secure Sockets Layer](#x2038004).

### SSO
{: #x3456450}

See [single sign-on](#x2213318).

### stage
{: #x2067189}

To deploy an application, service, or instance to a pre-defined location  for running or testing before deployment to a production environment. See also [deployment](#x2104544).

### stanza
{: #x2094743}

A section of a software package that defines either a specific action to be performed on that the software package or a set of conditions under which actions are to be performed on the software package. The complete software package is a stanza that contains a hierarchy of many different stanzas.

### starter
{: #x7470511}

A template that includes predefined services and application code that is configured with a particular buildpack. A starter might be application code that is written in a specific programming language, or a combination of application code and a set of services. See also [runtime](#x2391929).

### state database
{: #x9826031}

A database that contains the current values for all keys on a blockchain ledger for a channel.

### subdomain
{: #x2040080}

A domain that makes up a part of a larger domain. See also [custom domain](#x5728384), [domain](#x2021210), [host](#x2002243), [route](#x2037338), [Uniform Resource Locator](#x2042491).

### subject
{: #x2380043}

The user, service ID, or access group that is granted access by an access policy.

### subnet
{: #x4282974}

See [subnetwork](#x2040149).

### subnetwork (subnet)
{: #x2040149}

A network that is divided into smaller independent subgroups, which still are interconnected.

### subscription code
{: #x9888956}

A code used to apply credits to an account after a subscription is purchased.

### subtype
{: #x2040253}

A type that extends or implements another type; the supertype.

### surface form
{: #x3271760}

The form of a word or multiword unit as it is found in the corpus. For example, some surface forms of the lemma 'organize' are the terms 'organizing' and 'organized'. See also [dictionary](#x2001532), [lemma](#x2763345).

### system of engagement (SoE)
{: #x6528306}

An information technology (IT) system that incorporates technologies that encourage user interaction through email, collaboration systems, and networking.  A system of engagement often uses cloud technologies to extend the usefulness of systems of record. See also [system of record](#x6735061).

### system of record (SOR)
{: #x6735061}

An information storage system (such as a database or application) that stores business records and automates standard processes. See also [system of engagement](#x6528306).


## T
{: #glosst}

### tag
{: #x2040924}

A user-defined identifier attached to a grouping of resources that are contained in an account. Tags are visible account-wide.

### target
{: #x2262507}

The resource or set of resources to provide a subject access to in an access policy. The set of resources is defined by one or more attributes. For example, a target could be all resources in a resource group, all resources of a certain resource type, or the resource with a certain resource ID.

### template
{: #x2041200}

A predefined structure for an artifact.

### testing data
{: #x7736833}

A set of annotated documents that can be used to evaluate system metrics after ingestion and training. See also [blind data](#x7881128), [training data](#x2860199).

### third-party
{: #x2877945}

Pertaining to a product or service that is provided by a company other than IBM.

### tile
{: #x2092493}

A visual representation of a running application that provides status on a dashboard.

### train
{: #x6076689}

To set up a Watson instance with components that enable the system to function in a particular domain (for example: corpus content, training data that generates machine learning models, programmatic algorithms, annotators, or other ground truth components) and then making improvements and updates to these components based on accuracy analysis.

### training data
{: #x2860199}

A set of annotated documents that can be used to train machine learning models. See also [blind data](#x7881128), [testing data](#x7736833).

### transaction
{: #x2005321}

The mechanism that participants on the blockchain network use to interact with assets. A transaction either creates new chaincode or invokes an operation in an existing chaincode. See also [chaincode](#x9829545).

### trigger
{: #x2005384}

A mechanism that initiates actions. Triggers can be explicitly fired by a user or fired on behalf of a user by an external event source.

### true negative
{: #x7881314}

An answer or annotation that is actually incorrect and is predicted to be incorrect.

### true positive
{: #x7881319}

An answer or annotation that is actually correct and is predicted to be correct.

### trusted profile
{: #x10127466}

 A grouping of federated users, compute resources, or both, that are granted the same IAM access. When an identity applies a trusted profile, temporary security credentials are provided for the duration of a session. All identities that are allowed to apply a single profile inherit the same access.

### trusted root
{: #x2042234}

A certificate signed by a trusted certificate authority (CA). See also [certificate authority](#x2016383), [intermediate certificate](#x3753781).

### type system
{: #x2959182}

The set of objects that may be discovered by a text analysis engine in a document. The type system defines all possible feature structures in terms of types and features. Any number of different types can be defined in a type system. A type system is domain and application specific.


## U
{: #glossu}

### Uniform Resource Identifier (URI)
{: #x2116436}

A unique address that is used to identify content on the web. The most common form of URI is the web page address, which is a particular form or subset of URI called a Uniform Resource Locator (URL). A URI typically describes how to access the resource, the computer that contains the resource, and the location of the resource on that computer.

### Uniform Resource Locator (URL)
{: #x2042491}

The unique address of an information resource that is accessible in a network such as the Internet. The URL includes the abbreviated name of the protocol used to access the information resource and the information used by the protocol to locate the information resource. See also [custom domain](#x5728384), [domain](#x2021210), [host](#x2002243), [route](#x2037338), [subdomain](#x2040080).

### unit of measure (UOM)
{: #x4259569}

A standardized unit that is used to measure a specified property of something.

### UOM
{: #x5783003}

See [unit of measure](#x4259569).

### URI
{: #x2116461}

See [Uniform Resource Identifier](#x2116436).

### URL
{: #x2042718}

See [Uniform Resource Locator](#x2042491).

### user
{: #x2069659}

- An IBMid or SoftLayer ID that is used as a person's identity in an account.
- A participant in a blockchain network that has indirect access to the ledger through a trust relationship to an existing member.

### user registry
{: #x2042894}

A collection of user information, such as user IDs and passwords, that is used as the basis for security control by a system such as a web application server.


## V
{: #glossv}

### virtual
{: #x2043123}

Pertaining to not physically existing as such but made by software to appear to do so.

### virtual local area network (VLAN)
{: #x2438470}

A logical association of switch ports based upon a set of rules or criteria, such as Medium Access Control (MAC) addresses, protocols, network address, or multicast address. This concept permits the LAN to be segmented again without requiring physical rearrangement.

### virtual machine (VM)
{: #x2043165}

A software implementation of a machine that executes programs like a real machine. See also [virtual server](#x2455638).

### virtual private cloud (VPC)
{: #x4585403}

A virtual network that is tied to a private user account and isolated from other networks in a public cloud. Only authorized users can access virtual private cloud resources, which include virtual servers, storage, and subnets.

### virtual private network (VPN)
{: #x2043188}

A private connection between two endpoints, even when the data is transferred across a public network. Usually, a VPN is used in combination with security methods, such as authentication and encryption, to provide maximum data security and privacy.

### virtual server
{: #x2455638}

A server that shares its resources with other servers to support applications. See also [virtual machine](#x2043165).

### VLAN
{: #x2484337}

See [virtual local area network](#x2438470).

### VM
{: #x2043253}

See [virtual machine](#x2043165).

### volume
{: #x2043272}

A fixed amount of physical or virtual storage on a data storage medium.

### VPC
{: #x2484345}

See [virtual private cloud](#x4585403).

### VPN
{: #x9866833}

See [virtual private network](#x2043188).

### VPN as a service
{: #x9829539}

A private connection between two endpoints, which remains private and can be encrypted even when the data is transferred across a public network.


## W
{: #glossw}

### WAR
{: #x2844389}

See [web archive](#x2116506).

### WAR file
{: #x2406005}

See [web archive](#x2116506).


### web app
{: #x7636628}

See [web application](#x2116500).

### web application (web app)
{: #x2116500}

An application that is accessible by a web browser and that provides some function beyond static display of information, for instance by allowing the user to query a database. Common components of a web application include HTML pages, JSP pages, and servlets. See also [app](#x4281528).

### web archive (WAR)
{: #x2116506}

A compressed file format, defined by the Java EE standard, for storing all the resources required to install and run a web application in a single file.

### workspace
{: #x2096037}

A context that contains a collection of artifacts that a user with appropriate permission can modify.


## Z
{: #glossz}

### zone
{: #x2070723}

An independent fault domain. A zone is an abstraction designed to assist with improved fault tolerance and decreased latency. See also [multizone region](#x9774820), [single-campus multizone region](#x10127487).
