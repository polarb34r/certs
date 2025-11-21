# certs
Azure Certification Paths (Markdown-Ready)
📘 Overview

This document outlines three certification paths for Azure professionals:

Path A: Infrastructure / Azure Administrator

Path B: Developer / DevOps Engineer

Path C: Security Engineer / Cybersecurity Architect

Each includes a visual roadmap and explanations that fit naturally into GitHub README files.

🛠️ Path A — Infrastructure / Azure Administrator
┌====================┐
│   AZ-900           │
│   Azure Basics     │
└=========┬==========┘
          │
          ▼
┌====================┐
│   AZ-104           │
│   Azure Admin      │
│   Core for Infra   │
└=========┬==========┘
          │
    ┌=====┴=======┬===============┐
    │             │               │
    ▼             ▼               ▼
┌================┐ ┌================┐ ┌=================┐
│   AZ-500       │ │   AZ-700       │ │   DP-203        │
│ Security Eng.  │ │ Network Eng.   │ │ Data Eng. Opt.  │
└=======┬========┘ └========┬=======┘ └========┬========┘
        │                    │                  │
        └===========┬========┴===========┬======┘
                    ▼                    ▼
           ┌======================┐  ┌==================┐
           │   AZ-305             │  │   Specialty (Opt) │
           │ Solutions Architect  │  │ IoT / Storage     │
           └======================┘  └==================┘

Summary

Best suited for Cloud Administrators, Infra Engineers, and Cloud Architects.

Focuses on VMs, networking, security, storage, and governance.

Ends at AZ-305, which elevates you to solution design and architecture.

💻 Path B — Developer / DevOps Engineer
┌====================┐
│   (Optional)        │
│   AZ-900            │
│   Fundamentals      │
└=========┬==========┘
          │
          ▼
┌====================┐
│   AZ-204           │
│   Developer Assoc. │
│   Build apps/APIs  │
└=========┬==========┘
          │
          ▼
┌========================┐
│   AZ-400               │
│   DevOps Expert        │
│   CI/CD · IaC · SRE    │
└=========┬==============┘
          │
          ▼
┌========================┐
│  (Optional) AZ-305     │
│  Architect Solutions    │
└========================┘

Summary

Ideal for Cloud Developers, DevOps Engineers, SREs, and Platform Engineers.

AZ-204 builds cloud application development skills.

AZ-400 adds CI/CD, GitHub Actions, automation, pipelines, IaC.

🔐 Path C — Security / Identity / Cybersecurity
┌====================┐
│   AZ-900           │
│   Fundamentals     │
└=========┬==========┘
          │
          ▼
┌========================┐
│   AZ-500               │
│   Security Engineer    │
│   Zero Trust · IAM     │
└=========┬==============┘
          │
    ┌=====┴=============┬=============┐
    │                   │             │
    ▼                   ▼             ▼
┌===============┐ ┌==============┐ ┌===============┐
│   SC-300       │ │   SC-200      │ │   SC-100       │
│ Identity Eng.  │ │ SecOps        │ │ Cyber Architect │
└===============┘ └==============┘ └===============┘

Summary

Best for Security Engineers, SOC Analysts, IAM Specialists, or Cyber Architects.

AZ-500 covers core Azure security controls and tooling.

SC-300 and SC-200 complement by specializing in identity and operations.

SC-100 caps the track by pushing you into architecture-level cybersecurity design.

🗓️ Recommended 12-Month Roadmap (Azure Engineer)

This roadmap works for someone targeting a solid cloud engineering role.

Months 1–2

Study AZ-900

Learn cloud basics, governance, pricing, workloads

Start using Azure Portal + CLI in a sandbox environment

Months 3–5

Study AZ-104

Hands-on labs: VMs, networking, storage, RBAC, monitoring

Begin ARM/Bicep basics

Months 6–8

Choose your specialization:

Option A — Security

Study AZ-500

Option B — DevOps

Study AZ-204 → Begin CI/CD foundations

Option C — Networking

Study AZ-700

Months 9–12

Aim for AZ-305 (Architect)

Build a full sample architecture:

Hub-spoke network

VM + App Service + AKS mix

Key Vault integration

Logging + monitoring

✔️ Bonus: Quick Copy/Paste Index for Your Repo
- /docs
  - azure-paths.md
  - infra-path.md
  - devops-path.md
  - security-path.md
