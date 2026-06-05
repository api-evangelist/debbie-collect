# Debbie Collect (debbie-collect)

Debbie (Debbie Collect, operated by Intellitech Systems A/S) is an AI-driven SaaS platform that automates debt collection and accounts receivable management. Companies, collection agencies, and law firms use Debbie to run digital reminder flows, debtor dialogue, payment plans, and case management. Debbie publishes two RESTful APIs - a Platform API for collectors integrating Debbie into existing systems, and a Client API for creditors creating cases and exchanging payment data.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/debbie-collect/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/debbie-collect/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Accounts Receivable
- Collections
- Debt Collection
- FinTech
- Payments
- SaaS

## Timestamps

- **Created:** 2025-02-24
- **Modified:** 2026-05-19

## APIs

### Debbie Platform API

The Debbie Platform API exposes resources for cases, creditors, customers, vouchers, files, updates, billing, and webhooks. It is used by collection agencies and other operators integrating Debbie into their core systems.

- **Human URL:** [https://documentation.debbiecollect.com](https://documentation.debbiecollect.com)
- **Base URL:** `https://api.debbie.dk`

#### Tags

- Cases
- Collections
- Creditors
- Customers
- Webhooks

#### Properties

- [Documentation](https://documentation.debbiecollect.com)
- [OpenAPI](openapi/debbie-platform-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/debbie-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/debbie-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/debbie-case.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/debbie-customer.json) — [JSON Schema](https://json-schema.org/specification)
- [Rules](rules/debbie-platform-api-rules.yml)
- [Capabilities](capabilities/debbie-platform-api-capabilities.yml)

### Debbie Client API

The Debbie Client API allows creditors to create collection cases, exchange payment data, and receive case status updates. It is the primary integration surface for ERP/billing systems pushing overdue invoices into Debbie.

- **Human URL:** [https://creditor-docs.debbie.dk](https://creditor-docs.debbie.dk)
- **Base URL:** `https://creditor.debbie.dk/api`

#### Tags

- Cases
- Creditor
- Payments

#### Properties

- [Documentation](https://creditor-docs.debbie.dk)
- [OpenAPI](openapi/debbie-client-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/debbie-client-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/debbie-client-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/debbie-rewards)
- [Website](https://debbiecollect.com/)
- [A P I  Documentation](https://debbiecollect.com/api-documentation)
- [Status Page](https://debbie.freshstatus.io)
- [Security &  Compliance](https://debbiecollect.com/security-compliance-2)
- [Blog](https://debbiecollect.com/blog)
- [Support](mailto:api-support@debbie.dk)
- [JSON-LD](json-ld/debbie-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/debbie-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
