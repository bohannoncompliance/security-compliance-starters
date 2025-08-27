## Security & Compliance Starters$

##  Automation to help startups and SMBs get audit-ready fast.

This repository contains demo playbooks, scripts, and evidence templates designed to give organizations a jumpstart on security baselines aligned with frameworks such as SOC 2, ISO 27001, and CIS Benchmarks.

---

##  Who This Is For$
- Startups preparing for SOC 2 or ISO 27001 audits
- Small businesses that need to show secure practices to insurers or clients
- DevOps teams looking for repeatable Linux hardening and evidence packs

---

##  What's Inside$
- /compliance-ansible  Ansible playbook for baseline hardening
  - Logging & audit service enabled (`auditd`)
  - Time synchronization enforced (`chrony`)
  - Basic password policy control (`PASS_MAX_DAYS`)
  - Generates a lightweight Markdown report
- /docs  Evidence templates
  - Sample Evidence Log
  - SOP / Change Log / Control Map (expandable for audits)

---

##  Quick Start$
    Clone this repo:
   #!/bin/bash
    git clone https://github.com/bohannoncompliance/security-compliance-starters.git
    cd security-compliance-starters/compliance-ansible

    Run the playbook against a test host:

ansible-playbook -i <your_inventory_file> playbook.yml

Collect the evidence report:

    cat /tmp/compliance_report.md

##  What You Get

    Working automation examples (ready to expand for your environment)

    Audit-friendly reports (Markdown/HTML logs to hand to auditors or insurers)

    Clear documentation (how controls map to common frameworks)

##  How to Use

    Use as a starting point for your organization's SOC 2 or ISO 27001 compliance.

    Extend the playbook with additional controls (firewall configs, MFA, backup tests).

    Adapt the evidence templates to your own audit binder or compliance platform.

##  Work With Me

    This repository is a demo of what I build for clients.

    If you need:

       A fixed-price SOC 2 Script Pack (baseline checks + report)

       A Security Hardening Jumpstart (logging, patching, MFA plan, backup checklist)

       Or a DevOps & Compliance Starter Kit (automation pipeline + evidence packs)

       Contact me on Upwork or connect on LinkedIn.

##  Disclaimer

This repo is for educational/demo purposes only.
Before production use, controls must be adapted, validated, and approved for your environment.
