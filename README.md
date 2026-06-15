# ThingsBoard (thingsboard)

ThingsBoard is an open-source IoT platform for device connectivity, data collection, processing, and visualization. Licensed under Apache 2.0 and developed by ThingsBoard Inc., it supports multi-tenant device management, telemetry over MQTT/HTTP/CoAP/LwM2M/SNMP, a drag-and-drop rule engine, calculated fields, 600+ customizable dashboard widgets, alarms, RPC, OTA firmware updates, edge computing, mobile apps, and a distributed MQTT broker (TBMQ). Available as Community Edition (free, self-hosted), Professional Edition (self-hosted subscription), and ThingsBoard Cloud (managed PaaS).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/thingsboard/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/thingsboard/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- IoT
- Internet of Things
- Device Management
- Telemetry
- Open Source
- Apache 2.0
- MQTT
- LwM2M
- CoAP
- Rule Engine
- Dashboards
- Edge
- Multi-tenant
- Java
- Spring

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### ThingsBoard Devices API

Provision, list, retrieve, update, assign, and delete IoT devices and device profiles. Includes device connectivity helpers and OTA package management for over-the-air firmware updates. 40 endpoints across device, device-profile, device-connectivity, and ota-package controllers.

- **Human URL:** [https://thingsboard.io/docs/reference/rest-api/](https://thingsboard.io/docs/reference/rest-api/)

#### Tags

- IoT
- Devices
- Provisioning
- OTA

#### Properties

- [Documentation](https://thingsboard.io/docs/reference/rest-api/)
- [OpenAPI](openapi/thingsboard-devices-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-devices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-devices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/thingsboard-device-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/thingsboard-deviceprofile-schema.json) — [JSON Schema](https://json-schema.org/specification)

### ThingsBoard Assets API

Logical/physical asset modelling with profiles, entity views, and typed entity relations for hierarchical IoT solutions (Buildings, Floors, Rooms, Machines). 41 endpoints.

- **Human URL:** [https://thingsboard.io/docs/user-guide/assets/](https://thingsboard.io/docs/user-guide/assets/)

#### Tags

- IoT
- Assets
- Hierarchy
- EntityViews

#### Properties

- [Documentation](https://thingsboard.io/docs/user-guide/assets/)
- [OpenAPI](openapi/thingsboard-assets-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-assets.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-assets.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/thingsboard-asset-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/thingsboard-assetprofile-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/thingsboard-entityrelation-schema.json) — [JSON Schema](https://json-schema.org/specification)

### ThingsBoard Telemetry API

Read and write device/asset time-series telemetry and key/value attributes (CLIENT/SERVER/SHARED scopes), run entity queries, and manage calculated fields. 26 endpoints.

- **Human URL:** [https://thingsboard.io/docs/reference/rest-api/](https://thingsboard.io/docs/reference/rest-api/)

#### Tags

- IoT
- Telemetry
- TimeSeries
- Attributes
- CalculatedFields

#### Properties

- [Documentation](https://thingsboard.io/docs/user-guide/telemetry/)
- [OpenAPI](openapi/thingsboard-telemetry-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-telemetry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-telemetry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ThingsBoard Alarms API

Manage IoT alarms — list, acknowledge, clear, assign, and comment. Includes alarm queries and the alarm-comment thread. 15 endpoints.

- **Human URL:** [https://thingsboard.io/docs/user-guide/alarms/](https://thingsboard.io/docs/user-guide/alarms/)

#### Tags

- IoT
- Alarms
- Operations

#### Properties

- [Documentation](https://thingsboard.io/docs/user-guide/alarms/)
- [OpenAPI](openapi/thingsboard-alarms-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-alarms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-alarms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/thingsboard-alarm-schema.json) — [JSON Schema](https://json-schema.org/specification)

### ThingsBoard Rule Engine API

Manage Rule Chains, Rule Nodes, and component descriptors that power ThingsBoard's drag-and-drop data-processing engine. 26 endpoints.

- **Human URL:** [https://thingsboard.io/docs/user-guide/rule-engine-2-0/re-getting-started/](https://thingsboard.io/docs/user-guide/rule-engine-2-0/re-getting-started/)

#### Tags

- IoT
- RuleEngine
- Automation
- Workflow

#### Properties

- [Documentation](https://thingsboard.io/docs/user-guide/rule-engine-2-0/re-getting-started/)
- [OpenAPI](openapi/thingsboard-rule-engine-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-rule-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-rule-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/thingsboard-rulechain-schema.json) — [JSON Schema](https://json-schema.org/specification)

### ThingsBoard RPC API

One-way and two-way Remote Procedure Calls from server to device, with persistent RPC support (RPC v2). 6 endpoints.

- **Human URL:** [https://thingsboard.io/docs/user-guide/rpc/](https://thingsboard.io/docs/user-guide/rpc/)

#### Tags

- IoT
- RPC
- DeviceControl

#### Properties

- [Documentation](https://thingsboard.io/docs/user-guide/rpc/)
- [OpenAPI](openapi/thingsboard-rpc-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-rpc.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-rpc.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ThingsBoard Dashboards API

Create and manage dashboards, widget bundles, widget types, image resources, and tenant resources that drive the ThingsBoard UI. Includes SCADA dashboards. 57 endpoints.

- **Human URL:** [https://thingsboard.io/docs/user-guide/dashboards/](https://thingsboard.io/docs/user-guide/dashboards/)

#### Tags

- IoT
- Dashboards
- Visualization
- Widgets

#### Properties

- [Documentation](https://thingsboard.io/docs/user-guide/dashboards/)
- [OpenAPI](openapi/thingsboard-dashboards-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-dashboards.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-dashboards.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/thingsboard-dashboard-schema.json) — [JSON Schema](https://json-schema.org/specification)

### ThingsBoard Authentication API

Login (JWT), refresh tokens, sign-up, API key management (since 4.3), 2FA, OAuth2 federation, and custom domain configuration. 46 endpoints.

- **Human URL:** [https://thingsboard.io/docs/reference/rest-api/](https://thingsboard.io/docs/reference/rest-api/)

#### Tags

- IoT
- Authentication
- Security
- OAuth2
- 2FA

#### Properties

- [Documentation](https://thingsboard.io/docs/reference/rest-api/)
- [OpenAPI](openapi/thingsboard-auth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ThingsBoard Tenants and Customers API

Manage tenants, tenant profiles, customers, and users — the multi-tenancy backbone of ThingsBoard. 38 endpoints.

- **Human URL:** [https://thingsboard.io/docs/user-guide/ui/customers/](https://thingsboard.io/docs/user-guide/ui/customers/)

#### Tags

- IoT
- Tenants
- Customers
- Users
- MultiTenant

#### Properties

- [Documentation](https://thingsboard.io/docs/user-guide/ui/customers/)
- [OpenAPI](openapi/thingsboard-tenants-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-tenants.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-tenants.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/thingsboard-tenant-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/thingsboard-customer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/thingsboard-user-schema.json) — [JSON Schema](https://json-schema.org/specification)

### ThingsBoard Admin API

System-administrator endpoints — admin settings, audit logs, events, usage info, queues and queue stats, mail-config templates, QR-code settings, and background jobs. 42 endpoints.

- **Human URL:** [https://thingsboard.io/docs/reference/rest-api/](https://thingsboard.io/docs/reference/rest-api/)

#### Tags

- IoT
- Administration
- AuditLog
- Queue
- Usage

#### Properties

- [Documentation](https://thingsboard.io/docs/reference/rest-api/)
- [OpenAPI](openapi/thingsboard-admin-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ThingsBoard Notifications API

Manage notification requests, rules, templates, and targets across email, SMS, Slack, MS Teams, mobile push, and web delivery channels. 24 endpoints.

- **Human URL:** [https://thingsboard.io/docs/user-guide/notifications/](https://thingsboard.io/docs/user-guide/notifications/)

#### Tags

- IoT
- Notifications
- Messaging
- Email
- Slack

#### Properties

- [Documentation](https://thingsboard.io/docs/user-guide/notifications/)
- [OpenAPI](openapi/thingsboard-notifications-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-notifications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-notifications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ThingsBoard Edge API

Manage ThingsBoard Edge instances — provisioning, synchronization, event tracking, and entity version control between edge and cloud. 32 endpoints.

- **Human URL:** [https://thingsboard.io/docs/edge/](https://thingsboard.io/docs/edge/)

#### Tags

- IoT
- Edge
- Sync
- VersionControl

#### Properties

- [Documentation](https://thingsboard.io/docs/edge/)
- [OpenAPI](openapi/thingsboard-edge-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-edge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-edge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ThingsBoard Mobile App API

Manage mobile app configurations and mobile-app bundles used by the ThingsBoard mobile applications (Flutter). 9 endpoints.

- **Human URL:** [https://thingsboard.io/docs/user-guide/mobile-app/](https://thingsboard.io/docs/user-guide/mobile-app/)

#### Tags

- IoT
- Mobile
- AppCenter

#### Properties

- [Documentation](https://thingsboard.io/docs/user-guide/mobile-app/)
- [OpenAPI](openapi/thingsboard-mobile-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-mobile.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-mobile.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ThingsBoard LwM2M API

LwM2M (Lightweight M2M) device-management endpoints for low-power devices over CoAP/DTLS. 2 endpoints.

- **Human URL:** [https://thingsboard.io/docs/user-guide/lwm2m/](https://thingsboard.io/docs/user-guide/lwm2m/)

#### Tags

- IoT
- LwM2M
- Protocols

#### Properties

- [Documentation](https://thingsboard.io/docs/user-guide/lwm2m/)
- [OpenAPI](openapi/thingsboard-lwm2m-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-lwm2m.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-lwm2m.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ThingsBoard AI API

AI model management and Trendz Analytics integration for forecasting, anomaly detection, and predictive-maintenance workflows over IoT telemetry. 4 endpoints.

- **Human URL:** [https://thingsboard.io/products/trendz/](https://thingsboard.io/products/trendz/)

#### Tags

- IoT
- AI
- PredictiveMaintenance
- Trendz

#### Properties

- [Documentation](https://thingsboard.io/products/trendz/)
- [OpenAPI](openapi/thingsboard-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thingsboard-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thingsboard-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://thingsboard.io)
- [Documentation](https://thingsboard.io/docs/)
- [Getting Started](https://thingsboard.io/docs/getting-started-guides/helloworld/)
- [Documentation](https://thingsboard.io/docs/reference/rest-api/)
- [OpenAPI](https://demo.thingsboard.io/v3/api-docs) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://demo.thingsboard.io/swagger-ui/index.html)
- [Pricing](https://thingsboard.io/pricing/)
- [Portal](https://thingsboard.io/products/thingsboard/)
- [Portal](https://thingsboard.io/products/thingsboard-cloud/)
- [Portal](https://thingsboard.io/products/thingsboard-pe/)
- [Portal](https://thingsboard.io/products/thingsboard-edge/)
- [Portal](https://thingsboard.io/products/tbmq/)
- [Portal](https://thingsboard.io/products/trendz/)
- [Portal](https://thingsboard.io/products/iot-gateway/)
- [Blog](https://thingsboard.io/blog/)
- [Release Policy](https://thingsboard.io/docs/releases/release-policy/)
- [Changelog](https://thingsboard.io/docs/releases/releases-table/)
- [Sign Up](https://thingsboard.cloud/signup)
- [Sandbox](https://demo.thingsboard.io/)
- [Support](https://thingsboard.io/docs/contact-us/)
- [GitHub Organization](https://github.com/thingsboard)
- [Source Code](https://github.com/thingsboard/thingsboard)
- [Tool](https://github.com/thingsboard/thingsboard-gateway)
- [Tool](https://github.com/thingsboard/thingsboard-edge)
- [Tool](https://github.com/thingsboard/tbmq)
- [SDK](https://github.com/thingsboard/thingsboard-java-client)
- [SDK](https://github.com/thingsboard/thingsboard-python-client)
- [Tool](https://github.com/thingsboard/flutter_thingsboard_app)
- [Tool](https://github.com/thingsboard/flutter_thingsboard_pe_app)
- [SDK](https://github.com/thingsboard/ngx-flowchart)
- [Tool](https://hub.docker.com/u/thingsboard)
- [Forum](https://stackoverflow.com/questions/tagged/thingsboard)
- [License](https://github.com/thingsboard/thingsboard/blob/master/LICENSE)
- [License](https://www.apache.org/licenses/LICENSE-2.0)
- [Plans](plans/thingsboard-plans-pricing.yml)
- [Rate Limits](rate-limits/thingsboard-rate-limits.yml)
- [Fin Ops](finops/thingsboard-finops.yml)
- [Vocabulary](vocabulary/thingsboard-vocabulary.yml)
- [Spectral Rules](rules/thingsboard-rules.yml)
- [JSON-LD](json-ld/thingsboard-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
