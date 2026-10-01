# Homelab Documentation

This repository contains my personal notes and troubleshooting records for my homelab. It documents the hardware, virtualization environment, and self-hosted services I run at home while learning more about infrastructure, networking, and container management.

## Overview

The goal of this homelab is to build a private, self-hosted environment for learning and experimentation. I am using a small, practical setup focused on reliability, ease of access, and hands-on experience with:

- Virtualization with Proxmox
- Linux administration and system configuration
- Docker-based self-hosted services
- Remote access via Tailscale
- Service monitoring and maintenance

## Repository structure

- [Hardware.md](Hardware.md) — hardware specifications and the physical machine used in the lab
- [Proxmox.md](Proxmox.md) — Proxmox setup, VM layout, networking notes, and operational guidance
- [Services/Docker.md](Services/Docker.md) — Docker services, configuration notes, and common issues
- [Services/Terraria.md](Services/Terraria.md) — Terraria server setup, Docker deployment details, and troubleshooting

## Current setup

The current environment is built around a Dell Optiplex 3050 Micro PC running Proxmox, with virtual machines used to separate workloads. At the moment, the main focus includes:

- A Proxmox host for VM management
- A Docker VM for containerized services
- A Terraria server running in Docker
- Tailscale for secure remote access and private networking

## Documentation style

These notes are intentionally practical and personal. They focus on:

- What was built
- How it was configured
- What problems came up
- Which fixes worked

This makes the repository useful as a living reference for future changes or rebuilds.

## Important notes

- This is a personal learning project and not a production-grade deployment guide.
- Configuration details may evolve as the homelab changes.
- Security and networking decisions are documented as they are learned and tested.

This repository is meant to be a record of my homelab experience, from initial setup through troubleshooting and ongoing improvements.