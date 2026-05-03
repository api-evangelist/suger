# Suger

Suger is the fastest and easiest way for ISVs to list, transact, and co-sell on cloud marketplaces including AWS Marketplace, Azure Marketplace, GCP Marketplace, and Snowflake Marketplace. Suger provides a full REST API for managing products, offers, entitlements, buyers, usage metering, and revenue reporting.

## Links

- [Website](https://www.suger.io/)
- [Documentation](https://doc.suger.io/)
- [API Client Getting Started](https://www.suger.io/docs/get-started/api-client)
- [GitHub SDKs](https://github.com/sugerio)
- [Pricing](https://www.suger.io/pricing)

## APIs

### Suger API

Full CRUD API for cloud marketplace management. Base URL: `https://api.suger.cloud`

Authentication: API Key in `Authorization` header

**82 endpoints across 11 resource groups:**
- **Products** — Create and manage marketplace product listings
- **Offers** — Configure pricing and terms for buyers
- **Entitlements** — Manage customer subscription lifecycle
- **Buyers** — Customer and buyer management
- **Usage Metering** — Report and validate usage for billing
- **Billing** — Addons, invoices, payment transactions, wallets
- **Revenue** — Revenue records and daily revenue reporting
- **Contacts** — CRM contacts linked to buyers and offers
- **Notifications** — Notification events and messages
- **Support** — Support ticket management
- **API Clients** — API credential management

## Artifacts

### OpenAPI

- [suger-openapi.yml](openapi/suger-openapi.yml) — Complete OpenAPI 3.0 specification for the Suger API

### Spectral Rules

- [suger-rules.yml](rules/suger-rules.yml) — Spectral ruleset enforcing Suger API conventions

### Capabilities

- [marketplace-management.yaml](capabilities/marketplace-management.yaml) — Unified workflow capability for cloud marketplace management
- [shared/suger.yaml](capabilities/shared/suger.yaml) — Per-API shared capability definition

### JSON Schema

- [suger-product-schema.json](json-schema/suger-product-schema.json) — JSON Schema for marketplace product resources
- [suger-entitlement-schema.json](json-schema/suger-entitlement-schema.json) — JSON Schema for customer entitlements

### JSON Structure

- [suger-product-structure.json](json-structure/suger-product-structure.json) — Documented field structure for product resources

### JSON-LD

- [suger-context.jsonld](json-ld/suger-context.jsonld) — JSON-LD context mapping Suger vocabulary to schema.org

### Examples

- [suger-list-products-example.json](examples/suger-list-products-example.json) — Example list products request/response
- [suger-create-entitlement-example.json](examples/suger-create-entitlement-example.json) — Example create entitlement request/response

### Vocabulary

- [suger-vocabulary.yml](vocabulary/suger-vocabulary.yml) — Domain vocabulary for cloud marketplace and GTM concepts

## Maintainers

- **Kin Lane** — kin@apievangelist.com
