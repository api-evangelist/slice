# Slice (slice)

Slice is an online ordering and management platform built specifically for independent local pizzerias, giving small shops digital ordering, marketing, loyalty, and back-office tools that compete with large delivery marketplaces at a low flat per-order fee. For technology partners, Slice publishes a Slice Public API documented on a Stoplight developer portal, exposing pizzeria-oriented resources such as shops and orders over a RESTful HTTP interface in two versions (v1 and v2). The platform serves pizzeria owners and the partners that integrate ordering, POS, and operations into the Slice network across thousands of locations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/slice/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/slice/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Restaurant
- Pizza
- Online Ordering
- Local Commerce
- Menus
- Orders

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-03

## APIs

### Slice Public API (v1)

Version 1 of the Slice Public API: a RESTful HTTP API documented on Slice's Stoplight developer portal (project slice-public-api, spec node /API-V1.yaml). It provides programmatic access to pizzeria-focused resources in the Slice network — shops and orders — for technology partners integrating ordering and operations with local pizzerias. Paths, methods, operation summaries, and component-schema names were confirmed from Slice's live Stoplight project node tree; schema property internals are auth-gated and not enumerated.

- **Human URL:** [https://developer.slicelife.com/](https://developer.slicelife.com/)

#### Tags

- Online Ordering
- Shops
- Orders
- Pizzerias
- REST

#### Properties

- [Documentation](https://developer.slicelife.com/)
- [OpenAPI](openapi/slice-public-api-v1-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slice-public-api-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slice-public-api-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.slicelife.com/)
- [JSON-LD](json-ld/slice-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Slice Public API (v2)

Version 2 of the Slice Public API on Slice's Stoplight developer portal (spec node /API-V2.yaml). It exposes the same shops and orders surface as v1 — GET /shops plus create/get/update/delete on /orders — confirmed from the live Stoplight project node tree.

- **Human URL:** [https://developer.slicelife.com/](https://developer.slicelife.com/)

#### Tags

- Online Ordering
- Shops
- Orders
- Pizzerias
- REST

#### Properties

- [Documentation](https://developer.slicelife.com/)
- [OpenAPI](openapi/slice-public-api-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/slice-public-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/slice-public-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.slicelife.com/)
- [JSON-LD](json-ld/slice-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [Website](https://slicelife.com/)
- [Documentation](https://developer.slicelife.com/)
- [Getting Started](https://developer.slicelife.com/docs/Getting-started.md)
- [Pricing](https://slice.com/pricing/)
- [Support](https://slicelife.com/pages/support)
- [Contact](mailto:api-support@slicelife.com)
- [GitHub Organization](https://github.com/slicelife)
- [Plans](plans/slice-plans-pricing.yml)
- [Rate Limits](rate-limits/slice-rate-limits.yml)
- [Fin Ops](finops/slice-finops.yml)
- [Vocabulary](vocabulary/slice-vocabulary.yml)
- [Spectral Rules](rules/slice-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
