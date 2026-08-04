# Cleanup.pictures (cleanup-pictures)

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

Cleanup.pictures provides AI-powered photo cleanup, object and watermark removal via inpainting. The public API is hosted on the ClipDrop platform (now Jasper.ai) at https://clipdrop-api.co/cleanup/v1, billed at 1 credit per successful call.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cleanup-pictures/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cleanup-pictures/refs/heads/main/apis.yml)

## Tags

- AI
- Image Editing
- Object Removal
- Inpainting
- Visual

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Cleanup.pictures Inpainting API

REST API for object/watermark/blemish removal via mask-based inpainting. POST multipart/form-data with image_file, mask_file, and optional mode (fast/quality) to https://clipdrop-api.co/cleanup/v1. Default quota is 60 requests/minute. 1 successful call = 1 credit. Hosted on ClipDrop (Jasper.ai).

- **Human URL:** [https://clipdrop.co/apis/docs/cleanup](https://clipdrop.co/apis/docs/cleanup)
- **Base URL:** `https://clipdrop-api.co/cleanup/v1`

#### Tags

- Inpainting
- Object Removal
- Image Editing

#### Properties

- [Documentation](https://clipdrop.co/apis/docs/cleanup)
- [Sign Up](https://clipdrop.co/apis)
- [Pricing](https://clipdrop.co/apis/pricing)
- [Postman Collection](collections/cleanup-pictures.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cleanup-pictures.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/initml)
- [Website](https://cleanup.pictures/)
- [Documentation](https://clipdrop.co/apis/docs/cleanup)
- [Plans](plans/cleanup-pictures-plans-pricing.yml)
- [Rate Limits](rate-limits/cleanup-pictures-rate-limits.yml)
- [Fin Ops](finops/cleanup-pictures-finops.yml)
- [Integrations](https://cleanup.pictures/integrations)
- [L L Ms Txt](https://cleanup.pictures/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
