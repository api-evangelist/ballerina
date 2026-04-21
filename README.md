# Ballerina (ballerina)
Ballerina is an open-source, cloud-native programming language and platform designed specifically for integration use cases. Created by WSO2 and now governed as an open-source project, Ballerina provides first-class support for network-distributed systems with built-in constructs for REST APIs, GraphQL, gRPC, WebSockets, Kafka, and database connectivity. The Ballerina Central registry hosts thousands of reusable integration packages.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ballerina/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Integrations, Orchestrations, Open Source, Programming Language

## Timestamps

- **Created:** 2025-06-05
- **Modified:** 2026-04-19

## APIs

### Ballerina Central API
The Ballerina Central REST API provides access to the Ballerina package registry for discovering, searching, and retrieving Ballerina language packages.

**Human URL:** [https://ballerina.io/](https://ballerina.io/)

#### Tags:

 - Integrations, Orchestrations

#### Properties

- [Documentation](https://ballerina.io/)
- [OpenAPI](openapi/ballerina-central-api.yml)

## Common Properties

- [Website](https://ballerina.io/)
- [CaseStudies](https://ballerina.io/case-studies/)
- [Learning](https://ballerina.io/learn/)
- [Packages](https://central.ballerina.io/)
- [Blog](https://blog.ballerina.io/)
- [TermsOfService](https://ballerina.io/terms-of-service/)
- [PrivacyPolicy](https://ballerina.io/privacy-policy/)
- [Libraries](https://central.ballerina.io/ballerina-library)

## Features

| Name | Description |
|------|-------------|
| Web Services | Built-in HTTP listener and client with REST API, GraphQL API, and gRPC API support. |
| Working With Data | Declarative data processing, immutability, pattern matching, and model optionality. |
| Sequence Diagrams | Automatic sequence diagram generation from Ballerina code. |
| VS Code Integration | First-class VS Code extension with language server, diagramming, and debugging. |
| Kafka Support | Native Kafka consumer and producer constructs. |
| Database Connectivity | SQL and NoSQL database client libraries in Ballerina Central. |
| XML and JSON Support | First-class XML and JSON data types built into the language. |

## Use Cases

| Name | Description |
|------|-------------|
| Integration | Build enterprise and cloud integrations with native protocol support. |
| Microservices | Develop cloud-native microservices with built-in network constructs. |
| Event-Driven Architecture (EDA) | Build event-driven applications using Kafka and message broker connectors. |
| B2B Integrations | Connect business systems using pre-built connector packages from Central. |
| ETL | Transform and route data between systems using declarative data processing. |
| Healthcare | FHIR and HL7 integration libraries available in Ballerina Central. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Ballerina Central API](openapi/ballerina-central-api.yml)

### JSON Schema

- [central-api-*-schema.json files](json-schema/)

### JSON-LD

- [Ballerina JSON-LD Context](json-ld/ballerina-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Ballerina Central API](capabilities/shared/central-api.yaml) — 3 operations for package search and retrieval

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Package Registry](capabilities/package-registry.yaml) | Central API | 3 | Ballerina Developer, Integration Engineer |

## Vocabulary

- [Ballerina Vocabulary](vocabulary/ballerina-vocabulary.yaml) — Unified taxonomy mapping 1 resource, 4 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Ballerina Spectral Rules](rules/ballerina-spectral-rules.yml) — 11 rules across 5 categories enforcing Ballerina API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
