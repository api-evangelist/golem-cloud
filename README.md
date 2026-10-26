# Golem (golem-cloud)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
