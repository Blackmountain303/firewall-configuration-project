# Linux Firewall & Traffic Analysis Lab

## Project Overview
This project demonstrates the setup, configuration, and testing of a Linux-based firewall and traffic analysis environment. The lab uses Ubuntu Server as the primary system and VirtualBox as the virtualization platform. The goal is to build a controlled environment for practicing firewall rule creation, network scanning, packet analysis, and system hardening.

This lab simulates real-world tasks performed by IT support, SOC analysts, and cybersecurity technicians.

---

## 1. Lab Architecture
- Host Machine (Windows)
- VirtualBox Hypervisor
- Ubuntu Server (Firewall + Logging)
- Optional: Kali Linux (Attacker/Scanner)

Network Modes:
- NAT or NAT Network (Internet access)
- Host-only (Isolated testing)

---

## 2. Ubuntu Server Installation
- Created a new Ubuntu Server virtual machine in VirtualBox
- Assigned CPU, RAM, and storage appropriate for a lightweight lab environment
- Installed Ubuntu Server (no GUI)
- Verified the system boots cleanly into the terminal login prompt

---

## 3. System Updates and Essential Tools
- Logged in using the local administrator account created during setup
- Updated package lists and installed system upgrades:
```bash
sudo apt update && sudo apt upgrade -y
