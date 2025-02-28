<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://youtu.be/TYBc_WmoGFE)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create Virtual Machines
- Create Network Security Group
- Inspect Traffic
- Configure Inbound/Outbound Rules

<h2>Actions and Observations</h2>

<p>
In configuring a Network Security Group (NSG) and inspecting traffic between Azure Virtual Machines (VMs), the first action is to create and deploy the VMs, followed by setting up an NSG to manage network traffic. The NSG is associated with either the VM’s network interface or subnet, and specific inbound and outbound traffic rules are defined to control communication. To inspect traffic, Azure Network Watcher is enabled, allowing the use of tools like Traffic Analytics and packet capture. These tools help monitor and analyze traffic flow between VMs.
</p>
<br />

![Screenshot 2025-02-12 at 4 03 01 PM](https://github.com/user-attachments/assets/42c6a7e5-41ec-4b82-9ffb-6818f878b902)

![Screenshot 2025-02-12 at 4 13 49 PM](https://github.com/user-attachments/assets/89ccabdf-7c85-4efe-9955-eef9f170a8e4)

![Screenshot 2025-02-12 at 4 25 01 PM](https://github.com/user-attachments/assets/00e2afe4-9d8b-4770-a381-c417f876db30)

![Screenshot 2025-02-28 at 8 20 51 AM](https://github.com/user-attachments/assets/0aa66b08-e005-4661-a338-6ca534af4989)

![Screenshot 2025-02-28 at 8 21 50 AM](https://github.com/user-attachments/assets/6907ec32-9292-4789-ac55-5633cc1dfc5e)

![Screenshot 2025-02-28 at 8 26 31 AM](https://github.com/user-attachments/assets/e52d1047-f7ef-42e6-bfa5-3d5b38534847)

![Screenshot 2025-02-28 at 8 49 39 AM](https://github.com/user-attachments/assets/adff6847-4a84-4e35-b9e6-ef3c4968cbd3)


<br />
