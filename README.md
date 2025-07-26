<h1> Troubleshooting Network Issue</h1>

<h2>Description</h2>
This project demonstrates the complete process of configuring a virtual home network using GNS3 and OpenWRT, from building the network topology and connecting devices to managing router settings and verifying internet access. It highlights practical networking skills such as assigning interfaces, identifying DHCP issues, and interpreting IP configuration data within a Linux environment, as well as using browser-based tools to configure router settings and test external connectivity. The task reinforces essential IT technician competencies in network setup, basic troubleshooting, and foundational router management.
<br />


<h2>Lab walk-through:</h2>

<p align="center">
<b>1. Built Network Topology in GNS3:</b>
Created a virtual network environment using GNS3 with PC1, PC2, a router, and internet cloud node to simulate a basic home network.
 <br/>
<img src="https://i.imgur.com/AOug849.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>2. Connected PC1 to the Router:</b>
Linked PC1 to the router’s LAN interface using the "Add a link" tool to establish network communication between devices.
  <br/>
<img src="https://i.imgur.com/EHsBqFk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>3. Started PC1 and Opened Console:</b>
Powered on the virtual PC1 node and opened its console to launch the Linux desktop environment. <br/>
<img src="https://i.imgur.com/Q1awYdK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>4. Diagnosed Adapter Configuration Issue:</b>
Identified a failed network adapter on PC1 and determined the root cause was the absence of a DHCP server on the router.
<br/>
<img src="https://i.imgur.com/eqsLfl4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>5. Accessed Router Interface in Browser:</b>
Used the PC1 Firefox browser to navigate to the OpenWRT router’s default IP and accessed the web interface for configuration.
<br/>
<img src="https://i.imgur.com/1QNQ3fs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>6. Set Router Admin Password:</b>
Configured a secure administrator password through OpenWRT’s web interface under the System > Administration settings.
<br/>
<img src="https://i.imgur.com/aguPhic.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>7. Verified Network Interfaces:</b>
Inspected LAN and WAN interface settings in OpenWRT to confirm the router’s internal configuration and packet traffic status.
<br/>
<img src="https://i.imgur.com/BWNBORn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>8. Connected Router to Internet Node:</b>
Connected the router’s WAN port to the internet cloud node and confirmed successful DHCP lease with a public IPv4 address.
<br/>
<img src="https://i.imgur.com/VhjRUH0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>9. Verified Internet Access on PC1:</b>
Used the browser on PC1 to navigate to NeverSSL.com, confirming active internet connectivity through the configured router.  
<br/>
<img src="https://i.imgur.com/XeRjfNy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>10. Connected and Tested PC2:</b>
Linked PC2 to the network and repeated the connectivity test to verify both PCs had access to the internet via the router.
<br/>
<img src="https://i.imgur.com/sH3WVrb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
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
