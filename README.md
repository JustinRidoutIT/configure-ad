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
<img src="https://i.imgur.com/hZGiVbJ.png" height="80%" width="80%" alt=""/>
</p>
<p>
Now is time to create our first virtual machine! First, we'll go back to the search bar and type in "Virtual Machines" or you can navigate to that page from the Home Page. On the Virtual Machines page, you would click on the "create" button to create our Azure Virtual Machine. There are a few options to choose from after hitting the create button, so be sure to choose the one that best suits your needs. Next, we need to fill out the details for our virtual machine, such as the resource gorup, the name, region, operating system, etc. We'll add this virtual machine to the resource group we just created in Step 1 and choose windows 10 as the operating system. We also need to create a username and passowrd for the virtual machine; be sure to write this down so you don't forget! Much like when creating our resource group, we will be prompted to review our Virtual Machine's settings before creation can finish. Make sure everything is good to go and then hit create. We'll follow these same steps when creating our second virtual machine. When creating our second virtual machine, make sure that you selecting the same region and size.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
