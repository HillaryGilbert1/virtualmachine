<p align="center">
<img src="https://i.imgur.com/4wqxHID.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>

<h1>Microsoft Azure</h1>
Microsoft Azure is a cloud platform and an online portal that will let you rent space to store or process your own data. This guide will demonstrate how to create an Azure account and create a virtual machine.

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
<img src="https://i.imgur.com/XHEph5v.png" height="70%" width="70%" alt="Azure Free Account"/> <p align="center">
<img src="https://i.imgur.com/Nr5RDyp.png" height="70%" width="70%" alt="Azure Free Account"/> <p align="center">
<img src="https://i.imgur.com/WabrIx6.png" height="70%" width="70%" alt="Azure Free Account"/>
</p>
</p>

<h3>Step 3: Create Virtual Machine</h3>
     
- Go to search bar and search "virtual machine"
- Select create, then select Azure virtual machine
- You will need to select the resource group, the region, and create a name for the virtual machine
    - For the example we will name the virtual machine virtualmachine
    - Use same resource group and region as step 2/3


<p align="center">
<img src="https://i.imgur.com/XC53r2o.png" height="80%" width="80%" alt="Virtual Machine Menu with arrow"/>
</p>

<p align="center">
<img src="https://i.imgur.com/a0OIYax.png" height="80%" width="80%" alt="Create Virtual Machine"/>
</p>

<h3>Step 4: Connect to virtual machine using Microsoft Remote Desktop on macOS</h3>
The final step to this process is accessing the virtual machine using Microsoft Remote Desktop. If you are using macOS (like me), you have to download the application in the App Store. 

<p align="center">
<img src="https://i.imgur.com/pp1yQTE.png" height="80%" width="80%" alt="Microsoft Remote Desktop"/>
</p>

In order to connect to the virtual machine, first you need the public IP address. You can find this on the right hand side of this menu.

<p align="center">
<img src="https://i.imgur.com/gT6F62H.png" height="80%" width="80%" alt="SampleVM menu with arrow and circle"/>
</p>

Once Microsoft Remote Desktop is downloaded, open the application. Click add PC. Copy and paste the public IP address of the virtual machine that was created when prompted. Type in the username and password the click connect. 

<p align="center">
<img src="https://i.imgur.com/WcRdlX3.png" height="80%" width="80%" alt="Microsoft Remote Desktop 1"/>
</p>

<p align="center">
<img src="https://i.imgur.com/4IKJFik.png" height="80%" width="80%" alt="Windows 10 VM"/>
</p>

Congratulations! You have created your first virtual machine within Azure. If you want to save your free $200 credits, make sure you delete ALL resource groups because most of Azure services are pay as you go (unless otherwise stated). Thank you!
