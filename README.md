# Franco Carrera

I work in IT with a focus on cloud infrastructure, Kubernetes, and Linux. I like getting into the weeds of how systems actually work — setting things up, breaking them, figuring out why, and doing it better the next time. Lately I've been spending most of my time on container orchestration and cloud-native tooling.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/franco-carrera-857ba81a8/)

---

### Tech Stack

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![OpenShift](https://img.shields.io/badge/OpenShift-EE0000?style=flat-square&logo=redhatopenshift&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![RHEL](https://img.shields.io/badge/RHEL-EE0000?style=flat-square&logo=redhat&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=FrancoCarrera1&show_icons=true&theme=github_dark&hide_border=true&count_private=true" alt="GitHub Stats" height="170" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=FrancoCarrera1&layout=compact&theme=github_dark&hide_border=true" alt="Top Languages" height="170" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=FrancoCarrera1&theme=github-dark-blue&hide_border=true" alt="GitHub Streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=FrancoCarrera1&theme=github-dark&hide_border=true&area=true" alt="Activity Graph" />

</div>

---

## Jarvis AI Homelab

Self-hosted AI assistant ecosystem running on a K3s cluster (Proxmox VM, Rocky Linux 9). Everything is deployed with Helm and orchestrated through n8n workflows.

| Component | Stack |
|-----------|-------|
| Morning Briefing Bot | Open-Meteo + RSS feeds + LLM summarization, delivered daily via Telegram |
| Second Brain | PostgreSQL with pgvector + Ollama (local embeddings) — semantic search over my entire Obsidian vault |
| Social Media Pipeline | LLM content generation, delivered to Telegram for review |
| Infrastructure | K3s, Helm, rclone (OneDrive sync), PVCs, NodePort services |

Built with: K3s, Helm, n8n, Ollama, PostgreSQL, pgvector, Telegram Bot API, rclone

---

## CKAD Killercoda Scenarios

**[ckad-killercoda-scenarios](https://github.com/FrancoCarrera1/ckad-killercoda-scenarios)**

I built 33 interactive Kubernetes scenarios for Killercoda covering all five CKAD exam domains. The goal was to create practice problems that actually feel like the exam — not toy examples, but scenarios where you have to think through the problem and use the right tools to solve it. Covers everything from RBAC and NetworkPolicy to Helm, Ingress, PV/PVC, Jobs, and debugging live clusters.

| Domain | Scenarios |
|--------|-----------|
| Application Environment, Configuration & Security | 8 |
| Application Design & Build | 7 |
| Application Deployment | 7 |
| Services & Networking | 7 |
| Application Observability & Maintenance | 4 |

Difficulty split: 10 Easy · 13 Medium · 10 Hard

---

## Ansible Automation Study Lab

**[ansible-study-lab](https://github.com/FrancoCarrera1/rhce-study)**

A terminal-based practice exam runner I built to study Ansible automation. It presents timed tasks in a TUI, then verifies your work by SSHing into Vagrant VMs and checking that everything was actually configured correctly — inventory files, vault encryption, user accounts, LVM volumes, cron jobs, the works.

Includes 20 progressive lessons, 4 full-length practice exams, and automated grading against real VM state. The whole lab runs locally on a multi-node AlmaLinux 9 Vagrant environment (1 control + 5 managed nodes).

| Content | Count |
|---------|-------|
| Guided lessons | 20 |
| Practice exams | 4 |
| Unique tasks | 70+ |
| Automated checks | 300+ |

Built with Python (Textual TUI), Ansible, Vagrant, and AlmaLinux 9.

---

## Portfolio Site

**[francolinux.ramsec.net](https://francolinux.ramsec.net)**

Static portfolio hosted on AWS S3 + CloudFront with a custom domain via Cloudflare DNS. Built as a hands-on exercise for the AWS Solutions Architect Associate exam — covers S3 static hosting, CloudFront distributions, Origin Access Control, ACM certificates, and custom domain configuration.

Built with: HTML, CSS, AWS S3, CloudFront, ACM, Cloudflare DNS

---

## Other Projects

### Cloud & DevOps

- **[CloudUploader-CLI](https://github.com/FrancoCarrera1/CloudUploader-CLI)** — Bash CLI for uploading files to Azure

### Homelab

- **[Kasm Server](https://github.com/FrancoCarrera1/kasmsrv)** — Kasm workspace server setup
- **[Vaultwarden](https://github.com/FrancoCarrera1/vaultwardenfc23)** — Self-hosted password manager running on my own hardware

### IT Operations

- **[osTicket: Prerequisites and Installation](https://github.com/FrancoCarrera1/osticket-prereqs)**
- **[osTicket: Post Installation Setup](https://github.com/FrancoCarrera1/osTicketpostinstallation-setup)**
- **[osTicket: Ticket Lifecycles](https://github.com/FrancoCarrera1/tlifecycles)**
