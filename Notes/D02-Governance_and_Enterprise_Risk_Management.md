# Domain 2 - Governance and Enterprise Risk Management

## 2.0 - Intro

Goverenance and risk management are broad topics. This guidance focuses on how they change in cloud computing.

* *Governance* includes the policy, process and internal controls that dictate how an organisation is run.
* *Enterprise Risk Management* covers managing the risk to information, including information technology.
* *Information security* is the tools and practices to manage risk to information.

## 2.1 - Overview

### 2.1.1 - Governance

Cloud computing affects governance since it either introduces a third party into the process, or potentially alters internal governance structures in the case of self-hosted private cloud.

The key point: *an organisation can never outsource governance*.

#### 2.1.1.1 Tools of Cloud Governance

* *Contracts* are the primary tool of governance. It is your only guarentee of any level of service or commitment (assuming no breach).
* *Supplier assessments* are performed by the potential cloud customer. They combine:
    * Contractural and manual research.
    * Third party attestations
    * Technical research.
* *Compliance reporting* includes all the documentation on a provider's internal and external compliance assessments. They are the reports from *audits of controls*.

The [Cloud Alliance STAR Registry](https://cloudsecurityalliance.org/star/#_overview) is an assurance program for cloud provider assessments based on the CSA cloud controls matrix.

### 2.1.2 - Enterprise Risk Management

ERM is the overall management of risk for an organisation. As with governance, the contract defines the roles and responsibilities for risk management between a cloud provider and a cloud customer.

As with governance, you can never outsource your overall responsibility and accountability for risk management to an external provider.

*Fore more on risk management:*
* [ISO 31000:2009 - Risk management – Principles and guidelines](https://www.iso.org/standard/43170.html)
* [ISO/IEC 31010:2009 - Risk management – Risk assessment techniques](https://www.iso.org/standard/51073.html)

Risk management is based on a *shared responsibility* model. The cloud provider acceptssome responsibility for some risks, and the cloud customer is responsibile for anything beyond that.

The cloud provider is responsible for the *risk management* - the cloud user is ultimately responsible for the ownership of the risks.

ERM relies on good contracts and documentation, with clear division of responsibilites and knowledge of where the potential for untreated risk lie.

*Risk tolerance* is the amount of risk that the leadership and stakeholders of the organisation are willing to accept. Assessments should align with the value and requirements of the assets involved.

### 2.1.3 - The Effects of Service Model and Deployment Model

#### 2.1.3.1 - Service Models

SaaS presents the most critical example of the need for negotiated contract. The contract will protect the ability to govern or validae risk as it relates to data stored, processed or transmitted with and in the application.

PaaS has an increased level of detail available, which in turn gives the user the ability to self-manage goverenance and risk issues. The likelihood of a fully negotiated contract is lower than wth the other service models, as the core driver of PaaS is to deliver a single capability with high efficiency.

IaaS represents the closest cloud comes to traditional data centre. Thus the majority of the existing governance and risk management activites that organisations have already built are directly transferable. There are however new complexities related to the management and orchestration layers that IaaS has.

#### 2.1.3.2 - Deployment Models

**Public cloud** customers have a reduced ability to govern operations since the provider is responsible for the management and governance of their infrastructure, employees, etc. Customers also generally have a reduced ability to negotiate contracts.

If contract negotiation doesn't work, the choice is either a different provider, or an adjustment of needs and use of alternate governance mechanisms to mitigate concerns.

**Private cloud** will also have an effect on governance. If a third party is used to manage the private cloud, the governance changes are similar to a public cloud. 

A public provider has various incentives to keep its service well documented and at particular levels of performance. A hosted provider may only offer what is exactly in the contract, with everything else at an additional cost.

**Hybrid and community** contracts must consider the minimum set of common controls comprised of the cloud service provider's contract and the organisations internal governance agreements.

#### 2.1.3.3 - Cloud Risk Management Trade-offs

* Less physical controls over assets and their controls and processes.
* Greater reliance on contracts, audits and assessments, as you lack day-to-day visibility or management.
* Increased requirement for proactive management of relationship and adherence to contracts. 
* Cloud customers have a reduced need (and therefore cost) to manage risks that the cloud provider accepts under the shared responsibility model.

#### 2.1.3.4 - Cloud Risk Management Tools

The core tenets of risk management is that you can *manage, transfer, accept, or avoid* risks.

The supplier assessment sets the groundwork for the cloud risk management program:
* Request documentation
* Review their security program and documentation
* Review any legal, regulatory, contractual, and jurisdictional requirements for both the provider and yourself.
* Evaluate the contracted service in the context of your information assets.
* Separately evaluate the overall provider, such as finances/stability, reputation, and outsourcers.

Periodically review audits and assessments to ensure they are up to date.

After reviewing and understanding, what remains is the residual risk. This can be managed by controls you implement.

If after all assessments and the controls you implement there is still residual risk your only options are to transfer it, avoid it, or accept it.

Risk transfer, most often enabled by insurance, is an imperfect mechanism.

## 2.2 - Recommendations

* Identify the shared responsibilities of security and risk management based on the chosen cloud deployment and service model.
* Understand how a contract affects your governance framework/model.
* Develop a process for cloud provider assessments.
* Cloud providers should offer easy access to documentation and reports needed by prospective cloud customers.
* Align risk requirements to the specific assets involved and the risk tolerance for those assets.
* Create a specific risk management and risk acceptance/mitigation methodology to assess the risks of every solution in the space.
* Use controls to manage residual risk.
* Use tooling to track approved providers based on asset type, cloud usage and management.
