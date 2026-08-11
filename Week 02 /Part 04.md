# *PART 4 — ENTERPRISE NETWORK INVENTORY*

## 4.1 Network Equipment Inventory

| Asset ID | Equipment | Qty. | Recommended Specification | Purpose |
|---|---|---:|---|---|
| NET-001 | ISP Modem / Fiber ONT | 1 | ISP-provided | Terminates the fiber internet connection |
| NET-002 | Enterprise Router | 1 | Gigabit or multi-gigabit WAN/LAN | Routes internal and external network traffic |
| NET-003 | Next-Generation Firewall | 1 | VLAN, VPN, IDS/IPS capable | Secures and filters network traffic |
| NET-004 | Managed Network Switch | 1 | 48-port Gigabit / 2.5GbE PoE+ | Provides primary wired network distribution |
| NET-005–006 | Wireless Access Points | 2 | Wi-Fi 6 or newer, VLAN capable | Provides corporate and guest wireless access |
| NET-007 | CAT6 Patch Panel | 1 | 48-port | Organizes structured network cabling |
| NET-008 | CAT6 UTP Cable | 2 boxes | 305 meters per box | Provides structured office network cabling |
| NET-009 | RJ45 Connectors | 100 | CAT6 compatible | Supports cable termination and maintenance |
| NET-010 | Network Rack | 1 | 12U–18U | Houses network and server-room equipment |
| NET-011 | CAT6 Patch Cords | 40 | Various lengths | Connects patch panels, switches, and devices |
| NET-012 | CAT6 Keystone Jacks | 30 | CAT6 compatible | Provides network connections at wall outlets |
| NET-013 | Cable Management Panels | 2 | 1U rack mount | Keeps rack cabling organized and manageable |

## 4.2 Network Segmentation

| VLAN | Department / Purpose | Suggested Subnet |
|---|---|---|
| VLAN 10 | Information Technology | 192.168.10.0/24 |
| VLAN 20 | Human Resources | 192.168.20.0/24 |
| VLAN 30 | Finance | 192.168.30.0/24 |
| VLAN 40 | Sales | 192.168.40.0/24 |
| VLAN 50 | Servers and NAS | 192.168.50.0/24 |
| VLAN 60 | Printers / Infrastructure | 192.168.60.0/24 |
| VLAN 70 | Corporate Wi-Fi | 192.168.70.0/24 |
| VLAN 80 | Guest Wi-Fi | 192.168.80.0/24 |
---
**Note:** Some details presented in this file were developed with the assistance of web-based research and AI tools to improve accuracy, clarity, and completeness.
