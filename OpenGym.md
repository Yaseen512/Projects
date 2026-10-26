# 💪 openGym

## Overview

openGym is a self-hosted fitness tracking application deployed in my personal homelab. The project gives me hands-on experience with containerised application deployment, service configuration, networking and troubleshooting.

## Technologies

- Docker
- Docker Compose
- Web application deployment
- API-based application architecture
- Environment configuration
- Cloudflare Tunnel experimentation

## Deployment & Configuration

I deployed openGym using Docker Compose and configured the web application to run on a dedicated host port to avoid conflicts with existing services.

The deployment includes:

- Configuring application services and their connectivity.
- Managing environment variables for application configuration.
- Exposing the web interface through a host port.
- Checking application health and HTTP responses.
- Troubleshooting connectivity and external-access configuration.

## Technical Challenges

During setup, I worked through:

- Resolving host port conflicts with existing applications.
- Validating that the web interface responded correctly.
- Managing configuration for external access.
- Understanding the relationship between application ports, host ports and reverse-proxy or tunnel configuration.

## Screenshots

See [openGym — Evidence](Screenshots/openGym.md) for screenshots of the application dashboard and workout tracking interface.

## Key Takeaway

openGym is a practical example of self-hosting an application and troubleshooting the networking and configuration required to make it accessible.
