# Apache APISIX (apache-apisix)
Apache APISIX is a dynamic, real-time, high-performance cloud-native API gateway built on NGINX and etcd, developed by the Apache Software Foundation. It supports Lua and multi-language plugins for traffic management, authentication, observability, and security. APISIX provides a RESTful Admin API for dynamic configuration of routes, upstreams, services, consumers, SSL certificates, and plugins, and a Control API for health monitoring and schema introspection.

**URL:** [https://apisix.apache.org/](https://apisix.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Apache, API Gateway, Cloud Native, Kubernetes, Lua, NGINX, Open Source, Traffic Management

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-04-19

## APIs

### Apache APISIX Gateway
Apache APISIX provides rich traffic management features including load balancing, dynamic upstream configuration, canary releases, circuit breaking, authentication, observability plugins, and more.

**Human URL:** [https://apisix.apache.org/](https://apisix.apache.org/)

#### Tags

 - API Gateway, Apache, Cloud Native

#### Properties

- [Documentation](https://apisix.apache.org/docs/apisix/getting-started/)
- [GettingStarted](https://apisix.apache.org/docs/apisix/getting-started/README/)

### Apache APISIX Admin API
The Apache APISIX Admin API provides a RESTful interface to dynamically control and configure a running APISIX instance, supporting routes, services, upstreams, consumers, SSL, global rules, plugin configs, consumer groups, and secrets.

**Human URL:** [https://apisix.apache.org/docs/apisix/admin-api/](https://apisix.apache.org/docs/apisix/admin-api/)

#### Tags

 - Admin, Configuration, Management, REST

#### Properties

- [Documentation](https://apisix.apache.org/docs/apisix/admin-api/)
- [OpenAPI](openapi/apache-apisix-admin-api-openapi.yml)
- [Authentication](https://apisix.apache.org/docs/apisix/admin-api/#using-the-admin-api)

### Apache APISIX Control API
The Apache APISIX Control API provides internal status and health check endpoints for monitoring and introspecting a running APISIX instance.

**Human URL:** [https://apisix.apache.org/docs/apisix/control-api/](https://apisix.apache.org/docs/apisix/control-api/)

#### Tags

 - Control, Health Check, Monitoring, Observability

#### Properties

- [Documentation](https://apisix.apache.org/docs/apisix/control-api/)
- [OpenAPI](openapi/apache-apisix-control-api-openapi.yml)

## Common Properties

- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/apisix)
- [Documentation](https://apisix.apache.org/docs/)
- [GettingStarted](https://apisix.apache.org/docs/apisix/getting-started/)
- [Blog](https://apisix.apache.org/blog/)
- [ChangeLog](https://github.com/apache/apisix/releases)
- [Support](https://apisix.apache.org/docs/general/community/)
- [StackOverflow](https://stackoverflow.com/questions/tagged/apache-apisix)

## Features

| Name | Description |
|------|-------------|
| Dynamic Route Configuration | Dynamically add, update, and delete routes without restarting via the Admin API and etcd-backed config. |
| Multi-Protocol Support | Supports HTTP, HTTPS, HTTP/2, gRPC, TCP, UDP, and WebSocket protocols for diverse API types. |
| Plugin Ecosystem | Rich plugin ecosystem for authentication (JWT, key-auth, OAuth2), rate limiting, transformations, and observability. |
| Multi-Language Plugin Support | Plugins can be written in Lua, Go, Python, Java, and Node.js via the Plugin Runner architecture. |
| Load Balancing | Supports round-robin, consistent hashing, EWMA, and least connections load balancing strategies. |
| Canary Releases | Traffic splitting for canary deployments and A/B testing with percentage-based routing. |
| Circuit Breaking | Built-in circuit breaker plugin for resilience and fault tolerance in upstream communication. |
| Kubernetes Integration | Native Kubernetes ingress controller (APISIX Ingress) for Kubernetes-native API gateway deployments. |
| Observability | Native integrations with Prometheus, Zipkin, SkyWalking, Datadog, and OpenTelemetry for metrics and tracing. |
| Service Discovery | Dynamic service discovery via Kubernetes, Nacos, Consul, Eureka, and DNS for upstream resolution. |

## Use Cases

| Name | Description |
|------|-------------|
| API Gateway for Microservices | Route and manage traffic to microservices with dynamic configuration and plugin-based policies. |
| Authentication and Authorization | Apply JWT, key-auth, LDAP, OIDC, and OAuth2 plugins to protect APIs without changing upstream services. |
| Rate Limiting and Throttling | Apply global or per-consumer rate limits to protect upstream services from traffic spikes. |
| Canary and Blue-Green Deployments | Use traffic splitting to gradually roll out new API versions with percentage-based routing. |
| Kubernetes Ingress Controller | Replace traditional ingress controllers with APISIX for rich API gateway features in Kubernetes. |
| API Observability | Collect metrics, traces, and logs via native integrations with Prometheus, Zipkin, and SkyWalking. |

## Integrations

| Name | Description |
|------|-------------|
| Kubernetes | Native Kubernetes Ingress controller (APISIX Ingress Controller) for cloud-native deployments. |
| Prometheus | Native Prometheus metrics exporter for monitoring route, consumer, and upstream metrics. |
| Zipkin and Jaeger | Distributed tracing integration for request flow analysis across microservices. |
| OpenTelemetry | OpenTelemetry plugin for standardized telemetry data export. |
| etcd | etcd backend for distributed configuration storage and cluster synchronization. |
| Nacos and Consul | Dynamic service discovery integrations for automatic upstream resolution. |
| HashiCorp Vault | Secret management integration for storing API credentials and TLS certificates. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache APISIX Admin API](openapi/apache-apisix-admin-api-openapi.yml)
- [Apache APISIX Control API](openapi/apache-apisix-control-api-openapi.yml)

### JSON Schema

- [Route](json-schema/route.json)
- [Upstream](json-schema/upstream.json)
- [Service](json-schema/service.json)
- [Consumer](json-schema/consumer.json)
- [SSL](json-schema/ssl.json)
- [Global Rule](json-schema/global-rule.json)
- [Plugin Config](json-schema/plugin-config.json)
- [Consumer Group](json-schema/consumer-group.json)
- [Stream Route](json-schema/stream-route.json)
- [Secret](json-schema/secret.json)

### JSON Structure

- [Route Structure](json-structure/route-structure.json)
- [Upstream Structure](json-structure/upstream-structure.json)
- [Service Structure](json-structure/service-structure.json)
- [Consumer Structure](json-structure/consumer-structure.json)
- [SSL Structure](json-structure/ssl-structure.json)

### JSON-LD

- [Apache APISIX Context](json-ld/apache-apisix-context.jsonld)

### Examples

- [Route Example](examples/route-example.json)
- [Upstream Example](examples/upstream-example.json)
- [Consumer Example](examples/consumer-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache APISIX Admin API](capabilities/shared/apisix-admin.yaml) — 11 operations for route, upstream, service, consumer, and SSL management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache APISIX Gateway Configuration](capabilities/apisix-gateway-config.yaml) | APISIX Admin | 8 | Platform Engineer, API Gateway Administrator |

## Vocabulary

- [Apache APISIX Vocabulary](vocabulary/apache-apisix-vocabulary.yaml) — Unified taxonomy mapping 12 resources, 6 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache APISIX Spectral Rules](rules/apache-apisix-spectral-rules.yml) — 19 rules across 7 categories enforcing Apache APISIX API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
