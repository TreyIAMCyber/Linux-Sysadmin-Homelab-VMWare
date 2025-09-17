# Linux System Administrator Homelab (VMware Edition)

## Environment Setup
- Platform: VMware Workstation Pro or ESXi
- VMs:
  - `linux-admin-01`: Ubuntu Server LTS
  - `linux-client-01`: Rocky Linux
  - `monitor-node`: Debian or Ubuntu
- Networking: NAT + internal network

## Module 1: User & Access Control
- Create users/groups
- Configure sudo access
- Enforce password policies
- Automate provisioning with Bash

## Module 2: Storage & Filesystem
- Add virtual disk via VMware
- Partition, format, mount
- Set up LVM
- Configure quotas
- Automate backups with rsync + cron

## Module 3: Networking & Remote Access
- Static IP config
- SSH hardening
- Firewall setup (iptables/ufw)
- Optional VPN (WireGuard)

## Module 4: Monitoring & Logging
- Install sysstat, htop, glances
- Configure rsyslog + auditd
- Optional: Prometheus + Grafana

## Module 5: Security Hardening
- Run Lynis/OpenSCAP
- Disable unused services
- Map to CIS/NIST benchmarks

## GitHub Documentation Strategy
- Repo: `linux-sysadmin-homelab-vmware`
- Each module = folder with:
  - Setup steps
  - Commands
  - Screenshots
  - Compliance mapping
  - Lessons learned
