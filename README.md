# Wine-Searcher

Wine-Searcher is the world's leading wine search engine and marketplace, providing access to prices, availability, and data on millions of wines from retailers worldwide. The Wine-Searcher API allows developers to integrate wine pricing data, merchant listings, critic scores, vintage availability, and wine details directly into websites and applications. Typical API consumers include wine apps, websites, blogs, market research companies, wine investment platforms, and insurance services.

**URL:** [https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Data
- Marketplace
- Merchants
- Prices
- Vintages
- Wine

## Timestamps

- **Created:** 2025-02-24
- **Modified:** 2026-05-03

## APIs

### Wine-Searcher API
The Wine-Searcher API provides wine pricing data, aggregated critic scores, grape variety, region, and merchant listings for any wine in the Wine-Searcher database. The API uses HTTP GET with query parameters. Responses are available in JSON or XML.

**Human URL:** [https://www.wine-searcher.com/trade/ws-api](https://www.wine-searcher.com/trade/ws-api)

#### Endpoints

| Endpoint | Description |
|----------|-------------|
| Wine Check | Aggregated wine data: price avg/min/max, critic score, grape, region, ABV |
| Market Price | Individual merchant listings sorted by price (lowest first, max 24) |

#### Properties

| Type | URL |
|------|-----|
| Documentation | https://www.wine-searcher.com/trade/ws-api |
| OpenAPI | [wine-searcher-openapi.yml](openapi/wine-searcher-openapi.yml) |
| Spectral Rules | [wine-searcher-rules.yml](rules/wine-searcher-rules.yml) |

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.wine-searcher.com |
| Developer Portal | https://www.wine-searcher.com/trade/developer |
| Pricing | https://www.wine-searcher.com/trade/api |
| FAQ | https://www.wine-searcher.com/trade/faq |
| Data Feed | https://www.wine-searcher.com/trade/datafeed |

## Artifacts

### OpenAPI Specification
- [wine-searcher-openapi.yml](openapi/wine-searcher-openapi.yml) — 2 endpoints (Wine Check + Market Price)

### Spectral Rules
- [wine-searcher-rules.yml](rules/wine-searcher-rules.yml)

### Naftiko Capabilities

#### Shared Definitions
- [capabilities/shared/wine-searcher-api.yaml](capabilities/shared/wine-searcher-api.yaml)

#### Workflow Capabilities
- [capabilities/wine-data.yaml](capabilities/wine-data.yaml) — Wine Data lookup and price comparison (2 tools)

### JSON Schema
- [wine-searcher-wine-schema.json](json-schema/wine-searcher-wine-schema.json)
- [wine-searcher-merchant-listing-schema.json](json-schema/wine-searcher-merchant-listing-schema.json)

### JSON-LD Context
- [wine-searcher-context.jsonld](json-ld/wine-searcher-context.jsonld)

### Examples
- [wine-searcher-wine-check-example.json](examples/wine-searcher-wine-check-example.json)
- [wine-searcher-market-price-example.json](examples/wine-searcher-market-price-example.json)

### Vocabulary
- [wine-searcher-vocabulary.yml](vocabulary/wine-searcher-vocabulary.yml)

## Maintainers

**Kin Lane** — kin@apievangelist.com
