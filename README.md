# Ansible Apache Web Server Automation 🚀

This project demonstrates how to **automate Apache web server installation and configuration** on **AWS EC2 Ubuntu instances** using **Ansible roles**.  
It deploys a custom HTML page and manages services following best practices.

---

## 📌 Features
- Automated Apache installation using Ansible
- Role-based project structure
- Custom HTML page deployment
- Service management (start & enable Apache)
- Supports multiple hosts
- Secure and reusable automation

---

## 🛠️ Technologies Used
- Ansible
- Apache HTTP Server
- AWS EC2 (Ubuntu)
- Git & GitHub
- Linux (Ubuntu)

---

## 📂 Project Structure
```text
ansible-apache-role/
├── site.yml
├── inventory.ini
├── roles/
│   └── grp1/
│       ├── tasks/
│       │   ├── main.yml
│       │   ├── config.yml
│       │   └── service.yml
│       └── files/
│           └── index.html
└── README.md
