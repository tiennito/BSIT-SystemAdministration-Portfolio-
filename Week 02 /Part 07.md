# *PART 7 — INFRASTRUCTURE RECOMMENDATIONS*

## Internet Provider

For a Manila-based startup, I recommend a business-grade fiber connection from PLDT Enterprise as the primary connection, subject to actual service availability at the office location.

PLDT Enterprise currently provides business fiber products targeted at MSMEs and enterprise customers.

Recommended primary connection:

300–500 Mbps Business Fiber

A business connection is preferable to depending entirely on residential internet because company operations rely on software repositories, cloud services, online meetings, remote access and customer communications.

A second connection from another provider such as Converge Business should eventually be installed for redundancy if available in the building. Converge currently provides fiber connectivity specifically for business customers.

Using different providers decreases the possibility that a single ISP outage completely disconnects company operations.

## Server Specification

Recommended server:

Processor: 8-core or higher enterprise-class Intel Xeon or AMD EPYC processor

Memory: 64 GB ECC RAM, expandable to at least 128 GB

System Storage: 2 × 1.92 TB enterprise SSD in RAID 1

Network: Dual Gigabit or 10 Gigabit Ethernet interfaces

Power Supply: Redundant power supplies where budget permits

Operating System: Ubuntu Server 26.04 LTS

Virtualization: Virtual machines and/or containers when necessary

The server should initially host internal development services, monitoring systems, internal applications and other centralized services. Virtualization allows several services to run separately without purchasing an individual physical server for every workload.

## Backup Strategy

3 copies of important data

2 different storage types

1 copy stored off-site

Proposed design:

Production Data -> Local NAS with automatic snapshots -> Encrypted External Backup Drive -> Encrypted Off-Site/Cloud Backup

The NAS should perform frequent local snapshots of critical company data.

Two external drives should be rotated so that one drive can remain disconnected from the network.

Important company data should additionally be encrypted and backed up to an approved cloud backup service.

Backup jobs should be monitored and test restorations should be performed regularly. A backup should not be considered successful until the company confirms that data can actually be restored.

## Security Recommendations

The company should implement security from the beginning rather than adding protection only after an incident occurs.

Recommended controls include:

Next-generation firewall
VLAN network segmentation
Multi-factor authentication
Least-privilege user access
Separate administrator accounts
Automatic operating-system and software updates
Microsoft Defender endpoint protection
BitLocker disk encryption for company laptops
Encrypted backups
Secure corporate Wi-Fi
Completely separated guest Wi-Fi
Firewall logging
Centralized monitoring
Employee cybersecurity awareness training
Device inventory
Documented incident-response procedures
Regular vulnerability and patch reviews
Account removal immediately after employee separation

CISA recommends core small-business practices that include enabling MFA, applying software updates and patches, and performing and testing backups.

## Antivirus

All Windows 11 workstations should have Microsoft Defender Antivirus enabled and properly updated.

For stronger centralized administration, management should consider upgrading to Microsoft Defender for Business or another centrally managed Endpoint Detection and Response solution as the company grows.

Employees should not be permitted to disable endpoint protection without IT authorization.

## Password Policy

Recommended organizational policy:

Minimum password/passphrase length: 15 characters

Users should be encouraged to use long, memorable passphrases rather than simple short passwords.

The company should:

- Block commonly used and compromised passwords
- Enable MFA for company services
- Require MFA for every administrator account
- Use a company-approved password manager
- Never allow employees to share passwords
- Never store passwords in plain text
- Change passwords immediately when compromise is suspected
- Protect password-reset procedures with identity verification

Current NIST guidance requires at least 15 characters when passwords are the only authentication factor and advises against mandatory periodic password changes unless there is evidence of compromise. It also advises against arbitrary composition rules such as forcing particular combinations of character types.

Therefore, SBH Startup Solutions should prioritize long passphrases, MFA and compromised-password detection rather than relying only on complicated password patterns.

## Expansion Plan

The infrastructure should be designed for the company to grow from 20 employees to approximately 40–50 employees without completely rebuilding the network.

The 48-port managed switch provides spare network capacity.

The server should support memory and storage upgrades.

The network rack should have unused rack space.

Additional access points can be installed if wireless demand increases.

The VLAN architecture can support additional departments.

The NAS should support larger hard drives.

Cloud infrastructure can gradually host applications that no longer need to remain on-premises.

A second switch can eventually be installed and connected to the existing core network.

A secondary internet provider should be introduced when availability requirements increase.

This approach allows the organization to expand gradually rather than replacing the entire infrastructure every time the company hires new employees.





