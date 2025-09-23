# 🛡️ Red Hat System Administration Homelab: AeroSecure Systems Inc.

## Overview
This homelab simulates the daily responsibilities of a Sr. System Administrator managing secure Linux infrastructure for a fictional defense contractor, **AeroSecure Systems Inc.** The lab is designed to mirror real-world enterprise environments using Red Hat-based systems (Rocky Linux or AlmaLinux), with a focus on security, automation, and compliance.

## 🏢 Scenario: AeroSecure Systems Inc.
- **Industry:** Aerospace & Defense
- **Location:** Tampa, FL
- **Environment:** Classified development systems under DoD contracts
- **Compliance:** RMF, JSIG, NIST 800-171, DoD 8570

## 🧑‍💻 Your Role
As the Sr. System Administrator, you're responsible for:
- Provisioning secure Linux servers
- Enforcing SELinux and firewall policies
- Managing users and groups
- Automating backups and monitoring
- Collaborating with cybersecurity teams

## 🧪 Lab Setup
- **Virtualization:** VirtualBox or VMware Workstation
- **VMs:**
  - `rocky-linux-server` (Rocky Linux 9)
  - Optional: `windows-client` (Windows 10/11 for AD testing)
- **Specs:** 2 CPUs, 2–4 GB RAM, 20 GB disk

## 🔧 Tasks

### Morning: System Setup
- [x] Install Rocky Linux and configure hostname, timezone, SSH
- [x] Create users (`admin1`, `dev1`, `sec1`) and groups (`admins`, `developers`, `security`)
- [x] Install packages: `httpd`, `vim`, `net-tools`, `firewalld`
- [x] Enable and start Apache (`httpd`)

### Midday: Security & Networking
- [x] Configure `firewalld` to allow HTTP and SSH
- [x] Enforce SELinux and adjust contexts for `/var/www/html`
- [x] Set static IP and configure `/etc/hosts`
- [x] Create and mount a new disk using `fdisk`, `mkfs.xfs`, and `/etc/fstab`

### Afternoon: Monitoring & Automation
- [x] Monitor system with `top`, `journalctl`, `df -h`
- [x] Create backup script using `tar` and `cron`
- [x] Write bash script to monitor disk usage and restart Apache if needed
- [x] Log all actions to `/var/log/sysadmin.log`

## 📁 File Structure

