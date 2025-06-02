# 🔥 LAMP Stack on CentOS 8 (64-bit) — A Red Hat Practice Lab

**Author:** Leo Alexander III  
**Started:** May 26, 2025  
**Status:** In Progress  
**Repository Purpose:** Real-world RHCSA-aligned lab

---

## 🧭 Project Overview

This repository documents the setup and configuration of a full **LAMP stack** (Linux, Apache, MariaDB, PHP) on **CentOS 8** within a VMware virtual machine. It’s part of a broader professional development journey toward becoming a Red Hat Certified System Administrator (**RHCSA**) — grounded in real-world, reproducible, and auditable system design.

> *This project is one piece of a larger portfolio demonstrating command-line fluency, Linux operations, and spiritual craftsmanship through tech.*

---

## ⚙️ Technology Stack

| Layer       | Tool               |
|-------------|--------------------|
| OS          | CentOS 8 (VMware)  |
| Web Server  | Apache HTTPD       |
| Database    | MariaDB (MySQL)    |
| Scripting   | PHP 7.x            |
| Admin Tool  | phpMyAdmin         |
| Versioning  | Git + GitHub       |

---

## ✅ Current Progress

- ✅ CentOS 8 LAMP VM configured and connected to the internet
- ✅ Apache installed and running
- ✅ PHP installed and verified via `phpinfo()` page
- ✅ MariaDB installed and secured (`mysql_secure_installation`)
- ✅ phpMyAdmin downloaded, extracted, and configured
- ✅ Access error resolved
- 🛠️ Web root verified; permissions under review
- ⏳ Final phpMyAdmin login security hardening in progress

---

## 🔜 Next Steps

- [ ] Configure secure phpMyAdmin login
- [ ] Add limited MySQL database user
- [ ] Harden Apache file permissions
- [ ] Finalize firewall rules (`firewalld`)
- [ ] Generate a final report with lessons learned + system audit

---

## 📂 Network + Access Details

- **VM Network:** `192.168.40.0/24`
- **VM Static IP:** `192.168.40.100`
- **phpMyAdmin URL:** [http://192.168.40.100/phpmyadmin](http://192.168.40.100/phpmyadmin)

> Access limited to host-only/local test lab.

---

## 📜 Documentation

Session logs, terminal commands, and troubleshooting steps are tracked in the `/documentation/` folder. These logs serve dual purposes:
1. Reference for future deployments,
2. Practice for RHCSA task repetition and memorization.

---

## 💡 Vision Beyond the Stack

This is more than a LAMP stack — it’s a living lab of discipline, clarity, and craft. Every decision made here builds toward something greater: a portfolio of mastery in Linux systems, thoughtful architecture, and digital sovereignty.

---

## ✍️ Author

**Leo Alexander III**  
_Avid reader • Historian • Tech thinker • Conscious creator_

> _"We build not just systems, but legacies."_ 🛠️🧠

---

## 🌱 Future Enhancements *(Optional)*

- Ansible playbook for automated deployment
- Bash scripts for VM snapshot rollback and provisioning
- Integration into `redhatops-ai-lab`
