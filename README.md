# Microsoft_azure
Microsoft Certified: Azure Fundamentals

## concepts 
1. storage
2. cloud computing (Iaas ,Paas ,Saas)
3. networking
4. tools:admin,govern

## Study guide for Exam AZ-900: Microsoft Azure Fundamentals
### https://learn.microsoft.com/en-gb/credentials/certifications/resources/study-guides/az-900
- Describe cloud concepts (25–30%)
- Describe Azure architecture and services (35–40%)
- Describe Azure management and governance (30–35%)

## Unit -1 module 1
Azure Fundamentals includes interactive exercises that give you hands-on experience with Azure. Many exercises provide a temporary Azure portal environment called the sandbox
a. Define cloud computing.
b. Describe the shared responsibility model.
c. Define cloud models, including public, private, and hybrid.
- Identify appropriate use cases for each cloud model.
- Describe the consumption-based model.
d. Compare cloud pricing models.

a. cloud computing is where the PC is in the cloud center insted of physically with us , we only pay for the services used .
- all the cloud provider mainly provide ( compute power and storage)
- compute power : is how much processeing a computer can do and which allows for latest upadte and processing quick
- storage : PC/traditional  has limited hard drive space and cloud make sure its up to date and its backedup



b. shared responsibility model , in traditional computers there where datacenter which was taken care of and if the cilent wanted any details they had to rely on the employee working in datacenter

- Then, for some things, the responsibility depends on the situation. If you’re using a cloud SQL database, the cloud provider would be responsible for maintaining the actual database. However, you’re still responsible for the data that gets ingested into the database. If you deployed a virtual machine and installed an SQL database on it, you’d be responsible for database patches and updates, as well as maintaining the data and information stored in the database.
- as the datacenter has shifted to cloud they have three diffrent models IAAS , PAAS ,SAAS.
- IaaS places the most responsibility on the consumer, with the cloud provider being responsible for the basics of physical security, power, and connectivity. On the other end of the spectrum
-  SaaS places most of the responsibility with the cloud provider. PaaS, being a middle ground between IaaS and SaaS
-  Saas-Paas-Iaas
-  You’ll always be responsible for:
The information and data stored in the cloud
,Devices that are allowed to connect to your cloud (cell phones, computers, and so on)
,The accounts and identities of the people, services, and devices within your organization

- The cloud provider is always responsible for:
The physical datacenter
,The physical network
,The physical hosts
- Your service model will determine responsibility for things like:

Operating systems
,Network controls
,Applications
,Identity and infrastructure

c. What are cloud models? The cloud models define the deployment type of cloud resources. The three main cloud models are: private, public, and hybrid.
- It companies use the private which comes with great value and which have datacenters ( in private there are 2 types on permis and host services by 3rd party)
- thirdparty service given by the aws or azure for public cloud
- Hybrid clouds rely on secure network connections, often using technologies like virtual private networks (VPNs)
- **Azure Arc** is a set of technologies that helps manage your cloud environment. Azure Arc can help manage your cloud environment, whether it's a public cloud solely on Azure, a private cloud in your datacenter, a hybrid configuration, or even a multi-cloud environment running on multiple cloud providers at once.
- What if you’re already established with VMware in a private cloud environment but want to migrate to a public or hybrid cloud? Azure VMware Solution lets you run your **VMware** **workloads** in Azure with seamless integration and scalability.
- Azure VMware Solution (AVS) is a cloud service offered by Microsoft Azure in collaboration with VMware. It enables organizations to run their   VMware workloads natively within the Microsoft Azure cloud environment.

d.Capital expenditure (CapEx) and operational expenditure (OpEx).

- CapEx is typically a one-time, up-front expenditure to purchase or secure tangible resources. A new building, repaving the parking lot, building a datacenter, or buying a company vehicle are examples of CapEx.

- In contrast, OpEx is spending money on services or products over time. Renting a convention center, leasing a company vehicle, or signing up for cloud services are all examples of OpEx.

### module 2
- Describe the benefits of using cloud services
  a.Describe the benefits of high availability and scalability in the cloud.
  b.Describe the benefits of reliability and predictability in the cloud.
  c.Describe the benefits of security and governance in the cloud.
  d.Describe the benefits of manageability in the cloud.

 - You’ll also learn about security, governance, and overall manageability in the cloud.
 - **SLA (Service level agreement)** , which is agreement between the company and IT services to give UP time services from 90% to 99.9% avaiblibe to customers from the cloud provider.
 - Scaling generally comes in two varieties: vertical and horizontal. Vertical scaling is focused on increasing or decreasing the capabilities of resources. Horizontal scaling is adding or subtracting the number of resources.
 - **cost:**You can even use tools like the Total Cost of Ownership (TCO) or Pricing Calculator to get an estimate of potential cloud spend.
 - **Predictability** in the cloud lets you move forward with confidence. Predictability can be focused on performance predictability or cost predictability. Both performance and cost predictability are heavily influenced by the Microsoft Azure Well-Architected Framework.
 - The cloud, by virtue of its decentralized design, naturally supports a reliable and **resilient** infrastructure. With a decentralized design, the cloud enables you to have resources deployed in regions around the world. With this global scale, even if one region has a catastrophic event other regions are still up and running.
 - And because the cloud is intended as an over-the-internet delivery of IT resources, cloud providers are typically well suited to handle things like distributed denial of service (DDoS) attacks, making your network more robust and secure.

- Management in the cloud
- Management in the cloud speaks to how you’re able to manage your cloud environment and resources. You can manage these:

- Through a web portal
a.Using a command line interface.
b.Using APIs.
c.Using PowerShell.

### module3

- In this module, you’ll be introduced to cloud service types. You’ll learn how each cloud service type determines the flexibility you’ll have with managing and configuring resources.
a.Describe infrastructure as a service (IaaS).
b.Describe platform as a service (PaaS).
c.Describe software as a service (SaaS).
d.Identify appropriate use cases for each cloud service (IaaS, PaaS, SaaS).
 
  

