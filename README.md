# MetalBin-S.A.-Lab-infrastructure-assessment-
End-to-end black-box infrastructure assessment and remediation project covering CUPS exposure, firewall hardening, network segmentation, and pfSense rule design.

# End-to-End Infrastructure Assessment

This project documents a full black-box security assessment and remediation exercise for MetalBin S.A. The lab included exploitation of an exposed CUPS service, local privilege escalation, and the design of a hardened network architecture with pfSense firewall rules and dedicated VLAN segmentation.

## Technologies
- pfSense
- Kali Linux
- Debian / Ubuntu Linux
- Network Segmentation
- CUPS
- Firewalls
- Bash

## Scope
- External black-box penetration testing
- Service exposure validation
- Privilege escalation analysis
- Persistence assessment
- Firewall remediation and hardening

## Remediation
- Creation of PRINT and DMZ segments
- Strict pfSense firewall rules
- WebUI access restriction
- CUPS hardening through `cupsd.conf`
- Logging enabled on critical firewall rules
