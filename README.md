# Reonomy (reonomy)

Reonomy (an Altus Group company) is a commercial real-estate property-intelligence platform whose REST API delivers property search, property detail, ownership, mortgage, sales and debt, tax, tenant, and contact / skip-trace data across U.S. commercial real estate. The API resolves addresses to a stable Reonomy property ID and returns rich detail records keyed by that ID.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/reonomy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/reonomy/refs/heads/main/apis.yml)

## Tags

- Commercial Real Estate
- Property Data
- Property Intelligence
- Ownership
- Skip Trace

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Reonomy Property Search API

Searches U.S. commercial real-estate properties by attribute filters (asset category, land use, building area, sale price, dates) and map filters (radius circle, polygon, bounding box), returning matching property IDs and coordinates. Includes the address / geolocation resolution endpoint that maps a known property to its Reonomy property ID.

- **Human URL:** [https://api.reonomy.com/v2/docs/guides/search/](https://api.reonomy.com/v2/docs/guides/search/)
- **Base URL:** `https://api.reonomy.com/v2`

#### Tags

- Search
- Properties
- Geospatial

#### Properties

- [Documentation](https://api.reonomy.com/v2/docs/guides/search/)
- [API Reference](https://api.reonomy.com/v2/docs/api/reference/)
- [OpenAPI](openapi/reonomy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/reonomy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reonomy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Reonomy Property Detail API

Retrieves detailed records for a single property by ID, or up to 250 properties at once via the bulk endpoint, with selectable detail types (basic, taxes, sales, mortgages, ownership, tenants, foreclosure).

- **Human URL:** [https://api.reonomy.com/v2/docs/guides/property-details/](https://api.reonomy.com/v2/docs/guides/property-details/)
- **Base URL:** `https://api.reonomy.com/v2`

#### Tags

- Property Detail
- Parcel
- Bulk

#### Properties

- [Documentation](https://api.reonomy.com/v2/docs/guides/property-details/)
- [API Reference](https://api.reonomy.com/v2/docs/api/reference/)
- [OpenAPI](openapi/reonomy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/reonomy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reonomy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Reonomy Ownership API

The ownership detail type on the Property Detail API returns likely owners, reported owners, mortgage signatories, and linked companies for a property, surfaced through the property and bulk endpoints.

- **Human URL:** [https://api.reonomy.com/v2/docs/api/reference/](https://api.reonomy.com/v2/docs/api/reference/)
- **Base URL:** `https://api.reonomy.com/v2`

#### Tags

- Ownership
- Reported Owners
- Companies

#### Properties

- [API Reference](https://api.reonomy.com/v2/docs/api/reference/)
- [OpenAPI](openapi/reonomy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/reonomy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reonomy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Reonomy Sales & Debt API

The sales, mortgages, and foreclosure detail types on the Property Detail API return transaction history, deed sale amounts, lender and loan data (including CMBS), and default / foreclosure records for a property.

- **Human URL:** [https://api.reonomy.com/v2/docs/api/reference/](https://api.reonomy.com/v2/docs/api/reference/)
- **Base URL:** `https://api.reonomy.com/v2`

#### Tags

- Sales
- Mortgages
- Debt

#### Properties

- [API Reference](https://api.reonomy.com/v2/docs/api/reference/)
- [OpenAPI](openapi/reonomy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/reonomy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reonomy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Reonomy Tenants API

The tenants detail type on the Property Detail API returns occupant business data and associated contacts for a property.

- **Human URL:** [https://api.reonomy.com/v2/docs/api/reference/](https://api.reonomy.com/v2/docs/api/reference/)
- **Base URL:** `https://api.reonomy.com/v2`

#### Tags

- Tenants
- Occupancy
- Businesses

#### Properties

- [API Reference](https://api.reonomy.com/v2/docs/api/reference/)
- [OpenAPI](openapi/reonomy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/reonomy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reonomy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Reonomy Contacts API

Contact data (persons with names, jobs, addresses, phones, and emails) is returned through the ownership and tenant detail types; a filter_pii option excludes personally identifiable fields when required.

- **Human URL:** [https://api.reonomy.com/v2/docs/api/reference/](https://api.reonomy.com/v2/docs/api/reference/)
- **Base URL:** `https://api.reonomy.com/v2`

#### Tags

- Contacts
- Skip Trace
- Persons

#### Properties

- [API Reference](https://api.reonomy.com/v2/docs/api/reference/)
- [OpenAPI](openapi/reonomy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/reonomy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reonomy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/reonomy)
- [LinkedIn](https://www.linkedin.com/company/reonomy)
- [Website](https://www.reonomy.com)
- [Documentation](https://api.reonomy.com/v2/docs/)
- [Plans](plans/reonomy-plans-pricing.yml)
- [Rate Limits](rate-limits/reonomy-rate-limits.yml)
- [Fin Ops](finops/reonomy-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
