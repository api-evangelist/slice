# Slice (slice)

Slice is an online ordering and management platform built specifically for independent local pizzerias, giving small shops digital ordering, marketing, loyalty, and back-office tools that compete with large delivery marketplaces at a low flat per-order fee. For technology partners, Slice publishes a Slice Public API documented on a Stoplight developer portal, exposing pizzeria-oriented resources such as shops and orders over a RESTful HTTP interface in two versions (v1 and v2). The platform serves pizzeria owners and the partners that integrate ordering, POS, and operations into the Slice network across thousands of locations.

**URL:** [Visit APIs.json URL](https://developer.slicelife.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, Pizza, Online Ordering, Local Commerce, Menus, Orders

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-03

## APIs

### Slice Public API (v1)

Version 1 of the Slice Public API: a RESTful HTTP API documented on Slice's Stoplight developer portal (project slice-public-api, spec node /API-V1.yaml). It provides programmatic access to pizzeria-focused resources in the Slice network — shops and orders — for technology partners integrating ordering and operations with local pizzerias. Paths, methods, operation summaries, and component-schema names were confirmed from Slice's live Stoplight project node tree; schema property internals are auth-gated and not enumerated.

**Human URL:** [https://developer.slicelife.com/](https://developer.slicelife.com/)

#### Tags:

 - Online Ordering, Shops, Orders, Pizzerias, REST

#### Properties

- [Documentation](https://developer.slicelife.com/)
- [OpenAPI](openapi/slice-public-api-v1-openapi.yml)
- [API Key (partner-issued)](https://developer.slicelife.com/)
- [Naftiko Capability — Shops](capabilities/slice-public-api-v1-shops.yaml)
- [Naftiko Capability — Orders](capabilities/slice-public-api-v1-orders.yaml)
- [JSON-LD](json-ld/slice-context.jsonld)

### Slice Public API (v2)

Version 2 of the Slice Public API on Slice's Stoplight developer portal (spec node /API-V2.yaml). It exposes the same shops and orders surface as v1 — GET /shops plus create/get/update/delete on /orders — confirmed from the live Stoplight project node tree.

**Human URL:** [https://developer.slicelife.com/](https://developer.slicelife.com/)

#### Tags:

 - Online Ordering, Shops, Orders, Pizzerias, REST

#### Properties

- [Documentation](https://developer.slicelife.com/)
- [OpenAPI](openapi/slice-public-api-v2-openapi.yml)
- [API Key (partner-issued)](https://developer.slicelife.com/)
- [Naftiko Capability — Shops](capabilities/slice-public-api-v2-shops.yaml)
- [Naftiko Capability — Orders](capabilities/slice-public-api-v2-orders.yaml)
- [JSON-LD](json-ld/slice-context.jsonld)

## Common Properties

- [Website](https://slicelife.com/)
- [Documentation](https://developer.slicelife.com/)
- [GettingStarted](https://developer.slicelife.com/docs/Getting-started.md)
- [Pricing](https://slice.com/pricing/)
- [Support](https://slicelife.com/pages/support)
- [API Support](mailto:api-support@slicelife.com)
- [GitHubOrganization](https://github.com/slicelife)
- [Plans](plans/slice-plans-pricing.yml)
- [RateLimits](rate-limits/slice-rate-limits.yml)
- [FinOps](finops/slice-finops.yml)
- [Vocabulary](vocabulary/slice-vocabulary.yml)
- [SpectralRules](rules/slice-rules.yml)

## Features

| Name | Description |
|------|-------------|
| Shop Discovery | Retrieve pizzerias (shops) available in the Slice network via GET /shops. |
| Order Lifecycle | Create, retrieve, update, and cancel orders against a Slice shop via the /orders resource. |
| Two API Versions | Both v1 and v2 of the Slice Public API are published, sharing the same shops-and-orders surface. |
| Partner API Key Authentication | Programmatic access is gated to approved technology partners via an API key issued by Slice. |
| Stoplight Developer Portal | API documentation, onboarding, and reference are hosted on developer.slicelife.com (Stoplight). |

## Use Cases

| Name | Description |
|------|-------------|
| Partner Order Integration | Technology partners place and manage orders against Slice pizzerias programmatically. |
| POS and Operations Sync | Integrate point-of-sale and operations systems with the Slice network of independent pizzerias. |
| Shop Catalog Sync | Pull the set of Slice shops to power partner-side discovery and routing. |

## Integrations

| Name | Description |
|------|-------------|
| Point-of-Sale Systems | Connect pizzeria POS systems to the Slice ordering and operations surface. |
| Ordering and Marketplace Partners | Technology partners that integrate ordering into the Slice network of local pizzerias. |

## Solutions

| Name | Description |
|------|-------------|
| Independent Pizzerias | Digital ordering, marketing, loyalty, and back-office tooling at a low flat per-order fee. |
| Technology Partners | Programmatic shops-and-orders access to the Slice network via the partner-issued Public API. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Slice Public API (v1)](openapi/slice-public-api-v1-openapi.yml)
- [Slice Public API (v2)](openapi/slice-public-api-v2-openapi.yml)

### JSON-LD

- [Slice Context](json-ld/slice-context.jsonld)

## Capabilities

Self-contained Naftiko capabilities, one per business surface (OpenAPI tag), each with inline REST and MCP exposers.

| Capability | API | Operations | Tools |
|------------|-----|------------|-------|
| [Shops (v1)](capabilities/slice-public-api-v1-shops.yaml) | Slice Public API (v1) | 1 | 1 |
| [Orders (v1)](capabilities/slice-public-api-v1-orders.yaml) | Slice Public API (v1) | 4 | 4 |
| [Shops (v2)](capabilities/slice-public-api-v2-shops.yaml) | Slice Public API (v2) | 1 | 1 |
| [Orders (v2)](capabilities/slice-public-api-v2-orders.yaml) | Slice Public API (v2) | 4 | 4 |

## Vocabulary

- [Slice Vocabulary](vocabulary/slice-vocabulary.yml) — Unified taxonomy mapping 2 APIs, 4 resources, and 5 actions across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [Slice Spectral Ruleset](rules/slice-rules.yml) — 14 rules enforcing Slice API conventions (info/metadata, OpenAPI version, security, path naming, operations, and Title Case tags).

## Commercial

- [Plans (API Commons Plans 0.1)](plans/slice-plans-pricing.yml) — Slice Essentials ($2.99/order) and Slice Premium ($2.50/order) flat per-order tiers; partner-gated API access.
- [Rate Limits (API Commons Rate Limits 0.1)](rate-limits/slice-rate-limits.yml) — Per-key limits not publicly published; partner-agreement governed.
- [FinOps (FOCUS-aligned)](finops/slice-finops.yml) — Flat per-order billing model with the order as the billable unit.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
