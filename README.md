# Selfhosted-Home-Server
Reused an old hard disk and hosted a personal home server - cloud storage within my LAN 


Reused an old hard disk and hosted a personal home server - cloud storage within my LAN

Overview:

This project documents my setup of a self-hosted home cloud storage server using TrueNAS SCALE and Nextcloud. 
The goal was to build a personal cloud solution on my local network using unused hard drives and manage it entirely from within my home environment — no external cloud required.

Project Setup:

Hardware & Base Setup
• Utilized an unused HDD as the main disk to install TrueNAS SCALE OS. 
• Configured the system to boot directly from this HDD. 
• Hosted the TrueNAS Web Dashboard on my LAN using the local IP address.

Storage Configuration
• Added another unused HDD as a data pool in TrueNAS SCALE.
• Created a dedicated NAS storage pool to hold files, media, and backups. 
• Set up user permissions and network sharing (SMB) for easy access.

Network & Access
• Connected to the TrueNAS Dashboard through another device on the same LAN using the local IP.
• Mapped the NAS storage pool as a network drive on my laptop for direct access.

Nextcloud Integration
• Installed and configured Nextcloud as the primary cloud storage interface.
• Connected Nextcloud to the NAS data pool for seamless access and synchronization. 
• This allows access to files from any LAN-connected device through the Nextcloud web app or mobile client.

Tools & Technologies Used:

• TrueNAS SCALE OS – For NAS and storage management 
• Nextcloud – For cloud storage and file synchronization 
• SMB for Windows – For network drive mapping 
• LAN Access – For internal control and monitoring

Features:

• Self-hosted private cloud system.
• Local network access — no dependency on external providers.
• Managed via TrueNAS Dashboard.
• Fast file transfer speeds through LAN mapping.
• Integrated Nextcloud cloud interface.
• Multi-drive storage pool management

Repository Purpose:

This repository serves as a documentation of my home server setup journey and configuration notes. It can help others interested in:

Building a personal NAS system

Self-hosting private cloud storage

Learning about TrueNAS SCALE and Nextcloud integration
