# nemetchek-library-management-system-design
System design proposal for a library check-in/check-out platform.

# Library Check-in / Check-out System

## Overview

This repository contains a system design proposal for a library management platform supporting book inventory management, check-out and return operations.

The proposed architecture considers scalability, reliability, security, and multi-tenancy, with an AWS-based SaaS deployment model.

## Architecture Highlights

- Modular application architecture with clearly defined domain boundaries.
- REST API for catalog and circulation operations.
- PostgreSQL as the transactional source of truth.
- Transactional consistency and concurrency control.
- Multi-tenant SaaS architecture.
- AWS infrastructure using ECS, Fargate, Aurora PostgreSQL, SQS, and related managed services.
- Reliability, observability, security, and disaster recovery considerations.

## Documentation

The complete system design proposal is available here:

[Library Check-in / Check-out System Design](docs/Library_Checkin_Checkout_System_Design.pdf)

## Scope

The document covers functional and non-functional requirements, assumptions, architecture, physical and logical design, data model, API design, sequence diagrams, AWS infrastructure, and mission-critical design principles.
