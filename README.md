# Test Rate Limit Check (test-rate-limit-check)

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
