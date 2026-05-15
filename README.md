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

## Security note

This repository does not include customer data, credentials, private configuration files or production-sensitive information.

## Author

Ariel Corvalán  
Founder of nube ERP  
https://nube.com.py
