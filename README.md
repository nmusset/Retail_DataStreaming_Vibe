# Retail Data Streaming Platform

An ETL platform that captures database changes from retail client systems, applies client-specific transformations, and delivers data reliably to external endpoints.

## Overview

This platform enables retail clients to stream operational data (tickets, products, catalog, stores) from their databases to external systems with minimal technical overhead. The platform handles change data capture (CDC), transformation execution, and delivery guarantees independently per client.

## Key Capabilities

- **Change Data Capture**: Monitors client databases for delta changes
- **Custom Transformations**: Executes client-specific data transformation logic
- **Reliable Delivery**: Ensures accurate data delivery to configured endpoints
- **Client Isolation**: Independent operation per client with no cross-contamination
- **Observability**: Monitoring, logging, and debugging capabilities

## Project Structure

```
docs/
  ├── design/              # Architecture and design decisions
  │   ├── architecture-overview.md
  │   ├── 1_proposals/     # Technical proposal documents (draft status)
  │   ├── 2_wip/           # Work-in-progress designs
  │   └── 3_final/         # Finalized design documents
  └── personas/            # Stakeholder personas and requirements
```

## Status

**Early design phase** - Architecture proposals are currently under review. No technical implementation decisions have been finalized.

## Documentation

- **[Architecture Overview](docs/design/architecture-overview.md)**: High-level system design and stakeholder views
- **[Proposals](docs/design/1_proposals/README.md)**: Technical proposals for CDC, transformations, execution, configuration, delivery guarantees, and disaster recovery
- **[Personas](docs/personas/README.md)**: Stakeholder requirements and perspectives

## Repository Contents (Expected)

This repository will contain:
- Platform core components (CDC, orchestration, execution engine, connectors)
- Configuration schemas and validation
- Transformation SDK and contracts
- Infrastructure as Code (IaC) for deployment
- Integration and end-to-end tests
- Developer tooling and local environment setup
