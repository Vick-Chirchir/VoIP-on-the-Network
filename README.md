
<h1>VTP-Port Security</h1>

<!-- ### [Kaltura Capture Recording](https://mediaspace.minnstate.edu/media/Kaltura+Capture+recording+-+April+26th+2025%2C+11%3A11%3A10+pm/1_sp0j5ef9) -->

<h2>Description</h2>
This project demonstrates the implementation of a VoIP (Voice over IP) network using Cisco IP Phones and a centralised DHCP server for dynamic IP address assignment. The simulation was built in Cisco Packet Tracer and models a basic small office environment with voice and data communication over a single infrastructure.
This project showcases how voice and data networks can coexist efficiently in a modern enterprise setting, highlighting my understanding of VoIP architecture and DHCP services in Cisco environments.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Cisco IOS CLI commands</b> 

<h2>Environments Used </h2>

- <b>Cisco Packet Tracer</b> (8.2)

<h2>Program walk-through:</h2>

<p align="center">
Network Design: <br/>
<img src="https://i.imgur.com/WrywgSZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Switch Switchport Config (voice and data vlans):  <br/>
<img src="https://i.imgur.com/KM1jzOi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Switch Trunk Config: <br/>
<img src="https://i.imgur.com/7ft9rDM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP Server Pool Config:  <br/>
<img src="https://i.imgur.com/Jb0naBo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Router Configuration (Router on a Stick) using (ip helper-address:  <br/>
<img src="https://i.imgur.com/zpn4ucK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify Communication between VLAN 10,20,30:  <br/>
<img src="https://i.imgur.com/kzTsRjw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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

