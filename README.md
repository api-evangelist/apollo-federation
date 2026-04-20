# Apollo Federation (apollo-federation)
Apollo Federation is an architecture and platform for building a unified supergraph that composes multiple GraphQL APIs (subgraphs) into a single distributed GraphQL endpoint, enabling teams to work independently on different parts of the graph while delivering a unified API to consumers. Federation 2 is the current stable version, supported by the Apollo Router written in Rust and the Rover CLI for schema management.

**URL:** [https://www.apollographql.com/docs/federation/](https://www.apollographql.com/docs/federation/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Gateway, Federation, GraphQL, Microservices, Open Source, Subgraphs, Supergraph

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-19

## APIs

### Apollo Federation
Apollo Federation enables declarative composition of multiple subgraph APIs into a single federated supergraph. The Apollo Router orchestrates requests across subgraphs, combining GraphQL APIs and REST APIs (via Apollo Connectors) into a unified endpoint. Federation 2 defines the supergraph schema, federation directives, and composition rules. The Rover CLI manages schema publishing and checks.

**Human URL:** [https://www.apollographql.com/docs/federation/](https://www.apollographql.com/docs/federation/)

#### Tags:

 - API Gateway, Federation, GraphQL, Microservices, Open Source, REST Integration, Router, Subgraphs, Supergraph

#### Properties

- [Documentation](https://www.apollographql.com/docs/federation/)
- [GettingStarted](https://www.apollographql.com/docs/federation/quickstart/)
- [JSONSchema](json-schema/supergraph-configuration.json)
- [JSONSchema](json-schema/router-configuration.json)
- [GitHubRepository](https://github.com/apollographql/federation)
- [ChangeLog](https://www.apollographql.com/docs/graphos/reference/federation/versions)

## Common Properties

- [Documentation](https://www.apollographql.com/docs/federation/)
- [GettingStarted](https://www.apollographql.com/docs/federation/quickstart/)
- [GitHubOrganization](https://github.com/apollographql)
- [Federation Spec](https://github.com/apollographql/federation)
- [Apollo Router](https://github.com/apollographql/router)
- [Rover CLI](https://github.com/apollographql/rover)
- [Subgraph Compatibility Tests](https://github.com/apollographql/apollo-federation-subgraph-compatibility)
- [JVM Support](https://github.com/apollographql/federation-jvm)
- [Blog](https://www.apollographql.com/blog/)
- [Pricing](https://www.apollographql.com/pricing/)
- [SignUp](https://studio.apollographql.com/signup)

## Features

| Name | Description |
|------|-------------|
| Supergraph Composition | Compose multiple subgraph schemas into a single unified supergraph schema. |
| Federation Directives | Declarative federation directives (@key, @external, @requires, @provides, @shareable, @link) for schema coordination. |
| Apollo Router | High-performance Rust-based router that orchestrates queries across subgraphs. |
| Apollo Connectors | Declarative integration of REST APIs into federated graphs without writing a separate GraphQL server. |
| Schema Registry | Apollo GraphOS schema registry for publishing, checking, and managing supergraph schemas. |
| Rover CLI | Command-line tool for publishing subgraph schemas, running checks, and managing the supergraph. |
| Query Planning | Intelligent query planning that decomposes client queries into efficient subgraph requests. |
| Subgraph Compatibility | Federation-compatible subgraphs can be built in any language or framework. |
| Gray Release Support | Progressive schema rollout with incremental migration from monolith to federated graph. |

## Use Cases

| Name | Description |
|------|-------------|
| Distributed Team Development | Enable independent teams to own and develop separate subgraphs while delivering a unified API. |
| REST API Modernization | Gradually expose existing REST APIs as GraphQL via Apollo Connectors without full rewrites. |
| API Consolidation | Consolidate multiple disparate APIs into a single unified supergraph for consumers. |
| Microservices GraphQL Layer | Add a federated GraphQL layer over existing microservice architectures. |
| Schema Governance | Enforce schema design standards across all subgraphs via composition checks. |

## Integrations

| Name | Description |
|------|-------------|
| Anthropic | Apollo Connector for integrating Anthropic AI APIs into the supergraph. |
| OpenAI | Apollo Connector for integrating OpenAI APIs into the supergraph. |
| AWS DynamoDB | Apollo Connector for AWS DynamoDB via REST API integration. |
| AWS Lambda | Apollo Connector for AWS Lambda function invocation. |
| Stripe | Apollo Connector for Stripe payment API integration. |
| OData | Apollo Connector for OData REST API integration. |
| Strapi | Apollo Connector for Strapi CMS API integration. |
| Kubernetes | Deploy Apollo Router as a Kubernetes service via Helm charts and operator patterns. |
| Terraform | Official Terraform provider for Apollo GraphOS management. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Supergraph Configuration](json-schema/supergraph-configuration.json)
- [Router Configuration](json-schema/router-configuration.json)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
