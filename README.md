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
<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/loM4WP7.png" height="80%" width="80%" alt="Setting two network Adapters"/>

<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
