<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2) (select this in virtual machine creation)

<h2>List of Prerequisites</h2>

- Microsoft Azure Subscription (free subscription works!)
- Create a virtual machine and setup username/password
- Install/Enable IIS (Internet Information Services)
- Install MySQL
- Install WebPlatform Installer
- Install C++ redistributable
- Configure permissions and install osTicket

<h2>Installation Steps</h2>

<h3>Create a Virtual Machine</h3>
<p>
<img src="https://i.imgur.com/3kOUMl1.png" height="80%" width="80%" alt="Create Virtual Machine"/>
</p>
<p>
Go to your Azure portal and create a virtual machine. From here you can create a resource group that will contain your virtual machine. Follow the prompts and fill in all the information including the username and password. Remember to write it down so you can log in to the virtual machine once it is created. 
</p>
<br />

<h3>Enable IIS</h3>
<p>
<img src="https://i.imgur.com/wBCaslA.png" height="40%" width="40%" alt="Enable IIS"/>
</p>
<p>
Open your control panel to enable IIS and install the web server that osTicket runs on.</p>
<br />

<h3>install osTicket</h3>
<p>
<img src="https://i.imgur.com/sYUb8P3.png" height="80%" width="80%" alt="install osTicket"/>
</p>
<p>
Install osTicket and enable all extensions from the PHP manager
</p>
<br />
