# Awesome-Integrated-Financial-Suite

# Awesome-Integrated-Financial-Suite

## Top Incident Response & Incident Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on On-Call Scheduling, Alert Routing, Escalation Policies, ChatOps, Postmortems & Status Pages*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Incident Response & Incident Management**. These tools streamline alert aggregation, on-call rotations, escalation workflows, war-room collaboration (Slack/Teams), automated runbooks, root cause analysis (RCA), and stakeholder status communication.



**Examples** include Zoho Response, PagerDuty, Opsgenie, VictorOps (Splunk On-Call), FireHydrant, Rootly, Incident.io, xMatters, BigPanda, and ServiceNow Incident Management (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, alert deduplication, automated remediation, and status page hosting — ideal for SREs, DevOps teams, SOC analysts, and platform engineers building resilient incident response workflows.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[PagerDuty](https://pagerduty.com)**  

  Industry-leading digital operations management platform offering real-time alerting, on-call scheduling, escalation policies, and AIOps automation.



- **[Incident.io](https://incident.io)**  

  Modern, Slack-native incident management platform covering alert routing, on-call schedules, automated timelines, and status pages.



- **[Rootly](https://rootly.com)**  

  End-to-end incident management and on-call platform automating Slack workflows, Jira ticketing, Zoom war rooms, and postmortems.



- **[FireHydrant](https://firehydrant.com)**  

  Reliability and incident management platform providing automated runbooks, service catalogs, on-call alerting, and retrospective analytics.



- **[Opsgenie (Atlassian)](https://atlassian.com)**  

  Alerting and on-call management solution tightly integrated with Jira Service Management, Confluence, and Bitbucket.



- **[Splunk On-Call (formerly VictorOps)](https://splunk.com)**  

  DevOps-focused incident response platform combining real-time alert routing, timeline collaboration, and observability context.



- **[xMatters (Everbridge)](https://xmatters.com)**  

  Service reliability and incident response automation platform connecting monitoring tools with targeted on-call notifications.



- **[BigPanda](https://bigpanda.io)**  

  Event correlation and AIOps automation platform that deduplicates noisy monitoring alerts into actionable incidents.



- **[ServiceNow Incident Management](https://servicenow.com)**  

  Enterprise IT service management (ITSM) suite for logging, triaging, escalating, and resolving IT service disruptions.



- **[Zoho Response (Zoho Desk / Site24x7)](https://zoho.com)**  

  Integrated customer support and IT incident response tooling for tracking outages, SLA escalations, and cross-team resolution.



## Open-Source GitHub Projects



- **[Grafana OnCall](https://github.com)**  

  Developer-friendly open-source incident response and on-call management tool integrated with Grafana, Prometheus, Alertmanager, and Slack.



- **[GoAlert](https://github.com)**  

  Open-source on-call scheduling, automated escalation, and multi-channel notification platform (SMS, voice, Slack, webhooks) built by Target.



- **[Dispatch (by Netflix)](https://github.com)**  

  Crisis and incident management orchestration framework that integrates with Slack, Jira, Google Workspace, and Zoom to spin up incident resources automatically.



- **[Keep](https://github.com)**  

  Open-source AIOps and alert management platform enabling alert deduplication, correlation, enrichment, and automated workflows across monitoring stacks.



- **[ Cabot](https://github.com)**  

  Self-hosted, lightweight infrastructure monitoring and alerting service providing PagerDuty-like phone, SMS, HipChat, and email alerts.



- **[Prometheus Alertmanager](https://github.com)**  

  Core open-source alert handling engine responsible for deduplicating, grouping, silencing, inhibiting, and routing alerts to receivers.



- **[Robusta](https://github.com)**  

  Open-source Kubernetes troubleshooting and alert automation platform that enriches Prometheus alerts with logs, graphs, and auto-remediation playbooks.



- **[Iris (by LinkedIn)](https://github.com)**  

  Highly scalable open-source incident alerting and escalation routing system supporting dynamic schedules and multi-channel notifications.



- **[Oncall (by LinkedIn)](https://github.com)**  

  Open-source calendar and shift-scheduling web application designed for creating and managing engineering on-call rotations.



- **[TheHive](https://github.com)**  

  Scalable open-source Security Incident Response Platform (SIRP) built for SOC teams to collaborate on investigations, observables, and tasks.



- **[DFIR-IRIS](https://github.com)**  

  Collaborative open-source digital forensics and incident response platform enabling security analysts to track timelines, IOCs, and assets.



- **[Shuffle](https://github.com)**  

  Open-source Security Orchestration, Automation, and Response (SOAR) platform for building visual incident response playbooks.



- **[Uptime Kuma](https://github.com)**  

  Self-hosted, easy-to-use monitoring and alerting tool with multi-channel notifications (Telegram, Discord, Slack, PagerDuty, webhooks) and status pages.



- **[Cachet](https://github.com)**  

  Open-source status page system for communicating service incidents, scheduled maintenance, and real-time component health to users.



- **[Gatus](https://github.com)**  

  Developer-oriented automated health dashboard and incident alerting tool configurable via YAML with built-in status pages.



- **[Statping-ng](https://github.com)**  

  Open-source status page and uptime monitor for web applications and APIs with automated incident notifications.



- **[OneUptime](https://github.com)**  

  Complete open-source observability and incident management suite combining status pages, on-call duty, incident response, and log monitoring.



- **[Postmortem Templates & Runbook Engines (Rundeck)](https://github.com)**  

  Open-source runbook automation and operational orchestration platform enabling self-service incident remediation procedures.



- **[Opsdroid](https://github.com)**  

  Open-source ChatOps bot framework written in Python for triggering incident workflows directly from Slack, Matrix, and Mattermost.



- **[Errbot](https://github.com)**  

  Extensible Python chatbot framework enabling teams to execute deployment, triage, and incident response commands inside chat rooms.



### Additional Strong Open-Source Options



- **[Alertmanager Webhook Receivers & Bridges](https://github.com)** for connecting Prometheus alerts to custom incident ticketing and voice/SMS gateways.

- **[Blameless Postmortem & RCA Templates](https://github.com)** for standardized incident timelines, 5-Whys analysis, and action-item tracking.

- **[ChatOps Slash-Command Bots](https://github.com)** for declaring incidents, assigning Incident Commanders, and archiving war rooms.

- **[SOAR & Threat Hunting Playbooks](https://github.com)** for automated containment and forensic evidence collection.

- Many community **Terraform providers** and **Helm charts** for codifying escalation policies, alert rules, and on-call rotations as code.



**Frameworks for building custom systems**: Combine **Prometheus Alertmanager** or **Keep** with **Grafana OnCall / GoAlert**, **Dispatch**, and **Uptime Kuma / OneUptime** alongside **Rundeck** for automated, end-to-end self-hosted incident management.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Incident response systems must maintain high availability, out-of-band alerting, and strict access controls during outages.

- Self-hosted open-source solutions should be deployed on isolated infrastructure separate from the primary production workloads they monitor.



---



**Made for SREs, DevOps engineers, SOC analysts, and platform reliability teams.**  

Let's make incident detection, response, and recovery faster, calmer, and more open.
