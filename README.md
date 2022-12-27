<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

1.  Create a Resource Group </br>
2. Create a Windows 10 Virtual Machine (VM) </br>
   -  a. While creating the VM, select the previously created Resource Group </br>
   - b. While creating the VM, allow it to create a new Virtual Network (Vnet) and Subnet </br>
3. Create a Linux (Ubuntu) VM </br>
    - While create the VM, select the previously created Resource Group and Vnet </br>
4. Observe Your Virtual Network within Network Watcher</br>


<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/PKK8BK9.png" height="80%" width="80%" alt=""
</p>
<p>
Within Azure, the first thing we would do after setting up our subscription, would be to create a resource group. To do this, we can go to the search bar and type in "Resource Groups", or you can navigate through the "Azure Services" section on the Microsoft Azure Home Page and from there you can find the "Resource Groups" button and click on it. Next, we would click on "Create New Resource Group" and follow the prompts. The first page will ask you to select which subscription to use, the name of the resource group you are creating, and the region. The second page asks about tags, where you can locally organize your Azure resources by categories. This isn't important for what we're doing, so we can just move along onto the next step which is to "review and create" our resource group. If the resource group passes validation, all that's left to do is wait for the group to finish creating after hitting "create". 
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
