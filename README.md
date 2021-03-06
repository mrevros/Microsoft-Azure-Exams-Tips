# Microsoft-Azure-Exams-Tips

These lists are composed taking twitter posts with study tips from [@techtrainertim](https://twitter.com/techtrainertim) and adding links from docs.com on the the specific tip.
Thanks [@techtrainertim](https://twitter.com/techtrainertim) for these posts, they are very useful studying for the AZ certifications.

If you find a link being outdated or another link that would be better suited, please feel free to do a pull request.

Also If you find this useful please share it and let me know on twitter if it was useful or not [@Michael_Jonsson](https://twitter.com/Michael_Jonsson)

Happy Studying.

- [AZ-100](AZ-100Links.md) Study tips for AZ 100
- [AZ-101](AZ-101Links.md) Study tips for AZ 101

To know what will be measured look below, the study tips have been grouped accordingly

- [AZ-100 Skills Measured](README.md#AZ-100-Microsoft-Azure-Infrastructure-and-Deployment)
- [AZ-101 Skills Measured](README.md#AZ-101-Microsoft-Azure-Integration-and-Security)


# **AZ-100 Microsoft Azure Infrastructure and Deployment**
Skills measured, look at the official link for potential updates [AZ-100](https://www.microsoft.com/en-us/learning/exam-AZ-100.aspx)

- **Manage Azure subscriptions and resources (15-20%)**
- **Implement and manage storage (20-25%)**
- **Deploy and manage virtual machines (VMs) (20-25%)**
- **Configure and manage virtual networks (20-25%)**
- **Manage identities (15-20%)**



## **Manage Azure subscriptions and resources (15-20%)**
May include but not limited to: Assign administrator permissions; configure cost center quotas and tagging; configure Azure subscription policies at Azure subscription level

### **Analyze resource utilization and consumption May include but not limited to**
Configure diagnostic settings on resources; create baseline for resources; create and rest alerts; analyze alerts across subscription; analyze metrics across subscription; create action groups; monitor for unused resources; monitor spend; report on spend; utilize Log Search query functions; view alerts in Log Analytics 

### **Manage resource groups**
May include but not limited to: Use Azure policies for resource groups; configure resource locks; configure resource policies; implement and set tagging on resource groups; move resources across resource groups; remove resource groups 
 
## **Implement and manage storage (20-25%)**
Create and configure storage accounts  May include but not limited to: Configure network access to the storage account; create and configure storage account; generate shared access signature; install and use Azure Storage Explorer; manage access keys; monitor activity log by using Log Analytics; implement Azure storage replication

## Import and export data to Azure  May include but not limited to: 
Create export from Azure job; create import into Azure job; Use Azure Data Box; configure and use Azure blob storage; configure Azure content delivery network (CDN) endpoints

## Configure Azure files  
May include but not limited to: Create Azure file share; create Azure File Sync service; create Azure sync group; troubleshoot Azure File Sync 

## Implement Azure backup
May include but not limited to: Configure and review backup reports; perform backup operation; 
create Recovery Services Vault; create and configure backup policy; perform a restore operation 
 
## **Deploy and manage virtual machines (VMs) (20-25%)** 
## Create and configure a VM for Windows and Linux
May include but not limited to: Configure high availability; configure monitoring, networking, storage, and virtual machine size; deploy and configure scale sets 

## Automate deployment of VMs 
May include but not limited to: Modify Azure Resource Manager (ARM) template; configure location of new VMs; configure VHD template; deploy from template; save a deployment as an ARM template; deploy Windows and Linux VMs 

## Manage Azure VM
May include but not limited to: Add data discs; add network interfaces; automate configuration management by using PowerShell Desired State Configuration (DSC) and VM Agent by using custom script extensions; manage VM sizes; move VMs from one resource group to another; redeploy VMs 

## Manage VM backups
May include but not limited to: Configure VM backup; define backup policies; implement backup policies; perform VM restore 
 
## **Configure and manage virtual networks (20-25%)** 
## Create connectivity between virtual networks
May include but not limited to: Create and configure VNET peering; create and configure VNET to VNET; verify virtual network connectivity; create virtual network gateway 

- ## Implement and manage virtual networking
May include but not limited to: Configure private and public IP addresses, network routes, network interface, subnets, and virtual network 

- ## Configure name resolution
May include but not limited to: Configure Azure DNS; configure custom DNS settings; configure private and public DNS zones 

- ## Create and configure a Network Security Group (NSG)  
May include but not limited to: Create security rules; associate NSG to a subnet or network interface; identify required ports; evaluate effective security rules 

## **Manage identities (15-20%)** 
- ## Manage Azure Active Directory (AD) 
May include but not limited to: Add custom domains; configure Azure AD Identity Protection, Azure AD Join, and Enterprise State Roaming; configure self-service password reset; implement conditional access policies; manage multiple directories; perform an access review 
 
- ## Manage Azure AD objects (users, groups, and devices)
May include but not limited to: Create users and groups; manage user and group properties; manage device settings; perform bulk user updates 

- ## Implement and manage hybrid identities
May include but not limited to: Install and configure Azure AD Connect; configure federation and single sign-on; manage Azure AD Connect; manage password sync and writeback 





# **AZ-101 Microsoft Azure Integration and Security**
Skills measured, look at the official link for potential updates [AZ-101](https://www.microsoft.com/en-us/learning/exam-AZ-101.aspx)

- **Evaluate and perform server migration to Azure (15-20%)**
- **Implement and manage application services (20-25%)**
- **Implement advanced virtual networking (30-35%)**
- **Secure identities (25-30%)**

## **Evaluate and perform server migration to Azure (15-20%)**

- ## Evaluate migration scenarios by using Azure Migrate 
May include but is not limited to: Discover and assess environment, identify workloads that can and cannot be deployed, identify ports to open, identify changes to network, identify if target environment is supported, setup domain accounts and credentials 

- ## Migrate servers to Azure
May include but is not limited to: Migrate by using Azure Site Recovery (ASR), migate using P2V, configure storage, create a recovery services vault, prepare source and target environments, backup and restore data, deploy Azure Site Recovery (ASR) agent, prepare virtual networ

## **Implement and manage application services (20-25%)**
- ## Configure serverless computing
May include but is not limited to: Create and manage objects,  manage an Logic App Resource, manage Azure Function app settings, manage Event Grid, manage Service Bus 

- ## Manage App Service Plan
May include but is not limited to: configure application for scaling, enable monitoring and diagnostics, configure App Service Plans 

- ## Manage App services 
May include but is not limited to: Assign SSL Certificates, configure application settings, configure deployment slots, configure CDN integration, manage App service protection, manage roles for an App service, create and manage App Service Environment 

## **Implement advanced virtual networking (30-35%)**
- ## Implement application load balancing   
May include but is not limited to: Configure application gateway, configure load balancing rules, implement front end IP configurations, troubleshoot load balancing  

- ## Implement Azure load balancer  
May include but is not limited to: Configure internal load balancer, configure load balancing rules, configure public load balancer, troubleshoot load balancing 
- ## Monitor and troubleshoot networking  
May include but is not limited to: Monitor on-premises connectivity, use Network resource monitoring, use Network Watcher, troubleshoot external networking, troubleshoot virtual network connectivity 
 
- ## Integrate on premises network with Azure virtual network  
May include but is not limited to: Create and configure Azure VPN Gateway, create and configure site to site VPN, configure Express Route, verify on premises connectivity, troubleshoot on premises connectivity with Azure 


## **Secure identities (25-30%)**
- ## Implement multi-factor authentication (MFA)  
May include but is not limited to: Configure user accounts for MFA, enable MFA by using bulk update, configure fraud alerts, configure bypass options, configure Trusted IPs, configure verification methods 

- ## Manage role based access control (RBAC)  
May include but is not limited to: Create a custom role, configure access to Azure resources by assigning roles, configure management access to Azure, troubleshoot RBAC, implement RBAC policies, assign RBAC Roles 

- ## Implement Azure AD Privileged Identity Management  
May include but is not limited to: Activate a PIM role, configure Just-in-time access, configure permanent access, configure PIM management access, configure time-bound access, create a Delegated Approver account, enable PIM, process pending approval requests 