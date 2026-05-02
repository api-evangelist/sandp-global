# S&P Global

S&P Global is a leading provider of credit ratings, benchmarks, analytics, and workflow solutions in the global capital, commodity, and automotive markets. S&P Global offers multiple API product lines including Capital IQ for financial and market intelligence data, Commodity Insights (Platts) for commodity price assessments and energy market data, and a Marketplace Catalog API for discovering data products.

## APIs

### S&P Capital IQ API
Provides programmatic access to comprehensive global financial data including fundamental financials, valuations, pricing, credit ratings, capital structure, and reference data. Uses Bearer token authentication with tokens valid for 60 minutes.

- [Documentation](https://www.marketplace.spglobal.com/en/solutions/api-solutions-(61953ac7-ea64-4fac-826a-feb7f846c2be))
- [Developer Guide](https://www.support.marketplace.spglobal.com/content/dam/spglobal/mi/en/documents/marketplace/api/guides/spglobalapidevelopersguide.pdf)
- [OpenAPI](openapi/sandp-global-capital-iq-openapi.yml)

### S&P Global Commodity Insights API
RESTful access to commodity price assessments, market data, and analytics across energy, metals, agriculture, and petrochemicals markets. Formerly known as the Platts API.

- [Documentation](https://developer.spglobal.com/commodityinsights/api/getting-started)
- [Developer Portal](https://developer.spglobal.com)
- [OpenAPI](openapi/sandp-global-commodity-insights-openapi.yml)

### S&P Global Marketplace Catalog API
Programmatic access to the S&P Global data marketplace for discovering and consuming available data products.

- [Documentation](https://www.marketplace.spglobal.com/en/solutions/s-p-global-marketplace-catalog-api-(03f3c047-dcac-4fa7-a1ef-fb48a4d9b75d))

## Properties

| Type | URL |
|------|-----|
| Website | https://www.spglobal.com |
| Developer Portal | https://developer.spglobal.com |
| Marketplace | https://www.marketplace.spglobal.com |
| Authentication | https://developer.spglobal.com/getting-started/Auth.html |
| Python SDK (SPGCI) | https://pypi.org/project/spgci/ |
| Python SDK (SPGMICIQ) | https://pypi.org/project/SPGMICIQ/ |
| Support | https://commodityinsightssupport.spglobal.com |

## Artifacts

### OpenAPI Specifications
| Spec | Description |
|------|-------------|
| [Capital IQ OpenAPI](openapi/sandp-global-capital-iq-openapi.yml) | Financial data retrieval API spec |
| [Commodity Insights OpenAPI](openapi/sandp-global-commodity-insights-openapi.yml) | Commodity price assessment API spec |

### Capabilities
| Capability | Description |
|------------|-------------|
| [Market Intelligence](capabilities/market-intelligence.yaml) | Unified financial and commodity data workflows |

### Shared Capabilities
| Capability | Description |
|------------|-------------|
| [Capital IQ](capabilities/shared/capital-iq.yaml) | Capital IQ financial data consumed definition |
| [Commodity Insights](capabilities/shared/commodity-insights.yaml) | Platts commodity price data consumed definition |

### Schemas
| Schema | Description |
|--------|-------------|
| [Price Assessment Schema](json-schema/sandp-global-price-assessment-schema.json) | Commodity price assessment data model |
| [Financial Data Request Schema](json-schema/sandp-global-financial-data-request-schema.json) | Capital IQ API request structure |

### Other Artifacts
| Artifact | Description |
|----------|-------------|
| [JSON Structure](json-structure/sandp-global-price-assessment-structure.json) | Price assessment field documentation |
| [JSON-LD Context](json-ld/sandp-global-context.jsonld) | Linked data context for S&P Global concepts |
| [Vocabulary](vocabulary/sandp-global-vocabulary.yml) | Financial and commodity market vocabulary |
| [Rules](rules/sandp-global-rules.yml) | Spectral ruleset for API governance |

### Examples
| Example | Description |
|---------|-------------|
| [Get Financial Data](examples/sandp-global-get-financial-data-example.json) | Capital IQ financial data request/response |
| [Get Latest Prices](examples/sandp-global-get-latest-prices-example.json) | Commodity Insights price request/response |
