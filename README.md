# Urban Outfitters (urban-outfitters)
Urban Outfitters is a multi-channel lifestyle retailer offering an eclectic mix of women's, men's, and kids apparel, footwear, accessories, beauty, and home goods. Part of URBN, Inc. (which also owns Anthropologie, Free People, Bhldn, and Nuuly), Urban Outfitters operates stores in the US, Europe, and Canada alongside a robust ecommerce platform. The brand provides affiliate marketing integration through the Rakuten Advertising network and a third-party seller marketplace program (UO MRKT) that accepts independent brands selling through EDI and third-party integration platforms. Urban Outfitters uses Stripe for payment processing, Stripe Connect for marketplace seller payouts, and Stripe Terminal for in-store payments.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/urban-outfitters/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Retail, Fashion, Apparel, Ecommerce, Affiliate, Marketplace

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-03

## APIs

### Urban Outfitters Affiliate Program
Urban Outfitters affiliate program managed through Rakuten Advertising (formerly LinkShare) network. Provides affiliate tracking links, banner ads, marketing copy, and product data feeds for affiliates to promote Urban Outfitters products. Commission rates are approximately 2% per confirmed sale, with a 30-day cookie window and monthly payouts.

**Human URL:** [https://www.urbanoutfitters.com/help/affiliate](https://www.urbanoutfitters.com/help/affiliate)

#### Tags:

 - Affiliate, Marketing, Product Feed, Tracking

#### Properties

- [Documentation](https://www.urbanoutfitters.com/help/affiliate)
- [OpenAPI](openapi/urban-outfitters-affiliate-api-openapi.yml)
- [JSONSchema - Product](json-schema/affiliate-api-product-schema.json)
- [JSONSchema - Affiliate Link](json-schema/affiliate-api-affiliate-link-schema.json)
- [JSONSchema - Commission Report](json-schema/affiliate-api-commission-report-schema.json)
- [JSONSchema - Creative](json-schema/affiliate-api-creative-schema.json)

### Urban Outfitters Marketplace (UO MRKT) Integration
Urban Outfitters operates a curated third-party marketplace called UO MRKT for independent lifestyle and fashion brands. Seller integration is managed through EDI and third-party connectors such as ConnectPointz, SellerCloud, and e-tailize. Provides product catalog sync, inventory management, order routing, and shipment tracking for approved sellers.

**Human URL:** [https://www.urbanoutfitters.com/mrkt-seller-form](https://www.urbanoutfitters.com/mrkt-seller-form)

#### Tags:

 - Marketplace, Sellers, EDI, Inventory, Orders

#### Properties

- [Documentation](https://www.urbanoutfitters.com/mrkt-seller-form)
- [OpenAPI](openapi/urban-outfitters-marketplace-api-openapi.yml)
- [JSONSchema - Seller Product](json-schema/marketplace-api-seller-product-schema.json)
- [JSONSchema - Order](json-schema/marketplace-api-order-schema.json)
- [JSONSchema - Shipment](json-schema/marketplace-api-shipment-schema.json)
- [JSONSchema - Inventory Update](json-schema/marketplace-api-inventory-update-schema.json)

## Common Properties

- [Website](https://www.urban-outfitters.com)
- [Website](https://www.urbanoutfitters.com)
- [Portal](https://www.urbanoutfitters.com/help/affiliate)
- [GitHubOrganization](https://github.com/urbn)
- [JSONLD](json-ld/urban-outfitters-context.jsonld)
- [SpectralRules](rules/urban-outfitters-spectral-rules.yml)
- [Vocabulary](vocabulary/urban-outfitters-vocabulary.yaml)
- [NaftikoCapability - Retail Commerce](capabilities/retail-commerce.yaml)
- [NaftikoCapability - Affiliate API (Shared)](capabilities/shared/affiliate-api.yaml)
- [NaftikoCapability - Marketplace API (Shared)](capabilities/shared/marketplace-api.yaml)

## Features

| Name | Description |
|------|-------------|
| Affiliate Product Data Feeds | Product catalog data feeds for affiliate partners to display and link Urban Outfitters products. |
| Affiliate Tracking Links | Unique tracking links and banner ads through Rakuten Advertising for commission tracking. |
| Marketplace Seller Integration | EDI and API-based integration for third-party brands selling through the UO MRKT marketplace. |
| Inventory Sync | Real-time inventory synchronization between seller systems and Urban Outfitters marketplace. |
| Order Routing | Automated order routing and fulfillment management for marketplace sellers. |
| Stripe Payments | Stripe-powered payment processing for both online checkout and in-store POS via Stripe Terminal. |
| Stripe Connect Payouts | Automated marketplace seller payouts through Stripe Connect. |

## Use Cases

| Name | Description |
|------|-------------|
| Content Creator Monetization | Bloggers, influencers, and content creators earning commissions by promoting Urban Outfitters products. |
| Comparison Shopping | Price comparison and product discovery platforms integrating Urban Outfitters product catalog. |
| Independent Brand Sales | Independent fashion and lifestyle brands expanding distribution through Urban Outfitters marketplace. |
| Inventory Management | Sellers using EDI or integration platforms to sync inventory and orders with Urban Outfitters. |

## Integrations

| Name | Description |
|------|-------------|
| Rakuten Advertising | Affiliate network platform managing Urban Outfitters affiliate program tracking and payouts. |
| ConnectPointz EDI | EDI integration platform for Urban Outfitters marketplace seller connectivity. |
| SellerCloud | Multi-channel inventory management platform with Urban Outfitters marketplace connector. |
| e-tailize | European multi-channel selling platform with Urban Outfitters marketplace integration. |
| Stripe | Payment processing and marketplace payout infrastructure powering all URBN brands. |
| Skimlinks | Alternative affiliate network offering higher commission rates for Urban Outfitters. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Urban Outfitters Affiliate API](openapi/urban-outfitters-affiliate-api-openapi.yml)
- [Urban Outfitters Marketplace API](openapi/urban-outfitters-marketplace-api-openapi.yml)

### JSON Schema

- [Product](json-schema/affiliate-api-product-schema.json)
- [Affiliate Link](json-schema/affiliate-api-affiliate-link-schema.json)
- [Commission Report](json-schema/affiliate-api-commission-report-schema.json)
- [Creative](json-schema/affiliate-api-creative-schema.json)
- [Seller Product](json-schema/marketplace-api-seller-product-schema.json)
- [Order](json-schema/marketplace-api-order-schema.json)
- [Shipment](json-schema/marketplace-api-shipment-schema.json)
- [Inventory Update](json-schema/marketplace-api-inventory-update-schema.json)
- *(18 total schema files in json-schema/)*

### JSON Structure

- *(18 total structure files in json-structure/)*

### JSON-LD

- [Urban Outfitters Context](json-ld/urban-outfitters-context.jsonld)

### Examples

- [Product Example](examples/affiliate-api-product-example.json)
- [Affiliate Link Example](examples/affiliate-api-affiliate-link-example.json)
- [Commission Report Example](examples/affiliate-api-commission-report-example.json)
- [Seller Product Example](examples/marketplace-api-seller-product-example.json)
- [Order Example](examples/marketplace-api-order-example.json)
- *(18 total example files in examples/)*

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Affiliate API](capabilities/shared/affiliate-api.yaml) — 5 operations for product search, affiliate link generation, commission reporting, and creatives
- [Marketplace API](capabilities/shared/marketplace-api.yaml) — 5 operations for product listing, inventory sync, order management, and shipment tracking

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Retail Commerce](capabilities/retail-commerce.yaml) | Affiliate API, Marketplace API | 10 | Affiliate Partner, Marketplace Seller, Developer |

## Vocabulary

- [Urban Outfitters Vocabulary](vocabulary/urban-outfitters-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 6 actions, 1 workflow, and 3 personas across operational and capability dimensions

## Rules

- [Urban Outfitters Spectral Rules](rules/urban-outfitters-spectral-rules.yml) — Rules across multiple categories enforcing Urban Outfitters API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
