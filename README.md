<h1>Azure Sentinel Homelab</h1>

<h2>Description</h2>
This project uses a custom PowerShell script to extract metadata from the Windows Event Viewer and determine the geolocation data, which is then sent to a third-party API. It also sets up a Log Analytics Workspace in Azure to collect custom logs that include geographic data, and links this data to Azure Sentinel using Custom Fields. Finally, it configures an Azure Sentinel workbook to display information about global RDP brute force attacks on a world map, based on the physical location and scale of the attacks.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell: Retrieve logs of failed RDP login attempts from the Windows Event Viewer.</b> 


<h2>Utilities Used </h2>

- <b>ipgeolocation.io: IP Address to Geolocation API</b> 

<h2>World map of incoming attacks after 18 hours </h2>

<p align="center">
<br/>
<img src="https://i.imgur.com/ueyjzYA.jpg" height="80%" width="80%" alt="Map"/>
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
