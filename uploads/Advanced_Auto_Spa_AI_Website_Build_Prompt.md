# Advanced Auto Spa Website Redesign — Master AI Build Prompt

## Role

Act as a senior automotive UX/UI designer, local SEO strategist, conversion copywriter, WCAG 2.2 AA accessibility specialist, and front-end engineer. Create a polished, production-minded website redesign for Advanced Auto Spa using the attached mockup as the primary visual reference.

## Required inputs

1. Primary visual reference: `advanced_auto_spa_mockup_with_real_site_photos.png`
2. Existing website for verified business content and real photography: `https://www.advancedautospa.com/`
3. Any additional Advanced Auto Spa images, logo files, review exports, service pricing, business hours, and booking links supplied with the project.

Do not invent business facts, prices, review counts, warranties, coating durations, certifications, or hours. Use the verification tokens listed below until the client confirms the final information.

## Project objective

Redesign the website so it accurately reflects the reputation and craftsmanship of Advanced Auto Spa while improving local SEO, user experience, accessibility, Google Business Profile integration, lead quality, and completed bookings.

The current business already has strong assets: real automotive work, an owner-operated story, a purpose-built studio, public service pricing, a Manalapan location, and hundreds of five-star Google reviews. The current website does not organize those assets clearly enough. The redesigned site must turn that reputation into a premium, easy-to-use local conversion system.

## Core positioning

Advanced Auto Spa is not a generic car wash and should not look like a tuner shop, dealership template, or neon automotive landing page. Position it as a private, owner-operated automotive care studio built around precision, controlled lighting, professional equipment, transparent service selection, and proven customer trust.

Primary positioning statement:

> Premium auto detailing, paint correction, and ceramic protection in Manalapan, New Jersey.

Supporting differentiation:

- Owner-operated and personally accountable
- Purpose-built professional studio
- Real vehicles and real results
- Strong Google reputation
- Clear service pathways for maintaining, restoring, or protecting a vehicle
- Premium service without visual gimmicks

## Current-site problems the redesign must solve

### Local SEO and entity consistency

- Old Matawan business information remains visible on third-party listings while the website uses the current Manalapan address.
- The website, Google Business Profile, directories, and social profiles need one verified business name, address, phone number, hours, founding date, and review count.
- The website must clearly reinforce the current Manalapan location with a dedicated location page, written directions, parking/drop-off instructions, map, storefront photography, and matching structured data.

### Duplicate and legacy URLs

- Two windshield-repair URLs expose the same service and need one canonical destination.
- The legacy `/service-page/hand-wash` URL actually represents the Maintenance Detail and overlaps with `/service-page/maintenance-detail`.
- Transactional booking-calendar pages should not compete with full service pages in organic search.
- Preserve existing URLs that have proven search value whenever possible. When changing a URL, create an explicit 301 redirect map and update all internal links, canonicals, and XML sitemap entries.

### Content and on-page SEO

- The homepage and detailing hub both target nearly the same “Auto Detailing in Manalapan” intent.
- Service descriptions are useful but are often presented through a repetitive booking template instead of a persuasive service-page structure.
- Prices and durations appear more than once in rendered content.
- Generic link labels such as “Read More,” “Book It,” and “Book Now” are repeated without service context.
- The gallery contains a very large number of images with inconsistent or missing image descriptions.
- The video page exposes very little crawlable supporting text.

### UX and conversion

- The homepage needs one dominant booking journey and clearer pathways based on customer needs.
- The existing contact form is too limited to qualify an automotive-service lead.
- High-ticket services such as ceramic coating and paint correction need consultation-oriented paths, package comparisons, proof, and FAQs.
- Reviews, before-and-after work, the owner story, and studio advantages need to appear closer to booking decisions.

### Accessibility

- Some images have generic, inaccurate, duplicated, or irrelevant alternative text.
- Repeated generic links are unclear outside their visual context.
- Interactive navigation, filters, galleries, sliders, forms, and booking functions must work by keyboard and screen reader.
- The final site must meet WCAG 2.2 AA, not rely on an accessibility overlay, and include reduced-motion support.

### Google Business Profile integration

