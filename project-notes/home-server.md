# Home Server

**Personal home lab infrastructure and automation**

Public project summary · Personal lab with running services and recorded verification work

## Overview

A self-directed Proxmox home lab provides infrastructure for applications, automation, and course work. It runs on dedicated hardware and includes an Ubuntu Server virtual machine, a Debian monitoring container, and services deployed with Docker Compose.

This personal project is independent of my employer. I use it to develop practical skills in system administration, virtualization, Linux, monitoring, backup, and automation.

## Work completed

- Installed and configured Proxmox VE with an Ubuntu Server virtual machine and a Debian monitoring container.
- Deployed n8n and PostgreSQL using Docker Compose.
- Configured remote administration through Tailscale without exposing services through public port forwarding.
- Implemented internal health checks and an independent external watchdog with Telegram alerts; tested both failure alerts and recovery notifications.
- Configured automated snapshot backups to dedicated USB storage with a keep-last-7 retention policy.
- Completed an isolated end-to-end restore test, including boot and functional validation, while preserving the original virtual machine and backup files.
- Verified that core services recover successfully after a full host reboot.

## Technologies

Proxmox VE · Ubuntu Server · Debian · LXC · Docker Compose · n8n · PostgreSQL · Tailscale · SSH · systemd

## Current status and scope

The lab has running services and recorded verification work. It uses a single physical host. Recovery exercises and service checks apply to the specific scenarios documented in the project.

This page is a public summary of the lab and its recorded work; it does not publish the underlying project repositories or configuration files.

## What I am learning

Understanding service dependencies, maintaining Linux services, documenting operational changes, and planning and testing recovery.

*Summary based on project records and published profile information available on 15 September 2026.*

---

[All project notes](../PROJECTS.md) · [GitHub profile](https://github.com/DrorAlpern) · [LinkedIn](https://www.linkedin.com/in/dror-alpern/)
