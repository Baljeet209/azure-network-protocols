# azure-network-protocols
<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Observe ICMP Traffic
- Observe SSH Traffic
- Observe DHCP Traffic, and DNS
- Observe RDP Traffic 

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/r4oYSgX.png">
  />
</p>
<p>
Pinged the VM2's private ip and traffic is being shown in wireshark
</p>
<br />

<p>
<img src="https://i.imgur.com/AGR9PSp.png">
  />
</p>
<p>
Logged into VM2 using SSH and observed the traffic being generated in Wireshark 
</p>
<br />

<p>
<img src="https://i.imgur.com/wJSs0uX.png">
>
</p>
<p>
Observed RDP traffic using tcp.port==3389 in wireshark.It is a constant flow of traffic because it is showing a live stream from one PC to another 
</p>
<br />
