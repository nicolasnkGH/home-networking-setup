# Home Networking Setup & Proxmox Cluster

## 🚀 Overview:
This repository documents my personal home networking setup and virtualization lab, which I have built to simulate enterprise-level infrastructure. It includes networking configurations, security measures, and virtualization with Proxmox, showcasing my knowledge in system administration, network design, and automation.

## 🛠️ Key Technologies:
- **Proxmox**: Virtualization platform to host multiple VMs and containers.
- **VLANs**: Used for network segmentation and isolating traffic.
- **Firewalls & VPNs**: Configured for secure remote access.
- **Docker**: Containerization of services for ease of deployment and scalability.
- **Ansible**: Automation of deployment and configuration management.
- **Network Monitoring**: Tools to monitor network health and performance.

## 🌐 Network Architecture:
### High-Level Design:
- **Home Network Diagram**: ![image](https://github.com/user-attachments/assets/89d16e09-e999-48db-9eef-ba70ed120210)

- **Proxmox Cluster**: Deployed a Proxmox cluster to manage virtual machines (VMs) for various services, including media server stacks and development environments.
- **Security**: Configured firewalls, VPN access, and used secure network protocols to protect internal resources.
- **Routing & VLAN Setup**: Split the network into multiple segments for enhanced security and performance. Configured static routes and VLANs to isolate different services.

## 🔧 Services & Tools Hosted:
- **Redundant Pi-hole + Unbound DNS Server**: Provides ad-blocking and DNS resolution with redundancy.
- **Home Dashboard**: Centralized interface to monitor and control home systems.
- **Isolated Docker/LXC Containers**: For secure, containerized environments running various applications.
- **Tailscale**: Simplified VPN for secure remote access to internal services.
- **Cloudflare Tunnel**: Securely exposes internal applications to the internet without exposing direct IPs.
- **Home Assistant**: Automation platform for controlling smart home devices.
- **Jellyfin**: Self-hosted media server for organizing and streaming personal media.
- **Plex**: Media server solution for streaming movies, TV shows, and music.
- **OpenMediaVault (OMV) with RAIDZ1**: Network-attached storage (NAS) with RAIDZ1 for data redundancy and protection.
- **Bitwarden Password Manager**: Securely stores and manages passwords for personal and organizational use.
- **Firewall Managed within UniFi Environment**: Centralized firewall management for better network security and control.
- **Honeypot**: Deployed to monitor and capture malicious activity.
- **Intrusion Detection System (IDS)**: Continuously monitors network traffic for malicious activity or policy violations.
- **VLAN Segmentation**:
  - **IoT**: Isolated network for smart devices.
  - **Guest**: Separate network for guest access.
  - **Management**: Secure network segment for administrative and management tasks.
  - **Main Network**: Primary network for regular home and office use.


## ⚙️ Automation:
- **Docker**: All services are containerized using Docker or LXC containers allowing for easy deployment and management.
- **Ansible**: Ansible playbooks are used to automate the provisioning of infrastructure and the deployment of services.


## 🔐 Security Measures:
- **VPN**: Configured for secure remote access to services.
- **Firewall Rules**: Custom firewall rules to restrict external access and allow only necessary traffic.
- **Access Control**: Used strong authentication methods (e.g., multi-factor authentication, SSH keys) for critical services.
- **CloudFlare Zero Trust integration**: Integrated to securely expose locally hosted applications with identity-based access control.

## 📚 Learnings & Challenges:
- **Networking Concepts**: Gained experience with VLANs, subnetting, and routing protocols while building out this network.
- **Virtualization**: Learned about virtual machine management, clustering, and resource allocation using Proxmox.
- **Security Best Practices**: Applied security measures to ensure secure access to hosted services, including VPNs and firewall rules.
- **Automation**: Automated the deployment of services and network configurations using tools like Ansible and Docker.

---

Feel free to explore this repository and see how I’ve applied my networking and virtualization skills to create a robust and secure home infrastructure.
