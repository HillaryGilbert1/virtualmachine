<p align="center">
<img src="https://i.imgur.com/4wqxHID.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>

<h1>Microsoft Azure</h1>
This guide will show you how to set up an account on Microsoft Azure, a cloud platform and online portal that enables you to rent storage or processing space for your data. Additionally, it will provide instructions on how to create a virtual machine.

<h2>Requirements</h2>

- Computer with Internet Connection
- Credit Card (Required for free Azure credits)

<h2>Configuration Steps</h2>


<h3>Step 1: Create an Azure Account</h3>


Create an Azure account [here](https://azure.microsoft.com/en-us/free/).
- Follow the prompt to create the account 
     - A credit card will be needed to create a free account. The account includes $200 worth of credit and you will not be charged for the first 30 days.

- After creating the account you are ready to start!

<p align="center">
<img src="https://i.imgur.com/fam4xOr.png" height="70%" width="70%" alt="Azure Free Account"/> 
</p>


<h3>Step 2: Create a Resource Group</h3>

- Go to the Azure portal
- Select Create Resource Group
- You will need to name the resource group and select the region 
- Select Review + Create on the lower left
    - For this example, we will be using RG-Lab-1 for the name and (US) West3 for the region

<p align="center">
<img src="https://i.imgur.com/RNJFEvG.png" height="70%" width="70%" alt="Azure Free Account"/> <p align="center">
<img src="https://i.imgur.com/ukItl69.png" height="70%" width="70%" alt="Azure Free Account"/> <p align="center">
<img src="https://i.imgur.com/BTMJhLX.png" height="70%" width="70%" alt="Azure Free Account"/>
</p>
</p>

<h3>Step 3: Create Virtual Machine</h3>
     
- At the portal, click on virtual machine and click create. 
- Once at the create virtual machine menu, follow all the instructions. Make sure to fill out all the areas that have a red asterisk on them (resource group, name, etc.).
- Remember your username and password! Once this is all completed, your virtual machine will appear in your resource group.


<p align="center">
<img src="https://i.imgur.com/3IwUDZw.png" height="80%" width="80%" alt="Virtual Machine Menu with arrow"/>
</p>

<p align="center">
<img src="https://i.imgur.com/8JikE9A.png" height="80%" width="80%" alt="Create Virtual Machine"/>
</p>

Step 4: Connect to Virtual Machine 
- The final step to this process is accessing the virtual machine using Microsoft Remote Desktop. 
- First you will need to find the Public IP address of your virtual machine
- Select the virtual machhine we created in step and the IP address will be on the right hand side
- Copy the IP address



In order to connect to the virtual machine, first you need the public IP address. You can find this on the right hand side of this menu.

<p align="center">
<img src="https://i.imgur.com/qIKSDsI.png" height="80%" width="80%" alt="SampleVM menu with arrow and circle"/>
</p>

After downloading Microsoft Remote Desktop, launch the application and select "add PC." When prompted, enter the public IP address of the virtual machine that was created. Next, enter the username and password, and finally, click "connect" to establish the connection. 

<p align="center">



<h2>Congratulations on successfully creating your first virtual machine on Azure! To ensure that you can make use of your free $200 credits, it is important to delete ALL resource groups.<h2>