- Website and profile information must match exactly.
- Google Business Profile service names should map to corresponding website service pages.
- Website, booking, post, and direction links should use intentional UTM tracking.
- Reviews, photos, posts, calls, directions, booking starts, booking completions, and lead submissions must be measurable.

## Visual direction: Precision Studio

Use the attached mockup as the principal design reference. Preserve its overall hierarchy and premium automotive tone while extending it into a complete website.

### Visual character

- Cinematic but controlled
- Premium and technical
- Clean, owner-operated, and trustworthy
- Dark where photography benefits from contrast
- Light where users compare services, prices, reviews, FAQs, and forms
- Minimal motion and no distracting automotive clichés

### Color system

Use these as the starting design tokens:

- Carbon black: `#0D0F10`
- Graphite: `#191C1E`
- Pearl white: `#F4F3EF`
- Clean white: `#FFFFFF`
- Steel gray: `#AEB3B7`
- Border gray: `#D8D8D4`
- Primary red accent: derive from the approved Advanced Auto Spa logo; begin near `#E31B23` and confirm against the logo
- Success/error colors must meet contrast requirements and should not rely on color alone

### Typography

Use a premium modern sans-serif system:

- Headings: Manrope, Neue Montreal, or a visually similar licensed/system-safe alternative
- Body: Inter or a visually similar highly legible sans-serif
- Small labels: uppercase with restrained letter spacing
- Avoid racing fonts, script fonts, faux carbon-fiber effects, and excessive italics

### Layout language

- Full-width cinematic hero
- Strong grid and generous spacing
- Mostly square or lightly rounded cards
- Thin borders and subtle dividers
- Clear hierarchy with short, direct headlines
- Photography must be real Advanced Auto Spa work whenever assets are available
- Never use stock supercars to imply work the company did not perform

## Global business data tokens

Create a single editable business-data object or CMS collection. Do not scatter these values across components.

- `{{BUSINESS_NAME}}` = Advanced Auto Spa
- `{{ADDRESS}}` = 221 Park Avenue, Manalapan, NJ 07726
- `{{PHONE}}` = (732) 441-1400
- `{{EMAIL}}` = verify whether a branded domain email will replace the public Gmail address
- `{{BUSINESS_HOURS}}` = VERIFY BEFORE PUBLISHING
- `{{FOUNDING_YEAR}}` = VERIFY BEFORE PUBLISHING
- `{{YEARS_OF_EXPERIENCE}}` = VERIFY BEFORE PUBLISHING
- `{{GOOGLE_RATING}}` = VERIFY LIVE
- `{{GOOGLE_REVIEW_COUNT}}` = VERIFY LIVE
- `{{GOOGLE_REVIEW_URL}}` = SUPPLY OFFICIAL LINK
- `{{GOOGLE_DIRECTIONS_URL}}` = SUPPLY OFFICIAL LINK
- `{{BOOKING_URL}}` = SUPPLY PREFERRED TRACKED LINK
- `{{HAND_WASH_STARTING_PRICE}}` = VERIFY
- `{{INTERIOR_DETAIL_STARTING_PRICE}}` = VERIFY
- `{{PAINT_CORRECTION_STARTING_PRICE}}` = VERIFY
- `{{CERAMIC_COATING_STARTING_PRICE_OR_ASSESSMENT}}` = VERIFY

Important: the attached mockup is a visual concept. Its hours, review count, and some service prices are placeholders and must not be published until verified against the client’s current operating information.

## Global navigation

### Utility bar

Desktop utility bar should contain:

- Current address
- Current hours or “Open today” status if reliable
- Verified Google rating/review proof
- Click-to-call phone number

Do not overcrowd the mobile header. On mobile, prioritize address/directions, review proof, call, and menu access.

### Main navigation

- Logo
- Services mega menu
- Results
- Reviews
- About
- Contact
- Primary “Book Now” button

Organize the Services menu by intent:

#### Maintain

- Premium Hand Wash
- Maintenance Detail
- Exterior Detail
- Engine Detail

#### Restore

- Full Detail
- Interior Detail
- Interior Odor Elimination
- Paint Correction
- Headlight Restoration
- Windshield Rock Chip Repair

#### Protect

- Ceramic Coating
- Glass, Trim, or Interior Ceramic Coating
- Window Tinting
- Any additional verified protection service

