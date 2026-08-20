# Advanced Auto Spa — Business-Data Verification Checklist

Single source of truth for every fact that must be confirmed by the client before launch. The design renders amber "VERIFY" chips wherever one of these appears. All values should live in one editable business-data object/CMS collection — never scattered across components.

## Must verify before publishing

| Token | Current evidence | Status |
|---|---|---|
| BUSINESS_HOURS | Mockup says Mon–Fri 8–6, Sat 8–4; live site widget differs | ⚠ CONFLICT — confirm with client |
| GOOGLE_RATING | Assumed 5.0 | Verify live on GBP |
| GOOGLE_REVIEW_COUNT | Site copy says "700+"; gallery page says "750+" | ⚠ CONFLICT — pull live count |
| FOUNDING_YEAR | Not stated on site | Confirm; distinguish from years of experience |
| YEARS_OF_EXPERIENCE | Site OG copy says "25+ years" | Confirm current, accurate number |
| EMAIL | advancedautospa@gmail.com (public Gmail) | Confirm whether branded domain email replaces it |
| GOOGLE_REVIEW_URL | goo.gl/VaoMkv found historically | Supply official current link |
| GOOGLE_DIRECTIONS_URL | Maps query link used as placeholder | Supply official tracked link |
| BOOKING_URL | Wix booking calendar | Supply preferred tracked link (UTM) |
| Parking / drop-off instructions | Not published | Write with client |
| Written directions | Placeholder text in design | Verify route description |
| Matawan → Manalapan timeline | Old Matawan info on 3rd-party listings | Confirm dates; fix citations (NAP cleanup) |

## Pricing (published on advancedautospa.com — re-verify before launch)

- Hand wash: Silver $79.95 · Gold $89.95 · Platinum $99.95 · Exterior Basic $59.95 · Plus $69.95
- Maintenance Detail from $185.95 (2 hr) · Exterior Detail from $189.95 (2 hr) · Interior Detail from $189.95 (3 hr)
- Full Detail varies (4 hr) · Paint Correction from $279.95 (4 hr) · Ceramic Coating call/assessment (16 hr)
- Engine Detailing $89.95 (1 hr) · Headlight Restoration from $89.95 (1 hr) · Rock Chip Repair $89.95 (30 min)
- Badge & Emblem Removal from $79.95 (1 hr) · Glass/Trim/Interior Coating from $99.95 (1 hr) · Window Tinting varies (2 hr)

## Content still needed from client

- Owner portrait + storefront photo + ceramic coating / paint correction photography (marked "REAL PHOTO PENDING" in the design)
- Before/after pairs for featured transformation and case studies, with vehicle make/model/year per job
- Verbatim Google review excerpts per service (design holds placeholder slots — never invent)
- Ceramic coating tier names, products, durability/warranty terms
- Interior Odor Elimination scope + pricing
- Consent language for the lead form (legal review)
- Confirmation of "New Jersey's highest rated" claim substantiation — otherwise remove

## Structured data plan (implement at build)

- LocalBusiness + Organization with verified NAP/hours; BreadcrumbList on all pages; Service where accurate
- No self-serving aggregate-rating markup for the business's own reviews
- VideoObject for meaningful videos once titles/transcripts exist
