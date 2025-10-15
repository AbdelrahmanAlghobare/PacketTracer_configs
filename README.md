Project Title:
Cisco Routers Configuration for Syslog, NTP, and SSH Operations

Project Overview:
This project demonstrates the configuration and integration of core network management and security services on Cisco routers and switches using Cisco Packet Tracer.
It focuses on enabling secure remote management, centralized time synchronization, and log monitoring to ensure reliability, consistency, and accountability in enterprise network environments.

Technical Description:
1. SSH Configuration (Secure Remote Access)
Configured SSH (version 2) on all routers for encrypted remote administration.
Created local user accounts with privilege levels for secure authentication.
Disabled Telnet to eliminate insecure access.
Verified access from management PC using ssh -l   command.
2. Syslog Server Integration (Centralized Logging)
Deployed a dedicated Syslog Server to collect and store log messages from all network devices.
Configured routers to send log messages using the logging  command.
Enabled timestamping for precise event tracking.
Verified successful log entries displayed in the Syslog service panel.
3. NTP Configuration (Time Synchronization)
Configured one router as the NTP Master Server.
All other routers and switches synchronized their clocks using NTP to ensure accurate and consistent log timestamps.
Verified synchronization with the show clock and show ntp status commands.

Network Topology Summary:
Core Devices: 3 Cisco Routers (R1, R2, R3) connected via serial links.
Access Layer: Switch connecting management servers (Syslog + NTP + SSH client PCs).
Servers Deployed:
Syslog Server – 192.168.10.5
NTP Server – 192.168.10.5
SSH Management PC – 192.168.1.5
Routing Protocol: Static routes (configured for end-to-end connectivity).
Management VLAN: Used to centralize monitoring and secure access.

Key Achievements:
Implemented secure encrypted management using SSH.
Established centralized logging and time synchronization systems.
Demonstrated understanding of network services integration in enterprise topology.
Verified end-to-end connectivity and service operation between all routers and servers.
Documented configuration commands and verification outputs for each device.

Skills Demonstrated:
Cisco IOS configuration
Network management and monitoring
Secure remote access (SSH)
Syslog and NTP service configuration
Logical network design and troubleshooting
Packet Tracer simulation and documentation 
