# certs
Azure Certification Paths (Markdown-Ready)
📘 Overview

This document outlines three certification paths for Azure professionals:

Path A: Infrastructure / Azure Administrator

Path B: Developer / DevOps Engineer

Path C: Security Engineer / Cybersecurity Architect

Each includes a visual roadmap and explanations that fit naturally into GitHub README files.

🛠️ Path A — Infrastructure / Azure Administrator
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
    ┌─────┴───────┬───────────────┐
    │             │               │
    ▼             ▼               ▼
┌────────────────┐ ┌────────────────┐ ┌─────────────────┐
│   AZ-500       │ │   AZ-700       │ │   DP-203        │
│ Security Eng.  │ │ Network Eng.   │ │ Data Eng. Opt.  │
└───────┬────────┘ └────────┬───────┘ └────────┬────────┘
        │                    │                  │
        └───────────┬────────┴───────────┬──────┘
                    ▼                    ▼
           ┌──────────────────────┐  ┌──────────────────┐
           │   AZ-305             │  │   Specialty (Opt) │
           │ Solutions Architect  │  │ IoT / Storage     │
           └──────────────────────┘  └──────────────────┘

Summary

Best suited for Cloud Administrators, Infra Engineers, and Cloud Architects.

Focuses on VMs, networking, security, storage, and governance.

Ends at AZ-305, which elevates you to solution design and architecture.

💻 Path B — Developer / DevOps Engineer
┌────────────────────┐
│   (Optional)        │
│   AZ-900            │
│   Fundamentals      │
└─────────┬──────────┘
          │
          ▼
┌────────────────────┐
│   AZ-204           │
│   Developer Assoc. │
│   Build apps/APIs  │
└─────────┬──────────┘
          │
          ▼
┌────────────────────────┐
│   AZ-400               │
│   DevOps Expert        │
│   CI/CD · IaC · SRE    │
└─────────┬──────────────┘
          │
          ▼
┌────────────────────────┐
│  (Optional) AZ-305     │
│  Architect Solutions    │
└────────────────────────┘

Summary

Ideal for Cloud Developers, DevOps Engineers, SREs, and Platform Engineers.

AZ-204 builds cloud application development skills.

AZ-400 adds CI/CD, GitHub Actions, automation, pipelines, IaC.

🔐 Path C — Security / Identity / Cybersecurity
┌────────────────────┐
│   AZ-900           │
│   Fundamentals     │
└─────────┬──────────┘
          │
          ▼
┌────────────────────────┐
│   AZ-500               │
│   Security Engineer    │
│   Zero Trust · IAM     │
└─────────┬──────────────┘
          │
    ┌─────┴─────────────┬─────────────┐
    │                   │             │
    ▼                   ▼             ▼
┌───────────────┐ ┌──────────────┐ ┌───────────────┐
│   SC-300       │ │   SC-200      │ │   SC-100       │
│ Identity Eng.  │ │ SecOps        │ │ Cyber Architect │
└───────────────┘ └──────────────┘ └───────────────┘

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
