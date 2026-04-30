# Debbie Collect (debbie-collect)

Debbie (Debbie Collect, operated by Intellitech Systems A/S) is an AI-driven SaaS platform that automates debt collection and accounts receivable management. Companies, collection agencies, and law firms use Debbie to run digital reminder flows, debtor dialogue, payment plans, and case management.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/debbie-collect/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party
- **x-type:** company

## Tags

- Accounts Receivable, Collections, Debt Collection, FinTech, Payments, SaaS

## Timestamps

- **Created:** 2025-02-24
- **Modified:** 2026-04-28

## APIs

### Debbie Platform API

The Debbie Platform API exposes resources for cases, creditors, customers, vouchers, files, updates, billing, and webhooks. It is used by collection agencies and other operators integrating Debbie into their core systems.

- **Base URL:** https://api.debbie.dk
- **Human URL:** https://documentation.debbiecollect.com

#### Properties

- [Documentation](https://documentation.debbiecollect.com)
- [OpenAPI](openapi/debbie-platform-api-openapi.yml)
- [JSONSchema - Case](json-schema/debbie-case.json)
- [JSONSchema - Customer](json-schema/debbie-customer.json)
- [Rules](rules/debbie-platform-api-rules.yml)
- [Capabilities](capabilities/debbie-platform-api-capabilities.yml)

### Debbie Client API

The Debbie Client API allows creditors to create collection cases, exchange payment data, and receive case status updates. It is the primary integration surface for ERP/billing systems pushing overdue invoices into Debbie.

- **Base URL:** https://creditor.debbie.dk/api
- **Human URL:** https://creditor-docs.debbie.dk

#### Properties

- [Documentation](https://creditor-docs.debbie.dk)
- [OpenAPI](openapi/debbie-client-api-openapi.yml)

## Common Properties

- [Website](https://debbiecollect.com/)
- [API Documentation](https://debbiecollect.com/api-documentation)
- [Status](https://debbie.freshstatus.io)
- [JSON-LD](json-ld/debbie-context.jsonld)
- [Vocabulary](vocabulary/debbie-vocabulary.yml)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
