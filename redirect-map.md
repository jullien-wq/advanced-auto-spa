# Advanced Auto Spa — Redirect & URL Consolidation Map

Preserve proven URLs wherever possible. Every changed or duplicate URL below gets an explicit 301 and updated internal links, canonicals, and sitemap entries.

## Duplicates & legacy URLs → canonical destination (301)

| Legacy URL | Action | Canonical destination | Reason |
|---|---|---|---|
| /service-page/hand-wash | 301 | /service-page/maintenance-detail (or /services/maintenance-detail) | Legacy hand-wash URL actually represents the Maintenance Detail |
| /windshield-repair (duplicate #1) | 301 | single canonical windshield rock chip repair page | Two URLs expose the same service — pick the stronger performer as canonical |
| /windshield-repair (duplicate #2) | 301 | same as above | — |
| /booking-calendar/* (all) | noindex or canonical → matching /service-page/* | matching full service page | Transactional calendar pages must not compete with service pages in organic search |

## Preserved URLs (do not change)

- / (homepage) — broad premium local intent
- /detailing — becomes the service-selection & comparison hub (this redesign's Services page)
- /hand-wash — hand wash packages (folded into hub anchor if migrated; otherwise keep)
- /ceramic-coating — consultation-first coating page
- /service-page/<service> — keep slugs; upgrade template
- /gallery — becomes Results/case studies (301 only if URL must change)
- /gift-card — retain and improve

## Intent separation (no redirect, content fix)

- Homepage vs /detailing: homepage targets broad premium local intent + conversion; /detailing targets service selection/comparison. De-duplicate title/H1 keywords.

## Launch validation checklist

1. Crawl old sitemap; verify every 200-status legacy URL resolves (200 or one-hop 301).
2. No redirect chains or loops; 301s (not 302s).
3. Internal links point at final URLs, not through redirects.
4. Canonicals self-reference on preferred pages.
5. XML sitemap contains only indexable 200 URLs; resubmit in Search Console.
6. GBP website/booking links updated with UTM params (utm_source=google, utm_medium=organic, utm_campaign=gbp_website / gbp_booking / gbp_posts).
7. Monitor Search Console coverage + top queries for 4–6 weeks post-launch.
