# OsTicket Install
<i>Prerequisites For OsTicket</i>
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
<i>I'm installing OsTicket and its pre-requisites.</i><br />


<h2>Video Demonstration</h2>

- ### [YouTube: OsTicket Installation](https://youtu.be/c0NefzDP_Zw)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- PHP Manager for IIS
- HeidiSQL
- MySQL
- Microsoft VC Distributable (x86)
- IIS Rewrite Module 2
- osTicket

<h2>Installation Steps</h2>

<p>
  <img src="https://i.imgur.com/h34tgJA.png" height="80%" width="80%" alt="IIS/CGI Install"/>
(https://imgur.com/a/tpfnNMX)
</p>
<p>
<i>First, We Need To Open Up Control Panel And Navigate To 'Enable Programs' And Click IIS>FTP>ADPF>CGI (Click Them Twice To Make Sure They All Download), While That's Installing We Can Create A Directory For PHP (C:\PHP).
</i></p>
<br />

<p>
<img src="https://i.imgur.com/reXhCUb.png" height="80%" width="80%" alt="MySQL/VC Redistributable/PHP Manager"/>
  (https://imgur.com/gallery/php-mysql-install-configuration-zPzqcBV)
</p>
<p>
Next, We Have To Install And Configure MySQL And Bring The Zipped (php-7.3.8-nts-Win32-VC13-x86) File To The PHP Directory, Unzip It And Register (php-cgi.exe) To PHP Manager. Install Rewrite Module II And The VC Redistributable As Well.
</p>
<br />

<p>
<img src="https://i.imgur.com/H8Tbd1w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  (https://imgur.com/gallery/Cl3zG8R)
  (https://imgur.com/gallery/ltfvLGE)
</p>
<p>
Configure MySQL. And Then, Configure osTicket. Finally, We Install HeidiSQL Set The Password And Username To "root", Create A New Database Renamed To "osTicket", the same as the file we renamed in (\wwwroot), And Fill Out The Fields In The OsTicker Browser And Click 'Install'.
</p>
<br />
