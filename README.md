# Teksystems - Technical Challenge Submission

Hi! This repository contains my submission for the Controls Deployment challenge. I’ve structured it into three main sections based on the tasks given:

---

## What's Inside

- **Cybersecurity Scenario** – My approach to threat identification, incident response planning, and recommended security measures.
- **Container Security Implementation** – Covers Docker best practices, Kubernetes security features, and a basic YAML setup.
- **CI/CD Pipeline Setup** – A basic setup using Terraform and GitHub Actions to handle build, lint, and deployment tasks.

---

## Assumptions

- AWS is used as the cloud environment.
- I chose GitHub Actions over Jenkins for the CI/CD part, as only one was needed.
- The focus is on showcasing understanding, so some examples are simplified for clarity.

---

## Section Breakdown

### 1. Cybersecurity Scenario
This part includes:
- A quick threat intel overview with possible attack types.
- An incident response plan that touches on detection, containment, and recovery.
- Practical network security measures like IAM controls, MFA, and firewalling.

### 2. Container Security Implementation
What I covered:
- Docker security tips (like using official images, patching, avoiding hardcoded secrets).
- Three Kubernetes security features.
- A basic `NetworkPolicy` YAML for ingress/egress rules.
- A short section on IaaS and its risks.

### 3. CI/CD Pipeline Setup
- Wrote a simple Terraform script to deploy an EC2 instance.
- Set up a GitHub Actions workflow that runs on `main` branch pushes:
  - Runs an `npm build`
  - Lints using `flake8`
  - Deploys with a basic action step

---

## How to Navigate

Each file is named based on its topic. You can go through them individually. They’re written to be clear and straight to the point.

---
