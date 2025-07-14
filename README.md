# Network Security Fundamentals and FortiGate Integration

## Project Description

This project simulates a real-life network security deployment using **Fortinet's FortiGate firewall** in a controlled lab environment. It focuses on configuring firewall rules, NAT (source and destination), and access control policies to enforce secure communication between network zones (LAN, WAN, DMZ).

The goal was to build a secure, functional topology that reflects how an actual organization might protect internal resources while providing controlled external access.

---

## Project Phases

| Phase        | Description                                                            | Deliverable                             |
|--------------|------------------------------------------------------------------------|------------------------------------------|
| Phase 1      | Research on current cybersecurity threats and mitigation strategies    | Threat Presentation + Network Diagram    |
| Phase 2      | FortiGate basic configuration (interfaces, IPs, firewall setup)        | Configuration Documents with Screenshots |
| Phase 3      | Policy rules, NAT configurations (SNAT/DNAT), and traffic testing      | Policy Report and Results                |
| Phase 4      | Final documentation and project summary                                | Final Report + Presentation              |

---

## Network Topology

![Network Topology]

The network includes:
- FortiGate firewall (trial license)
- Internal switch
- PC1 and PC2 (LAN clients)
- Kali Linux web server (DMZ zone)
- Simulated Internet cloud

Traffic flow includes:
- LAN to WAN
- LAN to DMZ
- DMZ to LAN
- NAT (source NAT for outbound, destination NAT for port forwarding)

---

## Addressing and Interfaces

| Device        | IP Address      | Role           |
|---------------|------------------|----------------|
| FortiGate WAN | 192.168.1.100    | Internet access |
| FortiGate LAN | 192.168.10.1     | Internal DHCP server |
| Web Server    | 192.168.20.1     | DMZ (External service) |
| PC1/PC2       | DHCP assigned    | Internal clients |

---

## Technologies Used

- GNS3 (for virtual lab simulation)
- FortiGate VM (firewall)
- VLAN segmentation
- NAT (source & destination)
- Firewall rules & access control
- Simulated clients and server

---

## Team Members

- Ziad Waled Ibrahim Hassan
- Ahmed Mohamed Sobhy Khalifa
- Nada Ehab Ghorab
- Mazen Amr Mohamed Hassan
- Abdelrahman Ebrahem
- Menna Mohamed Sayed

## Instructor and technical supervisor for the project

Eng. Mahmoud Abd EL-Ghani

---

## Repository Structure

