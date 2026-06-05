# Carbone (carbone)

Carbone is a document generation engine that uses Word, Excel, PowerPoint and ODF templates with JSON data to produce PDFs or office documents. The Carbone HTTP API offers a template-then-render workflow with both cloud (api.carbone.io) and on-prem deployments. The Carbone JS rendering engine is open-source and embeddable.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/carbone/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/carbone/refs/heads/main/apis.yml)

## Tags

- Document Generation
- PDF
- Templates
- Open Source
- Office
- DOCX
- XLSX

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Carbone Cloud HTTP API

Cloud-hosted Carbone API. Two flows — upload-once via POST /template then render with a template ID; or single-request inline-base64 render. Bearer-token auth (Authorization header). Sync and async via webhooks. Hosted on European providers (OVHCloud, Scaleway, BunnyCDN).

- **Human URL:** [https://carbone.io/api-reference.html](https://carbone.io/api-reference.html)
- **Base URL:** `https://api.carbone.io`

#### Tags

- REST
- Templates
- Render
- Async
- Webhooks

#### Properties

- [Documentation](https://carbone.io/api-reference.html)
- [Authentication](https://carbone.io/api-reference.html#authentication)
- [SDK](https://github.com/carboneio/carbone-sdk-js)
- [Postman Collection](collections/carbone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/carbone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Carbone On-Premises

Self-hosted Carbone deployment exposing the same HTTP API. Auth disabled by default; enable via configuration. 30-day free trial of paid features.

- **Human URL:** [https://carbone.io/documentation.html](https://carbone.io/documentation.html)
- **Base URL:** `http://<your-host>:4000`

#### Tags

- REST
- Self-Hosted
- On-Prem

#### Properties

- [Documentation](https://carbone.io/documentation.html)
- [Postman Collection](collections/carbone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/carbone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Carbone Render Engine (Open Source)

Open-source Node.js library that powers the rendering engine. Embed directly in your application; render templates with JSON data without hitting the cloud API.

- **Human URL:** [https://github.com/carboneio/carbone](https://github.com/carboneio/carbone)
- **Base URL:** `npm:carbone`

#### Tags

- SDK
- Open Source
- Node.js

#### Properties

- [Source Code](https://github.com/carboneio/carbone)
- [Documentation](https://carbone.io/documentation.html)
- [Postman Collection](collections/carbone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/carbone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/carboneio)
- [Website](https://carbone.io/)
- [Documentation](https://carbone.io/documentation.html)
- [Pricing](https://carbone.io/pricing.html)
- [Git Hub](https://github.com/carboneio)
- [Plans](plans/carbone-plans-pricing.yml)
- [Rate Limits](rate-limits/carbone-rate-limits.yml)
- [Fin Ops](finops/carbone-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
