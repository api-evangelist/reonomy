# Reonomy (reonomy)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
