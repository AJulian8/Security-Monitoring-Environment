# Security-Monitoring-Environment
<p align="center">
<img src="https://i.imgur.com/I0pUj9e.png" width="400"/> 
</p>

<h1>Splunk - Setup and Features</h1>
This tutorial outlines Splunk and how we set it up to monitor and ensure our environmnet was secure.<br />

<h2>Environments and Technologies Used</h2>

- Ubuntu (Virtual Machines/Compute)
- Remote Desktop
- Linux

<h2>Operating Systems Used </h2>

- Linux</b> (21H2)

<h2>List of Prerequisites</h2>

- Install Internet Information Services (IIS)
- Set up Domain Controller
- Create a Virtual Network and Subnet
- Create the Domain Controller VM's
- Log into the VM and edit the firewall

<h2>Active Directory Lab Steps</h2>

<p>
<img src="https://i.imgur.com/NAMjqa1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This diagram above is the easiest way to show  what I created as far as my client-1 and how it will be communicating with the domain controller. I also went in and created my rescourse groups along with a virtual network and subnet that will be shown in the next slides.
</p>
<br />

<p>
<img src="https://i.imgur.com/XOkkW9G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here we can see that I successfully created my domain controller and set it up properly allowing me to use Server Manager. In this VM is where I can make changes to the firewall and also change client-1 and change the IP to point to my domain controller.
</p>
<br />

<p>
<img src="https://i.imgur.com/X8I8Pet.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
