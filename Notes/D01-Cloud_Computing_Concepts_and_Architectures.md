# D01-Cloud Computing Concepts and Architectures

## Introduction

This domain provides the rest of the conceptual framework for the CSAs guidance. It: 

* Defines cloud computing
* Sets out the base terminology
* Details the overall logical and architectural frameworks.

## 1.1 - Overview

### 1.1.1 - Defining Cloud Computing

The cloud model envisages a world where components can be easly orchestrated, provisioned, implemented and decomissoned, and scaled up or down to provide and on-demand utility like model of allocation and consumption.

**Cloud User**: the person or organisation requesting and using the resources.
**Cloud Provider**: the person or organisation who delivers the resources.

[NIST 500-292](https://www.nist.gov/publications/nist-cloud-computing-reference-architecture) uses the term *cloud actor* and adds roles for *cloud brokers, carriers and auditors*.

The key techniques to create a cloud are abstracting and orchestration. The resources are abstracted away from the underlying physical infrastructure into pools. Orchestration (and automation) coordinates the carving out and delivery of the sets of resources from the pools.

Cloud are *multitenant* by nature. Multitenancy doesn't just apply between organisations - it can be applied between business units within an organisation.


### 1.1.2 - Definitional Model

The CSA uses the [NIST model](http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf) fir cloud computing as its standard, while also endorsing the more in-depth [ISO/IEC](http://www.iso.org/iso/catalogue_detail?csnumber=60544) model.

NIST defines the cloud compting model using:

* Five essential characteristics.
* Three cloud service models.
* Four cloud deployment models.

#### 1.1.2.1 - Characteristics

* **Resource Pooling** - the provider abstracts resources and collects them into a pool. Portions are allocated to different customers.
* **On-Demand Self Service** - the customers manage the resources wihtout having to talk to human administrators.
* **Broad Network Access** - all resources are available over a network. There is no need for direct physical access.
* **Rapid Elasticity** - consumers can expand and constract resources from the pool, often automatically.
* **Measured Service** - resources from the pool are metered, and customers are only charged for what they use. The resources are consumed like a utility.

#### 1.1.2.2 - Service Models

* **Software as a Service (SaaS)** - a full application hosted by the provider. Accessed using a web browser, mobile app, or lightweight client app.
* **Platform as a Service (PaaS)** - abstracts and provides development or application platforms. Examples include databases, file storage, collaboration. The key differentiator you don't manage the underlying servers.
* **Infrastructure as a Service** - access to a resource pool of fundamental computing infrastructure, e.g. compute, network or storage.

#### 1.1.2.3 - Depoyment Models

NIS and ISO/IEC use the same four depoloyment models.

* **Public Cloud**
* **Private Cloud**
* **Community Cloud**
* **Hybrid Cloud**

Deployment models are based on the cloud user.

### 1.1.4 - Logical Model

* Infrastrucure - the core components of a computing system.
* Metastructure - the protocols and mechanisms that provide the interface between the infrastructure and the other layers.
* Infostructure - the data and information
* Applistructure - applications deployed in the cloud.

The key difference between cloud and traditional computing is the metastructure. This includes the management plane components, which are network enabled and remotely accessible.

Another difference is that you tend to double up on each layer. Infrastructure includes the resource pools as well as the insfrastructure needed to create the cloud.

## 1.2 - Cloud Security Scope, Responsibilities, and Models

### 1.2.1 - Cloud Security and Compliance Scope and Responsibilities.

Cloud computing is a shared technology model where different organisations are responsible for implementing and managing different parts of the stack.

The security responsibility scales from mostly consumer (IaaS) to mostly provider (SaaS).

*The most important security consideration us knowing exactly who is responsible for what in any given cloud project*.

Cloud providers should clearly document their internal security controls. Cloud users, for any given project, should build a responsibility matrix to document who is implementing which controls and how.

The CSA has two tools:
* The [Consensus Assessments Initiative Questionnaire](https://cloudsecurityalliance.org/group/consensus-assessments/#_overview).
* The [Cloud Controls Matrix](https://cloudsecurityalliance.org/group/cloud-controls-matrix/#_overview)

### 1.2.2 - Cloud Security Models

* *Conceptual models or frameworks* include visualisations and descriptions used to explain cloud security concepts and principles.
* *Controls models or frameworks* categorise and detail specific cloud security controls or categories of controls.
* *Reference architectures* are templates for implementing cloud security. They can be very abstract, or quite detailed.
* *Design patterns* are resusable solutions to particular problems. As with reference architectures, they can be more or less abstract.

The CSA recommends the following models:
* The [CSA Enterprise Architecture](https://research.cloudsecurityalliance.org/tci/index.php/explore/)
* The [CSA Cloud Controls Matrix](https://cloudsecurityalliance.org/group/cloud-controls-matrix/#_overview)
* The NIST draft [Cloud Computing Security Reference Architecture](http://collaborate.nist.gov/twiki-cloud-computing/pub/CloudComputing/CloudSecurity/NIST_Security_Reference_Architecture_2013.05.15_v1.0.pdf)
* [ISO/IEC FDIS 27017 Information technology – Security techniques – Code of practice for information security controls based on ISO/IEC 27002 for cloud services](https://www.iso.org/standard/43757.html)

#### 1.2.2.1 - A Simple Cloud Security Process Model

There is a relatively straightforward, high-level process for managing cloud security:

1. Identify security and compliance requirements, and any existing controls.
1. Select your cloud provider, service, and deployment models.
1. Define the architecture.
1. Assess the security controls.
1. Identify control gaps.
1. Design and implement controls to fill the gaps.
1. Manage changes over time.

## 1.3 - Areas of Critical Focus

The 13 other domains are divided into two broad categories: governance and operations. Governance domains and broad and address strategiv and policy issues. The operational domains focus more on tactical security concerns and implementation within the architecture.
