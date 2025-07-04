<p align="center">

  ![Screenshot 2025-06-29 073744](https://github.com/user-attachments/assets/779ba374-7c54-48d6-87b1-67eaa8d150dc)

</p>

<h1>Creating An Azure Virtual Machine</h1>
This is an easy way to create Virtual Machines using Azure.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)


<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>Configuration Steps</h2>

- Create a Resource Group 
- Create Windows 10 Virtual Machine  
- Create Linux (Ubuntu) Virtual Machine


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
<h2>Create Linux Virtual Machine </h2>
<p>

  ![Screenshot 2025-07-04 102020](https://github.com/user-attachments/assets/0a5ac4bf-3a12-4f50-aa80-75f85832c13f)

  

</p>
<p>
To create a Linux virtual machine you're going to repeat all the same steps you did to make the Windows Virtual Machine, except under Image you're going to select Ubuntu Server.  Now you have both of your Virtual machines created.   

  ![Screenshot 2025-07-04 102901](https://github.com/user-attachments/assets/e3b3aabb-2f0a-44e5-82a6-9faf96c1a00c)

</p>
<br />
