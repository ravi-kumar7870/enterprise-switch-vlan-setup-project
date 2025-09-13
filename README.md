# Office Network VLAN Project

This project demonstrates **network segmentation using VLANs** in a company network.  
It was built using **Cisco Packet Tracer** as a learning project for networking fundamentals.

---

## Project Overview
The company network is divided into multiple departments using **VLANs** to improve security and manageability.

#Departments Covered:
- HR Department (VLAN 10)
- Accounts Department (VLAN 20)
- IT Department (VLAN 30)
- Sales Department (VLAN 40)

Each department is assigned a unique VLAN, and devices in the same VLAN can communicate with each other.

# Tools & Technologies Used
- Cisco Packet Tracer
- Cisco Switch (Layer 2)
- PCs (End Devices)
- VLAN Configuration (CLI Commands)...

# Configuration Steps (High Level)
1. Created VLANs for each department.
2. Assigned switch ports to respective VLANs.
3. Configured IP addresses for each PC in the same subnet.
4. Verified connectivity using ping..

 Sample Commands

like:-
Switch> enable
Switch# configure terminal
Switch(config)# vlan 10
Switch(config-vlan)# name HR
Switch(config-vlan)# exit
Switch(config)# interface fastEthernet 0/1
Switch(config-if)# switchport mode access
Switch(config-if)# switchport access vlan 4
