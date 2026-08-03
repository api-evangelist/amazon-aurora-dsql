# Amazon Aurora DSQL

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
