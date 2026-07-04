<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="Azura logo"/>
</p>

<h1>osTicket - Setting Up a Virtual Machine (VM) in Microsoft Azure</h1>
The objective of this project is to create and deploy a Windows Virtual Machine (VM) in Microsoft Azure. A virtual machine provides a cloud-based computing environment that can be used for hosting applications, testing software, and learning cloud technologies.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

1. Microsoft Azure Account – An active Azure account with a valid subscription.
2. Computer & Internet – A computer with a stable internet connection and a modern web browser.
3. Basic Azure Knowledge – Understanding of Virtual Machines, Resource Groups, and Virtual Networks.
4. Administrator Credentials – A secure username and password (or SSH key) to access the Virtual Machine after deployment.

<h2>Installation Steps</h2>

<p>
<img width="586" height="165" alt="Screenshot 2026-07-04 at 2 55 21 PM" src="https://github.com/user-attachments/assets/46ec1ce1-032b-498d-a594-a31eb718dcd6" />

<p>
Step 1: Sign in to Azure and Create a Virtual Machine

1. Sign in to the Microsoft Azure Portal.
2. Click Create a resource.
3. Search for the Virtual Machine and select it.
4. Click Create.
<br />

<p>
<img width="577" height="174" alt="Screenshot 2026-07-04 at 2 55 35 PM" src="https://github.com/user-attachments/assets/09d37418-e8c3-4c00-9335-76cc622c32f7" />

</p>
<p>
Step 2: Configure the Virtual Machine

1. Select your Subscription.
2. Create or choose a Resource Group.
3. Enter a Virtual Machine Name.
4. Choose the Region (e.g., East US).
5. Select the Operating System Image (Windows Server 2022 or Ubuntu).
6. Choose the VM Size based on your requirements.
7. Create an Administrator Username and Password.
<br />

<p>
<img width="580" height="173" alt="Screenshot 2026-07-04 at 2 55 44 PM" src="https://github.com/user-attachments/assets/fbd8066a-f264-49c7-80ea-39e8f508631a" />

</p>
<p>
Step 3: Configure Networking

1. Create or select an existing Virtual Network (VNet).
2. Select a Subnet.
3. Create a Public IP Address.
4. Configure the Network Security Group (NSG).
5. Allow the required inbound ports:
    * RDP (3389) for Windows.
    * SSH (22) for Linux.
</p>
<br />

 <img width="580" height="161" alt="Screenshot 2026-07-04 at 2 55 56 PM" src="https://github.com/user-attachments/assets/9b806c27-4d26-476d-9d35-9bf79fe4d475" />

</p>
<p>
Step 4: Review, Create, and Connect

1. Click the Review + Create tab.
2. Azure validates all configuration settings.
3. Click Create to deploy the Virtual Machine.
4. Wait for the deployment to finish.
5. Once deployment is complete, click Go to Resource.
6. Connect to the VM using:
    * Remote Desktop (RDP) for Windows, or
    * SSH for Linux.
</p>
<br />
