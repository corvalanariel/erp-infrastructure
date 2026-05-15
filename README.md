# ERP Infrastructure

General infrastructure notes, deployment guides and server configuration examples for ERP environments based on Linux, PostgreSQL, NGINX and iDempiere.

## Purpose

This repository documents reference architectures and technical practices for deploying ERP systems in Linux-based server environments.

The content is focused on practical infrastructure used for ERP implementation, support and maintenance.

## Reference architecture

Typical deployment model:

```text
Users
  ↓
Cloudflare
  ↓
NGINX Reverse Proxy
  ↓
iDempiere Application Server
  ↓
PostgreSQL Database Server
