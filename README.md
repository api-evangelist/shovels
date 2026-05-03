# Shovels

Shovels is the intelligence layer for the built world, providing building permit data and contractor intelligence aggregated from 1,800+ jurisdictions across the United States. The platform offers 130M+ building permits, 2.3M+ contractor profiles, property details, resident information, and geographic market metrics. Shovels helps materials suppliers, construction tech companies, energy and climate firms, home services companies, real estate professionals, and telecommunications providers identify qualified contractors, understand work history, and power sales and marketing with rich permit data.

**Human URL:** [https://www.shovels.ai/api](https://www.shovels.ai/api)

## APIs

### Shovels API v2
- **Documentation:** https://docs.shovels.ai
- **Getting Started:** https://docs.shovels.ai/docs/shovels-api-introduction
- **Base URL:** `https://api.shovels.ai/v2`
- **Authentication:** X-API-Key header — sign up at https://app.shovels.ai
- **Coverage:** 130M+ permits, 2.3M+ contractors, 1,800+ jurisdictions
- **Data Refresh:** 1st and 15th of each month

## Artifacts

### OpenAPI Specifications
- [shovels-openapi.yml](openapi/shovels-openapi.yml)

### JSON Schemas
- [shovels-permit-schema.json](json-schema/shovels-permit-schema.json)
- [shovels-contractor-schema.json](json-schema/shovels-contractor-schema.json)

### JSON Structure
- [shovels-permit-structure.json](json-structure/shovels-permit-structure.json)

### JSON-LD Context
- [shovels-context.jsonld](json-ld/shovels-context.jsonld)

### Examples
- [shovels-search-contractors-example.json](examples/shovels-search-contractors-example.json) — Search solar contractors in San Francisco
- [shovels-search-permits-example.json](examples/shovels-search-permits-example.json) — Search residential roofing permits in Austin

### Rules
- [shovels-rules.yml](rules/shovels-rules.yml)

### Capabilities
- [contractor-intelligence.yaml](capabilities/contractor-intelligence.yaml) — Permits, contractors, employees, addresses, and market metrics for contractor sales intelligence

### Vocabulary
- [shovels-vocabulary.yml](vocabulary/shovels-vocabulary.yml)

## Maintainers

**Kin Lane** - kin@apievangelist.com