- README.md (link to the 3 paths)



















Azure Certification Paths

A clean and GitHub Pages–friendly guide for Azure Engineers

🌐 Overview

This document describes three major Microsoft Azure certification paths:

Infrastructure / Administrator

Developer / DevOps Engineer

Security / Cybersecurity

Each section contains:

A readable diagram

A short explanation

A suggested progression

🛰️ Path A — Infrastructure / Azure Administrator
Diagram
┌────────────────────┐
│   AZ-900           │
│   Azure Basics     │
└─────────┬──────────┘
          │
          ▼
┌────────────────────┐
│   AZ-104           │
│   Azure Admin      │
│   Core for Infra   │
└─────────┬──────────┘
          │
    ┌─────┴───────────┬──────────────┬──────────────┐
    │                 │              │              │
    ▼                 ▼              ▼              ▼
┌────────────────┐ ┌────────────────┐ ┌────────────────┐ ┌─────────────────┐
│   AZ-500       │ │   AZ-700       │ │   DP-203       │ │   Specialty Opt │
│ Security Eng.  │ │ Network Eng.   │ │ Data Eng.      │ │ IoT/Storage     │
└───────┬────────┘ └────────┬───────┘ └────────┬──────┘ └────────┬────────┘
        │                    │                  │                 │
        └───────────┬────────┴───────────┬──────┴────────────────┘
                    ▼                    ▼
           ┌──────────────────────┐  ┌──────────────────┐
           │   AZ-305             │  │   Architecture    │
           │ Solutions Architect  │  │   Specialties     │
           └──────────────────────┘  └──────────────────┘

Summary

Perfect for: Cloud Administrators, Infra Engineers, System Engineers, Architects

You’ll learn:

Virtual machines

Networking

Identity & RBAC

Storage & backup

Governance

Monitoring

Ends with AZ-305 for full architecture design skills.

💻 Path B — Developer / DevOps Engineer
Diagram
┌────────────────────┐
│   (Optional)       │
│   AZ-900           │
│   Fundamentals     │
└─────────┬──────────┘
          │
          ▼
┌────────────────────┐
│   AZ-204           │
│   Developer Assoc. │
│   Apps, APIs       │
└─────────┬──────────┘
          │
          ▼
┌────────────────────────┐
│   AZ-400               │
│   DevOps Expert        │
│   CI/CD, IaC, SRE      │
└─────────┬──────────────┘
          │
          ▼
┌────────────────────────┐
│   (Optional) AZ-305    │
│   Solutions Architect   │
└────────────────────────┘

Summary

Perfect for: Developers, DevOps Engineers, SREs, Platform Engineers

You’ll learn:

Cloud-native development

API development

Serverless

GitHub Actions & CI/CD

Infrastructure as Code

Cloud automation

🔐 Path C — Security / Identity / Cybersecurity
Diagram
┌────────────────────┐
│   AZ-900           │
│   Fundamentals     │
└─────────┬──────────┘
          │
          ▼
┌────────────────────────┐
│   AZ-500               │
│   Security Engineer    │
│   Zero Trust, IAM      │
└─────────┬──────────────┘
          │
    ┌─────┴───────────────┬─────────────┬──────────────┐
    │                       │             │              │
    ▼                       ▼             ▼              ▼
┌───────────────┐     ┌──────────────┐ ┌───────────────┐
│   SC-300       │     │   SC-200      │ │   SC-100       │
│ Identity Eng.  │     │ SecOps        │ │ Cyber Architect │
└───────────────┘     └──────────────┘ └───────────────┘

Summary

Perfect for: Security Engineers, IAM Engineers, SOC Analysts, Cyber Architects

You’ll learn:

Threat protection

Zero Trust

Identity governance

Defender XDR

Security operations and incident response

📅 12-Month Azure Engineer Roadmap
Months 1–2 — Foundations

Study AZ-900

Learn governance, resource hierarchy, subscriptions, RBAC

Set up a free Azure subscription

Months 3–5 — Core Skills

Study AZ-104

Practice VM, networking, storage, monitoring

Start learning Bicep or Terraform

Months 6–8 — Specialization

Choose one:

Security → AZ-500

DevOps → AZ-204

Networking → AZ-700

