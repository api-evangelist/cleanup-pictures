# Cleanup.pictures (cleanup-pictures)

Cleanup.pictures provides AI-powered photo cleanup, object and watermark removal via inpainting. The public API is hosted on the ClipDrop platform (now Jasper.ai) at `https://clipdrop-api.co/cleanup/v1`, billed at 1 credit per successful call.

**APIs.json:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cleanup-pictures/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- AI, Image Editing, Object Removal, Inpainting, Visual

## APIs
1. **Cleanup.pictures Inpainting API** — REST API at `https://clipdrop-api.co/cleanup/v1`. POST multipart/form-data with image_file + mask_file + optional mode (fast/quality).

## Common Properties
- [Website](https://cleanup.pictures/)
- [Documentation](https://clipdrop.co/apis/docs/cleanup)
- [Plans](plans/cleanup-pictures-plans-pricing.yml) — partial
- [RateLimits](rate-limits/cleanup-pictures-rate-limits.yml) — reconciled (60 RPM, 16 MP, 30 MB)
- [FinOps](finops/cleanup-pictures-finops.yml) — reconciled

## Pricing Snapshot
- 1 successful call = 1 credit
- 100 free credits for new developers
- Per-credit USD price set on ClipDrop pricing page (varies by pack)
- Failed calls are free
- Default rate limit: 60 requests/minute (higher on request)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
