# Home Network and SIEM Lab Project
This repository documents the design, setup, and ongoing improvements to my advanced home network. It also outlines my future plans to implement a Security Information and Event Management (SIEM) system in a homelab environment. The project focuses on building a secure, scalable, and high-performance network while developing hands-on networking and cybersecurity skills.

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

## 📡 Network Overview

### **Key Components**
- **Ubiquiti USG 3P**: Central router and firewall, providing advanced traffic routing, NAT, and security capabilities.
- **Ubiquiti AC Pro**: High-performance wireless access point delivering reliable Wi-Fi coverage.
- **Linksys Switch**: Repurposed as a Layer 2 switch to expand Ethernet connectivity.
- **End Devices**: A mix of wired and wireless devices, including PCs, smart TVs, smartphones, and IoT devices.

### **Network Topology**

![Network Topology](./topology.png)

This setup includes:
- Ubiquiti USG 3P as the router and firewall.
- Ubiquiti AC Pro for wireless connectivity.
- Linksys switch for wired device expansion.

## 🔧 Features and Configurations

### **Current Features**
- **Firewall Rules**: Configured on the USG to secure traffic and prevent unauthorized access.
- **IP Management**: DHCP handled by the USG, with both dynamic and static IP assignments.
- **Traffic Segmentation**: Planning VLANs for IoT, guest, and trusted device isolation.
- **Traffic Monitoring**: Real-time monitoring via UniFi Controller.

### **Future Plans**
- **Homelab SIEM Implementation**:
  - Deploy a SIEM (e.g., Splunk, ELK Stack, or Graylog) to collect and analyze logs from network devices.
  - Set up automated alerts for detecting suspicious activity.
- **Advanced Security**:
  - VLAN implementation for isolating traffic.
  - Deploy IDS/IPS for intrusion detection/prevention.
- **Home Automation Integration**:
  - Secure IoT devices with VLAN segmentation.

---

## 🎯 Learning Objectives

This project aims to enhance expertise in:
- **Networking**:
  - Configuring enterprise-grade networking equipment.
  - Implementing VLANs and advanced firewall rules.
  - Monitoring and optimizing network traffic.
- **Cybersecurity**:
  - Deploying and managing a SIEM solution.
  - Implementing IDS/IPS for advanced threat detection.
  - Designing secure network architectures.
- **Homelab Management**:
  - Setting up virtualized environments for enterprise simulations.
  - Collecting and analyzing logs for incident detection and response.

---

## 🛠️ Tools and Technologies

### **Networking**
- [Ubiquiti UniFi Controller](https://ui.com/) (for managing USG and AC Pro)
- Linksys Switch (basic Layer 2 functionality)

### **Planned SIEM Tools**
- **Splunk** (log aggregation and analysis)
- **Elastic Stack (ELK)** for open-source SIEM capabilities
- **Graylog** for lightweight log management

---

## 🗺️ Roadmap

1. **Finalize Home Network**:
   - Enable VLANs for traffic segmentation.
   - Fine-tune firewall rules for enhanced security.
2. **Set Up Homelab**:
   - Install virtualized environments using Hyper-V, VMware, or Proxmox.
   - Build a logging infrastructure for SIEM data collection.
3. **Deploy and Test SIEM**:
   - Collect logs from USG, end devices, and homelab services.
   - Create use cases for monitoring and responding to incidents.
4. **Document and Share**:
   - Update this repository with configuration files, guides, and findings.
