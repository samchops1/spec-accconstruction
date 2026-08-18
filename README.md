# ACC Construction LLC — spec-site preview

- **Suggested slug:** `accconstruction`
- **Target host (not live, do not claim it is):** accconstruction.capitalreconsulting.com
- **Current public site:** https://accconstructions.com/
- **Site path:** `/workspace/previews/accconstruction/index.html`
- **One-line note (Outreach):** Replaced the StellR IT Elementor template — empty 0+ counters and a stock “Latest Projects” gallery — with a Wheat Ridge job-ticket site for Leon Holley: 25+ years, click-to-call (720) 298-7777.

This folder is a static preview only. Do not deploy. Do not treat the target host as live.

## What changed vs their current site

Stripped the StellR IT footer credit, Google Tag / Ads chrome, empty 0+ “Years / Projects / Clients / Expert Member” counters, and the template stock gallery presented as “Latest Projects.” Rebuilt a mobile-first four-page shop as a manila job ticket: pine header, logo green `#008000`, clay call buttons, Big Shoulders Display + Source Serif 4, a sticky call/email dock on phones, and one compressed photo.

## Facts used (with sources)

| Fact | Source |
| --- | --- |
| Brand **ACC Construction LLC** / **ACC CONSTRUCTION LLC** | Homepage H1, footer, every page |
| Tagline **“No Job is too small or too big”** | Homepage hero |
| Residential general contractor; driveways, patios, sidewalks, remodeling; on time, on budget, minimal disruption | Homepage hero |
| Small company, vast knowledge, any size project; cost savings passed to clients; Wheat Ridge and surrounding; commercial and residential; budget, schedule, sustainability, value engineering | Homepage “Welcome To” |
| Mission (beauty, comfort, value of the home) and vision (trusted choice throughout Colorado) | Homepage |
| Services: Home Improvements, Foundations, Driveways, Home Additions, Remodeling, Sidewalks | Homepage services |
| Footer service list also: Patios, Interior/Exterior, Decks, Fencing | Footer on every live page |
| **25+ Years of Experience**; owner-led, locally operated; **Leon Holley**; Wheat Ridge, Colorado | Homepage “Why Chose” |
| Quality that lasts; full-service (driveways and decks to remodeling and additions); clear communication & fair pricing; customer satisfaction first | Homepage “Why Chose” |
| Google reviews: Jessica M. Arvada (driveway + patio); Daniel R. Wheat Ridge (kitchen + deck); Maria T. Lakewood (fencing + sidewalk) | Homepage “See What Are People Saying” |
| Phone **(720) 298-7777**; email **leonholley45@gmail.com**; address Wheat Ridge, Colorado; hours **7:00am–7:00pm (Mon–Fri)** | Homepage contact block |
| Copyright © **2026** ACC CONSTRUCTION LLC | Footer |
| Licensed, insured, bonded; family-led; “We are not salespeople. We are builders.” | https://accconstructions.com/about-us/ |
| Exterior hardscapes / structural / interior / GC split; “We answer the phone”; travel to 20 listed cities; freeze-thaw, expansive soils, building codes | About Us |
| Driveway, patio, sidewalk, deck, fence, remodel, interior/exterior, addition, foundation blurbs; free consultation → on-site estimate → permits → construction → walkthrough | https://accconstructions.com/home-improvements/ |
| Concrete driveway specialty; Colorado failure modes (cracking, settling, scaling, drainage) and published fixes; “Call or text” | https://accconstructions.com/driveways/ |
| Areas: Denver, Colorado Springs, Aurora, Fort Collins, Lakewood, Thornton, Arvada, Westminster, Pueblo, Greeley, Centennial, Boulder, Longmont, Loveland, Broomfield, Castle Rock, Commerce City, Parker, Grand Junction, Littleton | Footer “Areas we serve” |
| Logo green **#008000** on black | `wp-content/uploads/2025/07/Image-451.png` |

## Facts deliberately omitted

- **Empty counters** — “Years Of Experience 0 +”, “Project Complete 0 +”, “Happy Clients 0 +”, “Expert Member 0 +”. Not printed, not turned into schema ratings.
- **StellR IT** footer credit (“Design By : StellR IT”).
- **Stock “Latest Projects” gallery** (hard-hat models, suburban houses, shop-light stills). One concrete-pour frame (`Image-460.png` → `assets/pour.jpg`) is kept as site texture and captioned as a photo from their site, **not** a named ACC job.
- **Saturday hours** — About / Home Improvements / Driveways say Monday–Saturday 7 AM–7 PM; the homepage contact widget (and this brief) say Mon–Fri. Preview uses the contact-block hours only.
- **Street address** — city/state only on the live pages.
- **Social destinations** — “Follow Us On” has no usable profile URLs in the fetched markup.
- **Template leftovers** — “Fell free to contact”, “ACC Construction LLCCompany”, “Write a Review”, per-service SEO link farm (“Driveways Service In Colorado”).
- **Google Tag / Ads / Sign-in-with-Google** chrome.
- **Any claim this preview is live** at accconstruction.capitalreconsulting.com.

## Pages

- `index.html` — job-ticket hero, services snapshot, Leon, three published Google reviews, city list, click-to-call
- `services.html` — the full published menu, Colorado driveway notes, five-step process
- `about.html` — Leon, mission/vision, licensed-insured-bonded, “we answer the phone”
- `contact.html` — tel, mailto, Mon–Fri hours, estimate form (mailto draft)

Forms open a mail draft to leonholley45@gmail.com. They do not post to WordPress.

## Images

One photo: `assets/pour.jpg` (33KB JPEG, from `Image-460.png` on the live site). Same file is small enough for web and email. No fat original kept. No 1MB+ files. Logo is a fresh SVG house mark in their `#008000`, plus tiny favicon / apple-touch PNGs.

## JSON-LD

`GeneralContractor` on the homepage only, verified fields: name, telephone, email, live URL, Wheat Ridge CO, Mon–Fri 07:00–19:00, founder Leon Holley, areaServed, description, the one image. No aggregateRating, no street, no invented geo.

## Blockers

- No street address or prices on the live pages.
- Hours conflict (Mon–Fri vs Mon–Sat) left unresolved; preview follows the contact widget.
- Gallery images read as Elementor stock, not documented job photos.
