# Mahmoud Abdelkawy | Junior DevOps & Observability Engineer

<div align="center">

[![DevOps Focus](https://img.shields.io/badge/Role-Junior%20DevOps%20%26%20Observability%20Engineer-00f0ff?style=for-the-badge&logo=docker&logoColor=white)](https://github.com/m7moud2)
[![Location](https://img.shields.io/badge/Location-Cairo%2C%20Egypt-ff007f?style=for-the-badge&logo=googlemaps&logoColor=white)](https://github.com/m7moud2)

[![Linux & Admin](https://img.shields.io/badge/Linux-Ubuntu%20%2F%20Alpine-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://github.com/m7moud2)
[![Containers](https://img.shields.io/badge/Containers-Docker%20%2F%20Kubernetes-2496ED?style=for-the-badge&logo=kubernetes&logoColor=white)](https://github.com/m7moud2)
[![Monitoring](https://img.shields.io/badge/Monitoring-Prometheus%20%2F%20Grafana-E6522C?style=for-the-badge&logo=grafana&logoColor=white)](https://github.com/m7moud2)
[![Networking](https://img.shields.io/badge/Networking-Network%2B%20%2F%20Cisco%20CCNA-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)](https://github.com/m7moud2)

---

### About Me

```
╔══════════════════════════════════════════════════════════════════════════════════╗
║  Junior DevOps & Observability Engineer based in Cairo, Egypt.                   ║
║  Hands-on experience in Linux Administration, Docker Containerization,          ║
║  Kubernetes Deployments, Web Servers (Nginx / Apache / PHP-FPM),                 ║
║  Prometheus & Grafana Observability Stacks, and Networking (CCNA & Network+).    ║
╚══════════════════════════════════════════════════════════════════════════════════╝
```

</div>

---

## Technical Skills & Core Arsenal

<div align="center">

### Linux & Operating Systems
![Linux](https://img.shields.io/badge/Linux%20Administration-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Alpine](https://img.shields.io/badge/Alpine%20Linux-0D597F?style=for-the-badge&logo=alpine-linux&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)

### Containers & Orchestration
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

### Web Servers & Databases
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache%20HTTPD-D22128?style=for-the-badge&logo=apache&logoColor=white)
![PHP-FPM](https://img.shields.io/badge/PHP--FPM-777BB4?style=for-the-badge&logo=php&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL%208.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### Monitoring & Observability
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Alertmanager](https://img.shields.io/badge/Alertmanager-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![PromQL](https://img.shields.io/badge/PromQL-00F0FF?style=for-the-badge&logo=prometheus&logoColor=black)

### Networking & Security
![Cisco CCNA](https://img.shields.io/badge/Cisco-CCNA%20Networking-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Network+](https://img.shields.io/badge/CompTIA-Network%2B-FF0000?style=for-the-badge&logo=comptia&logoColor=white)
![UFW](https://img.shields.io/badge/Firewall-UFW%20Hardening-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

### Scripting & CI/CD
![Bash](https://img.shields.io/badge/Bash%20Scripting-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

---

## Featured Projects

### 1. [Online Boutique - Microservices Deployment](https://github.com/m7moud2/online-boutique-deployment)
*Production-ready deployment of Google's 11 polyglot microservices e-commerce application on Docker Compose & Kubernetes.*
- **Docker Compose Orchestration:** Configured all 11 polyglot services (Go, Python, C#, Java, Node.js) and Redis across an isolated custom bridge network (`boutique_net`).
- **Kubernetes Architecture:** Created modular manifests per service plus an all-in-one manifest (`complete-deployment.yaml`) with readiness/liveness HTTP and exec probes, resource requests/limits, and DNS service discovery.
- **Stateful Redis Cart Persistence:** Configured a dedicated `PersistentVolumeClaim` (PVC) for `redis-cart` to preserve customer cart sessions across container restarts and rescheduling.
- **Automation & Quality Assurance:** Built a `Makefile` for one-command lifecycle operations, automated curl-based health probe validation, and GitHub Actions CI workflow to validate syntax and manifests on push.

### 2. [TaskFlow Observability Stack](https://github.com/m7moud2/taskflow-docker-api)
*Enterprise-grade containerized observability infrastructure using Prometheus and Grafana.*
- **Modular Multi-Container Stacks:** Decoupled Compose configurations for standalone Nginx and WordPress with MySQL 8.0 paired with dedicated metrics exporters (Nginx Exporter, MySQLd Exporter).
- **Automated Provisioning:** Pre-configured Grafana datasources and pre-loaded JSON dashboards for instant metric visualization with zero manual GUI steps.
- **Alerting & Incident Workflows:** Production alert rules for service outages, high error rates, and Alertmanager notification routing with silencing capabilities.

### 3. [Linux System Administration Labs](https://github.com/m7moud2/linux-system-administration-labs)
*Automated server maintenance, user management, and health diagnostic scripts.*
- **User Provisioning:** Shell script automating secure user creation, group permissions, home directory creation, and SSH key authorization (`user_management.sh`).
- **Health Diagnostics:** System resource monitor checking CPU load, memory thresholds, disk usage, and alerting on critical utilization (`systemhealthcheck.sh`).
- **Backup & Retention Automation:** Script handling compressed tar backups with timestamped file rotation and automated removal of archives older than retention limits (`backup_rotation.sh`).

### 4. [Linux Web Stack Deployments](https://github.com/m7moud2/linux-webstack-deployments)
*Production web server setups for Nginx, WordPress, Apache, and PHP-FPM.*
- **Nginx Architecture:** Optimized Virtual Host configurations with FastCGI PHP pass-through, gzip compression, security headers, and `/stub_status` metrics path.
- **Apache Integration:** VirtualHost configuration with `mod_proxy_fcgi` handler routed to PHP-FPM pools (`127.0.0.1:9000`).
- **Pre-flight Validation:** Automation script for syntax testing configuration files before reloading production services (`verify_configs.sh`).

### 5. [Linux Networking and Security Suite](https://github.com/m7moud2/linux-networking-security-suite)
*Network diagnostics, IPv4 subnetting tools, and firewall hardening scripts.*
- **UFW Firewall Hardening:** Shell script enforcing default-deny incoming traffic, SSH rate limiting on port 22, and explicit web traffic rules (`firewall_hardening.sh`).
- **Subnet Calculator:** Python CLI tool calculating IPv4 CIDR blocks, network/broadcast addresses, and usable host ranges (`subnet_calculator.py`).
- **DNS Diagnostics:** Utility script testing DNS resolution for A, MX, NS records and measuring query response latency (`zone_test.sh`).

---

## Career Roadmap & Growth

- **Current Learning:**
  - **Kubernetes (K8s):** Ingress Controllers (Traefik/Nginx), Helm Charts packaging, StatefulSets, and Service Mesh.
  - **Infrastructure as Code (IaC):** Terraform modules, state management, and declarative cloud resource provisioning.
  - **Advanced Observability:** OpenTelemetry (OTel) Collector and Grafana Loki log aggregation.
- **Career Goal:**
  - Joining a high-performance DevOps / SRE team to build resilient infrastructure, optimize CI/CD pipelines, and maintain high service availability.

---

## GitHub Activity & Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=m7moud2&show_icons=true&theme=tokyonight&hide_border=true" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=m7moud2&layout=compact&theme=tokyonight&hide_border=true" width="49%" />

</div>

---

<div align="center">

### Connect & Collaborate

[![Email](https://img.shields.io/badge/Email-m7moud3bdelkawy%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:m7moud3bdelkawy@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mahmoud--Abdelkawy-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mahmoud-abdelkawy-99290020b)
[![Twitter](https://img.shields.io/badge/X-m7moud3bdelkawy-000000?style=for-the-badge&logo=x)](https://x.com/m7moud3bdelkawy)
[![GitHub](https://img.shields.io/badge/GitHub-m7moud2-181717?style=for-the-badge&logo=github)](https://github.com/m7moud2)

</div>
