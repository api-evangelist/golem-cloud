# Golem (golem-cloud)

Golem is an open-source durable computing platform for building agents and distributed applications that never lose state. You deploy WebAssembly components and invoke durable serverless workers through a REST API; the runtime transparently persists every worker's execution so it survives crashes, restarts, and redeploys. Golem ships as open source you self-host and as the managed Golem Cloud hosted service.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/golem-cloud/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/golem-cloud/refs/heads/main/apis.yml)

## Tags

- Durable Computing
- Serverless
- WebAssembly
- Workers
- Agents

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Golem Components API

Upload, version, and list WebAssembly components in an environment. Each component is the deployable unit of code from which durable workers (agents) are launched, with revisions and downloadable WASM binaries.

- **Human URL:** [https://learn.golem.cloud/concepts/components](https://learn.golem.cloud/concepts/components)
- **Base URL:** `https://release.api.golem.cloud`

#### Tags

- Components
- WebAssembly
- Registry

#### Properties

- [Documentation](https://learn.golem.cloud/concepts/components)
- [API Reference](https://learn.golem.cloud/rest-api/component)
- [OpenAPI](openapi/golem-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/golem-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/golem-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/golemcloud/golem)

### Golem Workers & Invocation API

Launch, invoke, and manage durable workers. Invoke fire-and-forget or invoke-and-await for results, interrupt, resume, update, revert, fork, inspect oplog and files, and stream live events over a WebSocket connection. Execution is durably persisted so workers survive failures.

- **Human URL:** [https://learn.golem.cloud/concepts/workers](https://learn.golem.cloud/concepts/workers)
- **Base URL:** `https://release.api.golem.cloud`

#### Tags

- Workers
- Invocation
- Durable Execution

#### Properties

- [Documentation](https://learn.golem.cloud/concepts/workers)
- [API Reference](https://learn.golem.cloud/rest-api/worker)
- [OpenAPI](openapi/golem-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/golem-cloud-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/golem-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/golem-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/golemcloud/golem)

### Golem API Definitions & Deployments API

Define and deploy custom HTTP APIs (the Worker Gateway) that map external HTTP routes onto worker invocations, bind them to domains, and manage deployment revisions per environment - turning durable workers into public HTTP endpoints.

- **Human URL:** [https://learn.golem.cloud/invoke/making-custom-apis](https://learn.golem.cloud/invoke/making-custom-apis)
- **Base URL:** `https://release.api.golem.cloud`

#### Tags

- API Gateway
- Deployments
- HTTP APIs

#### Properties

- [Documentation](https://learn.golem.cloud/invoke/making-custom-apis)
- [API Reference](https://learn.golem.cloud/rest-api/api-deployment)
- [OpenAPI](openapi/golem-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/golem-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/golem-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/golemcloud/golem)

### Golem Plugins API

Register, list, and delete plugins and grant them to environments; plugins can be activated or deactivated on individual workers to extend the runtime with component transformation and observability hooks.

- **Human URL:** [https://learn.golem.cloud/concepts/plugins](https://learn.golem.cloud/concepts/plugins)
- **Base URL:** `https://release.api.golem.cloud`

#### Tags

- Plugins
- Extensibility

#### Properties

- [Documentation](https://learn.golem.cloud/concepts/plugins)
- [API Reference](https://learn.golem.cloud/rest-api/plugin)
- [OpenAPI](openapi/golem-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/golem-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/golem-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/golemcloud/golem)

## Common Properties

- [GitHub Organization](https://github.com/golemcloud)
- [LinkedIn](https://www.linkedin.com/company/golem-cloud)
- [Website](https://www.golem.cloud)
- [Documentation](https://learn.golem.cloud)
- [Plans](plans/golem-cloud-plans-pricing.yml)
- [Rate Limits](rate-limits/golem-cloud-rate-limits.yml)
- [Fin Ops](finops/golem-cloud-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
