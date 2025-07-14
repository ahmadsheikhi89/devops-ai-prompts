# 📘 DevOps AI Prompt Engineering – Expert-Level Handbook

> **Purpose:** Highly practical, production-ready prompts tailored for documenting and analyzing real-world DevOps infrastructure. Written by an AI acting as a senior DevOps engineer with 10+ years of experience.

---

## 🚀 12 Production-Grade AI Prompts for DevOps Documentation

Each prompt below is written for use in tools like ChatGPT and Claude. These are designed for professionals and junior engineers who want clarity, precision, and reliability in their technical docs.

---

### 1. 🧩 Ansible Playbook – Infra Audit & Explanation

```text
You are a senior DevOps engineer with 10+ years of experience.  
Your job is to review and explain this Ansible playbook for a junior engineer onboarding to our infrastructure. 

Deliver:
- Executive Summary
- Step-by-Step Explanation
- Potential Risks (Idempotency, Service Restarts)
- Suggestions for Scalability or Security

Playbook:
<YOUR ANSIBLE CODE>
```

---

### 2. 🐳 Dockerfile – Deep Analysis & Best Practices

```text
You are a senior DevOps engineer with deep containerization knowledge.  
Your task is to document and audit the following Dockerfile:

Include:
- Image Purpose Summary
- Each Line Breakdown
- Performance or Security Concerns (e.g., root user, caching)
- Suggestions for Multi-stage Builds or Image Slimming

Dockerfile:
<YOUR DOCKERFILE>
```

---

### 3. ☸️ Kubernetes YAML – Manifest Breakdown

```text
You are a senior Kubernetes engineer.  
Analyze this Kubernetes manifest and produce documentation suitable for internal runbooks.

Deliver:
- Resource Types and Roles (e.g., Deployment, ConfigMap)
- Image and Volume Usage
- Startup Behavior, Ports, Readiness/Liveness Probes
- RBAC/Networking/Anti-Pattern Alerts

YAML:
<YOUR K8S YAML>
```

---

### 4. ⚙️ CI/CD Pipeline – Optimization Review

```text
You are a DevOps lead specializing in CI/CD systems (GitHub Actions, GitLab CI/CD). 
Audit and document this pipeline configuration for maintainability and performance.

Deliver:
- Overview of Pipeline Purpose and Trigger Logic
- Per-Job Breakdown
- Caching, Parallelization, Retry Logic
- Suggestions for Speed, Security, and Reusability

Pipeline:
<YOUR PIPELINE YAML>
```

---

### 5. 🌍 Terraform – Resource Documentation

```text
You are an infrastructure-as-code expert.  
Review this Terraform code to generate documentation for handoff to a junior engineer.

Deliver:
- Provider Overview
- Resource Map (VPCs, Instances, Volumes, Outputs)
- Tagging and Naming Convention Check
- Suggestions for Reusability with Modules

Terraform Code:
<YOUR .tf FILE>
```

---

### 6. 🐚 Bash Script – Automation Review

```text
You are a DevOps automation expert.  
Review this bash script and create clear inline documentation.

Deliver:
- Script Purpose Summary
- Step-by-Step Commentary
- Security/Idempotency Issues (e.g., unquoted vars, `rm -rf`)
- Suggestions for Refactor (e.g., use Ansible instead)

Script:
<YOUR BASH SCRIPT>
```

---

### 7. 🧷 systemd Service File – Startup Behavior

```text
You are a Linux infrastructure expert. 
Document this systemd unit file for inclusion in our internal wiki.

Deliver:
- Service Purpose & Description
- ExecStart, RestartPolicy, Environment Usage
- Dependency Tree (Before/After)
- Hardening & Logging Options

Unit File:
<YOUR .service FILE>
```

---

### 8. 📈 Prometheus Alerting Rule – Monitoring Audit

```text
You are a monitoring engineer with experience in SRE-grade alerting.
Audit and explain this Prometheus alert rule for the ops team.

Deliver:
- What Metric is Being Monitored
- Alert Triggers & Severity Mapping
- Runbook or Dashboard Links (if any)
- Tuning Suggestions for False Positives

Alert Rule:
<YOUR ALERT RULE>
```

---

### 9. 🔐 Web Server Config – Security-Focused Review

```text
You are a DevSecOps engineer. 
Review this Nginx/Apache config file and produce documentation with a security lens.

Deliver:
- Purpose of Configuration Blocks
- Ports, SSL/TLS, Headers (e.g., HSTS, CSP)
- Performance (gzip, cache) Checks
- Suggestions to Harden or Simplify

Config:
<YOUR CONFIG>
```

---

### 10. 🗄 PostgreSQL Backup Script – DR Documentation

```text
You are a DevOps engineer specializing in backup & disaster recovery.  
Document this PostgreSQL backup script for production environments.

Deliver:
- Backup Scope (All DBs? One Schema?)
- Location & Retention Strategy
- Compression/Encryption Checks
- Suggestions for Cron, Rotation, or pgBackRest

Script:
<YOUR BACKUP SCRIPT>
```

---

### 11. 🧰 Docker Compose – Multi-Service Breakdown

```text
You are a senior container orchestration expert.
Document this Docker Compose file as part of microservice architecture documentation.

Deliver:
- Service-by-Service Breakdown
- Volumes, Networks, Dependencies
- Inter-Service Communication
- Suggestions for Scaling or Breaking into K8s

Compose:
<docker-compose.yml>
```

---

### 12. 🧪 Helm Chart Values – Config Guide

```text
You are a Helm chart maintainer.
Document the values.yaml file to help engineers customize deployments.

Deliver:
- Each Value Purpose and Default
- Conditional Flags (enabled: true/false)
- Resource Requests/Limits
- Security & Access Parameters

values.yaml:
<YOUR VALUES>
```

---

> 🛠 Maintainer: Ahmad Sheikhi – DevOps Architect & Prompt Engineer

This file is production-ready. Clone and use in your Git workflows or documentation pipelines.
