
# Project Title

# Enterprise Identity & Access Management (IAM) Lab

Active Directory • Keycloak • Kerberos • LDAP • Jenkins • OpenID Connect • Docker • PostgreSQL


## Project Overview

This project demonstrates the design and implementation of an enterprise Identity and Access Management (IAM) solution in a production-like lab environment.

The objective was to centralize authentication using Microsoft Active Directory, implement Single Sign-On (SSO) with Keycloak, integrate Jenkins using OpenID Connect (OIDC), synchronize users and groups through LDAP, and implement Kerberos-based Windows Integrated Authentication.

The environment was deployed using Windows Server, Ubuntu Server, Docker Compose, PostgreSQL, and Jenkins while following enterprise security and identity management best practices.
## Project Objectives



- Build an enterprise Identity & Access Management lab
- Integrate Active Directory with Keycloak
- Configure LDAP User Federation
- Configure LDAP Group Mapping
- Implement OpenID Connect (OIDC)
- Integrate Jenkins with Keycloak
- Configure Role-Based Access Control (RBAC)
- Implement Kerberos Single Sign-On (SSO)
- Understand enterprise authentication workflows
- Document installation and troubleshooting
## Technology Stack

Category	                  Technologies

Operating System	          Windows Server   2022,  Ubuntu Server 26.04

Identity Provider	Keycloak 26

Directory Services	Active Directory, LDAP

Authentication	    Kerberos, OpenID Connect (OIDC)

Database	        PostgreSQL

CI/CD	            Jenkins

Containerization    Docker, Docker Compose

Networking	        DNS

Scripting	        PowerShell, Bash
## Architecture Diagram

Coming Soon

Architecture diagram illustrating the integration between:

- Active Directory
- DNS
- Keycloak
- PostgreSQL
- Jenkins
- Windows Client## Authentication Flow

Windows Client
       │
       ▼
Active Directory
       │
 LDAP / Kerberos
       │
       ▼
Keycloak
       │
 OpenID Connect
       │
       ▼
Jenkins

## Features

- Active Directory Authentication
- LDAP User Federation
- LDAP Group Synchronization
- OpenID Connect Single Sign-On
- Jenkins Integration
- Role-Based Access Control
- Kerberos Authentication
- Windows Integrated Authentication
- Docker Compose Deployment
- PostgreSQL Database
- Enterprise DNS Configuration
- Authentication Troubleshooting

## Repository Structure

Enterprise-Identity-and-SSO-Lab

README.md

docs/

architecture/

images/

screenshots/

scripts/
## Skills Demonstrated

## Skills Demonstrated

- Active Directory Administration
- DNS Configuration
- LDAP Integration
- Kerberos Authentication
- Identity Federation
- OpenID Connect (OIDC)
- OAuth 2.0
- Keycloak Administration
- Jenkins Security Integration
- Docker Compose
- PostgreSQL Administration
- Linux Administration
- Windows Server Administration
- Role-Based Access Control (RBAC)
- Enterprise Troubleshooting

## Documentation

- Chapter 1 – Lab Overview
- Chapter 2 – Network Architecture
- Chapter 3 – Active Directory
- Chapter 4 – DNS Configuration
- Chapter 5 – Keycloak Installation
- Chapter 6 – LDAP Integration
- Chapter 7 – Jenkins Integration
- Chapter 8 – OpenID Connect Configuration
- Chapter 9 – LDAP Group Mapping
- Chapter 10 – Kerberos Single Sign-On
- Chapter 11 – Troubleshooting
## Screenshots

- Active Directory
- LDAP User Federation
- Jenkins Login
- Keycloak Administration
- OIDC Configuration
- LDAP Group Mapping
- Kerberos Authentication
## Future Enhancements
## Key Learning Outcomes

Designed and deployed an enterprise IAM lab from scratch.
Integrated Microsoft Active Directory with Keycloak using LDAP.
Implemented OIDC-based Single Sign-On for Jenkins.
Configured Active Directory group synchronization and RBAC.
Implemented Kerberos/SPNEGO for Windows Integrated Authentication.
Gained hands-on experience troubleshooting DNS, LDAP, OIDC, Kerberos, Docker, and authentication issues.
## Authors

Virendra Yashvantrai Navre

Infrastructure | Cloud | Identity & Access Management

LinkedIn

GitHub

