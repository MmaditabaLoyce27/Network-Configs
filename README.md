# Network-Configs
Network Configuration for VLAN, DHCP, VoIP, and VTP Integration
This repository contains a comprehensive network configuration for a multi-site setup using Cisco devices. The configuration includes Layer 3 switches, VoIP gateways, and access switches, providing a fully integrated network environment. 

 Key features of this configuration include:

- DHCP Services: The Layer 3 switch (HQ_MLS) provides DHCP for multiple VLANs (SALES, FINANCE, VOICE), automatically assigning IP addresses to devices across the network for streamlined device connectivity.

- VoIP Telephony: The voice gateways (HQ_VoiceGateway and JHB_VoiceGateway) manage IP phone registrations, assigning directory numbers (DNs), and configuring dial peers for call routing within the organization.

- VTP Integration: The HQ_MLS switch acts as a VTP server, managing VLAN configurations and propagating updates to access switches (such as SALES, FINANCE, VOICE), which are set as VTP clients.
