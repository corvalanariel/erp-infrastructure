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
```
## Security note

This repository does not include customer data, credentials, private configuration files or production-sensitive information.

## Documentation

- [iDempiere Password Policy](docs/security/password-policy.md)

## Security Data

- [iDempiere Password Dictionary](data/security/idempiere-password-blacklist.csv)

## Author

Ariel Corvalán  
Founder of nube ERP  
https://nube.com.py
