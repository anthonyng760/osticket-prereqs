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
<p>
 Install PHP Manager for IIS.
<p> Install the Rewrite module.
<p> Install the PHP 738 file, then create a directory "C:PHP", then unzip the contents in a c:PHP.
<p>
<img src="https://imgur.com/Ws9SLJt.png" height="100%" width="100%" alt="Disk Sanitization Steps"/></p>
</p>
Install VC redist file
<p> Install MySQL - typical setup > Launch configuration Wizard (after install) > standard configuration option > set your own password.
<p>
<img src="https://imgur.com/Q6KJ9Lz.png" height="100%" width="100%" alt="Disk Sanitization Steps"/></p>
<P>
Install Osticket v1.15.8
<p> Download osTicket (download from within lab files: link).
<p> Extract and copy the “upload” folder INTO c:\inetpub\wwwroot
<p> Rename the "upload" folder to "Osticket"
<img src="https://imgur.com/knuiOpR.png" height="100%" width="100%" alt="Disk Sanitization Steps"/></p>
