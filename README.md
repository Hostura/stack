# 🌐 Hostura – A Production-Ready Docker Stack for Self-Hosting

**Hostura** is an automated server setup solution designed to deploy a secure, modular, and production-ready Docker stack on a fresh Linux server (VPS, dedicated, or cloud). Inspired by platforms like YunoHost, Hostura focuses on simplicity, transparency, and adherence to DevOps best practices.

## 🚀 Key Features

- 🔐 **Built-in Security**  
  Automatic installation and configuration of `ufw`, `fail2ban`, secure SSH setup, user creation, and more.

- 🐳 **Docker & Docker Compose**  
  Orchestrates isolated, maintainable services through containers.

- 🌍 **Traefik as Reverse Proxy**  
  Automatic SSL via Let’s Encrypt, dynamic routing, multi-domain support.

- 📦 **Modular Services**  
  Easily add services (e.g., Portainer, Watchtower) in the `services/` directory.

- 🔧 **Automated Installation Script**  
  Silent execution, logging, credentials generation, and automatic detection of production vs. development environments.

- 🛡️ **Read-Only Configs**  
  Protects critical service configurations (e.g., Traefik) from accidental or unauthorized changes.

## 🛠️ Who Is It For?

Hostura is ideal for:

- Advanced self-hosters  
- Professionals looking for a ready-to-use server base  
- Developers wanting a portable DevOps-ready environment  
- Trainers or educators teaching secure server deployment practices
