# Awesome CI/CD & Project Management Tool Connectors

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](LICENSE)
[![Tracked Connectors](https://img.shields.io/badge/Connectors_Tracked-20+-blue.svg)](#saas-platforms)

> A curated list of production-ready SaaS integration platforms, open-source workflow automation engines, and cross-platform connectors bridging CI/CD pipelines with project management, issue tracking, and team collaboration tools.

---

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS Platforms](#saas-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Architecture & Key Integration Patterns](#architecture--key-integration-patterns)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## Sector Overview & Market Dynamics

The integration middleware and workflow automation sector is valued between **$32 billion and $45 billion** globally (with Integration Platform as a Service / iPaaS accounting for ~$10B–$15B and enterprise workflow automation representing ~$25B–$30B), growing at a compound annual growth rate (CAGR) of 19% to 24%.

The market is **moderately fragmented**: mega-ecosystem incumbents (Microsoft, Salesforce, Atlassian, and ServiceNow) capture roughly 30% of aggregate enterprise volume through native app directories and operating systems of record, while the remaining 70% is distributed across dedicated cloud iPaaS providers (Zapier, Make), developer-centric continuous delivery tools (GitLab, CircleCI, BrowserStack), and a thriving tier of open-source self-hosted automation engines.

---

## SaaS Platforms

Below is a comparison of leading hosted CI/CD connectors, project management bridges, and workflow automation platforms, sorted by **Company Valuation / Market Cap (Descending)**.

| Product | Company Valuation / Market Cap | Description | Pricing (Starting Tier) | Free Tier / Trial Limits |
|:---|:---|:---|:---|:---|
| **[Microsoft Teams Store](https://learn.microsoft.com/en-us/microsoftteams/platform/)** | ~$3.85T (Microsoft Market Cap) | Enterprise chat and collaboration hub with native extensions connecting Azure DevOps, GitHub, Jira, and Jenkins for build alerts, approvals, and agile cards. | **$4.00/user/month** (Microsoft Teams Essentials, billed annually) | **Free forever**: Unlimited 1-on-1 meetings up to 30 hrs, group meetings up to 60 mins (100 participants), 5 GB cloud storage per user. |
| **[GitHub Marketplace](https://github.com/marketplace)** | ~$2.0B ARR (Microsoft Subsidiary, ~$3.85T Parent) | Central developer hub for GitHub Actions, webhook integrations, and project management apps linking commits and PRs to Jira, Trello, and Linear. | **$4.00/user/month** (GitHub Team, billed monthly/annually) | **Free forever**: Unlimited public/private repos, 2,000 Actions CI/CD mins/month, 500 MB package storage, community support. |
| **[Azure DevOps Extensions](https://marketplace.visualstudio.com/azuredevops)** | Enterprise Division (Microsoft, ~$3.85T Parent) | Visual Studio Marketplace extensions enabling bidirectional sync between Azure Pipelines/Boards and BrowserStack, Slack, Jenkins, and Jira. | **$6.00/user/month** (Basic Plan, 6th user onwards) | **Free forever**: First 5 users free with Azure Boards, Repos, 1 hosted pipeline job (1,800 mins/mo), and 2 GiB Artifacts storage. |
| **[Slack App Directory](https://slack.com/apps)** | ~$178B (Salesforce Market Cap; acquired for $27.7B) | Central chatOps integration directory with 2,600+ apps connecting GitHub, GitLab, Jira, and Bitbucket directly into operational team channels. | **$7.25/user/month** (Slack Pro, billed annually) | **Free forever**: 90-day message history, 10 app integrations, 1-on-1 voice/video huddles, 5 GB storage. |
| **[Atlassian Marketplace](https://marketplace.atlassian.com/)** | ~$44B (Atlassian NASDAQ: TEAM Market Cap) | Ecosystem of 5,000+ connectors and apps unifying Jira Software, Confluence, and Bitbucket with CI/CD runners, release pipelines, and testing grids. | **$9.70/user/month** (Jira Cloud Standard, 1–100 user tier) | **Free forever**: Up to 10 users, 2 GB file storage, Scrum/Kanban boards, standard backlog and reporting. |
| **[Make](https://www.make.com/)** | ~$13B (Celonis Subsidiary Valuation) | Visual iPaaS and workflow builder featuring 3,000+ modular connectors for multi-step DevOps routing, Jira status sync, and webhook transformations. | **$9.00/month** (Core plan, 10,000 operations, billed annually) | **Free forever**: 1,000 operations/month, 2 active scenarios, 15-minute execution interval, 5-minute max execution duration. |
| **[GitLab Integrations](https://docs.gitlab.com/ee/integration/)** | ~$8.5B (GitLab NASDAQ: GTLB Market Cap) | Built-in native connector suite bridging GitLab CI/CD pipelines, merge requests, and issues with Jira, Slack, MS Teams, Bugzilla, and Jenkins. | **$29.00/user/month** (GitLab Premium, billed annually) | **Free forever**: Up to 5 users per namespace, 400 CI/CD compute minutes/month, 5 GiB storage, 10 GiB transfer/month. |
| **[Postman](https://www.postman.com/)** | ~$5.6B (Series D Valuation) | API platform with integrations bridging CI/CD pipelines (GitHub Actions, GitLab, Jenkins) with automated API testing and incident/issue management. | **$19.00/user/month** (Team plan, billed annually) | **Free forever**: Single user, unlimited API collections and mock calls, 1,000 API monitoring runs/month, 50 AI credits/month. |
| **[Zapier](https://zapier.com/)** | ~$5.0B (Private Valuation) | Leading no-code automation platform with 7,000+ connectors orchestrating triggers and actions across GitHub, Jira, Asana, Monday.com, and Slack. | **$19.99/month** (Professional plan, 750 tasks/month, billed annually) | **Free forever**: 100 tasks/month, single-step Zaps (1 trigger, 1 action), 15-minute update polling; 14-day Pro trial with 1,000 tasks. |
| **[BrowserStack Third-Party Integrations](https://www.browserstack.com/)** | ~$4.0B (Series B Valuation) | Cloud testing grid with 150+ native connectors piping automated test execution results directly into Jira, GitHub, Jenkins, Azure Pipelines, and Slack. | **$12.50/month** (Automate Desktop base tier, billed annually) | **Free trial**: 1-minute automated test runs, 30 minutes live manual interactive testing; lifetime free access for verified open-source projects. |
| **[CircleCI](https://circleci.com/)** | ~$1.7B (Series F Valuation) | Cloud-native CI/CD orchestration engine using reusable "Orbs" to automate deployments, notify Slack/Teams, and update Jira issues. | **$15.00/month** (Performance plan, includes 5 seats and 30,000 credits) | **Free forever**: Up to 5 active users, 30,000 credits/month (~3,000 build minutes on Linux Medium), 30 concurrent jobs, 1-hr max job runtime. |
| **[CloudBees CI / Jenkins Plugins](https://www.cloudbees.com/)** | ~$1.2B (Series F Valuation) | Enterprise governance suite backing the Jenkins ecosystem, orchestrating multi-controller CI/CD pipelines with Jira, ServiceNow, and Git providers. | **$30.00/user/month** (CloudBees Team entry tier estimate; custom annual quote for enterprise CI) | **Free trial**: 14-day trial of CloudBees Platform; core Jenkins software and community plugins are 100% free and open-source forever. |

---

## Open-Source GitHub Projects

Self-hosted, vendor-neutral integration platforms, CI/CD runners, and workflow orchestrators. Sorted by **GitHub Stars (Descending)**.

| Project | Stars | Primary Focus | Description |
|:---|:---|:---|:---|
| **[n8n](https://github.com/n8n-io/n8n)** | [![Stars](https://img.shields.io/github/stars/n8n-io/n8n?style=social&color=white)](https://github.com/n8n-io/n8n/stargazers) | Workflow Automation & iPaaS | Fair-code workflow automation tool with 400+ native nodes connecting GitHub, GitLab, Jira, Slack, Discord, and REST APIs without per-task limits. |
| **[Ansible](https://github.com/ansible/ansible)** | [![Stars](https://img.shields.io/github/stars/ansible/ansible?style=social&color=white)](https://github.com/ansible/ansible/stargazers) | IT Automation & Configuration | Radically simple IT automation engine automating cloud provisioning, configuration management, application deployment, and continuous delivery. |
| **[Huginn](https://github.com/huginn/huginn)** | [![Stars](https://img.shields.io/github/stars/huginn/huginn?style=social&color=white)](https://github.com/huginn/huginn/stargazers) | Event Orchestration & Scraping | Self-hosted system for building agents that read the web, watch for events, and trigger webhooks across development tools and chat services. |
| **[ToolJet](https://github.com/ToolJet/ToolJet)** | [![Stars](https://img.shields.io/github/stars/ToolJet/ToolJet?style=social&color=white)](https://github.com/ToolJet/ToolJet/stargazers) | Low-Code Internal Tooling | Low-code framework to build internal developer portals and dashboards connected to GitHub, Jira, PostgreSQL, Slack, and CI/CD pipelines. |
| **[Drone CI](https://github.com/harness/drone)** | [![Stars](https://img.shields.io/github/stars/harness/drone?style=social&color=white)](https://github.com/harness/drone/stargazers) | Container-Native CI/CD | Self-service continuous integration and delivery platform using Docker containers with an extensive plugin library for notification and status sync. |
| **[Jenkins](https://github.com/jenkinsci/jenkins)** | [![Stars](https://img.shields.io/github/stars/jenkinsci/jenkins?style=social&color=white)](https://github.com/jenkinsci/jenkins/stargazers) | Continuous Integration | Leading open-source automation server with 1,800+ community plugins connecting SCM repositories, build pipelines, bug trackers, and communication tools. |
| **[Activepieces](https://github.com/activepieces/activepieces)** | [![Stars](https://img.shields.io/github/stars/activepieces/activepieces?style=social&color=white)](https://github.com/activepieces/activepieces/stargazers) | Open-Source Zapier Alternative | No-code business and developer automation tool with 200+ TypeScript-native connectors for GitHub, Linear, Jira, Slack, and Discord. |
| **[Argo CD](https://github.com/argoproj/argo-cd)** | [![Stars](https://img.shields.io/github/stars/argoproj/argo-cd?style=social&color=white)](https://github.com/argoproj/argo-cd/stargazers) | GitOps Continuous Delivery | Declarative GitOps continuous delivery tool for Kubernetes that links Git commits directly to live cluster states with webhook and notification integrations. |
| **[Temporal](https://github.com/temporalio/temporal)** | [![Stars](https://img.shields.io/github/stars/temporalio/temporal?style=social&color=white)](https://github.com/temporalio/temporal/stargazers) | Resilient Workflow Orchestration | Open-source platform for orchestrating mission-critical multi-step deployment pipelines, long-running CI jobs, and cross-system sync flows. |
| **[Prefect](https://github.com/PrefectHQ/prefect)** | [![Stars](https://img.shields.io/github/stars/PrefectHQ/prefect)](https://github.com/PrefectHQ/prefect/stargazers) | Workflow Orchestration | Python-native workflow engine with built-in task scheduling, failure recovery, and notification connectors for modern platform engineering. |
| **[Argo Workflows](https://github.com/argoproj/argo-workflows)** | [![Stars](https://img.shields.io/github/stars/argoproj/argo-workflows?style=social&color=white)](https://github.com/argoproj/argo-workflows/stargazers) | Kubernetes Workflow Engine | Container-native workflow engine orchestrating parallel jobs, continuous delivery pipelines, and step-by-step CI tasks natively on Kubernetes. |
| **[Tekton Pipelines](https://github.com/tektoncd/pipeline)** | [![Stars](https://img.shields.io/github/stars/tektoncd/pipeline?style=social&color=white)](https://github.com/tektoncd/pipeline/stargazers) | Cloud-Native CI/CD Framework | Kubernetes-native framework for creating reusable, composable continuous integration and delivery systems with event triggers. |
| **[Woodpecker CI](https://github.com/woodpecker-ci/woodpecker)** | [![Stars](https://img.shields.io/github/stars/woodpecker-ci/woodpecker?style=social&color=white)](https://github.com/woodpecker-ci/woodpecker/stargazers) | Lightweight CI/CD Engine | Community-driven container-based CI engine forked from Drone with complete pipeline configuration in YAML and webhook notifications. |
| **[Concourse CI](https://github.com/concourse/concourse)** | [![Stars](https://img.shields.io/github/stars/concourse/concourse?style=social&color=white)](https://github.com/concourse/concourse/stargazers) | Pipeline-Based Automation | Concourse provides a visual, pipeline-first approach to continuous delivery where every job and resource is an immutable container. |
| **[StackStorm](https://github.com/StackStorm/st2)** | [![Stars](https://img.shields.io/github/stars/StackStorm/st2?style=social&color=white)](https://github.com/StackStorm/st2/stargazers) | Event-Driven Automation | Powerful event-driven DevOps automation platform with sensor and action packs connecting Jira, Slack, Jenkins, and cloud providers. |
| **[Rundeck](https://github.com/rundeck/rundeck)** | [![Stars](https://img.shields.io/github/stars/rundeck/rundeck?style=social&color=white)](https://github.com/rundeck/rundeck/stargazers) | Runbook Automation | Open-source runbook automation service providing self-service operations, role-based access control, and integration with ticketing systems. |
| **[RunWright](https://github.com/PramodKumarYadav/runwright)** | [![Stars](https://img.shields.io/github/stars/PramodKumarYadav/runwright?style=social&color=white)](https://github.com/PramodKumarYadav/runwright/stargazers) | Test Execution Optimizer | Intelligent GitHub Action that dynamically scales CI runners based on Playwright test suite duration and shard distribution. |

---

## Architecture & Key Integration Patterns

When connecting CI/CD pipelines to project management systems, platform teams commonly employ three distinct architectural patterns:

```
+--------------------------------------------------------------------------------------------------+
|                                CI/CD & Project Management Connectors                              |
+--------------------------------------------------------------------------------------------------+
|                                                                                                  |
|  [ CI/CD Pipelines ]           [ Integration Middleware ]          [ Project Management & Ops ]  |
|  - GitHub Actions              - n8n / Activepieces (OSS)          - Jira / Linear / Asana       |
|  - GitLab CI / Jenkins   ===>  - Zapier / Make (iPaaS)       ===>  - Slack / Microsoft Teams     |
|  - CircleCI / Argo CD          - Event Webhooks / APIs             - Incident & Ops Dashboards   |
|                                                                                                  |
+--------------------------------------------------------------------------------------------------+
```

1. **Webhook-Driven Event Forwarding**: Lightweight HTTP callbacks triggered on pipeline completion (e.g., commit push, test pass/fail) sending payloads to chat channels or issue trackers.
2. **Bidirectional State Synchronization**: Full synchronization engines that transition Jira/Linear tickets when a pull request merges, and conversely trigger CI builds when a sprint issue enters a specific status.
3. **Quality Gates & Governance Connectors**: Pre-deployment validation bridges (e.g., BrowserStack automated test reports, SonarQube quality gates) preventing production rollouts unless project acceptance criteria and security checks pass.

---

## How to Contribute

We welcome additions, fixes, and updates from the community!

1. **Fork** this repository.
2. **Add or update** entries in `README.md` following the existing format:
   - For SaaS products: Include specific starting tier pricing, explicit free tier / trial limits, and official company valuation / market cap.
   - For Open-Source projects: Include active GitHub link, social white star badge linking to `/stargazers`, and 1–2 sentence description.
3. Ensure tables remain **sorted** (SaaS by Valuation descending, OSS by Star count descending).
4. **Submit a Pull Request** with a concise description of your additions.

---

## Disclaimer

- This list is **community-curated** for educational and architectural reference — not a paid endorsement.
- SaaS pricing structures, marketplace revenue shares, and free tier limits change frequently; verify directly with each vendor's documentation before making purchasing decisions.
- Secure all connector API keys, OAuth tokens, and webhook secrets using secrets managers (such as HashiCorp Vault or cloud provider KMS) with least-privilege permissions.
