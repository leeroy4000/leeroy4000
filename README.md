# Hi, I'm Nathan 👋

I'm a systems technician learning DevOps, with a background in data center operations and hands-on biomedical equipment maintenance. My day job involves device-level troubleshooting and documentation across complex medical systems — my nights and weekends are spent experimenting in my homelab. I like building things that are reliable, automated, and well-documented — and then breaking them to see what happens.

---

## 🏠 Homelab

My homelab is my primary learning environment. It runs production-grade services on consumer hardware and is where I put everything into practice.

**Network & Security**
- pfSense firewall handling DHCP, DNS resolver, OpenVPN, and DDNS
- VLAN segmentation isolating IoT devices (7+) and IP cameras (5) from the main network
- Omada SDN managing a PoE switch and two wireless APs
- Pi-hole for network-wide DNS filtering

**Proxmox Node**
- Dedicated to stable, set-and-forget services
- VM: Home Assistant OS for home automation
- LXC: Caddy reverse proxy with SSL termination
- LXC: Omada SDN controller
- LXC: Uptime Kuma for service monitoring

**Debian Server (headless, primary workhorse)**
- Docker services: Frigate NVR (with Coral TPU for local ML inference), Jellyfin media server
- 5-camera surveillance system with local AI object detection — no cloud required
- Self-hosted file storage via SMB; exploring offline sync solutions (Syncthing/Nextcloud)

**Coming Soon**
- k3s Kubernetes cluster on the Debian server
- Terraform for infrastructure provisioning
- Migrating key services to k8s manifests

---

## 🛠️ Skills & Tools

**Infrastructure & Virtualization**
`Proxmox` `Linux (Debian/Ubuntu)` `pfSense` `Docker` `LXC`

**Networking**
`VLANs` `DNS` `DHCP` `OpenVPN` `Reverse Proxy` `Omada SDN`

**Monitoring & Automation**
`Uptime Kuma` `Home Assistant` `Caddy` `Frigate`

**Currently Learning**
`AWS (Solutions Architect Associate — in progress)` `Kubernetes / k3s` `Terraform`

---

## 📁 Featured Projects

- [**proxmox-ssl-setup**](https://github.com/leeroy4000/proxmox-ssl-setup) — Automated SSL certificate management for Proxmox VE using Let's Encrypt and Cloudflare.
- [**patch_proxmox_nosub**](https://github.com/leeroy4000/patch_proxmox_nosub) — Removes the Proxmox subscription nag for homelab use
- [**Coral_TPU_Install**](https://github.com/leeroy4000/Coral_TPU_Install) — Setup guide for Google Coral TPU with Frigate NVR on Debian
- [**usb_mount_and_share**](https://github.com/leeroy4000/usb_mount_and_share) — Bash script for mounting a USB HDD or block device and sharing it via Samba

---

## 🎯 What I'm Working Toward

Pursuing a remote DevOps/Infrastructure role where I can bring real-world systems experience to a team that values reliability and automation. When I'm not breaking things in the lab, I'm probably hosting a Valheim server for friends.

---

*Des Moines, IA | Open to remote*
