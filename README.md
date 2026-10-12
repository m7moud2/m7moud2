# Mahmoud Abdelkawy

**Junior DevOps Engineer** based in Cairo, Egypt.  
Passionate about Linux systems, Docker containerization, Kubernetes fundamentals, and infrastructure monitoring.

---

### About Me

I am a Junior DevOps Engineer with a solid foundation in Linux administration, networking fundamentals (CCNA & Network+), and container technologies. I focus on practical, hands-on learning—building and deploying containerized applications, configuring web servers, automating routine tasks with Bash, and setting up monitoring stacks with Prometheus and Grafana.

---

### Technical Skills

- **Linux & Scripting:** Ubuntu, Debian, Alpine Linux, Bash Scripting, Systemd, User & Permission Management, SSH Hardening.
- **Containers & Orchestration:** Docker, Docker Compose, Kubernetes (Pods, Services, PVCs, Deployments on Kind & Minikube).
- **Web Servers & Databases:** Nginx (Reverse Proxy, Virtual Hosts), Apache HTTPD, PHP-FPM, MySQL, Redis.
- **Monitoring & Observability:** Prometheus, Grafana (Dashboards & Datasources), Alertmanager, Node Exporter.
- **Networking Fundamentals:** TCP/IP, DNS, Subnetting (IPv4/CIDR), VLANs, Routing & Switching, Firewalls (UFW).
- **Version Control & CI/CD:** Git, GitHub, GitHub Actions.

---

### Featured Projects

#### 1. [Online Boutique - Microservices Deployment](https://github.com/m7moud2/online-boutique-deployment)
*Full-stack deployment of Google's 11-microservice polyglot e-commerce application.*
- **Docker Compose Setup:** Orchestrated all 11 polyglot microservices (Go, Python, C#, Java, Node.js) and Redis on a single bridge network with proper gRPC service discovery.
- **Kubernetes Manifests:** Configured individual service manifests and an all-in-one deployment with health probes and resource limits.
- **Stateful Redis Storage:** Implemented a `PersistentVolumeClaim` (PVC) for the Redis cart service, ensuring user cart data persists across pod restarts.
- **Automation & CI:** Created a `Makefile`, an automated bash health-check probe, and a GitHub Actions workflow validating manifests on push.

#### 2. [TaskFlow Observability Stack](https://github.com/m7moud2/taskflow-docker-api)
*Containerized application monitoring with Prometheus and Grafana.*
- **Modular Stacks:** Multi-container setups for Nginx, WordPress, and MySQL 8.0 with dedicated Prometheus metrics exporters.
- **Automated Provisioning:** Pre-loaded Grafana datasources and custom JSON dashboards for instant metric visualization without manual UI setup.
- **Alerting Workflows:** Configured alert rules for service downtime and Alertmanager notification routing.

#### 3. [Linux System Administration Labs](https://github.com/m7moud2/linux-system-administration-labs)
*Practical Bash scripts for server maintenance and process monitoring.*
- **User Management:** Script automating user creation, group assignments, and SSH key configurations (`user_management.sh`).
- **Health Diagnostics:** System resource monitor tracking CPU load, memory thresholds, and disk usage (`systemhealthcheck.sh`).
- **Backup Automation:** Automated file archiving script with timestamped rotation and cleanup policies (`backup_rotation.sh`).

#### 4. [Linux Web Stack Deployments](https://github.com/m7moud2/linux-webstack-deployments)
*Production-ready web server configurations for hosting web applications.*
- **Nginx Setup:** Virtual host configs with FastCGI pass-through, security headers, gzip compression, and `/stub_status` metrics endpoint.
- **Apache Integration:** VirtualHost configuration with `mod_proxy_fcgi` handler routed to PHP-FPM pools.
- **Syntax Verification:** Pre-flight configuration validation script testing config files before reloading services.

#### 5. [Linux Networking and Security Suite](https://github.com/m7moud2/linux-networking-security-suite)
*Networking tools and firewall configuration scripts.*
- **UFW Firewall:** Script establishing a default-deny incoming policy with rate-limited SSH and allowed web traffic ports.
- **Subnet Calculator:** Python CLI tool calculating IPv4 CIDR blocks, network/broadcast addresses, and usable host ranges.
- **DNS Diagnostics:** Utility script validating DNS records (A, MX, NS) and measuring query resolution latency.

---

### What I'm Learning Now

- Deepening Kubernetes knowledge (Ingress controllers, Helm charts, and cluster networking).
- Infrastructure as Code with Terraform.
- CI/CD pipeline automation for cloud deployments.

---

### Contact & Profiles

- **Email:** [m7moud3bdelkawy@gmail.com](mailto:m7moud3bdelkawy@gmail.com)
- **LinkedIn:** [linkedin.com/in/mahmoud-abdelkawy-99290020b](https://www.linkedin.com/in/mahmoud-abdelkawy-99290020b)
- **GitHub:** [github.com/m7moud2](https://github.com/m7moud2)
- **X (Twitter):** [@m7moud3bdelkawy](https://x.com/m7moud3bdelkawy)
