# Docker and Kubernetes Exam

**Containerized crypto price tracker · DevOps course lab**

Public project summary · Verified in a local lab; not yet submitted for grading

## Overview

I took a Python and Flask course starter application through a complete local deployment workflow. The web frontend requests Bitcoin and XRP prices from the backend, which retrieves the prices and saves them to MySQL. This exercise connects application behavior to container packaging, service networking, persistent data, and Kubernetes operations.

## Work completed

- Built Python 3.12 frontend and backend images and ran them with MySQL 5.7 through Docker Compose on a dedicated network.
- Deployed the application to a local kind Kubernetes cluster with two frontend replicas, two backend replicas, and one MySQL instance with persistent storage.
- Used a LoadBalancer Service for the frontend and internal ClusterIP Services for the backend and database.
- Added a Helm chart with configurable images, replica counts, ports, storage, and database Secret references.
- Verified the browser flow, service health, and Bitcoin and XRP database writes in Docker Compose, Kubernetes, and Helm.

## Technologies

Python · Flask · Docker · Docker Compose · MySQL · Kubernetes · kind · Helm

## Current status and scope

The [source code, setup instructions, and test evidence](https://github.com/DrorAlpern/docker-kubernetes-exam/tree/solution/docker-kubernetes-exam/exam-code/docker) are public. The deployments and checks described here were performed in my local lab. This project has not been deployed to AWS or a separate course cluster, and it has not yet been submitted for grading.

## What I am learning

How to package connected services, troubleshoot startup and networking issues, verify persistence, and turn a working local deployment into reusable Kubernetes manifests and Helm templates.

*Summary based on local verification and project records available on 18 September 2026.*

---

[All project notes](../PROJECTS.md) · [GitHub profile](https://github.com/DrorAlpern) · [LinkedIn](https://www.linkedin.com/in/dror-alpern/)
