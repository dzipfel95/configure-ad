<p align="center">

  ![Image](https://github.com/user-attachments/assets/0410bf4c-77ae-4ee1-8132-5eb90b36fe10)
</p>

<h1>Creating An Azure Virtual Machine</h1>
This is an easy way to create an Azure Virtual Machine.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a Resource Group 
- Create Windows 10 Virtual Machine  
- Create Linux (Ubuntu) Virtual Machine
- Login to Windows Virtual Machine

<h2>Deployment and Configuration Steps</h2>

<h2>Create A Resource Group </h2>
<p>

![Screenshot 2025-07-04 093316](https://github.com/user-attachments/assets/3111e48e-cd8f-4186-996b-646967f6320e)

<p>
In Azure, you're going to click on Resource Groups, and then click Create in the top left-hand corner of the screen.  You will choose the subscription you have and then create a resource group name, I chose RG-Network-Activities. After choosing a name, you will choose which region you would like your resource group in. I chose to put my resource group in (US) West US 2, then click review + create at the bottom then click create again.      
</p>
<br />
<h2>Create Windows 10 Virtual Machine </h2>
<p>

  ![Screenshot 2025-07-04 095249](https://github.com/user-attachments/assets/2146eb6b-76bd-4569-8c9a-7695c4f58b5b)

</p>


![Screenshot 2025-07-04 095345](https://github.com/user-attachments/assets/0e47948d-e987-40ed-a773-3fe3868f226b)


<p>
Go to Virtual Machines and click create, then select Virtual Machine. Select your Subscription  and then choose your resource group, this will the the same resource group created in the first step.  Create your Virtual machine name, and then select the same Region you selected for the Resource Group.  If you scroll down to Image you will select Windows 10 Pro, then under Size you will select something with at least 2 vcpus. Next, under Administrator account select password and then choose a username and password, and then scroll down and click the licensing agreement at the bottom as shown in the second image. Now all you have to do is select Review+Create and then select create again.           
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
