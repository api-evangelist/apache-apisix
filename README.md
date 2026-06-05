# Apache APISIX (apache-apisix)

Apache APISIX is a dynamic, real-time, high-performance cloud-native API gateway built on NGINX and etcd, developed by the Apache Software Foundation. It supports Lua and multi-language plugins for traffic management, authentication, observability, and security. APISIX provides a RESTful Admin API for dynamic configuration of routes, upstreams, services, consumers, SSL certificates, and plugins, and a Control API for health monitoring and schema introspection.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-apisix/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-apisix/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Apache
- API Gateway
- Cloud Native
- Kubernetes
- Lua
- NGINX
- Open Source
- Traffic Management

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-05-19

## APIs

### Apache APISIX Gateway

Apache APISIX provides rich traffic management features including load balancing, dynamic upstream configuration, canary releases, circuit breaking, authentication, observability plugins, and more. It is built on NGINX for high performance with etcd for distributed configuration.

- **Human URL:** [https://apisix.apache.org/](https://apisix.apache.org/)

#### Tags

- API Gateway
- Apache
- Cloud Native

#### Properties

- [Documentation](https://apisix.apache.org/docs/apisix/getting-started/)
- [Getting Started](https://apisix.apache.org/docs/apisix/getting-started/README/)
- [Postman Collection](collections/apache-apisix-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-apisix-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/apache-apisix-control-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-apisix-control-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache APISIX Admin API

The Apache APISIX Admin API provides a RESTful interface to dynamically control and configure a running APISIX instance. It supports management of routes, services, upstreams, consumers, SSL certificates, global rules, plugin configurations, consumer groups, and secrets, and listens by default on port 9180 with API key authentication.

- **Human URL:** [https://apisix.apache.org/docs/apisix/admin-api/](https://apisix.apache.org/docs/apisix/admin-api/)

#### Tags

- Admin
- Configuration
- Management
- REST

#### Properties

- [Documentation](https://apisix.apache.org/docs/apisix/admin-api/)
- [OpenAPI](openapi/apache-apisix-admin-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-apisix-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-apisix-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://apisix.apache.org/docs/apisix/admin-api/#using-the-admin-api)

### Apache APISIX Control API

The Apache APISIX Control API provides internal status and health check endpoints for monitoring and introspecting a running APISIX instance. It listens by default on port 9090, is accessible only from localhost, and exposes endpoints for health checking, schema retrieval, and runtime diagnostics.

- **Human URL:** [https://apisix.apache.org/docs/apisix/control-api/](https://apisix.apache.org/docs/apisix/control-api/)

#### Tags

- Control
- Health Check
- Monitoring
- Observability

#### Properties

- [Documentation](https://apisix.apache.org/docs/apisix/control-api/)
- [OpenAPI](openapi/apache-apisix-control-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-apisix-control-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-apisix-control-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/apache-apisix)
- [GitHub Organization](https://github.com/apache)
- [GitHub Repository](https://github.com/apache/apisix)
- [Documentation](https://apisix.apache.org/docs/)
- [Getting Started](https://apisix.apache.org/docs/apisix/getting-started/)
- [Blog](https://apisix.apache.org/blog/)
- [Changelog](https://github.com/apache/apisix/releases)
- [Support](https://apisix.apache.org/docs/general/community/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/apache-apisix)
- [JSON Schema](json-schema/route.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/upstream.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/service.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/consumer.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ssl.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/global-rule.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/plugin-config.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/consumer-group.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/stream-route.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/secret.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/apache-apisix-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/apache-apisix-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-apisix-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
