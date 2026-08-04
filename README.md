# S&P Global (sandp-global)

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

S&P Global is a leading provider of credit ratings, benchmarks, analytics, and workflow solutions in the global capital, commodity, and automotive markets. S&P Global offers multiple API product lines across its business divisions: the Capital IQ API provides comprehensive financial and market intelligence data; the Commodity Insights API provides price assessments, market data, and analytics for energy and commodities markets; and the Marketplace API enables programmatic access to the S&P Global data marketplace catalog.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Financial Data
- Market Intelligence
- Commodity Insights
- Credit Ratings
- Analytics
- Fortune 500
- Enterprise

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### S&P Capital IQ API

The S&P Capital IQ API provides programmatic access to one of the industry's most comprehensive sets of global financial data, including fundamental financials, industry-specific data, valuations and pricing, S&P Global Credit Ratings and Research, capital structure data, and reference data. The API uses REST with JSON responses and Bearer token authentication. The primary endpoint is https://api-ciq.marketintelligence.spglobal.com/gdsapi/rest/v3/clientservice.json.

- **Human URL:** [https://www.marketplace.spglobal.com/en/solutions/api-solutions-(61953ac7-ea64-4fac-826a-feb7f846c2be)](https://www.marketplace.spglobal.com/en/solutions/api-solutions-(61953ac7-ea64-4fac-826a-feb7f846c2be))

#### Tags

- Financial Data
- Fundamentals
- Credit Ratings
- Market Intelligence
- REST

#### Properties

- [Documentation](https://www.marketplace.spglobal.com/en/solutions/api-solutions-(61953ac7-ea64-4fac-826a-feb7f846c2be))
- [Developer  Guide](https://www.support.marketplace.spglobal.com/content/dam/spglobal/mi/en/documents/marketplace/api/guides/spglobalapidevelopersguide.pdf)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/openapi/sandp-global-capital-iq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sandp-global-financial-data-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sandp-global-capital-iq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sandp-global-capital-iq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sandp-global-commodity-insights.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sandp-global-commodity-insights.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### S&P Global Commodity Insights API

The S&P Global Commodity Insights API (formerly Platts API) provides HTTP-based RESTful access to commodity price assessments, market data, and analytics across energy, metals, agriculture, and petrochemicals markets. Authentication uses Bearer token generated via the Token Generation API endpoint at https://developer.spglobal.com. The base domain for API requests is https://api.platts.com.

- **Human URL:** [https://developer.spglobal.com/commodityinsights/](https://developer.spglobal.com/commodityinsights/)

#### Tags

- Commodity Data
- Energy
- Metals
- Platts
- Price Assessments
- REST

#### Properties

- [Documentation](https://developer.spglobal.com/commodityinsights/api/getting-started)
- [Developer  Portal](https://developer.spglobal.com)
- [Service  Catalog](https://developer.spglobal.com/commodityinsights/servicecatalog)
- [Authentication](https://developer.spglobal.com/Token_Generation_API.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/openapi/sandp-global-commodity-insights-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sandp-global-price-assessment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sandp-global-capital-iq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sandp-global-capital-iq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sandp-global-commodity-insights.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sandp-global-commodity-insights.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### S&P Global Marketplace Catalog API

The S&P Global Marketplace Catalog API provides programmatic access to the S&P Global data marketplace, enabling discovery and consumption of available data products, datasets, and API solutions across all S&P Global business units.

- **Human URL:** [https://www.marketplace.spglobal.com/en/solutions/s-p-global-marketplace-catalog-api-(03f3c047-dcac-4fa7-a1ef-fb48a4d9b75d)](https://www.marketplace.spglobal.com/en/solutions/s-p-global-marketplace-catalog-api-(03f3c047-dcac-4fa7-a1ef-fb48a4d9b75d))

#### Tags

- Data Catalog
- Marketplace
- Discovery
- REST

#### Properties

- [Documentation](https://www.marketplace.spglobal.com/en/solutions/s-p-global-marketplace-catalog-api-(03f3c047-dcac-4fa7-a1ef-fb48a4d9b75d))
- [Postman Collection](collections/sandp-global-capital-iq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sandp-global-capital-iq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sandp-global-commodity-insights.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sandp-global-commodity-insights.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/spgi-ci)
- [Website](https://www.spglobal.com)
- [Developer  Portal](https://developer.spglobal.com)
- [Marketplace](https://www.marketplace.spglobal.com)
- [Documentation](https://www.support.marketplace.spglobal.com)
- [Authentication](https://developer.spglobal.com/getting-started/Auth.html)
- [Python  S D K](https://pypi.org/project/spgci/)
- [Python  S D K](https://pypi.org/project/SPGMICIQ/)
- [F A Q](https://developer.spglobal.com/support/faq)
- [Support](https://commodityinsightssupport.spglobal.com)
- [Vocabulary](vocabulary/sandp-global-vocabulary.yml)
- [Spectral Rules](rules/sandp-global-rules.yml)
- [Capabilities](capabilities/market-intelligence.yaml)
- [JSON-LD](json-ld/sandp-global-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [L L Ms Txt](https://developer.spglobal.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
