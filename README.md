<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


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

- Step 1 - Create Resource Group
- Step 2 - Create Azure Virtual Machine
- Step 3 - Modify Network Security Group ( Firewall )
- Step 4 - Examine network traffic of Virtual Machine

<h2>Actions and Observations</h2>

![image](https://github.com/droderickb/azure-network-protocols/assets/138819497/0c294306-e17e-4b0f-b9bb-84b6e7c90704)


I start by creating a resource group for the virtual machines to be on. Then I created a subnet with two virtual machines to be attached. One of the virtual machine has an Os of Windows and the other is running on a Linux Server.
</p>
<br />


