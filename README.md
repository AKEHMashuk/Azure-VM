<p align="center">
<img src="https://i.imgur.com/ZSETLU0.png" alt="Azure Logo"/>
</p>

<h1> Deployment of Virtual Machine in Azure </h1>
This tutorial outlines the prerequisites and installation of Virtual machine and Resource group .<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

Azure Subscription: You must have an active Azure subscription. If you don't have one, you can sign up for a free trial or a paid subscription.

Resource Group: Create an Azure resource group that will serve as a logical container for your virtual machine and associated resources.

Virtual Network: Set up a virtual network (VNet) in Azure to provide network connectivity to your virtual machine. You can create a new VNet or use an existing one.

Subnet: Within the virtual network, create a subnet to allocate IP addresses for your virtual machines. This subnet will define the network range available for your virtual machine deployment.

Storage Account: Create an Azure Storage Account to store the virtual machine's virtual hard disks (VHDs) and any associated data disks.

Availability Set (Optional): If you require high availability and fault tolerance, you can create an availability set. It ensures that your virtual machines are distributed across multiple fault domains and update domains to minimize downtime during planned and unplanned events.

Virtual Machine Image: Choose the appropriate virtual machine image from the Azure Marketplace or bring your own custom image. The image will serve as the base for your virtual machine deployment.

Virtual Machine Size: Select the appropriate virtual machine size based on your workload requirements, such as CPU, memory, storage, and network capacity.

Authentication: Decide on the authentication method for accessing the virtual machine. You can choose between using username/password or SSH key-based authentication.

Public IP Address (Optional): If you need your virtual machine to have a public IP address for remote access or public-facing applications, allocate a public IP address resource.

Network Security Group (NSG): Define network security rules using NSGs to control inbound and outbound traffic to your virtual machine.

Firewall and Network Connectivity: If you have specific network requirements, such as connecting your virtual machine to an on-premises network, you may need to configure a virtual network gateway or Azure ExpressRoute.

Monitoring and Diagnostics: Consider enabling Azure Monitor and Azure Diagnostics to gain insights into the performance, health, and diagnostics of your virtual machine.

Backup and Disaster Recovery (Optional): Establish a backup and recovery strategy for your virtual machine, such as configuring Azure Backup or replicating the virtual machine to a secondary Azure region.

Operating System Licensing: Ensure you have the appropriate licenses for the operating system you are deploying on the virtual machine. Azure provides the option to bring your own license or use a provided license for certain operating systems.

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
