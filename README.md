# Computer Networks Project 4: VLAN Configuration

## 📌 Project Overview
This project demonstrates Virtual Local Area Network (VLAN) configuration using Cisco Packet Tracer. VLANs logically separate devices into different network groups using a managed switch.

## 🎯 Objective
To create VLANs and assign switch ports to different departments, such as IT and HR.

## 🛠️ Tools Used
- Cisco Packet Tracer
- Network Switch
- PCs
- Copper Straight-Through cables

## 🌐 VLAN Configuration

| VLAN ID | VLAN Name | Assigned Port |
|---|---|---|
| 10 | IT | Fa0/1 |
| 20 | HR | Fa1/1 |
| 1 | Default | Fa2/1 and other default ports |

## ⚙️ Steps to Implement
1. Add a switch in Cisco Packet Tracer.
2. Open the switch CLI.
3. Create VLAN 10 and name it IT.
4. Create VLAN 20 and name it HR.
5. Assign the required switch ports to their respective VLANs.
6. Run `show vlan brief` to verify the VLAN configuration.
7. Save the configuration using `copy running-config startup-config`.

## ✅ Expected Result
VLAN 10 and VLAN 20 should appear as active in the switch VLAN table, with their assigned ports listed under the correct VLANs.

## 📚 Conclusion
This project demonstrates VLAN creation, switch-port assignment, and verification of network segmentation using Cisco Packet Tracer.

## 👩‍💻 Author
Mahalakshmi S
