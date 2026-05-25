# ThingsBoard (thingsboard)

ThingsBoard is an open-source IoT platform for device connectivity, data collection, processing, and visualization. Licensed under Apache 2.0 and developed by ThingsBoard Inc., it supports multi-tenant device management, telemetry over MQTT/HTTP/CoAP/LwM2M/SNMP, a drag-and-drop rule engine, calculated fields, 600+ customizable dashboard widgets, alarms, RPC, OTA firmware updates, edge computing, mobile apps, and a distributed MQTT broker (TBMQ). Available as Community Edition (free, self-hosted), Professional Edition (self-hosted subscription), and ThingsBoard Cloud (managed PaaS).

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/thingsboard/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=opensource-api-evangelist&utm_content=repo)

## Tags

- IoT, Internet of Things, Device Management, Telemetry, Open Source, Apache 2.0, MQTT, LwM2M, CoAP, Rule Engine, Dashboards, Edge, Multi-tenant, Java, Spring

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Editions

| Edition | Hosting | License | Pricing |
|---|---|---|---|
| Community Edition | Self-hosted | Apache 2.0 | Free |
| Professional Edition | Self-hosted | Commercial | From $10/mo (Maker) to $499/mo (Business) |
| ThingsBoard Cloud | Managed PaaS | SaaS | Free, $49, $149, $399, $749 / month |
| ThingsBoard Private Cloud | Dedicated managed | SaaS | From $1,499 to custom enterprise |

## APIs

ThingsBoard exposes a single REST API surface (`/api/*`) that we split into 15 logical sub-APIs aligned to the project's own Spring controllers.

### ThingsBoard Devices API
Provision, list, retrieve, update, assign, and delete IoT devices and device profiles. Includes device connectivity helpers and OTA package management.

- [OpenAPI](openapi/thingsboard-devices-openapi.yml)
- [JSON Schema — Device](json-schema/thingsboard-device-schema.json)
- [JSON Schema — DeviceProfile](json-schema/thingsboard-deviceprofile-schema.json)
- [Naftiko Capability — Devices](capabilities/devices-devices.yaml)

### ThingsBoard Assets API
Logical/physical asset modelling with profiles, entity views, and typed entity relations for hierarchical IoT solutions.

- [OpenAPI](openapi/thingsboard-assets-openapi.yml)
- [JSON Schema — Asset](json-schema/thingsboard-asset-schema.json)
- [JSON Schema — AssetProfile](json-schema/thingsboard-assetprofile-schema.json)
- [JSON Schema — EntityRelation](json-schema/thingsboard-entityrelation-schema.json)

### ThingsBoard Telemetry API
Read and write device/asset time-series telemetry and key/value attributes (CLIENT/SERVER/SHARED scopes), run entity queries, and manage calculated fields.

- [OpenAPI](openapi/thingsboard-telemetry-openapi.yml)
- [Naftiko Capability — Telemetry](capabilities/telemetry-timeseries.yaml)

### ThingsBoard Alarms API
Manage IoT alarms — list, acknowledge, clear, assign, and comment.

- [OpenAPI](openapi/thingsboard-alarms-openapi.yml)
- [JSON Schema — Alarm](json-schema/thingsboard-alarm-schema.json)
- [Naftiko Capability — Alarms](capabilities/alarms-alarms.yaml)

### ThingsBoard Rule Engine API
Manage Rule Chains, Rule Nodes, and component descriptors that power the drag-and-drop data-processing engine.

- [OpenAPI](openapi/thingsboard-rule-engine-openapi.yml)
- [JSON Schema — RuleChain](json-schema/thingsboard-rulechain-schema.json)
- [Naftiko Capability — Rule Engine](capabilities/rule-engine-rule-chains.yaml)

### ThingsBoard RPC API
One-way and two-way Remote Procedure Calls from server to device, with persistent RPC support (v2).

