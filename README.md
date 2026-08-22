# Test Rate Limit Check (test-rate-limit-check)

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

Testing and validation of API rate limiting implementations to ensure that APIs correctly enforce request quotas, return appropriate error responses, and recover gracefully when limits are exceeded. Rate limit testing verifies throttling behavior, retry-after headers, burst allowances, and quota reset mechanisms across different API consumers and usage tiers.

**APIs.json:** [https://en.wikipedia.org/wiki/Rate_limiting](https://en.wikipedia.org/wiki/Rate_limiting)

## Tags

- API Governance
- API Management
- API Testing
- Performance Testing
- Rate Limiting
- Testing

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-03

## APIs

### Kong Gateway Admin API

Admin REST API for Kong API Gateway, providing endpoints to configure rate limiting plugins, quotas, consumers, and traffic policies for API rate limit enforcement.

- **Human URL:** [https://docs.konghq.com/gateway/latest/admin-api/](https://docs.konghq.com/gateway/latest/admin-api/)
- **Base URL:** `https://your-kong.example.com:8001`

#### Tags

- API Gateway
- API Management
- Rate Limiting
- Traffic Control

#### Properties

- [Documentation](https://docs.konghq.com/gateway/latest/admin-api/)
- [OpenAPI](https://docs.konghq.com/gateway/latest/admin-api/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/test-rate-limit-check.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-rate-limit-check.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AWS API Gateway API

AWS REST API for managing API Gateway usage plans, API keys, throttling limits, and quota enforcement across API deployments.

- **Human URL:** [https://docs.aws.amazon.com/apigateway/latest/developerguide/api-ref.html](https://docs.aws.amazon.com/apigateway/latest/developerguide/api-ref.html)
- **Base URL:** `https://apigateway.amazonaws.com`

#### Tags

- AWS
- API Gateway
- Cloud
- Rate Limiting

#### Properties

- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/api-ref.html)
- [Postman Collection](collections/test-rate-limit-check.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-rate-limit-check.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apigee API

REST API for Google Apigee API management platform supporting rate limit policy configuration, quota management, spike arrest, and traffic shaping for API testing.

- **Human URL:** [https://cloud.google.com/apigee/docs/reference/apis/apigee/rest](https://cloud.google.com/apigee/docs/reference/apis/apigee/rest)
- **Base URL:** `https://apigee.googleapis.com/v1`

#### Tags

- API Management
- Google Cloud
- Quotas
- Rate Limiting

#### Properties

- [Documentation](https://cloud.google.com/apigee/docs/reference/apis/apigee/rest)
- [Postman Collection](collections/test-rate-limit-check.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-rate-limit-check.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure API Management API

REST API for Azure API Management service supporting subscription quotas, rate limit policies, and throttling configuration for testing rate limit implementations.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/apimanagement/](https://learn.microsoft.com/en-us/rest/api/apimanagement/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}`

#### Tags

- API Management
- Azure
- Microsoft
- Rate Limiting

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/apimanagement/)
- [Postman Collection](collections/test-rate-limit-check.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-rate-limit-check.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tyk API Management API

REST API for Tyk open-source API gateway supporting rate limiting, quota management, key expiry, and throttling policy configuration and testing.

- **Human URL:** [https://tyk.io/docs/tyk-gateway-api/](https://tyk.io/docs/tyk-gateway-api/)
- **Base URL:** `https://your-tyk.example.com/api`

#### Tags

- API Gateway
- API Management
- Open Source
- Rate Limiting

#### Properties

- [Documentation](https://tyk.io/docs/tyk-gateway-api/)
- [OpenAPI](https://raw.githubusercontent.com/TykTechnologies/tyk/master/apidef/oas/schema/x-tyk-gateway.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/test-rate-limit-check.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-rate-limit-check.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Grafana API

REST API for Grafana observability platform, enabling rate limit test monitoring through dashboards, alerts, and metrics visualization for API traffic and throttling behavior.

- **Human URL:** [https://grafana.com/docs/grafana/latest/developers/http_api/](https://grafana.com/docs/grafana/latest/developers/http_api/)
- **Base URL:** `https://your-grafana.example.com/api`

#### Tags

- Dashboards
- Metrics
- Monitoring
- Observability

#### Properties

- [Documentation](https://grafana.com/docs/grafana/latest/developers/http_api/)
- [OpenAPI](https://raw.githubusercontent.com/grafana/grafana/main/public/api-spec.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/test-rate-limit-check.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/test-rate-limit-check.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Documentation](https://en.wikipedia.org/wiki/Rate_limiting)
- [Documentation](https://www.rfc-editor.org/rfc/rfc6585#section-4)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [JSON Schema](json-schema/test-rate-limit-check-rate-limit-config-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/test-rate-limit-check-rate-limit-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/test-rate-limit-check-quota-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/test-rate-limit-check-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/test-rate-limit-check-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
