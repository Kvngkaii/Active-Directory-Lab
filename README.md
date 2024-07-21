<h1> - Active Directory Lab - </h1>


<h2>Description</h2>
This project involves setting up a Windows network using virtual machines running Windows 10 and Windows Server 2019. A virtual machine with Windows Server 2019 is configured as the domain controller, utilizing two network adapters for external and private network connections. NAT and routing are set up to enable internet access for the client machine via the domain controller. DHCP is configured on the domain controller to provide IP addresses to client machines. Additionally, a PowerShell script is used to create 1,000 users in Active Directory.



<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>
Domain Controller Setup:

Configured a virtual machine with Windows Server 2019 as the domain controller.
Utilized two network adapters: one for connecting to the external network and another for the private network.
Network Configuration:

Set up NAT and routing to allow the client machine on the private network to access the internet through the domain controller.
DHCP Configuration:

Configured the domain controller to run DHCP, enabling the Windows 10 client machine to obtain an IP address.
Active Directory User Creation:

Executed a PowerShell script to create 1,000 users in Active Directory.
<p align="center">
Setting up two network Adapters: <br/>
<img src="https://i.imgur.com/loM4WP7.png" height="80%" width="80%" alt="Setting two network Adapters"/>

<br />
<br />
Configuring DHCP Server :  <br/>
<img src="https://i.imgur.com/BQoQWuY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Powershell Script <br/>
<img src="https://i.imgur.com/L9fZAbm.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating Users:  <br/>
<img src="https://i.imgur.com/OYg8IgO.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirmation of users:  <br/>
<img src="https://i.imgur.com/QvZSmoQ.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