All menu interactions must work with keyboard, touch, mouse, and screen readers. Do not rely on hover alone.

## Homepage requirements

Build the homepage in this exact strategic order.

### 1. Hero

Use a real Advanced Auto Spa image showing the owner or technician working on a glossy dark vehicle inside the studio. Preserve the dark photographic treatment shown in the mockup.

Eyebrow:

> OWNER-OPERATED IN MANALAPAN, NEW JERSEY

H1:

> Premium Auto Detailing, Paint Correction & Ceramic Protection

Supporting copy:

> Precision automotive care performed in a purpose-built studio, backed by a verified local reputation and a personal standard of craftsmanship.

Primary CTA:

- Book a Detail

Secondary CTA:

- Request an Assessment

Trust proof below CTA:

- Google rating and verified review count
- Link to read reviews on Google

### 2. Trust strip

Four concise items:

- Verified Google Reviews
- `{{YEARS_OF_EXPERIENCE}}` Years of Experience
- Owner Operated
- Purpose-Built Studio

Each item needs an accessible icon, heading, and one-line explanation.

### 3. “What does your vehicle need?”

Create three large photographic pathways exactly in the spirit of the mockup:

#### Maintain

For vehicles already in good condition that need regular care.

#### Restore

For stains, pet hair, odors, defects, scratches, or neglected finishes.

#### Protect

For ceramic protection, long-term gloss, and ownership-value preservation.

On mobile, the descriptive content must remain visible without hover.

### 4. Featured services

Feature no more than six priority services on the homepage. Each card must show:

- Real image
- Service name
- One-sentence outcome
- “Starting at” price or “Assessment Required”
- Approximate duration
- Service-specific CTA

Use contextual CTAs such as “View Interior Detailing” and “Request a Ceramic Coating Assessment,” never generic “Read More.”

### 5. Featured transformation

Create an accessible before-and-after case study module with:

- Vehicle make/model
- Initial condition
- Service performed
- Time or process summary
- Result
- Link to full case study
- Link to relevant service

If using a drag slider, provide an equally usable static before/after alternative and full keyboard support.

### 6. Reviews

Show six curated, service-specific Google review excerpts. Include:

- Reviewer name in an appropriate shortened form
- Review date or relative date
- Service context when known
- Google source indicator
- “Read on Google” link

Provide separate links for “Read Our Google Reviews” and “Share Your Experience.” Do not use self-serving review schema for the business’s own reviews.

### 7. Owner and studio story

Use a real portrait or working image of Marco/owner.

Headline direction:

> Not a Production Line. A Personal Standard.

Explain the owner-operated process, controlled studio, lighting, tools, vehicle inspection, and personal quality control. Keep homepage copy concise and link to the full About page.

### 8. How it works

Five steps:

1. Choose a Service
2. Schedule or Request an Assessment
3. Vehicle Evaluation
4. Service and Quality Control
5. Pickup and Care Guidance

### 9. Recent work

Show a curated set of six to twelve projects, not an endless unfiltered gallery. Include filters and links to detailed case studies.

### 10. FAQ

Include verified answers covering:

- How to choose a service
- How long services take
- Whether pricing varies by condition and vehicle size
- What customers should remove from the vehicle
- Drop-off and pickup
- Ceramic coating consultation
- Maintenance after coating
- Cancellation/rescheduling

### 11. Location and contact

Include:

- Matching address, phone, and hours
- Accessible map or map fallback
- Written directions
- Storefront image
- Parking/drop-off instructions
- Call, Book, and Get Directions CTAs
- Qualified lead form

### 12. Final CTA and footer

Repeat the three main customer actions:

- Book
- Call
- Get Directions

Footer must include consistent NAP, services, About, Reviews, Contact, privacy, accessibility statement, and social links.

## Mobile requirements

- Use the mobile layout shown in the attached mockup as the visual reference.
- Avoid a heavy autoplay video on mobile; use a properly optimized poster image unless performance testing supports video.
- Add a fixed bottom action bar: Call, Book Now, Directions.
- Ensure the bar never obscures focused controls or form messages.
- Use large, clear touch targets.
- Avoid tiny carousel arrows and hover-only interactions.
- Keep price, duration, and CTA visible on service cards.

