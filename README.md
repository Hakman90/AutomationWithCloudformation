<h1>Automation With Cloudformation</h1>

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />

<h2>Project walk-through:</h2>

<p align="center">
Create Template: <br/>
<img src="https://imgur.com/Qs3KDoB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Create Stack: <br/>
<img src="https://imgur.com/dw0gFxv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Upload Cloudformation Template:  <br/>
<img src="https://imgur.com/8Cqi6kP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Name Stack: <br/>
<img src="https://imgur.com/lrHcftg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm Role Access and submit Stack:  <br/>
<img src="https://imgur.com/SFCsYK4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Stack Creation Complete:  <br/>
<img src="https://imgur.com/9bCOTIA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
