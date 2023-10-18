## AZ-900

<details>
<summary>What is cloud computing?</summary><br><b>

[Wikipedia](https://en.wikipedia.org/wiki/Cloud_computing): "Cloud computing is the on-demand availability of computer system resources, especially data storage (cloud storage) and computing power, without direct active management by the user"
</b></details>

<details>
<summary>What types of clouds (or cloud deployments) are there?</summary><br><b>

  * Public - Cloud services sharing computing resources among multiple customers
  * Private - Cloud services having computing resources limited to specific customer or organization, managed by third party or organizations itself
  * Hybrid - Combination of public and private clouds
</b></details>


<details>
<summary>What is Azure Firewall?</summary><br><b>

Azure Firewall is a cloud-native and intelligent network firewall security service that provides the best of breed threat protection for your cloud workloads running in Azure.
</b></details>


<details>
<summary>What is Network Security Group?</summary><br><b>

A network security group contains security rules that allow or deny inbound network traffic to, or outbound network traffic from, several types of Azure resources. For each rule, you can specify source and destination, port, and protocol.
</b></details>

1.	What do you understand about cloud computing?

Cloud computing is a technology that enables the delivery of computing services, including storage, processing, and networking, over the internet. It offers on-demand access to resources, allowing users to scale and manage their IT infrastructure without the need for physical hardware. Cloud computing provides services through three main models: Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS). It offers benefits such as cost-efficiency, scalability, flexibility, and accessibility.

2.	Can you tell something about Azure Cloud Service?

Azure Cloud Service is a Platform as a Service (PaaS) offering by Microsoft Azure. It allows developers to build and deploy scalable web applications and APIs without managing the underlying infrastructure. Azure Cloud Services provide automatic load balancing, fault tolerance, and scalability. Developers can focus on writing code, while Azure handles the deployment, monitoring, and management of the application.

3.	What are the various models available for cloud deployment?

Cloud deployment models include:

Public Cloud: Services are provided by third-party cloud providers and are accessible to the public.
Private Cloud: Resources are dedicated to a single organization, providing greater control and security.
Hybrid Cloud: Combines both public and private cloud resources, allowing data and applications to move between them.
Multi-Cloud: Utilizes services from multiple cloud providers, offering redundancy and flexibility.
Define role instance in Azure.

In Azure, a role instance refers to a virtual machine (VM) running a specific role within a cloud service. It can be a web role, worker role, or a custom role. Role instances are managed by Azure and can automatically scale based on demand.

4.	How many cloud service roles are provided by Azure?

Azure offers two main roles: Web Roles and Worker Roles. These roles are used in Azure Cloud Services. Web Roles are designed for web applications, while Worker Roles handle background processes. Additionally, Azure allows you to create custom roles to meet specific application requirements.

5.	Why is Azure Diagnostics API needed?

The Azure Diagnostics API is used for collecting diagnostic data from applications and services running in Azure. It allows you to capture logs, performance counters, and other telemetry data, which is essential for monitoring and troubleshooting applications in the Azure environment.

6.	Define Azure Service Level Agreement (SLA).

An Azure Service Level Agreement (SLA) is a commitment by Microsoft Azure to provide a certain level of service availability and performance. SLAs specify the percentage of uptime and response times for Azure services, ensuring reliability for customers. SLAs vary by service and are legally binding agreements.

7.	VM creation is possible using Azure Resource Manager in a Virtual Network which was created by means of classic deployment. True or False?

True. Azure Resource Manager (ARM) allows you to create and manage virtual machines (VMs) in a Virtual Network created using classic deployment. ARM provides a unified way to manage resources in Azure, regardless of whether they were deployed using the classic model or the new Azure Resource Manager model. This facilitates the coexistence of resources deployed in different ways within the same Azure environment.

