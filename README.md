# Slice (slice)

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
