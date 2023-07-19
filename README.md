<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a Virtual Machine In Azure
- Install Web Platform Installer
- Install Osticket
- Install HeidiSQL


<h2>Installation Steps</h2>
First, create a Resource Group in Azure.
<p>
<img src="https://i.imgur.com/rJxArY9.png" height="120%" width="120%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, create a Windows 10 Virtual Machine (VM), typically with 2-4 Virtual CPUs. For username and password, it can be anything as we'll be using this info to remote in with our main computer.
</p>
<br />

<p>
<img src="https://imgur.com/zMNo9ec.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download Microsoft Remote Desktop
<p>In the Microsoft Remote Desktop app, connect to your Virtual Machine (with public IP address & username&password)
<p>
</p>
</p>
<br />

<p>
<img src="https://i.imgur.com/s3HPcvx.png" height="100%" width="100%" alt="Disk Sanitization Steps"/></p>
<p>
Now we need to install / Enable Internet Information Services(IIS) in Windows. Go to your Search Bar > Type "Control Panel" > Click "Programs" > "Turn Windows features on or off" > Scroll down to "Internet Information Services (IIS)
</p> Open common HTTP features and make sure everything is checked off. 
</p>In the World Wide Web Services tab, open the Application Development Features folder and check off CGI.
<br />
<p>
<img src="https://imgur.com/vaOJiTT.png" height="100%" width="100%" alt="Disk Sanitization Steps"/></p>
