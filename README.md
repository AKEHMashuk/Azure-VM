<p align="center">
<img src="https://i.imgur.com/ZSETLU0.png" alt="Azure Logo"/>
</p>

<h1> Deployment of Virtual Machine in Azure </h1>
This tutorial outlines the prerequisites and installation of Virtual machine with Resource group .<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (64 Bit)

<h2>List of Prerequisites</h2>

1. Azure Subscription: You must have an active Azure subscription. If you don't have one, you can sign up for a free trial or a paid subscription.

2. Resource Group: Create an Azure resource group that will serve as a logical container for your virtual machine and associated resources.

3. Virtual Network: Set up a virtual network (VNet) in Azure to provide network connectivity to your virtual machine. You can create a new VNet or use an existing one.

4. Subnet: Within the virtual network, create a subnet to allocate IP addresses for your virtual machines. This subnet will define the network range available for your virtual machine deployment.

5. Storage Account: Create an Azure Storage Account to store the virtual machine's virtual hard disks (VHDs) and any associated data disks.

6. Availability Set (Optional): If you require high availability and fault tolerance, you can create an availability set. It ensures that your virtual machines are distributed across multiple fault domains and update domains to minimize downtime during planned and unplanned events.

7. Virtual Machine Image: Choose the appropriate virtual machine image from the Azure Marketplace or bring your own custom image. The image will serve as the base for your virtual machine deployment.

8. Virtual Machine Size: Select the appropriate virtual machine size based on your workload requirements, such as CPU, memory, storage, and network capacity.

9. Authentication: Decide on the authentication method for accessing the virtual machine. You can choose between using username/password or SSH key-based authentication.

10. Public IP Address (Optional): If you need your virtual machine to have a public IP address for remote access or public-facing applications, allocate a public IP address resource.

11. Network Security Group (NSG): Define network security rules using NSGs to control inbound and outbound traffic to your virtual machine.

12. Firewall and Network Connectivity: If you have specific network requirements, such as connecting your virtual machine to an on-premises network, you may need to configure a virtual network gateway or Azure ExpressRoute.

13. Monitoring and Diagnostics: Consider enabling Azure Monitor and Azure Diagnostics to gain insights into the performance, health, and diagnostics of your virtual machine.

14. Backup and Disaster Recovery (Optional): Establish a backup and recovery strategy for your virtual machine, such as configuring Azure Backup or replicating the virtual machine to a secondary Azure region.

15. Operating System Licensing: Ensure you have the appropriate licenses for the operating system you are deploying on the virtual machine. Azure provides the option to bring your own license or use a provided license for certain operating systems.

<h2>Installation Steps</h2>

<p>
<img src="https://imgur.com/7oqumkW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1: Sign in to Azure Portal
Go to the Azure Portal (portal.azure.com) and sign in using your Azure account credentials.
<p>
<img src="https://imgur.com/7oqumkW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 2: Create a Resource Group
Create a new or select an existing resource group. A resource group acts as a logical container for your virtual machine and associated resources. Click on "Create a resource" and search for "Resource group." Provide a name, select the desired region, and click on "Review + Create" to create the resource group.
<p>
<img src="https://imgur.com/sTKDedm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Step 3: Create a Virtual Network (VNet)
Navigate to the resource group you just created and click on "Add." Search for "Virtual network" and click on "Create" to start creating a new virtual network. Provide a name, select the desired region, and configure the IP address range for the VNet. You can also create a subnet within the VNet if needed. Click on "Review + Create" to create the virtual network.

Step 4: Create a Virtual Machine
Inside the resource group, click on "Add" again. Search for "Virtual machine" and click on "Create" to start creating a new virtual machine. Or all the above process can be implemented all at once when created Virtual machine. 

<p>
<img src="https://imgur.com/Numxyc4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p> 

Step 5: Monitor Deployment
Azure will start deploying your virtual machine based on the provided configuration. You can monitor the progress in the Azure Portal by navigating to the resource group or the virtual machine itself. The deployment process may take a few minutes to complete.

Step 6: Access and Manage Virtual Machine
Once the deployment is successful, you can access and manage your virtual machine. You can use the Azure Portal's built-in features, such as Connect, to establish a remote desktop or SSH connection to the virtual machine. You can also install additional software, configure networking, and manage the virtual machine's resources based on your requirements.

Remember to manage and monitor your virtual machine's resources, security, and backups regularly to ensure optimal performance, availability, and data protection.

Disclaimer : This step-by-step process provides a general overview of the virtual machine deployment in Azure. The specific steps and configuration options may vary based on your requirements, Azure subscription type, and the latest updates from Microsoft. It's always recommended to refer to the Azure documentation for detailed and up-to-date instructions.
