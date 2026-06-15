# Maersk (maersk-line)

A.P. Moller - Maersk is the Danish integrated container shipping and logistics company. Maersk operates one of the world's largest ocean fleets and a global network of warehouses, inland transport, customs services, and air-freight capacity through Maersk Air Cargo. The Maersk Developer Portal exposes a catalogue of APIs for Track and Trace, Ocean Booking (DCSA-aligned), Schedules, Product Offers and pricing, electronic Bills of Lading, Verified Gross Mass, Demurrage and Detention, Air Booking, VGM, and container Maintenance and Repair. Many of Maersk's APIs implement Digital Container Shipping Association (DCSA) interface standards so the same client can address multiple carriers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/maersk-line/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/maersk-line/refs/heads/main/apis.yml)

## Scope

- **Position:** Producing
- **Access:** 3rd-Party

## Tags

- Shipping
- Logistics
- Container Shipping
- Ocean Freight
- Air Freight
- Supply Chain
- DCSA
- Maritime

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Maersk Track and Trace API

Retrieve neutralized container and shipment milestones via a RESTful API. Supports lookup by container number, bill-of-lading number, or booking reference. Returns transport, equipment, and shipment events with planned and actual timestamps.

- **Human URL:** [https://developer.maersk.com/api-catalogue/Track%20and%20Trace%20Plus](https://developer.maersk.com/api-catalogue/Track%20and%20Trace%20Plus)

#### Tags

- Shipping
- Tracking
- Containers
- Ocean

#### Properties

- [Documentation](https://developer.maersk.com/api-catalogue/Track%20and%20Trace%20Plus)
- [Documentation](https://developer.maersk.com/api-catalogue/multi-carrier-track-trace)
- [OpenAPI](openapi/maersk-track-and-trace-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maersk-track-and-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-track-and-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/maersk-shipment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/maersk-tracking-shipment-example.json)

### Maersk Ocean Booking API

Create, retrieve, amend, and cancel ocean shipment bookings. DCSA Booking 2.0 compliant so the same payloads work across DCSA-aligned ocean carriers. Includes booking status webhooks for asynchronous lifecycle notifications.

- **Human URL:** [https://developer.maersk.com/api-catalogue/EDP%20Booking](https://developer.maersk.com/api-catalogue/EDP%20Booking)

#### Tags

- Shipping
- Booking
- DCSA
- Ocean

#### Properties

- [Documentation](https://developer.maersk.com/api-catalogue/EDP%20Booking)
- [Documentation](https://developer.maersk.com/api-catalogue/Booking%20Status)
- [Documentation](https://developer.maersk.com/api-catalogue/ocean-booking-status-webhook)
- [OpenAPI](openapi/maersk-ocean-booking-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maersk-ocean-booking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-ocean-booking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/maersk-booking-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/maersk-booking-request-example.json)

### Maersk Schedules API

Retrieve point-to-point sailing options and commercial service schedules for Maersk ocean routes. Returns vessel, voyage, transit time, and intermediate transshipments for a given origin, destination, and date range.

- **Human URL:** [https://developer.maersk.com/api-catalogue/Point-to-Point%20Schedules](https://developer.maersk.com/api-catalogue/Point-to-Point%20Schedules)

#### Tags

- Shipping
- Schedules
- Ocean
- DCSA

#### Properties

- [Documentation](https://developer.maersk.com/api-catalogue/Point-to-Point%20Schedules)
- [Documentation](https://developer.maersk.com/api-catalogue/ocean-commercial-schedules)
- [OpenAPI](openapi/maersk-schedules-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maersk-schedules-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-schedules-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maersk Product Offers API

Quote ocean shipping offers. Returns route and schedule, vessel and deadline details, plus full price breakdowns including base ocean freight, bunker adjustment, terminal handling, and other surcharges. Supports origin and destination port lookups and supported container catalog endpoints.

- **Human URL:** [https://api.productmanagement.maersk.com/offers/docs/endpoints/productoffers.html](https://api.productmanagement.maersk.com/offers/docs/endpoints/productoffers.html)

#### Tags

- Shipping
- Pricing
- Quotes
- Surcharges

#### Properties

- [Documentation](https://api.productmanagement.maersk.com/offers/docs/endpoints/productoffers.html)
- [Documentation](https://api.productmanagement.maersk.com/offers/docs/datamodels/productoffers.html)
- [Documentation](https://api.productmanagement.maersk.com/offers/docs/datamodels/prices.html)
- [OpenAPI](openapi/maersk-product-offers-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maersk-product-offers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-product-offers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/maersk-product-offer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/maersk-product-offer-example.json)

### Maersk Bill of Lading API

DCSA-compliant Carrier Bill of Lading (eBL) API. Retrieve, approve, and surrender electronic transport documents per the DCSA eBL 3.0 interface standard.

- **Human URL:** [https://developer.maersk.com/api-catalogue/dcsa-bill-of-lading](https://developer.maersk.com/api-catalogue/dcsa-bill-of-lading)

#### Tags

- Shipping
- eBL
- DCSA
- Documents

#### Properties

- [Documentation](https://developer.maersk.com/api-catalogue/dcsa-bill-of-lading)
- [OpenAPI](openapi/maersk-bill-of-lading-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maersk-bill-of-lading-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-bill-of-lading-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maersk Verified Gross Mass API

Submit and retrieve Verified Gross Mass declarations for export containers per SOLAS regulations. Allows shippers to electronically file container weights before vessel cut-off.

- **Human URL:** [https://developer.maersk.com/api-catalogue/VGM](https://developer.maersk.com/api-catalogue/VGM)

#### Tags

- Shipping
- VGM
- SOLAS
- Export
- Compliance

#### Properties

- [Documentation](https://developer.maersk.com/api-catalogue/VGM)
- [Documentation](https://developer.maersk.com/api-catalogue/VGM/Learn-more)
- [OpenAPI](openapi/maersk-vgm-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maersk-vgm-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-vgm-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/maersk-vgm-submission-example.json)

### Maersk Import Demurrage and Detention API

Retrieve accruing demurrage and detention charges, free-day balances, and clock status for import containers. Helps consignees and freight forwarders avoid accessorial charges by surfacing live penalty risk.

- **Human URL:** [https://developer.maersk.com/api-catalogue/Import%20Demurrage%20and%20Detention](https://developer.maersk.com/api-catalogue/Import%20Demurrage%20and%20Detention)

#### Tags

- Shipping
- Demurrage
- Detention
- Import
- Charges

#### Properties

- [Documentation](https://developer.maersk.com/api-catalogue/Import%20Demurrage%20and%20Detention)
- [OpenAPI](openapi/maersk-demurrage-detention-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maersk-demurrage-detention-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-demurrage-detention-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maersk Air Booking API

Submit air freight booking requests via Maersk Air Cargo. Supports consolidation, charter, and forwarder bookings with product tiers for General, Express, Pharma, and Perishable cargo.

- **Human URL:** [https://developer.maersk.com/api-catalogue/external-air-booking](https://developer.maersk.com/api-catalogue/external-air-booking)

#### Tags

- Shipping
- Air
- Booking
- Cargo

#### Properties

- [Documentation](https://developer.maersk.com/api-catalogue/external-air-booking)
- [OpenAPI](openapi/maersk-air-booking-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maersk-air-booking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-air-booking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maersk Container Maintenance and Repair API

Container Maintenance and Repair (M&R) API surfacing equipment-management events and repair workflow data for Maersk container assets.

- **Human URL:** [https://developer.maersk.com/api-catalogue/aems-maintenance-repair](https://developer.maersk.com/api-catalogue/aems-maintenance-repair)

#### Tags

- Shipping
- Equipment
- Containers
- Maintenance

#### Properties

- [Documentation](https://developer.maersk.com/api-catalogue/aems-maintenance-repair)
- [Postman Collection](collections/maersk-air-booking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-air-booking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/maersk-bill-of-lading-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-bill-of-lading-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/maersk-demurrage-detention-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-demurrage-detention-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/maersk-ocean-booking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-ocean-booking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/maersk-product-offers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-product-offers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/maersk-schedules-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-schedules-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/maersk-track-and-trace-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-track-and-trace-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/maersk-vgm-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maersk-vgm-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.maersk.com)
- [Documentation](https://developer.maersk.com/api-catalogue)
- [Support](https://developer.maersk.com/support/:tabName)
- [Getting Started](https://developer.maersk.com/support/getting-started-api)
- [Authentication](https://developer.maersk.com/support/authorisation)
- [F A Q](https://developer.maersk.com/support/faqs)
- [Documentation](https://www.maersk.com/digital-services/data-integrations/api)
- [Documentation](https://www.maersk.com/digital-services/data-integrations)
- [Documentation](https://www.maersk.com/digital-services/data-integrations/solutions)
- [Portal](https://www.maersk.com)
- [About](https://www.maersk.com/about)
- [Blog](https://www.maersk.com/news)
- [Blog](https://www.maersk.com/insights)
- [Documentation](https://www.maersk.com/local-information)
- [Terms of Service](https://www.maersk.com/terms)
- [Privacy Policy](https://www.maersk.com/privacy-policy)
- [Documentation](https://www.maersk.com/career)
- [LinkedIn](https://www.linkedin.com/company/maersk-group)
- [X (Twitter)](https://twitter.com/Maersk)
- [YouTube](https://www.youtube.com/user/MAERSK)
- [GitHub Organization](https://github.com/Maersk-Global)
- [GitHub Organization](https://github.com/MaerskTech)
- [Standard](https://dcsa.org)
- [Specification](https://github.com/dcsaorg/DCSA-OpenAPI)
- [Spectral Rules](rules/maersk-rules.yml)
- [Vocabulary](vocabulary/maersk-line-vocabulary.yml)
- [JSON-LD](json-ld/maersk-line-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Plans](plans/maersk-line-plans-pricing.yml)
- [Rate Limits](rate-limits/maersk-line-rate-limits.yml)
- [Fin Ops](finops/maersk-line-finops.yml)
- [Authentication](https://developer.maersk.com/support/authorisation)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
