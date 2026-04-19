# Amazon Aurora DSQL

Amazon Aurora DSQL is a distributed SQL database service optimized for transactional workloads. It provides a serverless, fully managed PostgreSQL-compatible database with built-in high availability, scalability, and global distribution capabilities.

## Overview

The Amazon Aurora DSQL API enables programmatic control over distributed SQL clusters, multi-region configurations, and connection endpoint management. It enables building globally distributed transactional applications backed by PostgreSQL-compatible databases.

## API Documentation

- **Human URL:** https://docs.aws.amazon.com/aurora-dsql/latest/userguide/getting-started.html
- **Base URL:** https://dsql.us-east-1.amazonaws.com

## Features

- Serverless PostgreSQL-compatible distributed SQL database
- Automatic scaling with no database instances to manage
- Multi-region active-active replication for global distribution
- Built-in high availability with automatic failover
- Pay-per-use pricing based on I/O and storage
- Standard PostgreSQL client compatibility
- Transactional consistency across distributed nodes
- Integrated with AWS IAM for authentication
- Automatic software patching and maintenance
- Point-in-time recovery with continuous backups

## Use Cases

- Build globally distributed transactional applications
- Run PostgreSQL workloads without managing instances
- Deploy active-active multi-region database architectures
- Migrate PostgreSQL applications to serverless infrastructure
- Build applications requiring strong consistency at global scale
- Implement high-throughput transactional microservices

## Artifacts

### OpenAPI Specification
`openapi/amazon-aurora-dsql-openapi.yml`

Complete OpenAPI 3.1.0 specification covering all Aurora DSQL API paths.

### Spectral Rules
`rules/amazon-aurora-dsql-spectral-rules.yml`

### Naftiko Capabilities
- `capabilities/shared/aurora-dsql-api.yaml` — Shared per-API capability definition
- `capabilities/distributed-sql-management.yaml` — Workflow capability for distributed SQL management

### Vocabulary
`vocabulary/amazon-aurora-dsql-vocabulary.yaml`

### JSON Schemas
`json-schema/` — 19 JSON Schema files for all objects.

### JSON Structures
`json-structure/` — 19 JSON Structure files.

### JSON-LD Context
`json-ld/amazon-aurora-dsql-context.jsonld`

### Examples
`examples/` — 19 example JSON files.

## Integrations

- Amazon VPC
- AWS IAM
- Amazon CloudWatch
- AWS CloudTrail
- Amazon RDS
- AWS KMS
- Amazon Route 53
- AWS PrivateLink
- Amazon S3
- AWS Secrets Manager

## Tags

Amazon Aurora DSQL, Distributed SQL, PostgreSQL, Serverless, AWS

## Maintainers

- Kin Lane (kin@apievangelist.com)