Data → DP-203

Months 9–12 — Architecture

Study AZ-305

Build a real architecture diagram

Include Key Vault, VNet design, monitoring, compute, identity

📁 Suggested Repository Structure
docs/
  azure-certification-paths.md
  azure-infrastructure.md
  azure-devops.md
  azure-security.md

assets/
  diagrams/
    infra-path.png
    devops-path.png
    security-path.png

README.md


| Role                | Duration     | Core Certifications                 |
| ------------------- | ------------ | ----------------------------------- |
| DevOps Engineer     | **12 weeks** | AZ-900 → AZ-104 → AZ-204 → AZ-400   |
| AI/ML Engineer      | **14 weeks** | AI-900 → DP-900 → AI-102 → DP-100   |
| Data Engineer       | **12 weeks** | DP-900 → DP-203 → DP-300            |
| Security Engineer   | **10 weeks** | SC-900 → AZ-500 → SC-300/SC-200     |
| Solutions Architect | **12 weeks** | AZ-900 → AZ-104 → AZ-305            |
| Network Engineer    | **10 weeks** | AZ-900 → AZ-700 → AZ-500 (optional) |


# Azure Training Plan — Master Table (All Roles)

| Role | Phase | Duration | Weekly Hours | Certifications | Milestones |
|------|--------|-----------|--------------|----------------|-------------|
| **DevOps Engineer** | Fundamentals | Weeks 1–2 | 5–6 hrs | AZ-900 | Pass AZ-900 |
| DevOps Engineer | Admin Associate | Weeks 3–6 | 5–6 hrs | AZ-104 | Deploy core Azure infra (VM, VNet, Storage) |
| DevOps Engineer | Developer Associate (Optional) | Weeks 7–10 | 5–6 hrs | AZ-204 | Deploy small app + CI pipeline |
| DevOps Engineer | DevOps Expert | Weeks 11–12 | 5–6 hrs | AZ-400 | Implement CI/CD + IaC |
| **AI / ML Engineer** | AI Fundamentals | Weeks 1–2 | 5–6 hrs | AI-900 | Pass AI-900 |
| AI / ML Engineer | Data Fundamentals | Weeks 3–5 | 5–6 hrs | DP-900 | Pass DP-900 |
| AI / ML Engineer | AI Engineer Associate | Weeks 6–9 | 5–6 hrs | AI-102 | Deploy Cognitive Services app |
| AI / ML Engineer | Data Scientist Associate | Weeks 10–14 | 5–6 hrs | DP-100 | Build & deploy ML pipeline |
| **Data Engineer** | Data Fundamentals | Weeks 1–2 | 5–6 hrs | DP-900 | Pass DP-900 |
| Data Engineer | Data Engineer Associate | Weeks 3–8 | 5–6 hrs | DP-203 | Build ETL/ELT pipeline |
| Data Engineer | Database Admin Associate | Weeks 9–12 | 5–6 hrs | DP-300 | Deploy + tune database environment |
| **Security Engineer** | Security Fundamentals | Weeks 1–2 | 5–6 hrs | SC-900 | Pass SC-900 |
| Security Engineer | Security Engineer Associate | Weeks 3–6 | 5–6 hrs | AZ-500 | Deploy secure Landing Zone |
| Security Engineer | IAM or SOC Specialization | Weeks 7–10 | 5–6 hrs | SC-300 or SC-200 | Configure IAM or SOC workflows |
| **Solutions Architect** | Fundamentals | Weeks 1–2 | 5–6 hrs | AZ-900 | Pass AZ-900 |
| Solutions Architect | Admin Associate | Weeks 3–6 | 5–6 hrs | AZ-104 | Deploy Hub-Spoke infra |
| Solutions Architect | Architect Expert | Weeks 7–12 | 5–6 hrs | AZ-305 | Deliver full architecture blueprint |
| **Network Engineer** | Fundamentals | Weeks 1–2 | 5–6 hrs | AZ-900 | Pass AZ-900 |
| Network Engineer | Network Engineer Associate | Weeks 3–6 | 5–6 hrs | AZ-700 | Deploy hybrid network (VPN/ER) |
| Network Engineer | Security Enhancement (Optional) | Weeks 7–10 | 5–6 hrs | AZ-500 | Configure NSG, Firewall, WAF |


