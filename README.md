# Maersk (maersk-line)

A.P. Moller - Maersk is the Danish integrated container shipping and logistics company. Maersk operates one of the world's largest ocean fleets and a global network of warehouses, inland transport, customs services, and air-freight capacity through Maersk Air Cargo. The Maersk Developer Portal exposes a catalogue of APIs for Track and Trace, Ocean Booking (DCSA-aligned), Schedules, Product Offers and pricing, electronic Bills of Lading, Verified Gross Mass, Demurrage and Detention, Air Booking, and container Maintenance and Repair. Many of Maersk's APIs implement Digital Container Shipping Association (DCSA) interface standards so the same client can address multiple carriers.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/maersk-line/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Shipping, Logistics, Container Shipping, Ocean Freight, Air Freight, Supply Chain, DCSA, Maritime

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

| API | Description |
|---|---|
| Maersk Track and Trace API | Public ocean tracking with neutralized container and shipment milestones. |
| Maersk Ocean Booking API | DCSA Booking 2.0 — create, retrieve, amend, cancel. |
| Maersk Schedules API | Point-to-point and DCSA commercial service schedules. |
| Maersk Product Offers API | Quote ocean rates with full surcharge breakdown. |
| Maersk Bill of Lading API | DCSA eBL 3.0 transport documents. |
| Maersk Verified Gross Mass API | SOLAS VGM declarations for export containers. |
| Maersk Import Demurrage and Detention API | Accruing D&D charges and free-day clocks. |
| Maersk Air Booking API | Air freight bookings via Maersk Air Cargo. |
| Maersk Container Maintenance and Repair API | Equipment-management and M&R workflow data. |

## Authentication

Maersk APIs use a layered scheme: a per-app **Consumer-Key** header for application identity plus an **OAuth 2.0 client_credentials** access token for runtime authorization. See [Authorisation](https://developer.maersk.com/support/authorisation).

## Standards Alignment

Maersk is a founding member of the [Digital Container Shipping Association (DCSA)](https://dcsa.org). Booking, Schedules, eBL, and Track and Trace APIs implement DCSA interface standards. Canonical DCSA OpenAPI files are published at [dcsaorg/DCSA-OpenAPI](https://github.com/dcsaorg/DCSA-OpenAPI).

## Generated Artifacts

| Artifact | Path |
|---|---|
| OpenAPI specs (9) | `openapi/` |
| JSON Schema (3) | `json-schema/` |
| JSON-LD context | `json-ld/maersk-line-context.jsonld` |
| Examples (4) | `examples/` |
| Spectral ruleset | `rules/maersk-rules.yml` |
| Vocabulary | `vocabulary/maersk-line-vocabulary.yml` |
| Naftiko capabilities (8) | `capabilities/` |
| API Commons Plans | `plans/maersk-line-plans-pricing.yml` |
| API Commons Rate Limits | `rate-limits/maersk-line-rate-limits.yml` |
| FinOps (FOCUS) | `finops/maersk-line-finops.yml` |

## Developer Resources

- [Developer Portal](https://developer.maersk.com)
- [API Catalogue](https://developer.maersk.com/api-catalogue)
- [Getting Started](https://developer.maersk.com/support/getting-started-api)
- [Developer FAQs](https://developer.maersk.com/support/faqs)
- [API Solutions Overview](https://www.maersk.com/digital-services/data-integrations/api)

## Maintainer

- [Kin Lane](https://apievangelist.com) — info@apievangelist.com
