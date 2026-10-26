# 🔐 Linux Homelab Firewall & Cloudflare Zero Trust

## Overview

This project focuses on improving the security of my home lab by combining Linux-based infrastructure with Cloudflare Tunnel and Zero Trust access controls.

The objective is to control how external users and systems reach self-hosted services, reduce unnecessary exposure to the public internet, and maintain secure remote access to selected applications.

## Technologies

- Linux
- Cloudflare Tunnel
- Cloudflare Zero Trust
- Self-hosted applications
- Network access control

## Security Design

The setup uses Cloudflare Tunnel to provide a route between selected services in my homelab and Cloudflare, avoiding the need to expose those services directly through traditional inbound port forwarding.

Cloudflare Zero Trust provides an additional layer of access control for services configured to use its access policies.

Linux provides the underlying host environment in which services run.

## Key Areas

- Configuring remote access to selected homelab services.
- Using Cloudflare Tunnel to connect services without directly exposing their origin through inbound port forwarding.
- Exploring and configuring Zero Trust access controls.
- Reducing unnecessary public exposure of self-hosted applications.
- Managing service connectivity and troubleshooting access issues.

## Security Considerations

A secure deployment depends on the actual access policies, tunnel configuration, host firewall rules and service exposure.

Cloudflare Tunnel alone does not automatically protect every service. Access policies must be configured appropriately, and Linux firewall rules should be verified separately.

## Screenshots & Evidence

See [Firewall & Zero Trust — Evidence](Screenshots/Firewall-Zero-Trust.md) for screenshots of my Cloudflare Tunnel and dashboard insights.

## Key Takeaway

This project demonstrates practical exploration of remote-access security, Linux infrastructure and Cloudflare Zero Trust within a self-hosted environment.
