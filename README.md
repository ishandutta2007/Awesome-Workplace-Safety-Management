# Awesome-Workplace-Safety-Management

# Top Workplace Safety Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Incident Reporting, EHS Compliance & Self-Hosted Safety Platforms*  
**Last updated: October 2026**

This repository tracks notable **commercial workplace safety platforms** and **open-source projects** that manage incidents, track corrective actions, ensure regulatory compliance, and promote safer work environments across industries.

**Examples** include Salesforce Work.com, Envoy, Robin Powered, Density, Officespace Software, VergeSense, Archie, Teem by iOFFICE, Eptura, and SpaceIQ (the category leaders).

**Open-source emphasis**: Workplace safety management is a growing open-source domain. **SafeSphere** leads as a comprehensive open-source OSHE platform with AI-powered safety assistance, statutory repositories, and professional exposure calculators . **FlowIntel** delivers a vendor-neutral incident and forensic case management platform co-funded by CIRCL and the European Union . **FireFighter** provides Slack-integrated incident management with Jira synchronization . **Catalyst** brings an open-source SOAR platform for alert handling and incident response automation . **OpsKnight** offers a self-hosted alternative to PagerDuty with SLA management and ChatOps . This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Work.com](https://www.salesforce.com/products/work-com/)**  
  **Salesforce's workplace management platform** — employee wellness, shift scheduling, and workplace safety tools integrated with Salesforce.

- **[Envoy](https://envoy.com/)**  
  **Workplace platform** — visitor management, desk booking, and workplace safety features.

- **[Robin Powered](https://robinpowered.com/)**  
  **Hybrid workplace platform** — desk and room booking, visitor management, and workplace analytics.

- **[Density](https://density.io/)**  
  **Workplace occupancy analytics** — anonymous people counting and space utilization for workplace safety and optimization.

- **[VergeSense](https://www.vergesense.com/)**  
  **Workplace intelligence platform** — occupancy sensors and analytics for space utilization and safety.

- **[Eptura](https://eptura.com/)**  
  **Worktech platform** — workplace management, asset management, and safety compliance.

- **[SpaceIQ](https://spaceiq.com/)**  
  **Workplace management software** — space planning, desk booking, and workplace safety.

## Open-Source GitHub Projects

### Comprehensive EHS & Safety Platforms

- **[SafeSphere](https://github.com/)**  
  **Comprehensive open-source OSHE (Occupational Safety, Health, Environment) platform**, open-source  . **SafeWork AI** — interactive agentic AI assistant answering complex OSH questions based on national statutory guidelines . **National Statutory Repository** — complete database of Indian OSH legislation including OSHWC Code 2020 and Rules . **OSH Calculators** — professional screening tools for Noise Exposure (TWA/Dose), Heat Stress (WBGT), Chemical Exposure (TLV), Ventilation, and Illumination . **Virtual SafeSphere Lab** — interactive virtual laboratory simulations for safety drills, hazard identification, and emergency response training . **First Aid Guidelines** — comprehensive emergency protocols for industrial hazards . **Roadmap**: HIRA, Safety Audit Checklists, Incident Reporting & Analytics, Environmental Monitoring  . **Best for comprehensive open-source EHS management** .

- **[EHS Web Console](https://github.com/topics/safety-management)**  
  **Open-source EHS web console: incidents, CAPA, metrics, documents, training, and audits**, TypeScript  . **Role-aware with PostgreSQL-backed self-hostable architecture** . **Self-hosted EHS console: incidents, CAPA, audits, and TRIR-style metrics** with optional AI suggesting wording only — humans close records  . **Best for self-hosted EHS management with CAPA** .

### Incident Management & Response

- **[FlowIntel](https://github.com/flowintel/flowintel)**  
  **Open-source incident & forensic case management platform**, open-source, co-funded by CIRCL and the European Union  . **Day-to-day CSIRT/SOC work without spreadsheets or expensive closed platforms** . **Tracks cases, tasks, subtasks and their status** . **Organises notes, evidence, timelines and reports** . **Collaboration with shared workspace and templates** . **Built-in calendar & to-do management** . **Deep integration with MISP** — import MISP events as cases, attach MISP-Object, export cases to MISP . **Version 2.0 introduced a completely redesigned UI** with drag-and-drop task reordering, revamped calendar, and cleaner layout  . **Best for incident and forensic case management** .

- **[FireFighter](https://github.com/ManoManoTech/firefighter-incident)**  
  **Incident management application designed to work in Slack**, MIT licensed  . **Automatically creates a Slack channel for communication** . **Integrates with Jira with P1-P5 priority mapping** . **Streamlines incident detection, response, and resolution** . **Best for Slack-integrated incident management** .

- **[Catalyst](https://github.com/levisre/catalyst)**  
  **Open-source SOAR system for automated alert handling and incident response**, open-source  . **Ticket management for alerts, incidents, forensics, and threat hunts** . **Tasks can be assigned to users with status tracking** . **Reactions for automation** — triggers listen for events and execute actions (Python/HTTP) . **Timelines for documenting investigation progress** . **Dashboards for at-a-glance information** . **Custom fields and ticket types** — MITRE ATT&CK integration, affected system, malware type . **Best for SOAR and incident response automation** .

### Self-Hosted On-Call & Incident Operations

- **[OpsKnight](https://github.com/opsknight-labs/OpsKnight)**  
  **Self-hosted alternative to PagerDuty and Opsgenie**, Apache-2.0 licensed  . **Own the incident loop, operational evidence, and data** . **Unified command center** — manage incidents, responders, and runbooks from a single real-time dashboard . **Fair on-call rotations** with flexible scheduling and escalation policies . **Global escalations & war rooms** — multi-channel notifications via Slack, SMS, Email, Push . **Mobile PWA** with push notifications and biometric security . **Public status pages** for user communication . **22+ native integrations** including Prometheus, Datadog, Sentry, CloudWatch, Grafana, Zabbix, GitLab, Vercel . **No seat meter** — users are not priced per-seat . **Best for self-hosted on-call and incident management** .

### Additional Strong Open-Source Options

- **analisis-accidente-trabajo** — Web system for workplace accident analysis and management with interactive dashboard, automated reports, and action plans. Excel data processing with ApexCharts visualizations  .
- **MintHCM** — AI-enabled open-source Human Capital Management system with workplace management, analytics, and mobile apps, AGPL-3.0 licensed  .
- **Kanvas** — Open-source incident response case management tool with Excel backend, Markdown notes, data visualization, and MITRE D3FEND mapping  .
- **TWM (Technology Workplace Manager)** — Modular enterprise management platform with HR, attendance, payroll, logistics, and inventory modules  .
- **HeimDall** — AI-powered organizational platform unifying contracts, tasks, employees, and insights  .
- **LOTO Management System** — Professional Lock Out Tag Out management with React, Node.js, MongoDB, multi-language support  .

**Frameworks for building custom workplace safety solutions**: Combine **SafeSphere** for comprehensive OSHE management with AI assistance and statutory repositories  . Use **FlowIntel** for incident and forensic case management with MISP integration  . Deploy **FireFighter** for Slack-integrated incident management  . Choose **Catalyst** for SOAR and incident response automation  . Integrate **OpsKnight** for self-hosted on-call and incident operations  . Use **EHS Web Console** for self-hosted EHS management with CAPA and TRIR-style metrics  . Note that true enterprise workplace safety platforms with managed infrastructure, global compliance coverage, and vendor-supported SLAs (Salesforce Work.com, Envoy, Eptura) remain primarily commercial territory; open-source stacks provide strong incident management, EHS compliance, and safety analytics foundations that require integration for complete workplace safety management.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Workplace safety platforms handle sensitive incident data and may involve regulatory compliance obligations. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.
- **Regulatory compliance varies by jurisdiction** — workplace safety requirements (OSHA in the US, OSHWC Code 2020 in India, NTS-009/23 in Bolivia) differ significantly. Verify compliance before deployment  .
- **Open-source safety platforms vary significantly in maturity** — SafeSphere and FlowIntel are production-oriented  ; some projects are early-stage or proof-of-concept. Evaluate before relying on them for regulatory-critical workflows.
- The open-source ecosystem provides strong incident management, EHS compliance, and safety analytics foundations, but **managed infrastructure, global compliance coverage, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for safety professionals, EHS managers, and organizations seeking workplace safety sovereignty.**  
Let's make workplace safety management more open, transparent, and proactive.