- [OpenAPI](openapi/thingsboard-rpc-openapi.yml)
- [Naftiko Capability — RPC](capabilities/rpc-rpc.yaml)

### ThingsBoard Dashboards API
Create and manage dashboards, widget bundles, widget types, image and tenant resources. Includes SCADA dashboards.

- [OpenAPI](openapi/thingsboard-dashboards-openapi.yml)
- [JSON Schema — Dashboard](json-schema/thingsboard-dashboard-schema.json)
- [Naftiko Capability — Dashboards](capabilities/dashboards-dashboards.yaml)

### ThingsBoard Authentication API
Login (JWT), refresh tokens, sign-up, API key management (since 4.3), 2FA, OAuth2 federation, custom domains.

- [OpenAPI](openapi/thingsboard-auth-openapi.yml)
- [Naftiko Capability — Auth](capabilities/auth-login.yaml)

### ThingsBoard Tenants and Customers API
Tenants, tenant profiles, customers, and users — the multi-tenancy backbone.

- [OpenAPI](openapi/thingsboard-tenants-openapi.yml)
- [JSON Schema — Tenant](json-schema/thingsboard-tenant-schema.json)
- [JSON Schema — Customer](json-schema/thingsboard-customer-schema.json)
- [JSON Schema — User](json-schema/thingsboard-user-schema.json)

### ThingsBoard Admin API
System-administrator endpoints — admin settings, audit logs, events, usage info, queues, queue stats, mail-config templates, QR-code settings, jobs.

- [OpenAPI](openapi/thingsboard-admin-openapi.yml)

### ThingsBoard Notifications API
Notification requests, rules, templates, and targets across email, SMS, Slack, MS Teams, mobile push, and web.

- [OpenAPI](openapi/thingsboard-notifications-openapi.yml)
- [Naftiko Capability — Notifications](capabilities/notifications-notifications.yaml)

### ThingsBoard Edge API
ThingsBoard Edge instance lifecycle — provisioning, synchronization, event tracking, and entity version control.

- [OpenAPI](openapi/thingsboard-edge-openapi.yml)
- [Naftiko Capability — Edge](capabilities/edge-edges.yaml)

### ThingsBoard Mobile App API
Mobile app configurations and bundles used by the ThingsBoard Flutter mobile apps.

- [OpenAPI](openapi/thingsboard-mobile-openapi.yml)

### ThingsBoard LwM2M API
LwM2M device-management endpoints for low-power devices over CoAP/DTLS.

- [OpenAPI](openapi/thingsboard-lwm2m-openapi.yml)

### ThingsBoard AI API
AI model management and Trendz Analytics integration for forecasting, anomaly detection, and predictive-maintenance.

- [OpenAPI](openapi/thingsboard-ai-openapi.yml)

## Common Properties

