# Tremendous

Tremendous allows businesses to send rewards, incentives, and payouts worldwide using their simple API and dashboard. Access 2000+ payout methods including gift cards, prepaid Visa/Mastercard, PayPal, Venmo, bank transfers, and charity donations.

**Website:** [https://www.tremendous.com](https://www.tremendous.com)  
**API Docs:** [https://developers.tremendous.com](https://developers.tremendous.com)  
**Sandbox:** [https://testflight.tremendous.com](https://testflight.tremendous.com)

## APIs

### Tremendous API

The Tremendous REST API enables programmatic sending of rewards, incentives, and payouts worldwide. Covers orders, rewards, products, campaigns, funding sources, organizations, members, invoices, and webhooks. Rate limit: 30 requests per 30 seconds.

- **Sandbox URL:** `https://testflight.tremendous.com/api/v2`
- **Production URL:** `https://www.tremendous.com/api/v2`
- **Authentication:** Bearer API Key or OAuth 2.0
- **OpenAPI:** [openapi/tremendous-api-openapi.yml](openapi/tremendous-api-openapi.yml)

## Artifacts

| Type | File |
|---|---|
| OpenAPI | [openapi/tremendous-api-openapi.yml](openapi/tremendous-api-openapi.yml) |
| JSON Schema (Order) | [json-schema/tremendous-order-schema.json](json-schema/tremendous-order-schema.json) |
| JSON Schema (Product) | [json-schema/tremendous-product-schema.json](json-schema/tremendous-product-schema.json) |
| JSON Structure (Order) | [json-structure/tremendous-order-structure.json](json-structure/tremendous-order-structure.json) |
| JSON-LD Context | [json-ld/tremendous-context.jsonld](json-ld/tremendous-context.jsonld) |
| Spectral Rules | [rules/tremendous-spectral-rules.yml](rules/tremendous-spectral-rules.yml) |
| Vocabulary | [vocabulary/tremendous-vocabulary.yml](vocabulary/tremendous-vocabulary.yml) |

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/tremendous-api.yaml](capabilities/shared/tremendous-api.yaml) | Full Tremendous API consumed definition (orders, rewards, products, campaigns, funding sources) |

### Workflow Capabilities

| File | Description |
|---|---|
| [capabilities/rewards-and-payouts.yaml](capabilities/rewards-and-payouts.yaml) | Unified rewards and payouts capability (send incentives, track delivery, manage campaigns) |

## Examples

- [examples/tremendous-create-order-example.json](examples/tremendous-create-order-example.json)

## Common Properties

- [Website](https://www.tremendous.com/)
- [Documentation](https://developers.tremendous.com/)
- [Sign Up](https://app.tremendous.com/auth/sign_up)
- [Sandbox](https://testflight.tremendous.com)
- [GitHub Organization](https://github.com/tremendous-rewards)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com

## Tags

Employee Incentives, Global Payouts, Incentives, Market Research, Payouts, Rewards
