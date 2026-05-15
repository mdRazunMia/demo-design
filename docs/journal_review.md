# HAVEN – Journal Page UX & Content Spec

This document defines the UX, layout, and content direction for `journal.html`, turning it into a premium “Insights & News” hub aligned with HAVEN’s brand and key user journeys. [web:2][web:5][web:16][web:64][web:67]

---

## 1. Page Hero & Intro

**Current:**

- Eyebrow: `INSIGHTS & NEWS`
- H1: `TheJournal`
- Subheading: `Market updates, property news, and lifestyle features.`

**Issues:**

- Missing space: `TheJournal`.
- Intro is solid, but you can make it more specific to luxury and to your markets.

**Proposed structure:**

- Eyebrow: `INSIGHTS & NEWS`
- H1: `The Journal`
- Subheading:  
  `Market updates, property news, and lifestyle features curated by HAVEN’s advisors across Australia’s premier luxury markets.`

**Design notes:**

- Match hero typography and spacing with other internal pages (Locations/Services/About). [web:5][web:16]
- Consider a subtle editorial‑style background (e.g. open magazine, interior shot, or muted pattern) to lean into “journal” feel without distracting from content. [web:2][web:61]

---

## 2. Category Structure & Filters

Current categories appear as text headers:

- Market trends – MARKET UPDATE
- Investment tips – INVESTMENT
- Luxury living – LIFESTYLE

**Best‑practice patterns:** use clear categories and allow users to filter or scan quickly. [web:16][web:64][web:67]

**Recommended categories (top of page):**

- `All`
- `Market Updates`
- `Investment`
- `Lifestyle`
- (optional) `Neighbourhood Guides` later

Implementation options:

- Horizontal pill filters under the hero:  
  `All · Market Updates · Investment · Lifestyle`  
- Each article card is tagged with one category label (badge).

This helps users quickly find the kind of content they care about and aligns with blogging best practices. [web:64][web:67]

---

## 3. Article Card Layout

**Current sample posts:**

1. Market trends / MARKET UPDATE  
   `Sydney Luxury Market Trends 2025` – `Analysis of the latest trends in Sydney's premium property sector.`

2. Investment tips / INVESTMENT  
   `Top 5 Suburbs for Investment` – `Expert insights on emerging hotspots for property investment.`

3. Luxury living / LIFESTYLE  
   `The Art of Luxury Living` – `Exploring the finest homes and design inspiration.`

**Recommended card components:**

Each article card should include: [web:16][web:64][web:65]

- Category badge: `MARKET UPDATE`, `INVESTMENT`, `LIFESTYLE`.
- Title (H3):  
  - `Sydney Luxury Market Trends 2025`  
  - `Top 5 Suburbs for Investment`  
  - `The Art of Luxury Living`
- Short excerpt (1–2 sentences).
- Meta line:
  - `By [Author] · [Date] · [Reading time]` (you can initially omit author/time if not needed).
- CTA: `Read article` (button or link).
- Optional: Thumbnail image for each article to support visual scanning.

**Design notes:**

- Use a 3‑card grid on desktop, 1–2 on mobile/tablet. [web:16][web:61]
- Card styling should mirror property/service cards (same radius, shadow, hover). [web:2][web:5]

---

## 4. Article Excerpt Copy Suggestions

You can keep headlines and refine the one‑line summaries slightly to feel more editorial and targeted. [web:64][web:67]

### 4.1 Sydney Luxury Market Trends 2025 (MARKET UPDATE)

**Current:**  
`Analysis of the latest trends in Sydney's premium property sector.`

**Refined excerpt:**  
`A deep dive into pricing, buyer demand, and standout sales across Sydney’s prestige harbourside and inner‑city markets.`

---

### 4.2 Top 5 Suburbs for Investment (INVESTMENT)

**Current:**  
`Expert insights on emerging hotspots for property investment.`

**Refined excerpt:**  
`Our advisors reveal five suburbs across Sydney, Melbourne, and Brisbane where rental yields and long‑term growth look strongest.`

---

### 4.3 The Art of Luxury Living (LIFESTYLE)

**Current:**  
`Exploring the finest homes and design inspiration.`

**Refined excerpt:**  
`Explore signature design details, amenities, and architectural features that define truly exceptional homes.`

---

## 5. Link Articles to Core Journeys

Every article should guide users to a logical next step on the site, a key content‑marketing best practice. [web:64][web:67]

Examples:

- Market updates:
  - Link to relevant city/locations pages and property searches (e.g. `Explore Sydney homes`).
- Investment articles:
  - Link to Investment Advisory service and filtered investment‑grade properties.  
- Lifestyle articles:
  - Link to featured properties, new developments, or neighbourhood guides.

Implementation:

- At the end of each excerpt or article, add a small inline link:
  - `Explore Sydney homes`
  - `Learn more about investment advisory`
  - `View new developments`

---

## 6. Pagination or “Load More”

Even with few posts now, design for scalability. [web:16][web:63][web:64]

Options:

- “Load more articles” button styled like other primary buttons.
- Or simple pagination (`1 · 2 · 3`) at the bottom.

Include a micro‑copy line:

`Showing 3 of X articles` (as the journal grows).

---

## 7. Content Strategy & Types

Align your Journal topics with what high‑value real‑estate content performs best: market insights, how‑tos, neighbourhood guides, lifestyle. [web:64][web:65][web:67]

Recommended content pillars:

- **Market Updates**
  - Quarterly city/capital market reports.
  - Auction results and insights for prestige segments.

- **Investment**
  - Suburb investment guides.
  - Tax/portfolio considerations (high‑level, not advice).
  - “Case study” style posts on successful investments.

- **Lifestyle**
  - Architectural/design features in luxury homes.
  - High‑end amenities (pools, wellness, wine cellars, etc.).
  - “Inside a HAVEN listing” spotlight.

- (Later) **Neighbourhood Guides**
  - Deep dives into key suburbs with lifestyle, schools, and price ranges.

Each post should: [web:64][web:67]

- Answer a specific buyer/seller/investor question.
- Include internal links to relevant services, properties, and location pages.
- Use images where appropriate to break up text and sustain engagement.

---

## 8. Footer Alignment

Your footer skeleton is already present; fill it to match the global navigation used on other pages. [web:5][web:16]

Populate:

- **PROPERTIES**
  - `Search Homes`
  - `New Developments`
  - `Off-Market Access`
  - `Neighbourhood Guides`

- **SERVICES**
  - `Buyer’s Advisory`
  - `Property Appraisal`
  - `Property Management`
  - `Investment Advisory`
  - `International Buyers`
  - `Conveyancing`

- **COMPANY**
  - `About Haven`
  - `Our Advisors`
  - `Media & Press`
  - `Careers`
  - `Contact`

Ensure typography, colors, spacing, and hover states match your design system.

---

## 9. Design System Consistency

To keep `journal.html` aligned with the rest of HAVEN: [web:2][web:5][web:16][web:61]

- **Typography**
  - Same hero H1 style as Locations/Services/About.
  - Article titles at consistent H3 size, category labels at consistent small‑caps or badge style.

- **Color & Imagery**
  - Reuse brand accent color for category badges and CTAs.
  - Keep article thumbnail/photo grading consistent with site photography.

- **Layout & Spacing**
  - Section padding and grid gutters match other pages.
  - Card radius and shadows consistent with properties/services/team cards.

- **Interactions**
  - Hover states on article cards and buttons match global styles.
  - Category filters show clear active state (e.g., filled pill, underline, or bold).

---

End of spec.