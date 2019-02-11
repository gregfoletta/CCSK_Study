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

* **Software as a Service (SaaS)** - 
