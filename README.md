# Klaim

Klaim (Klaim Kapital Technologies Limited / Klaim Holdings Limited) is an Abu Dhabi-founded, UAE-based healthcare fintech that advances working capital against receivables. Healthcare providers, real estate brokers and SMEs submit unpaid insurance claims or invoices, Klaim's AI evaluates and prices the risk in real time, and Klaim advances up to 90% of face value within 24 hours, collecting only when the payer or client settles.

Founded December 2019 by Karim Dakki (CEO) and Ahmad Ghafour. Backed by Techstars. Operates across the GCC, North Africa and Turkey.

## Products

- **Klaim Health** — insurance claim advances for medical providers, plus AI denial prediction — https://klaim.ai/health
- **Klaim Flow** — SME receivables purchasing (invoice financing + escrow) — https://klaim.ai/flow
- **Klaim Estate** — real estate commission advances — https://klaim.ai/estate
- **Klaim Eligible** — insurance eligibility verification for medical providers

## API surface

Klaim publishes **no public developer portal, API documentation, API reference, OpenAPI description, SDKs, CLI, sandbox, changelog or status page**. No `api.` / `docs.` / `developer.` subdomain resolves, and no `/.well-known/` discovery document is served. The artifacts in this repo record that verified absence rather than asserting a developer surface that does not exist.

## Artifacts

- `apis.yml` — company profile and link properties
- `security/klaim-domain-security.yml` — probed TLS/DNSSEC/SPF/DMARC posture
- `well-known/klaim-well-known.yml` — probed `/.well-known/` surface (all 404, recorded)
- `llms/klaim-llms.txt` — generated agent-readable company summary

Backed by: techstars — https://klaim.ai/
