# Carbone (carbone)

Carbone is a document generation engine that uses Word, Excel, PowerPoint and ODF templates with JSON data to produce PDFs or office documents. The Carbone HTTP API offers a template-then-render workflow with both cloud and on-prem deployments. The Carbone JS rendering engine is open-source and embeddable.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **Cloud HTTP API** — `https://api.carbone.io` — POST /template + render-with-template-ID, or single-request inline base64. Bearer-token auth. Sync (60s) and async with webhooks (5min). [Reference](https://carbone.io/api-reference.html).
- **On-Prem** — `http://<your-host>:4000` — same HTTP API, self-hosted. 30-day trial of paid features.
- **Carbone Render (Open Source)** — Node.js library — embed directly in your app. [Source](https://github.com/carboneio/carbone).

## OpenAPI
Carbone does not currently publish a downloadable OpenAPI/Swagger document at a stable public URL as of 2026-05-08. SDKs (JS / Node, PHP, Python) cover the surface; pipeline did not retrieve a spec into `openapi/`.

## Tags
Document Generation, PDF, Templates, Open Source, Office, DOCX, XLSX

## Common Properties
- [Website](https://carbone.io/) · [Docs](https://carbone.io/documentation.html) · [Pricing](https://carbone.io/pricing.html) · [GitHub](https://github.com/carboneio)
- [Plans](plans/carbone-plans-pricing.yml) — reconciled
- [Rate Limits](rate-limits/carbone-rate-limits.yml) — reconciled (60s sync / 5min async; 1h render expiry; per-1MB data accounting)
- [FinOps](finops/carbone-finops.yml) — reconciled, FOCUS-aligned

## Plans (reconciled)
**Cloud (EU-hosted):**
- **Free** — $0/mo.
- **Essential** — $29/mo (or $26/mo annual).
- **Essential Plus** — $95/mo (or $85/mo annual).
- **Advanced** — $159/mo (or $149/mo annual).
- **Advanced Plus** — $295/mo (or $265/mo annual).
- **Advanced Ultra** — $595/mo (or $529/mo annual).

**On-Premises:**
- **Free** — $0/yr.
- **Fit** — $1,500/yr.
- **Unlimited** — from $2,940/yr.

**AWS Private Cloud (usage):** $0.15/doc first 100, falling to $0.008/doc above 10,000.

**Carbone Render (Open Source)** — free.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