- [Portal — thingsboard.io](https://thingsboard.io)
- [Documentation](https://thingsboard.io/docs/)
- [REST API Reference](https://thingsboard.io/docs/reference/rest-api/)
- [Live OpenAPI 3.1 Spec](https://demo.thingsboard.io/v3/api-docs)
- [Swagger UI](https://demo.thingsboard.io/swagger-ui/index.html)
- [Sandbox — demo.thingsboard.io](https://demo.thingsboard.io/)
- [Pricing](https://thingsboard.io/pricing/)
- [Blog](https://thingsboard.io/blog/)
- [SignUp — ThingsBoard Cloud](https://thingsboard.cloud/signup)
- [Releases Table](https://thingsboard.io/docs/releases/releases-table/)
- [GitHubOrganization — thingsboard](https://github.com/thingsboard)
- [SourceCode — ThingsBoard core](https://github.com/thingsboard/thingsboard)
- [Tool — IoT Gateway](https://github.com/thingsboard/thingsboard-gateway)
- [Tool — Edge](https://github.com/thingsboard/thingsboard-edge)
- [Tool — TBMQ MQTT Broker](https://github.com/thingsboard/tbmq)
- [Tool — Mobile (Flutter)](https://github.com/thingsboard/flutter_thingsboard_app)
- [Tool — PE Mobile (Flutter)](https://github.com/thingsboard/flutter_thingsboard_pe_app)
- [SDK — Java REST client](https://github.com/thingsboard/thingsboard-java-client)
- [SDK — Python REST client](https://github.com/thingsboard/thingsboard-python-client)
- [SDK — ngx-flowchart (Angular)](https://github.com/thingsboard/ngx-flowchart)
- [Tool — Docker Hub](https://hub.docker.com/u/thingsboard)
- [Forum — Stack Overflow](https://stackoverflow.com/questions/tagged/thingsboard)
- [License — Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)

## Artifacts

### OpenAPI

- [Devices](openapi/thingsboard-devices-openapi.yml)
- [Assets](openapi/thingsboard-assets-openapi.yml)
- [Telemetry](openapi/thingsboard-telemetry-openapi.yml)
- [Alarms](openapi/thingsboard-alarms-openapi.yml)
- [Rule Engine](openapi/thingsboard-rule-engine-openapi.yml)
- [RPC](openapi/thingsboard-rpc-openapi.yml)
- [Dashboards](openapi/thingsboard-dashboards-openapi.yml)
- [Authentication](openapi/thingsboard-auth-openapi.yml)
- [Tenants and Customers](openapi/thingsboard-tenants-openapi.yml)
- [Admin](openapi/thingsboard-admin-openapi.yml)
- [Notifications](openapi/thingsboard-notifications-openapi.yml)
- [Edge](openapi/thingsboard-edge-openapi.yml)
- [Mobile App](openapi/thingsboard-mobile-openapi.yml)
- [LwM2M](openapi/thingsboard-lwm2m-openapi.yml)
- [AI](openapi/thingsboard-ai-openapi.yml)

### JSON Schema

- [Device](json-schema/thingsboard-device-schema.json)
- [DeviceProfile](json-schema/thingsboard-deviceprofile-schema.json)
- [Asset](json-schema/thingsboard-asset-schema.json)
- [AssetProfile](json-schema/thingsboard-assetprofile-schema.json)
- [Dashboard](json-schema/thingsboard-dashboard-schema.json)
- [Customer](json-schema/thingsboard-customer-schema.json)
- [Tenant](json-schema/thingsboard-tenant-schema.json)
- [User](json-schema/thingsboard-user-schema.json)
- [Alarm](json-schema/thingsboard-alarm-schema.json)
- [RuleChain](json-schema/thingsboard-rulechain-schema.json)
- [EntityRelation](json-schema/thingsboard-entityrelation-schema.json)

### JSON-LD

- [ThingsBoard context](json-ld/thingsboard-context.jsonld)

### Capabilities (Naftiko)

- [Devices](capabilities/devices-devices.yaml)
- [Telemetry](capabilities/telemetry-timeseries.yaml)
- [Alarms](capabilities/alarms-alarms.yaml)
- [RPC](capabilities/rpc-rpc.yaml)
- [Dashboards](capabilities/dashboards-dashboards.yaml)
- [Authentication](capabilities/auth-login.yaml)
- [Rule Engine](capabilities/rule-engine-rule-chains.yaml)
- [Edge](capabilities/edge-edges.yaml)
- [Notifications](capabilities/notifications-notifications.yaml)

### Examples

- [Login example](examples/thingsboard-login-example.json)
- [Telemetry post example](examples/thingsboard-telemetry-post-example.json)

### Commercial artifacts

- [Plans / Pricing](plans/thingsboard-plans-pricing.yml)
- [Rate Limits](rate-limits/thingsboard-rate-limits.yml)
- [FinOps Definition](finops/thingsboard-finops.yml)

### Vocabulary and Rules

- [Vocabulary](vocabulary/thingsboard-vocabulary.yml)
- [Spectral Rules](rules/thingsboard-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
