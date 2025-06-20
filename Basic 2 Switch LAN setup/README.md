Basic LAN Setup (using Router, 2 Switches and multiple End devices)

Created a two separate Local Area Network (LAN) each connected to a single router via 2 switches and multiple end devices connected to those switches. 
I've assigned Static IP addresses to devices within each LANs (containing 3 end devices). Configured each router interface to serve as the gateway for individual LAN.
and tested conectivity by sending simple PDU (ICMP) packets between devices to verify configuration and communication.

Devices Used:
1 Router (SR433)
2 Switches (960-24T)
4 End Devices (4 PCs + 1 Printer + 1 Laptop)

IP Table for each Device:

(SWITCH2) (Router Interface: GigabitEthernet0/0/0)
Laptop0 - (IP ADDRESS - 192.168.1.12) (Default Gateway -  192.168.1.1)
PC3 - (IP ADDRESS - 192.168.1.11) (Default Gateway -  192.168.1.1)
PC4 - (IP ADDRESS - 192.168.1.10) (Default Gateway -  192.168.1.1)

(SWITCH3) (Router Interface: GigabitEthernet0/0/1)
PC5 - (IP ADDRESS - 192.168.2.10) (Default Gateway -  192.168.2.1)
PC6 - (IP ADDRESS - 192.168.2.11) (Default Gateway -  192.168.2.1)
Printer0 - (IP ADDRESS - 192.168.2.23) (Default Gateway -  192.168.2.1)

Subnet Mask: 255.255.255.0
