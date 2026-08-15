# *Week 02 — Enterprise IT Infrastructure Plan*

## Project Overview

This project presents the proposed IT infrastructure of ABC Startup Solutions, a newly established software development company located in Laguna, Philippines.

The organization has 20 employees distributed across Information Technology, Human Resources, Finance, and Sales. Because the company initially has no computers, servers, network infrastructure, internet infrastructure, or security policies, this project designs the company's IT environment from the ground up.

The infrastructure plan covers hardware, software, networking, security, server infrastructure, backups, network topology, System Administration roles, future expansion, and infrastructure recommendations.

View the Complete Enterprise Infrastructure Plan

## Learning Objectives

Through this project, I aim to:

- Understand how business requirements affect infrastructure design.
- Design an IT infrastructure for a small organization.
- Identify appropriate enterprise hardware and software.
- Understand basic network architecture and segmentation.
- Create a professional enterprise network topology.
- Apply basic cybersecurity and backup principles.
- Understand different System Administration career roles.
- Develop infrastructure documentation skills.
- Design infrastructure that can support future organizational growth.

## Company Scenario

Company: SBH Startup Solutions

Industry: Software Development and IT Services

Location: 2nd Floor, EDSA Central Square, Shaw Boulevard, corner Sto. Cristo Street, Greenfield District, Mandaluyong City, 1552, Philippines

Number of Employees: 20

Department	Employees: 

- Information Technology: 5
- Human Resources: 4
- Finance: 5
- Sales: 6

### Total: 	20

The company initially has no IT equipment or infrastructure. The objective of this project is to design a secure, reliable, manageable, and scalable IT environment before equipment is purchased.

## Hardware Inventory Summary

Hardware	Quantity:
- Desktop Computers:	14
- Laptops:	6
- Enterprise Server:	1
- 48-Port Managed Switch:	1
- Router:	1
- Firewall:	1
- Network Printers:	2
- Wireless Access Points:	2
- NAS Storage:	1
- External Backup Drives:	2
- Monitors:	20
- UPS Units:	6

The combination of 14 desktops and six laptops provides one primary workstation for every employee while allowing IT and Sales personnel to work more flexibly.

## Software Inventory Summary

The planned software environment includes:

| Software | Main Purpose |
|---|---|
| Windows 11 Pro | Employee workstation operating system |
| Ubuntu Server 26.04 LTS | Server operating system |
| Microsoft Office / Microsoft 365 | Productivity |
| Visual Studio Code | Software development |
| Git | Source control |
| GitHub Desktop | Git repository management |
| VirtualBox | Virtualization and testing |
| Google Chrome | Web browsing and development testing |
| Microsoft Defender | Endpoint security |
| AnyDesk | Remote support |
| 7-Zip | File compression |

## Enterprise Network Diagram

The network uses a centralized managed switch and logical VLAN segmentation for different departments and services.


Network Flow

Internet → ISP Modem/ONT → Router → Firewall → Managed Core Switch → Departments/Servers/Access Points

The network is separated into VLANs for:

- IT
- Human Resources
- Finance
- Sales
- Servers
- Printers
- Corporate Wi-Fi
- Guest Wi-Fi

## Technologies Used
- Windows 11 Pro
- Ubuntu Server
- Microsoft 365
- Visual Studio Code
- Git
- GitHub
- VirtualBox
- CAT6 Ethernet
- VLANs
- Wi-Fi
- TCP/IP
- NAS Storage
- Microsoft Defender
- Draw.io 
- Markdown

## Infrastructure Security

The proposed security architecture includes:

- Next-generation firewall
- VLAN network segmentation
- Multi-factor authentication
- Microsoft Defender
- Least-privilege access
- Secure Wi-Fi
- Separate guest network
- Data encryption
- 3-2-1 backup strategy
- Regular patch management
- Employee cybersecurity awareness
- Strong password/passphrase policies
  
## Challenges Encountered

One challenge was determining the correct number and type of computers required for each department. Instead of assigning the same hardware to every employee, I considered how employees actually perform their jobs.

Another challenge was designing the network topology. The network needed to support 20 employees while maintaining security between departments and allowing future expansion.

The third challenge was designing a backup and security strategy. I learned that having a NAS or antivirus alone is not enough. Multiple security layers, offline or off-site backups, network segmentation, authentication controls, and documented policies are necessary to properly protect organizational information.

## Reflection

Completing this Enterprise IT Infrastructure Plan helped me understand that System Administration is not only about installing an operating system, configuring a server, or troubleshooting computers. One of the most important responsibilities of a System Administrator happens before the actual installation begins: planning. Through this project, I learned how hardware, software, networking, security, backup systems, employees, and business requirements must all be considered when designing an IT environment.

One of the most challenging parts of the project was designing the network infrastructure. It was necessary to determine how computers from different departments would connect while also considering servers, printers, wireless devices, security, and future expansion. Creating separate VLANs for IT, Human Resources, Finance, Sales, servers, printers, corporate Wi-Fi, and guest Wi-Fi helped me understand how network segmentation can improve organization and security. I also learned that purchasing only the exact number of ports or devices currently required may create problems when the company expands.

Planning before deployment is important because infrastructure mistakes can become expensive once equipment has already been purchased and installed. For example, purchasing an undersized network switch could require an early replacement, while failing to create a proper backup system could result in permanent data loss. Security must also be planned from the beginning because a company that stores confidential employee, financial, business, and customer information cannot rely on default configurations alone.

The project also helped me understand how different System Administration roles depend on one another. Helpdesk personnel support employees, Network Administrators maintain connectivity, Linux System Administrators manage servers, and Cloud Administrators manage online infrastructure. Even though their responsibilities are different, they must communicate and work together to keep company services available.

This activity will help me become a better System Administrator because it trained me to think beyond individual computers and consider the organization as one complete system. Instead of immediately installing equipment, I learned to evaluate requirements, identify risks, design solutions, prepare for growth, and document my decisions. These skills are important because a professional System Administrator must build infrastructure that is not only functional today but also secure, manageable, reliable, and scalable in the future.

