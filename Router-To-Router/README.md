Router-to-Router Communication (Static Point-to-Point Link)

Created two independent LANs (Each with 3 separate end devices), connected them via a direct router-to-router link (simulated WAN), configure static routes, and verify end-to-end connectivity with ICMP.
Used a Serial DCE connection for the router link and verified communication and configuration.

Devices Used: 2 Routers, 2 Switches, 6 end devices

IP Table for each Device:

(Shared Default Gateway: 192.168.10.1)
PC0 - (IP ADDRESS: 192.169.10.10 Subnet: 255.255.255.0)
PC1 - (IP ADDRESS: 192.169.10.11 Subnet: 255.255.255.0)
PC2 - (IP ADDRESS: 192.169.10.12 Subnet: 255.255.255.0)

(Shared Default Gateway: 192.168.11.1)
PC3 - (IP ADDRESS: 192.169.11.10 Subnet: 255.255.255.0)
PC4 - (IP ADDRESS: 192.169.11.11 Subnet: 255.255.255.0)
PC5 - (IP ADDRESS: 192.169.11.12 Subnet: 255.255.255.0)

Connection between Routers:
Router0: FastEthernet 0/0 (192.168.10.1) Serial 0/2/0 (192.168.30.2)
Router1: FastEthernet 0/0 (192.168.11.1) Serial 0/2/0 (192.168.40.3)
