# Klaim

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
