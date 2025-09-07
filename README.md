# docker-media-automation

Docker-based media automation stack: Traefik v3, Authelia, LDAP, Elasticsearch, and service orchestration.

## Overview

This repository contains configuration files and documentation for a self-hosted media automation platform using Docker Compose. It pulls together reverse proxy (Traefik v3), single sign-on (Authelia), directory services (OpenLDAP), authentication/authorization (Authelia & LDAP), search and indexing (Elasticsearch), and a collection of media services for streaming, downloads, and metadata management.

The goal is to provide a secure, centralized, and automated environment for managing personal media libraries and related services.

## Features

- **Traefik v3 reverse proxy:** Handles routing, Let's Encrypt certificates, and secure SSL termination for all services.
- **Authelia & LDAP SSO:** Provides unified login and access control across media services via an LDAP-backed identity provider.
- **Elasticsearch indexing:** Stores logs and metrics for analysis and search; integrates with Kibana dashboards (optional).
- **Docker Compose orchestration:** All services are defined in Compose with environment variables and volumes; easy to deploy and update.
- **Automated deployments:** Includes scripts or notes on setting up watchtower, auto-updates, and health checks.
- **Cross-subnet networking:** Examples for bridging containers across multiple LAN/VLAN segments using macvlan or overlay networks.

Use this repository as a starting point for building a customized media stack; adapt services and configurations to your own needs.
