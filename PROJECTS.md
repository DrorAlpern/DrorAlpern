# Project notes

A closer look at the projects featured on my [GitHub profile](https://github.com/DrorAlpern). These summaries cover personal projects and course work. Statuses reflect the available project records as of 15 September 2026.

## VinylAgent

**Focus:** Application development, content workflows, and integration.

VinylAgent brings albums, content ideas, planned posts, and performance information into one application. The interface supports a Hebrew content workflow, while the backend provides structured storage and integration points.

- **Technologies:** Node.js, Express, JavaScript, SQLite, Docker Compose, n8n, and API integrations.
- **Work covered:** Application structure, content workflows, deployment to Ubuntu, and an authenticated API connection for a scheduled report.
- **Status:** Personal application in development. Deployment and workflow integration are documented; individual external integrations have their own testing and release steps.
- **Learning focus:** API boundaries, persistent data, service health, and controlled changes.

## Infrastructure Automation

**Focus:** Python, Bash, and repeatable service setup.

Stage 1 of my rolling DevOps course project collects multiple machine definitions, validates input with `jsonschema`, and saves the result as JSON. Machine creation is simulated. A Bash script installs and configures Nginx on the Linux host.

- **Technologies:** Python, Bash, jsonschema, Nginx, Git, and Ubuntu.
- **Work covered:** Input validation, a `Machine` class, modular code, atomic JSON storage, subprocess execution, and shared logging.
- **Status:** Stage 1 implemented and verified. Ten automated tests passed, alongside Bash syntax, ShellCheck, and live Nginx checks.
- **Learning focus:** Clear failure handling, repeatable runs, and the boundary between a simulation and real system changes.

The source repository currently requires access: [infra-automation](https://github.com/DrorAlpern/infra-automation). AWS and Terraform are planned for later course stages.

## Home Server

**Focus:** Linux infrastructure and service operations.

A personal Proxmox environment provides the infrastructure for applications, automation, and course work. It includes Ubuntu virtual machines, an LXC monitoring environment, and services deployed with Docker Compose.

- **Technologies:** Proxmox VE, Ubuntu, LXC, Docker Compose, PostgreSQL, Tailscale, SSH, and systemd.
- **Work covered:** Virtualization, remote access, service deployment, backups, monitoring, and operational documentation.
- **Status:** Personal lab with running services and recorded verification work.
- **Learning focus:** Understanding dependencies, maintaining services, and planning recovery.

The lab uses a single physical host. Recovery exercises and service checks apply to the specific scenarios documented in the project.

## Server Monitor

**Focus:** Monitoring workflows and actionable notifications.

This project connects server and service checks to a separate error-handling workflow that formats Telegram alerts. Deliberate test failures were used to check the notification path.

- **Technologies:** n8n, SSH, webhooks, Telegram, and heartbeat monitoring.
- **Work covered:** Separating service checks from error reporting and testing alerts.
- **Status:** Lab automation with documented notification tests.
- **Learning focus:** Distinguishing a service failure from a failure of the monitoring system itself.

Notification tests confirm the paths they exercise. Broader outage and recovery behavior needs its own verification.

## n8n Practice

**Focus:** Understanding workflow execution and data flow.

A collection of guided exercises covering triggers, HTTP requests, JSON transformations, data merging, error handling, and an AI agent connected to tools.

- **Technologies:** n8n, HTTP, JSON, OpenAI integrations, and conversation memory.
- **Work covered:** Following a workflow from input to output and inspecting intermediate data.
- **Status:** Quickstart completion documented in September 2026; further practice continues.
- **Learning focus:** Explaining each node's purpose and understanding how the workflow behaves when a step fails.

These are course exercises using practice data.

## HomeNet Monitor

**Focus:** Network observations and dashboard presentation.

A home-network dashboard combines device observations, names, and last-seen times. PowerShell prepares local JSON data for an HTML interface.

- **Technologies:** PowerShell, Windows Task Scheduler, JSON, and HTML.
- **Work covered:** Collecting observations, organizing device information, and improving dashboard layout.
- **Status:** Documented prototype; continuous scheduled operation has not been fully verified.
- **Learning focus:** Showing the age and reliability of data clearly.

A last-seen timestamp represents an observation, which may differ from a device's current connection state.

## BurnMonitor V2

**Focus:** Troubleshooting data freshness and interface timing.

This project explores a mismatch between updated backend data and a dashboard that remains in an updating state until the page is refreshed.

- **Technologies:** PowerShell, Windows Task Scheduler, JSON, HTTP APIs, and JavaScript.
- **Work covered:** Comparing scheduled exports, API responses, and the dashboard's refresh behavior.
- **Status:** In development. The available records do not include a completed acceptance check for the proposed fix.
- **Learning focus:** Separating data-production problems from display and timing problems.

## TovPup and CommerceAI

**Focus:** E-commerce operations and supporting software.

TovPup provides the business context for work on structured product information, operational workflows, and launch preparation. CommerceAI is the associated software project for exploring how those processes can be supported by an application.

- **Technologies:** JavaScript, Node.js, SQLite, structured data, and web interfaces.
- **Work covered:** Software foundations, product and workflow organization, validation, and launch-readiness documentation.
- **Status:** In development, with business and integration steps still pending.
- **Learning focus:** Translating an operational process into data, checks, and a usable interface.

This summary describes the tooling and preparation work. It does not claim that every proposed integration or store workflow has been launched.

## SHAPE AND DEFORM

**Focus:** Digital-product preparation and validation.

Tools and templates support a repeatable process for receiving final print files, checking their properties, organizing listing information, and preparing customer packages.

- **Technologies:** Python, JSON schemas, HTML, file manifests, and SHA-256 checks.
- **Work covered:** File and naming validation, print-size checks, package creation, pricing tools, and publication prerequisites.
- **Status:** The documented tooling stage is complete; the pilot artwork and publication stages remain pending.
- **Learning focus:** Preserving source files, validating outputs, and making repeatable packaging decisions.

Final artwork exports are supplied by the designer. Resizing and alternate-ratio generation are optional steps.

---

[Back to the profile](https://github.com/DrorAlpern)
