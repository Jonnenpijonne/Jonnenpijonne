# Jonne Silvennoinen 👋🏻

**DevSecOps Engineer | Governance & Compliance Automation | Regulated Environments | ISO 27001 · MDR · NIS2**

![Compliance-aware](https://img.shields.io/badge/Compliance%20aware-Security%20focused-darkblue?style=for-the-badge)
![DevSecOps](https://img.shields.io/badge/DevSecOps-Quality%20Automation-orange?style=for-the-badge)
![CI/CD Quality Gates](https://img.shields.io/badge/CI%2FCD-Quality%20Gating-blue?style=for-the-badge)
![Local First](https://img.shields.io/badge/Local--First-Dev%20%26%20AI%20Workflows-purple?style=for-the-badge)

![Solution Designer](https://img.shields.io/badge/role-Solution%20Designer-orangered)
![Infrastructure & Platform](https://img.shields.io/badge/role-Infrastructure%20%26%20Platform%20Engineer-brightgreen)
![Governance & Auditability](https://img.shields.io/badge/focus-Governance%20%26%20Auditability-darkblue)
![Operational Security](https://img.shields.io/badge/focus-Operational%20Security-black)

## About

I design and validate secure infrastructure, governance-aware workflows and compliance-driven technical solutions.

My work focuses on reliable, auditable delivery where configuration, testing, documentation and validation prevent issues from reaching end users. I operate across public-sector, healthcare-adjacent, regulated and infrastructure-heavy environments with attention to operational reliability, governance and controlled change.

My work aligns strongly with DevSecOps principles: security and compliance built into CI/CD pipelines, automated validation gates, local-first development safety and audit-ready delivery rather than post-hoc controls.

I’m strongest in designing and building portable, validated, documentation-driven solutions end-to-end. I may not yet own large-scale production platforms end-to-end, but I build systems and governance structures that are ready to be reviewed, transferred, operated and improved by others.

![Documentation & Tests](https://img.shields.io/badge/If%20it's%20not%20documented%20and%20tested-it%20doesn't%20exist-brightgreen?style=for-the-badge)
![Code is Debt](https://img.shields.io/badge/Code%20is%20Debt-Documentation%20is%20an%20Asset-darkblue?style=for-the-badge)
![Tests & Evidence](https://img.shields.io/badge/Tests%20%26%20Evidence-Make%20Systems%20Transferable-brightgreen?style=for-the-badge)
![Complexity Principle](https://img.shields.io/badge/Complexity%20is%20not%20maturity-Know%20what%20not%20to%20build%20yet-orange?style=for-the-badge)

## How I think

As a developer, I care about repeatability, validation and evidence.

As an operator, I care about recoverability, ownership and clear boundaries.

As an architect, I care about knowing what not to build yet.

**Code is debt.**

Not because code is bad, but because every line creates future responsibility: maintenance, security, documentation, testing, ownership and operational risk.

Documentation is an asset when it makes the system understandable, transferable and recoverable.

Tests and audit evidence are what keep technical debt from becoming organizational risk.

I do not try to build perfect final-state systems for imagined final-state worlds.

I prefer lightweight, auditable and recoverable structures where the right solution can evolve safely without the project collapsing under its own complexity.

**Complexity is not maturity.**
**Maturity is knowing what not to build yet.**

## Portfolio architecture

```mermaid
flowchart TB
    ME["Jonne Silvennoinen<br/>DevSecOps / Governance / Regulated IT"]

    GH["Gatehouse<br/>Infrastructure Change Quality Gate"]
    RBAC["RBAC-Lite<br/>Access-control governance example"]
    LOCAL["Local-First WordPress DevSecOps Kit<br/>Docker + privacy + AI boundaries"]
    ITSM["AI-ITSM Compliance Auto<br/>documentation & compliance workflows"]
    HAAS["HaaS<br/>reproducible infra / lifecycle thinking"]
    HOMESTACK["HomeStack<br/>GitLab infra foundation"]

    ME --> GH
    ME --> RBAC
    ME --> LOCAL
    ME --> ITSM
    ME --> HAAS
    ME --> HOMESTACK

    GH -->|"risk classes / approval / rollback / evidence"| GOV["Governance & auditability"]
    RBAC -->|"partner isolation / RBAC / NDA / audit log"| GOV
    LOCAL -->|"local dev / no prod data / AI boundaries"| GOV
    ITSM -->|"workflow documentation / compliance automation"| GOV
    HAAS -->|"repeatable runtime / lifecycle"| OPS["Operability & recovery"]
    HOMESTACK -->|"IaC foundation / CI/CD structure"| OPS

    GOV --> VALUE["Controlled change<br/>transferable systems<br/>lower operational risk"]
    OPS --> VALUE

    classDef core fill:#eef,stroke:#447,stroke-width:1px;
    classDef gov fill:#efe,stroke:#474,stroke-width:1px;
    classDef value fill:#fff3cd,stroke:#aa7,stroke-width:1px;

    class ME,GH,RBAC,LOCAL,ITSM,HAAS,HOMESTACK core;
    class GOV,OPS gov;
    class VALUE value;
```

## Current

* **Location:** Finland
* **Available:** Selective opportunities in Cloud Infrastructure, DevSecOps, Compliance Automation, Technical Consulting and regulated IT environments
* **Background:** Co-founder & Regulatory Lead experience in a MedTech startup context — ISO 13485 / MDR environment
* **Direction:** Secure infrastructure delivery, compliance-driven environments, IAM/RBAC, CI/CD quality gates, local-first development safety and operational governance
* **Core theme:** Building compliance automation and operational clarity as a response to governance debt in hype-driven development culture

## Core skills

* Azure & cloud governance foundations
* Microsoft 365 / Entra ID foundations
* Active Directory / hybrid identity fundamentals
* Infrastructure as Code thinking
* Docker Compose based development environments
* CI/CD automation and pipeline validation
* GitHub Actions quality gates
* MDR / ISO 27001-aligned documentation exposure
* ITIL 4 and operational processes
* Technical documentation and validation plans
* Audit-ready artefacts and evidence chains
* Access-control governance / RBAC thinking
* AI-assisted development with clear operational boundaries
* Local-first AI workflows and development data safety

## Tech stack & tooling

<!-- Platform & OS -->

![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge\&logo=linux\&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge\&logo=windows\&logoColor=white)

<!-- Cloud & identity -->

![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge\&logo=microsoft-azure\&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft%20365-0078D4?style=for-the-badge\&logo=microsoft\&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra%20ID-Identity%20%26%20Access-0078D4?style=for-the-badge)
![Active Directory](https://img.shields.io/badge/Active%20Directory-Hybrid%20Identity-003B57?style=for-the-badge)

<!-- Containers & CI -->

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-Local%20Runtime-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge\&logo=githubactions\&logoColor=white)

<!-- IaC & scripting -->

![YAML](https://img.shields.io/badge/YAML-000000?style=for-the-badge\&logo=yaml\&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge\&logo=gnu-bash\&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-012456?style=for-the-badge\&logo=powershell\&logoColor=white)

<!-- Languages & tooling -->

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Data%20%26%20Validation-012456?style=for-the-badge)
![Rust](https://img.shields.io/badge/Rust-Tooling%20Exposure-000000?style=for-the-badge\&logo=rust\&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-WordPress%20Context-777BB4?style=for-the-badge\&logo=php\&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-Platform%20Development-21759B?style=for-the-badge\&logo=wordpress\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Basic%20Working%20Knowledge-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-Basic%20Working%20Knowledge-339933?style=for-the-badge\&logo=node.js\&logoColor=white)
![HTTP/HTTPS](https://img.shields.io/badge/HTTP%20%2F%20HTTPS-Protocol%20%26%20Security-informational?style=for-the-badge)

I use these tools primarily for:

* building reproducible infrastructure
* validating changes through CI/CD
* producing audit-ready documentation and evidence
* making systems easier to review, recover and transfer between teams
* reducing local development drift and onboarding friction
* keeping AI-assisted development inside clear operational boundaries

Detailed areas:

* **Operating systems:** Linux, Windows
* **Cloud & identity:** Microsoft 365, Azure, Entra ID / Azure AD foundations, Active Directory fundamentals
* **Containers & runtime:** Docker, Docker Compose
* **CI/CD & automation:** GitHub Actions, validation workflows, quality gates
* **Infrastructure & configuration:** Infrastructure as Code thinking, YAML, repeatable runtime configuration
* **Scripting:** Bash, PowerShell, Python
* **Languages / tooling exposure:** Python, PHP / WordPress context, Rust tooling exposure, SQL, JavaScript / Node.js basics
* **ITSM & operations:** ITIL 4 practices, service processes, compliance workflows
* **AI & automation:** local-first AI workflows, RAG concepts, AI-agent boundaries, API-driven documentation automation
* **Documentation & validation:** technical documentation, validation plans, audit-ready artefacts, CLI-first repeatable scripts
* **Security & compliance exposure:** MDR, ISO 27001-aligned environments, GDPR-aware development practices, regulated delivery

## Project badges

![Auto Assign](https://github.com/JonSil89/demo-repository/actions/workflows/auto-assign.yml/badge.svg)
![Proof HTML](https://github.com/JonSil89/demo-repository/actions/workflows/proof-html.yml/badge.svg)

[![Gatehouse Audit Evidence](https://github.com/Jonnenpijonne/infrastructure-change-quality-gate/actions/workflows/audit-evidence-report.yml/badge.svg)](https://github.com/Jonnenpijonne/infrastructure-change-quality-gate/actions/workflows/audit-evidence-report.yml)
[![Gatehouse CodeQL Python](https://github.com/Jonnenpijonne/infrastructure-change-quality-gate/actions/workflows/codeql-python.yml/badge.svg)](https://github.com/Jonnenpijonne/infrastructure-change-quality-gate/actions/workflows/codeql-python.yml)

[![RBAC-Lite Compliance Check](https://github.com/Jonnenpijonne/RBAC-Lite/actions/workflows/compliance-check.yml/badge.svg)](https://github.com/Jonnenpijonne/RBAC-Lite/actions/workflows/compliance-check.yml)

[![HaaS CI](https://github.com/JonSil89/Home-Assistant-as-a-Service-HAaaS-/actions/workflows/blank.yml/badge.svg)](https://github.com/JonSil89/Home-Assistant-as-a-Service-HAaaS-/actions/workflows/blank.yml)
[![AI ITSM Full Stack CI](https://github.com/JonSil89/AI-ITSM-Compliance-Auto/actions/workflows/compliance-check.yml/badge.svg)](https://github.com/JonSil89/AI-ITSM-Compliance-Auto/actions/workflows/compliance-check.yml)
[![Compliance & Policy Guard](https://github.com/JonSil89/AI-ITSM-Compliance-Auto/actions/workflows/policy-guard.yml/badge.svg)](https://github.com/JonSil89/AI-ITSM-Compliance-Auto/actions/workflows/policy-guard.yml)

## Featured projects

### Gatehouse / Infrastructure Change Quality Gate

[![GitHub Repo](https://img.shields.io/badge/Repository-Gatehouse-purple?style=for-the-badge\&logo=github)](https://github.com/Jonnenpijonne/infrastructure-change-quality-gate)

**Role:** Architecture & implementation — compliance-aware automated change validation
**Tech:** Python, GitHub Actions, Markdown
**Focus:** Risk classification, approval requirements, rollback planning, audit evidence and CI/CD validation

Notes:

* Markdown-based change requests
* Risk classes 1–3
* Quality gate validation
* Audit evidence reporting
* CodeQL workflow
* RBAC-Lite integration example
* Demo-friendly validator flow for controlled change review

### RBAC-Lite

[![GitHub Repo](https://img.shields.io/badge/Repository-RBAC--Lite-darkgreen?style=for-the-badge\&logo=github)](https://github.com/Jonnenpijonne/RBAC-Lite)

**Role:** Access-control governance and compliance example
**Tech:** WordPress / PHP, Markdown, GitHub Actions, Python validation tooling
**Focus:** Partner isolation, RBAC thinking, NDA/terms enforcement, audit logging and governance validation

Notes:

* Lightweight WordPress-based RBAC/access-control reference
* Partner-based data isolation model
* User-to-partner assignment thinking
* NDA / terms enforcement concept
* Gatehouse-compatible compliance example
* Main branch protected against force pushes and deletion
* Completion report documenting the RBAC-Lite + Gatehouse governance work

### Local-First WordPress DevSecOps Kit

[![GitHub Repo](https://img.shields.io/badge/Repository-Local--First%20WordPress%20DevSecOps%20Kit-blue?style=for-the-badge\&logo=github)](https://github.com/Jonnenpijonne/local-first-wordpress-devsecops-kit)

**Role:** Local-first DevSecOps model and public-safe portfolio starter kit
**Tech:** Docker Compose, WordPress, MariaDB, Mailpit, Bash, Markdown, Mermaid
**Focus:** Safe local development, privacy-aware data handling, AI boundaries, developer onboarding and audit evidence templates

Notes:

* One-command WordPress development runtime
* Docker Compose stack with localhost-bound services
* No production data in development principle
* Development data flow with anonymization and secret scan model
* AI boundary model: assistive, not autonomous
* Evidence templates for local environment validation and anonymization logs
* Public-safe refactoring of a regulated project development model

### AI-Powered ITSM Documentation & Automated Compliance Workflows

[![GitHub Repo](https://img.shields.io/badge/Repository-AI--Powered--ITSM-blue?style=for-the-badge\&logo=github)](https://github.com/JonSil89/AI-Powered-ITSM-Documentation-Building-automated-compliance-workflows-using-ClickUp-AI.)

**Role:** Solution design & automation for ITSM documentation and compliance workflows
**Tech:** ClickUp + AI workflows, documentation automation
**Focus:** Compliance documentation, workflow automation, ITSM-oriented evidence generation

Notes:

* AI-assisted documentation workflow
* Compliance-oriented process thinking
* ITSM documentation and operational structure
* Early foundation for AI-assisted governance workflows

### Home Assistant as a Service — HaaS

[![GitHub Repo](https://img.shields.io/badge/Repository-HaaS-blue?style=for-the-badge\&logo=github)](https://github.com/JonSil89/Home-Assistant-as-a-Service-HAaaS-)

**Role:** Solution design & reproducible infrastructure
**Tech:** YAML, GitHub Actions, Docker
**Focus:** Lifecycle management, reproducible infrastructure and automation

Notes:

* Device onboarding → maintenance → decommissioning
* Lifecycle management model
* RAG architecture roadmap for AI-driven documentation search
* Automated Azure deployment validation workflows
* Supporting evidence for infrastructure lifecycle and repeatability thinking

### Auto-Assign Passing — CI/CD validation & reporting

**Role:** Pipeline automation & reporting
**Tech:** GitHub Actions, shell scripting, HTML reporting
**Focus:** Pass/fail gating and human-readable workflow output

Notes:

* The Auto Assign badge above points to the demo repository workflow.
* Used as a lightweight CI/CD reporting proof.

### Proof — HTML passing / reporting

**Role:** Validation reporting
**Tech:** GitHub Actions, HTML reporting, scripts
**Focus:** Human-readable pass/fail HTML reports for release gates

Notes:

* The Proof HTML badge above points to the demo repository workflow.

## GitLab — HomeStack

[![HomeStack GitLab](https://img.shields.io/badge/GitLab-HomeStack-ff69b4?style=for-the-badge\&logo=gitlab\&logoColor=white)](https://gitlab.com/Jonnenpijonne/homestack)

**Project:** HomeStack
**Summary:** Infrastructure-as-Code foundation for modular home services
**Key artefacts:** CI/CD configuration, CHANGELOG, CONTRIBUTING guidelines, Apache 2.0 license

## Achievements

* Migrated hundreds of devices in critical healthcare HVA environments with minimal disruption
* Built audit-ready documentation and validation artefacts for MedTech systems in regulated environments
* Designed and built Gatehouse / Infrastructure Change Quality Gate — an ISO 27001-aligned CI/CD quality gate concept, demo-friendly with example change requests
* Built RBAC-Lite + Gatehouse governance documentation showing how access-control changes can be made auditable, reviewable and CI/CD-validatable
* Created a public-safe Local-First WordPress DevSecOps Kit to demonstrate Dockerized local development, privacy-safe data handling, AI boundaries and audit evidence templates
* Applied lightweight governance thinking: build only the structure needed now, while preserving auditability, recoverability and future evolution

## Credentials & learning evidence

[![Microsoft Applied Skills](https://img.shields.io/badge/Microsoft%20Applied%20Skills-Active%20Directory%20Domain%20Services-0078D4?style=for-the-badge\&logo=microsoft\&logoColor=white)](https://learn.microsoft.com/users/jonnesilvennoinen-7257/credentials/ca01c7ed2e401f38)
![HealthTech Regulatory](https://img.shields.io/badge/HealthTech%20Regulatory-PRRC%20%2F%20MDR%20Exposure-darkblue?style=for-the-badge)
![Microsoft Learn](https://img.shields.io/badge/Microsoft%20Learn-Continuous%20Cloud%20%26%20Security%20Learning-5E5E5E?style=for-the-badge\&logo=microsoft\&logoColor=white)

* **Microsoft Applied Skills:** Administer Active Directory Domain Services
  Credential ID: `CA01C7ED2E401F38`
  Focus: AD DS administration, domain services, hybrid identity foundations and operational troubleshooting.
  ## Microsoft Applied Skills — Active Directory Domain Services


**Completed:** 5 May 2026
**Focus:** Active Directory Domain Services, Microsoft hybrid identity foundations, Group Policy, domain services and operational troubleshooting

This Microsoft Applied Skills credential is a practical, lab-based skills demonstration focused on administering Active Directory Domain Services.

I do not position this as an Expert-level Microsoft certification or as a replacement for years of production ownership of large enterprise AD environments. Its value is different: it validates hands-on capability in one of the most operationally important layers of Microsoft hybrid infrastructure.

The assessment aligns directly with practical AD DS administration work, including domain controller management, AD topology, AD DS objects, Group Policy Objects and AD DS security.

### Key areas demonstrated

* Deploying and managing AD DS domain controllers
* Understanding and working with FSMO roles
* Managing domain and forest-level AD DS responsibilities
* Configuring Active Directory topology, sites and subnets
* Managing AD DS users, groups and organizational units
* Handling disabled users, password resets and account-related operational tasks
* Managing privileged groups and protected user concepts
* Creating and linking Group Policy Objects
* Configuring GPO scope, inheritance and processing order
* Troubleshooting applied Group Policy with tools such as `gpresult` and `gpupdate`
* Understanding DNS dependencies in AD DS environments
* Troubleshooting domain controller health and DNS-related AD issues
* Understanding AD replication and operational diagnostics
* Using tools such as `repadmin`, `dcdiag`, `nltest`, `nslookup`, `eventvwr` and PowerShell
* Testing and resetting secure channel issues
* Configuring domain password policy and Fine-Grained Password Policies
* Understanding that Fine-Grained Password Policies are targeted to users or groups, not organizational units
* Delegating permissions in AD DS
* Configuring auditing and security-related settings through Group Policy
* Understanding event logs relevant to AD DS operations, including Directory Service, DNS Server and System logs

### Operational troubleshooting mindset

My AD DS study and lab work focused especially on practical troubleshooting rather than only directory object management.

A typical troubleshooting flow I use:

```text
1. gpresult / gpupdate  → Is Group Policy applying correctly?
2. nslookup             → Does DNS resolve correctly?
3. nltest               → Is the secure channel healthy?
4. repadmin             → Is AD replication healthy?
5. FSMO role check      → Which domain controller owns the critical role?
6. Event logs           → What does the system actually report?
```

Common AD DS root causes I pay attention to:

```text
1. Incorrect DNS configuration
2. Broken or delayed replication
3. Broken secure channel
4. Incorrect GPO or FGPP targeting
5. Wrong domain controller or PDC Emulator dependency
6. Missing or stale group membership
7. Authentication or policy dependencies affecting end users
```

### How this connects to my wider portfolio

In my portfolio, this credential acts as the Microsoft identity infrastructure foundation behind my broader DevSecOps, governance and operational security work.

My projects focus on controlled change, access control, auditability, recoverability and safe development workflows. AD DS connects directly to these themes because identity infrastructure is where governance becomes operational reality.

* **Gatehouse / Infrastructure Change Quality Gate** demonstrates risk-based change validation, approval requirements, rollback planning and audit evidence.
* **RBAC-Lite** demonstrates access-control governance, partner isolation, role-based access concepts and audit logging.
* **Local-First WordPress DevSecOps Kit** demonstrates safe local development, Docker-based reproducibility, no-production-data principles, AI boundaries and recoverability.
* **AD DS Applied Skills** anchors these themes in Microsoft hybrid infrastructure: users, groups, Group Policy, DNS dependencies, replication, secure channel, privileged access, auditing and operational troubleshooting.

This combination reflects my current technical direction:

```text
DevSecOps thinking
+ Microsoft hybrid infrastructure
+ identity and access governance
+ operational troubleshooting
+ regulated environment awareness
+ audit-ready documentation
```

### Why this matters

Active Directory is not simply a legacy technology. It remains a mature core infrastructure layer in many enterprise, public-sector, healthcare-adjacent and critical environments.

Modern Microsoft environments often depend on a hybrid reality where Microsoft 365, Entra ID, Intune and cloud services are connected to older but still critical AD DS, DNS, GPO and Windows Server foundations.

This credential supports my ability to understand that bridge:

```text
on-prem AD DS
→ hybrid identity
→ Entra ID / Microsoft 365
→ endpoint and access management
→ operational security
→ governed and auditable change
```

The value of this credential is not that it makes me a senior AD architect by itself. The value is that it gives practical, Microsoft-validated evidence that I understand the operational foundation behind identity, policy, access and troubleshooting in Microsoft-based environments.

Combined with my HVA migration experience, Microsoft 365 / Entra ID / Intune exposure, ITSM background, documentation work and governance-focused GitHub projects, it strengthens my profile toward Microsoft hybrid infrastructure, AD/Windows operations, identity governance and DevSecOps-oriented operational maturity.


* **HealthTech regulatory training:** Regulatory Essentials in Health Tech / PRRC
  Focus: MDR/IVDR responsibilities, risk management, audit readiness, post-market surveillance and authority communication.

* **Microsoft Learn transcript:** broad learning record across Microsoft 365, Azure, Entra ID, Purview, Defender, DevOps, governance and security fundamentals.

## Languages

![Finnish](https://img.shields.io/badge/Finnish-Native-003580?style=for-the-badge)
![English](https://img.shields.io/badge/English-C1-0a66c2?style=for-the-badge)

