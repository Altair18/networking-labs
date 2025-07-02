Subnet and IP Troubleshooting Lab

This lab simulates a common networking issue of a subnet mismatch and typo errors during manual configuration between multiple computers on the same LAN.

Objective of this Lab:

- Connect 3 PCs to a single switch
- Assign Static IP addresses and Subnet masks
- Simulate common IP and subnet misconfiguration
- Use basic network commands (like ping) to identify and fix the issue

NETWORK:
1 Switch
PC0, PC1, PC2

IP CONFIGURATIONS:
PC0 (IP Address - 192.168.1.10) (Subnet Mask - 255.255.255.0) (Default Gateway - 192.168.1.1)
PC1 (IP Address - 192.168.1.20) (Subnet Mask - 255.255.255.0) (Default Gateway - 192.168.1.1)
PC2 (IP Address - 192.168.2.30) (Subnet Mask - 255.255.0.0) (Default Gateway - 192.168.2.1)

*PC2 was misconfigured on purpose*

Steps taken:
- Go on PC0 terminal and ping PC1 - It worked
- Now try ping PC2 - It failed due to wrong subnet and IP address
- Go to PC2 and fix the IP to: 192.168.1.30 and subnet to: 255.255.255.0
- Ping Again PC2 from PC0 - It works!

  *ANDREJ GAZI* *Networking Fundamentals Self-Study*
