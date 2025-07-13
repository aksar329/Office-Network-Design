
# 🌐 Office Network Design Simulation

This project simulates a scalable and secure office network for a small organization using VLANs, static routing, and basic Layer 2/3 configurations.

## 🎯 Objectives
- Design a basic office network with multiple departments.
- Use VLANs to isolate traffic.
- Configure Inter-VLAN routing and DHCP.
- Apply basic security controls (ACLs, port security).

## 🧱 Network Topology
- 1 Router
- 2 Switches (Layer 2 or Layer 3)
- 1 Access Point (optional)
- 1 Server (DNS/DHCP/File Share)
- 5 Departments: HR, IT, Accounts, Management, Guest WiFi

## 🗂 VLAN Configuration

| Department   | VLAN ID | IP Range           |
|--------------|---------|--------------------|
| HR           | 10      | 192.168.10.0/24     |
| IT           | 20      | 192.168.20.0/24     |
| Accounts     | 30      | 192.168.30.0/24     |
| Management   | 40      | 192.168.40.0/24     |
| Guest WiFi   | 50      | 192.168.50.0/24     |

## 📜 Configuration Files

All configurations are stored in the `Configs/` folder:

- `router_config.txt`: VLAN routing & DHCP
- `switch1_config.txt`: VLAN setup and access ports
- `switch2_config.txt`: Backup/extension

## 🔐 Security Features
- Inter-VLAN Access Control Lists (ACLs)
- Port Security: max MAC addresses
- Disable unused ports

## 🖼 Diagram

> Upload your diagram here: `Network-Diagram.png`  
(You can use tools like Cisco Packet Tracer, draw.io, or GNS3)

## 📈 Future Improvements
- Add RADIUS authentication for users
- Simulate failover with a second router (HSRP/VRRP)
- Add monitoring (Nagios/Zabbix)

## 📎 Tools Used
- Cisco Packet Tracer / GNS3
- Windows Server (optional)
- CLI / IOS configurations

## 💻 Created By
Ali Aksar Hawari  
📍 Lalitpur, Nepal  
📧 aksarali490@gmail.com