## Required pages

### Homepage

Broad premium local intent and primary conversion.

### Detailing/services hub

Preserve `/detailing` unless an approved migration plan says otherwise. Turn it into a service-selection and comparison page rather than a repetitive booking feed.

### Individual service pages

Create a consistent page template for:

- Full Detail
- Exterior Detail
- Interior Detail
- Maintenance Detail
- Premium Hand Wash
- Ceramic Coating
- Paint Correction
- Interior Odor Elimination
- Automotive Window Tinting
- Engine Detailing
- Headlight Restoration
- Windshield Rock Chip Repair
- Glass, Trim, or Interior Ceramic Coating

Each service page must include:

1. Breadcrumbs
2. Unique local H1
3. Clear outcome statement
4. Price or pricing factors
5. Duration
6. Who it is for
7. What is included
8. What is not included or what changes pricing
9. Process
10. Real before-and-after proof
11. Service-specific reviews
12. FAQs
13. Related services
14. Booking or assessment CTA
15. Location reinforcement

### Ceramic coating page

Use consultation-first conversion. Include verified package levels, protection terms, preparation requirements, process, paint-correction relationship, care guidance, and FAQs. Never invent warranty or longevity claims.

### Paint correction page

Explain polishing versus correction, one-stage versus multi-stage work, inspection requirements, expected defect reduction, studio-lighting value, and optional protection after correction.

### Results/case studies

Create filterable projects with unique text, images, service links, vehicle information, and outcomes.

### Reviews

Create a dedicated review hub with current verified rating/count, service filters, curated excerpts, a link to Google, and a compliant review-request path.

### About

Include owner story, verified timeline, studio, tools, lighting, quality-control philosophy, real photos, and current Manalapan location.

### Contact and location

Include full NAP, branded email if approved, hours, map, directions, parking/drop-off instructions, storefront image, booking CTA, and a qualified form.

### Video

Each video needs a title, summary, service context, poster image, captions, transcript, and related CTA. Do not leave the page as an empty embed collection.

### Gift cards

Retain and improve the existing gift-card path with clear terms, purchase CTA, and tracking.

## Form requirements

The quote/contact form should include:

- Name
- Phone
- Email
- Preferred contact method
- Vehicle year
- Make
- Model
- Service of interest
- Vehicle condition
- Preferred date
- Message
- Optional photo upload
- Required consent language where applicable

Provide clear labels, instructions, required-field indicators, error summaries, field-level errors, and confirmation messages. Do not use placeholders as the only labels.

## SEO implementation requirements

- One clear H1 per page
- Unique title tag and meta description per indexable page
- Self-referencing canonical on each preferred page
- 301 redirect map for every changed or duplicate legacy URL
- Canonical XML sitemap containing only indexable 200-status URLs
- Exclude or canonicalize thin transactional booking-calendar pages as appropriate
- Descriptive internal links
- Breadcrumb navigation and `BreadcrumbList` schema
- `LocalBusiness` and `Organization` structured data using verified business information
- `Service` structured data where accurate and useful
- `VideoObject` for meaningful videos
- No misleading aggregate-rating markup for the business’s own reviews
- Open Graph and social sharing metadata
- Image filenames and alt text that describe the actual content without keyword stuffing
- Location and service information must remain visible in HTML, not only inside images or scripts
- Preserve existing organic value during migration; do not change proven URLs casually
- Create a complete redirect and launch-validation checklist

## Google Business Profile integration

- Ensure website NAP and hours exactly match the verified profile
- Map each GBP service to its corresponding service page
- Use a tracked website URL and tracked booking URL
- Use UTM parameters for GBP website, booking, and post traffic
- Create dedicated destinations for ceramic coating, interior detailing, paint correction, hand wash, studio tours, seasonal care, and case studies
- Add “Read Google Reviews,” “Leave a Google Review,” and “Get Directions” actions in appropriate locations
- Include current review proof without creating an unstable manually typed count in many components
- Make business data centrally editable so review count and hours can be updated once

Recommended tracking patterns:

- `utm_source=google`
- `utm_medium=organic`
- `utm_campaign=gbp_website`
- `utm_campaign=gbp_booking`
- `utm_campaign=gbp_posts`
- Use `utm_content` for the specific post or service

