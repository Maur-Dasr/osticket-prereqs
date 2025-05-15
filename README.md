# osticket-prereqs<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> 

<h2>List of Prerequisites</h2>

- Item 1  Enable Internet Information Services (IIS) in your Windows OS using CGI. -Open Control Panel -Select "Programs" -Select "Turn Windows Features ON/Off." -Select and Open Internet Information Services. -Open "World Wide Services" -Open "Application Developlement Features." -Select "CGI" then select "OK."
- Item 2  Install PHP Manager for IIS.
- Item 3  Install Rewrite module.
- Item 4  Create a PHP folder in your C: directory.
- Item 5  Install PHP 7.3.8.

- Item 6  Unzip PHP 7.3.8. onto your PHP folder.
- Item 7  Install VC redist.x86.exe
- Item 8  Install MySQL 5.5.62. -Typical Setup -Launch Config. Wizard after you install. -Standard configuration. -Set password to Password1 or create your own. -"Execute"
- Item 9  Register PHP from within IIS.
- Item 10 Stop and start the IIS server to update.
- 
- Item 11 Install current version of osTicket. -Extract and xopy "upload" folder to C:\inetpub\wwwroot. -Within C:\inetpub\wwwroot change "upload" to "osTicket".
- Item 12 Go to sites, Default, osTicket. -Look on the right side of the IIS screen. Click "Browse*80".
- Item 13 Open PHP Manager. -Enable: php_imap.dll, php_intl.dll, php_opcache.dll -Refresh the osTicket on your browser to see the changes.
- Item 14 Open C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php -Change ost-sampleconfig.php to ost-config.php.
- Item 15 Right click ost-config then select Properties. -Disable inheritance then remove all. -New permissions, give to "Everyone", select all.
- 
- Item 16 Set up your osTicket in your browser. Steps 18 and 19 are on the same page.
- Item 17 Open Heidi SQL -Create new session, root/Password1. -Connect to session. -Create a database called "osTicket".
- Item 18 Continue setting up osTicket in the browser. -Enter MYSQL information.
- Item 19 Select continue. -A "Congratulations" message should show on your screen.

-![image](https://github.com/user-attachments/assets/6e7cd38b-6984-479d-b320-4372240c0447)
 
<h2>Installation Steps</h2>

<p>
<img src=https://i.imgur.com/3Vb3J24.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src=https://i.imgur.com/n4X5JFL.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src=https://i.imgur.com/gXLqys6.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
</p>
<br />

<p>
<img src=https://i.imgur.com/5dwh0J0.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src=https://i.imgur.com/zc652xw.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<br /><p align="center">

</p>



<p>
<img src=https://i.imgur.com/QJKZFp0.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src=https://i.imgur.com/MIlLAsJ.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src= https://i.imgur.com/CPFVRBr.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
<p align="center">

</p>



<p>
<img src=https://i.imgur.com/X5nU69X.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src=https://i.imgur.com/ycVbFzt.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src=https://i.imgur.com/iQMMMgc.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
<p align="center">

</p>



<p>
<img src=https://i.imgur.com/6Fxdjyz.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src=https://i.imgur.com/ck8l44u.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src=https://i.imgur.com/cjZpDmY.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
<p align="center">

</p>



<p>
<img src=https://i.imgur.com/6E8lbZN.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src=https://i.imgur.com/tA0Thg4.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src=https://i.imgur.com/ueDopJG.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
<p align="center">

</p>




<h2>Installation Steps</h2>

<p>
<img src=https://i.imgur.com/IsZ8E4u.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Congrats to you at this point!
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />





