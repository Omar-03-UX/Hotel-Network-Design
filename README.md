# Hotel Network Design
<h2>Description</h2>
In this lab I will build a Hotel Network Design 
Step 1: Physical Setup

Install three routers in the IT department's server room, one for each floor.
Connect routers using serial DCE cables with network addresses 10.10.10.0/30, 10.10.10.4/30, and 10.10.10.8/30.
Step 2: VLAN Configuration

On each router, create VLANs for each department on their respective floors with assigned IP addresses:
1st Floor: Reception (VLAN 80 - 192.168.8.0/24), Store (VLAN 70 - 192.168.7.0/24), Logistics (VLAN 60 - 192.168.6.0/24)
2nd Floor: Finance (VLAN 50 - 192.168.5.0/24), HR (VLAN 40 - 192.168.4.0/24), Sales (VLAN 30 - 192.168.3.0/24)
3rd Floor: Admin (VLAN 20 - 192.168.2.0/24), IT (VLAN 10 - 192.168.1.0/24)
Step 3: OSPF Routing Configuration

Enable OSPF on each router to advertise routes between floors and ensure inter-floor communication.
Step 4: DHCP Configuration

Configure DHCP on each router for dynamic IP assignment in each VLAN.
Step 5: WiFi Network Setup

Install a switch on each floor and connect WiFi access points for laptops and phones.
Step 6: Printer Setup

Assign a printer to each department for network printing.
Step 7: SSH Configuration

Configure SSH on all routers for remote login.
Step 8: Testing with Test-PC

Connect a PC (Test-PC) to port fa0/1 on the IT department's switch.
Verify remote login to routers using SSH from Test-PC.
Step 9: Port Security on IT Department Switch

Configure port security on the IT department's switch:
Allow only Test-PC to access port fa0/1 using the sticky method for obtaining MAC addresses.
Set the violation mode to shutdown.
Step 10: Documentation

Document the network design, configurations, and any troubleshooting steps for future reference.
This concise and structured set of steps can be added to your portfolio on GitHub, providing a clear overview of your network design and implementation skills.
<br />

<h2>Languages and Utilities Used</h2>

- <b>CLI packet tracer</b> 
  
<h2>Environments Used </h2>

- <b>Cisco Packet tracer</b>

<h2>Program walk-through:</h2>
<p align="center">
<img src="https://i.imgur.com/BHOvXi9.png" height="80%" width="80%" alt="Hotel Design"/>
