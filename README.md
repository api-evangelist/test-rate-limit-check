# Test Rate Limit Check (test-rate-limit-check)
Testing and validation of API rate limiting implementations to ensure that APIs correctly enforce request quotas, return appropriate error responses, and recover gracefully when limits are exceeded. Rate limit testing verifies throttling behavior, retry-after headers, burst allowances, and quota reset mechanisms across different API consumers and usage tiers.

**URL:** [Visit APIs.json URL](https://en.wikipedia.org/wiki/Rate_limiting)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Governance, API Management, API Testing, Performance Testing, Rate Limiting, Testing

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-03

## APIs

### Kong Gateway Admin API
Admin REST API for Kong API Gateway, providing endpoints to configure rate limiting plugins, quotas, consumers, and traffic policies for API rate limit enforcement.

**Human URL:** [https://docs.konghq.com/gateway/latest/admin-api/](https://docs.konghq.com/gateway/latest/admin-api/)

#### Tags:

 - API Gateway, API Management, Rate Limiting, Traffic Control

#### Properties

- [Documentation](https://docs.konghq.com/gateway/latest/admin-api/)

### AWS API Gateway API
AWS REST API for managing API Gateway usage plans, API keys, throttling limits, and quota enforcement across API deployments.

**Human URL:** [https://docs.aws.amazon.com/apigateway/latest/developerguide/api-ref.html](https://docs.aws.amazon.com/apigateway/latest/developerguide/api-ref.html)

#### Tags:

 - AWS, API Gateway, Cloud, Rate Limiting

#### Properties

- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/api-ref.html)

### Apigee API
REST API for Google Apigee API management platform supporting rate limit policy configuration, quota management, spike arrest, and traffic shaping for API testing.

**Human URL:** [https://cloud.google.com/apigee/docs/reference/apis/apigee/rest](https://cloud.google.com/apigee/docs/reference/apis/apigee/rest)

#### Tags:

 - API Management, Google Cloud, Quotas, Rate Limiting

#### Properties

- [Documentation](https://cloud.google.com/apigee/docs/reference/apis/apigee/rest)

### Azure API Management API
REST API for Azure API Management service supporting subscription quotas, rate limit policies, and throttling configuration for testing rate limit implementations.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/apimanagement/](https://learn.microsoft.com/en-us/rest/api/apimanagement/)

#### Tags:

 - API Management, Azure, Microsoft, Rate Limiting

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/apimanagement/)

### Tyk API Management API
REST API for Tyk open-source API gateway supporting rate limiting, quota management, key expiry, and throttling policy configuration and testing.

**Human URL:** [https://tyk.io/docs/tyk-gateway-api/](https://tyk.io/docs/tyk-gateway-api/)

#### Tags:

 - API Gateway, API Management, Open Source, Rate Limiting

#### Properties

- [Documentation](https://tyk.io/docs/tyk-gateway-api/)
- [OpenAPI](https://raw.githubusercontent.com/TykTechnologies/tyk/master/apidef/oas/schema/x-tyk-gateway.json)

### Grafana API
REST API for Grafana observability platform, enabling rate limit test monitoring through dashboards, alerts, and metrics visualization for API traffic and throttling behavior.

**Human URL:** [https://grafana.com/docs/grafana/latest/developers/http_api/](https://grafana.com/docs/grafana/latest/developers/http_api/)

#### Tags:

 - Dashboards, Metrics, Monitoring, Observability

#### Properties

- [Documentation](https://grafana.com/docs/grafana/latest/developers/http_api/)
- [OpenAPI](https://raw.githubusercontent.com/grafana/grafana/main/public/api-spec.json)

## Common Properties

- [Documentation](https://en.wikipedia.org/wiki/Rate_limiting)
- [Documentation](https://www.rfc-editor.org/rfc/rfc6585#section-4)

## Features

| Name | Description |
|------|-------------|
| Rate Limit Header Validation | Verify that APIs return correct X-RateLimit-Limit, X-RateLimit-Remaining, and Retry-After headers. |
| 429 Response Testing | Confirm that APIs return HTTP 429 Too Many Requests when rate limits are exceeded. |
| Quota Reset Verification | Test that rate limit counters reset correctly after the defined window period. |
| Burst Allowance Testing | Validate burst rate limits that allow short-term traffic spikes above baseline quotas. |
| Per-Consumer Rate Limiting | Test that rate limits are correctly scoped to individual API keys or consumers. |
| Concurrent Request Testing | Verify rate limiting behavior under concurrent parallel request loads. |

## Use Cases

| Name | Description |
|------|-------------|
| API Gateway Rate Limit Validation | Verify that API gateway rate limiting plugins correctly enforce configured quotas. |
| Throttling Behavior Testing | Test that API clients receive appropriate throttling signals and can implement retry logic. |
| Usage Tier Enforcement | Validate that different subscription tiers enforce their respective rate limits correctly. |
| Rate Limit Recovery Testing | Confirm that APIs correctly recover and allow traffic after rate limit windows reset. |
| Load Test Rate Limit Interaction | Understand how rate limits interact with load testing to avoid false failures. |

## Integrations

| Name | Description |
|------|-------------|
| k6 | Use k6 load testing tool to generate traffic for rate limit validation and testing. |
| Apache JMeter | Use JMeter to send concurrent requests and validate rate limit enforcement. |
| Postman | Use Postman test scripts to assert rate limit headers and 429 responses. |
| Prometheus | Monitor rate limit metrics with Prometheus for alerting and trend analysis. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Rate Limit Config Schema](json-schema/test-rate-limit-check-rate-limit-config-schema.json)
- [Rate Limit Response Schema](json-schema/test-rate-limit-check-rate-limit-response-schema.json)
- [API Quota Schema](json-schema/test-rate-limit-check-quota-schema.json)

### JSON Structure

- [Rate Limit Config Structure](json-structure/test-rate-limit-check-rate-limit-config-structure.json)
- [Rate Limit Response Structure](json-structure/test-rate-limit-check-rate-limit-response-structure.json)
- [API Quota Structure](json-structure/test-rate-limit-check-quota-structure.json)

### JSON-LD

- [Test Rate Limit Check Context](json-ld/test-rate-limit-check-context.jsonld)

### Examples

- [Rate Limit Config Example](examples/test-rate-limit-check-rate-limit-config-example.json)
- [Rate Limit Response Example](examples/test-rate-limit-check-rate-limit-response-example.json)
- [API Quota Example](examples/test-rate-limit-check-quota-example.json)

## Vocabulary

- [Test Rate Limit Check Vocabulary](vocabulary/test-rate-limit-check-vocabulary.yml) — Unified taxonomy mapping 3 resources, 6 actions, and 4 personas across rate limit testing domains.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
