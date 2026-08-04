# Urban Outfitters (urban-outfitters)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Urban Outfitters is a multi-channel lifestyle retailer offering an eclectic mix of women's, men's, and kids apparel, footwear, accessories, beauty, and home goods. Part of URBN, Inc. (which also owns Anthropologie, Free People, Bhldn, and Nuuly), Urban Outfitters operates stores in the US, Europe, and Canada alongside a robust ecommerce platform. The brand provides affiliate marketing integration through the Rakuten Advertising network and a third-party seller marketplace program (UO MRKT) that accepts independent brands selling through EDI and third-party integration platforms. Urban Outfitters uses Stripe for payment processing, Stripe Connect for marketplace seller payouts, and Stripe Terminal for in-store payments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/urban-outfitters/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/urban-outfitters/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Retail
- Fashion
- Apparel
- Ecommerce
- Affiliate
- Marketplace

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-19

## APIs

### Urban Outfitters Affiliate Program

Urban Outfitters affiliate program managed through Rakuten Advertising (formerly LinkShare) network. Provides affiliate tracking links, banner ads, marketing copy, and product data feeds for affiliates to promote Urban Outfitters products. Commission rates are approximately 2% per confirmed sale, with a 30-day cookie window and monthly payouts.

- **Human URL:** [https://www.urbanoutfitters.com/help/affiliate](https://www.urbanoutfitters.com/help/affiliate)
- **Base URL:** `https://api.rakutenadvertising.com`

#### Tags

- Affiliate
- Marketing
- Product Feed
- Tracking

#### Properties

- [Documentation](https://www.urbanoutfitters.com/help/affiliate)
- [OpenAPI](openapi/urban-outfitters-affiliate-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/urban-outfitters-affiliate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/urban-outfitters-affiliate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/affiliate-api-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/affiliate-api-affiliate-link-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/affiliate-api-commission-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/affiliate-api-creative-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Urban Outfitters Marketplace (UO MRKT) Integration

Urban Outfitters operates a curated third-party marketplace called UO MRKT for independent lifestyle and fashion brands. Seller integration is managed through EDI and third-party connectors such as ConnectPointz, SellerCloud, and e-tailize. Provides product catalog sync, inventory management, order routing, and shipment tracking for approved sellers.

- **Human URL:** [https://www.urbanoutfitters.com/mrkt-seller-form](https://www.urbanoutfitters.com/mrkt-seller-form)
- **Base URL:** `https://www.urbanoutfitters.com`

#### Tags

- Marketplace
- Sellers
- EDI
- Inventory
- Orders

#### Properties

- [Documentation](https://www.urbanoutfitters.com/mrkt-seller-form)
- [OpenAPI](openapi/urban-outfitters-marketplace-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/urban-outfitters-marketplace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/urban-outfitters-marketplace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/marketplace-api-seller-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/marketplace-api-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/marketplace-api-shipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/marketplace-api-inventory-update-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/urban-outfitters)
- [Website](https://www.urban-outfitters.com)
- [Website](https://www.urbanoutfitters.com)
- [Portal](https://www.urbanoutfitters.com/help/affiliate)
- [GitHub Organization](https://github.com/urbn)
- [JSON-LD](json-ld/urban-outfitters-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/urban-outfitters-spectral-rules.yml)
- [Vocabulary](vocabulary/urban-outfitters-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