## Analytics and conversion tracking

Implement or prepare events for:

- `call_click`
- `text_click`
- `directions_click`
- `book_start`
- `book_complete`
- `assessment_start`
- `assessment_submit`
- `quote_start`
- `quote_submit`
- `review_read_click`
- `review_request_click`
- `gift_card_purchase`
- `email_click`

Capture UTM parameters and preserve them through the booking or lead process where technically possible.

## Accessibility requirements

Meet WCAG 2.2 AA across all templates and interactions.

- Semantic HTML landmarks
- Logical heading order
- Skip-to-content link
- Keyboard-accessible navigation, menu, filters, slider, gallery, lightbox, forms, and booking
- Visible focus states with sufficient contrast
- Accurate alternative text for meaningful images; empty alt for decorative images
- Text alternatives for icon-only controls
- Sufficient text and control contrast
- No information conveyed only by color
- No essential hover-only content
- Captions and transcripts for videos
- Error identification and recovery
- Accessible success messages
- Proper labels and descriptions for forms
- 200% zoom and responsive reflow without loss of functionality
- Reduced-motion support
- No scroll-jacking
- No overlay used as a substitute for accessible development

## Performance requirements

- Optimize the hero for Largest Contentful Paint
- Use responsive images in WebP or AVIF where supported
- Include explicit width/height or aspect-ratio to prevent layout shift
- Lazy-load below-the-fold images
- Do not load hundreds of gallery images on initial page view
- Use video posters and defer embeds
- Limit third-party scripts
- Avoid duplicate icon libraries and unnecessary animation frameworks
- Target strong mobile Core Web Vitals and test every major template separately

## Current mockup-specific instructions

Match these visible characteristics from the supplied mockup:

- Black utility bar with address, hours, Google review proof, and phone
- Dark sticky navigation with logo and red Book Now button
- Large left-aligned white hero headline over real studio photography
- Red primary CTA and outlined secondary CTA
- White trust strip with four icon-based proof points
- White section containing three dark photographic intent cards: Maintain, Restore, Protect
- Clean featured-service cards with image, service name, starting price, description, and duration
- Mobile header with review proof and menu
- Mobile hero that preserves image focus and readable contrast
- Fixed red mobile action bar for Call, Book Now, and Directions

Extend this design system consistently across every page. Do not redesign the site into a different aesthetic after the homepage.

## Content guardrails

- Do not use “New Jersey’s #1” as a dominant claim unless the client supplies objective, current substantiation.
- Use the verified Google review count as proof, but make it centrally updateable.
- Distinguish years in business from years of professional experience.
- Do not imply the business has always been in Manalapan if the timeline says otherwise.
- Do not use stock reviews, fabricated case studies, fake badges, fake certifications, or unverified package claims.
- Use real Advanced Auto Spa photographs and describe only the work shown.
- Keep copy premium, direct, and human. Avoid generic phrases such as “your one-stop shop,” “best-in-class solutions,” and “we treat your car like our own.”

## Build output

Deliver:

1. Complete responsive homepage
2. Desktop and mobile navigation
3. Reusable design system and components
4. Detailing/services hub
5. One fully developed Ceramic Coating page
6. One fully developed Interior Detail page
7. About page
8. Results/case-study page
9. Reviews page
10. Contact/location page
11. Mobile sticky action bar
12. Working forms with validation states
13. Accessible interactions
14. SEO metadata and schema placeholders
15. Redirect-mapping document
16. Business-data verification checklist
17. Clear notes identifying any placeholder information still awaiting client approval

## Final acceptance criteria

The output is successful only when:

- It visually matches the attached mockup’s premium black, white, and red design language.
- It uses real business photography rather than invented stock imagery.
- It is fully responsive and usable on mobile.
- Every primary action works.
- The user can understand which service fits their need without reading every service page.
- The owner, studio, reviews, and real work are prominent.
- SEO pages have distinct intent and do not compete unnecessarily.
- Duplicate URLs have a clear consolidation plan.
- Website and Google Business Profile information can be synchronized.
- Accessibility is built into the components.
- All unverified hours, review counts, prices, and package claims remain clearly marked for verification rather than being fabricated.
