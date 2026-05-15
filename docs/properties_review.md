# HAVEN – Properties Page UX & Content Spec

This document describes how to evolve `properties.html` into a premium, luxury-style listing page aligned with the HAVEN homepage and modern best practices. [web:5][web:16][web:23][web:26]

---

## 1. Page Hero & Intro

**Current:**

- Eyebrow: `CURATED SELECTION`
- H1: `Find YourPerfect Property`
- Intro: `Browse our handpicked selection of luxury properties across Australia's most prestigious locations.`

**Issues:**

- Minor spacing/kerning issue in “Find YourPerfect”.
- Hero does not visually match the more cinematic, editorial feel of the homepage.

**Recommended structure:**

- Eyebrow: `CURATED SELECTION`
- H1: `Find Your Perfect Property`
- Subheading:  
  `Browse a handpicked selection of luxury homes, penthouses, and estates in Australia’s most coveted postcodes.`

**Design notes:**

- Use the same heading type scale and alignment as the home hero (either centered or left-aligned, but consistent). [web:5][web:26]
- Add more vertical spacing above and below the hero block to create a calm, high-end first impression.
- Optional: place hero text over a soft image or gradient that matches the home page art direction.

---

## 2. Filters & Search Bar

**Current controls:**

- `All Types` (House, Apartment, Townhouse, Penthouse)
- `All Locations` (Sydney, Melbourne, Brisbane)
- `Any Price` (Up to $1M, $1M–$2M, $2M–$5M, $5M+)
- `Bedrooms` (1+, 2+, 3+, 4+)
- `SEARCH` button

**Problems / opportunities:**

- Filters are visually simple and a bit disconnected from the homepage search.
- No sort control.
- No visible result count or feedback.

**Updated content & labels:**

- Property Type: `All Types`, `House`, `Apartment`, `Townhouse`, `Penthouse`
- Location: `All Locations`, `Sydney`, `Melbourne`, `Brisbane` (can later expand to suburbs)
- Price: `Any Price`, `Up to $1M`, `$1M – $2M`, `$2M – $5M`, `$5M+`
- Bedrooms: `Any`, `1+`, `2+`, `3+`, `4+`
- Sort: `Featured`, `Newest`, `Price (Low–High)`, `Price (High–Low)`

**Design pattern:**

- Wrap filters and search into one “search bar” container that visually matches the homepage search:
  - Light background, subtle shadow, rounded corners.
  - Equal spacing between fields, consistent label styles. [web:6][web:23][web:25]
- Add a results sentence above listings:  
  `Showing 18 properties in All Locations` (update dynamically). [web:23][web:25]

**Layout suggestion:**

Row 1:
- Segmented control (if also used on home): `Buy · Rent · Sold · New Projects`

Row 2:
- `[Type] [Location] [Price Range] [Bedrooms] [Sort] [Search Button]`

---

## 3. Property Cards – Visual Structure

**Current card content examples:**

- Modern luxury house – `NEW LISTING` – `MOSMAN, NSW` – `14 Harbourview Crescent` – `4 Bed · 3 Bath · 2 Car` – `$4,850,000`
- Penthouse apartment – `PREMIUM` – `CIRCULAR QUAY, NSW` – `Penthouse 3201 — The Quay` – `3 Bed · 3 Bath · 2 Car` – `$8,200,000`
- And others including OFF THE PLAN, AUCTION, etc.

**Best‑practice goals:**

- Visual‑first, grid‑based layout with consistent image ratios. [web:16][web:23][web:26]
- Very readable and consistent hierarchy of text elements.

**Recommended card hierarchy:**

1. Image (fixed ratio, e.g. 4:3), full width.
2. Top-left badge (on image): `NEW LISTING`, `PREMIUM`, `OFF THE PLAN`, `AUCTION`.
3. Top-right icon: heart/favourite (optional for later functionality).
4. Location line: `MOSMAN, NSW` (small caps or subdued label).
5. Title:  
   - `14 Harbourview Crescent`  
   - `Penthouse 3201 — The Quay`
6. Lifestyle line (new):  
   - `Harbourfront family sanctuary with resort-style pool and skyline views.`  
   - `Skyline penthouse with wrap-around terrace and private lift access.`
7. Specs row: Bed / Bath / Car icons with counts: `4 Bed · 3 Bath · 2 Car`.
8. Price row: `$4,850,000` or `From $1,150,000` or `Price on Application`.

**Design notes:**

- Use the same card style as your home “Featured Properties” section (same border radius, shadow, hover effect). [web:5][web:16]
- Hover state: subtle zoom/brightness on image + show “View details” overlay. [web:21][web:23]

---

## 4. Property Cards – Content Refinement

**For each existing listing, add a lifestyle line:**

1. Modern luxury house – MOSMAN, NSW – 14 Harbourview Crescent  
   - Lifestyle: `Elevated family home with expansive harbour views, resort-style pool, and multiple entertaining terraces.`

2. Penthouse apartment – CIRCULAR QUAY, NSW – Penthouse 3201 — The Quay  
   - Lifestyle: `Iconic harbourfront penthouse with floor-to-ceiling glass, private rooftop terrace, and concierge.`

3. Contemporary house – VAUCLUSE, NSW – 7 Ridgecrest Boulevard  
   - Lifestyle: `Architect-designed residence with infinity pool, seamless indoor-outdoor living, and secure garaging.`

4. Modern apartment (OFF THE PLAN) – SOUTH YARRA, VIC – Ellara Residences  
   - Lifestyle: `Boutique residences with residents’ club, rooftop garden, and curated amenities in the heart of South Yarra.`

5. Luxury apartment – SURFERS PARADISE, QLD – Suite 12A — Ocean Towers  
   - Lifestyle: `Sunlit beachfront apartment with full-width balcony, ocean vistas, and direct beach access.`

6. Classic estate (AUCTION) – TOORAK, VIC – 22 Forest Ridge Estate  
   - Lifestyle: `Grand European-inspired estate with formal gardens, pool pavilion, and multiple living wings.`

These one‑liners align the properties page tonal style with the homepage’s “curated luxury living” positioning. [web:24][web:26]

---

## 5. Grid, Pagination & “Load More”

**Current:**

- Cards listed in a vertical sequence.
- Button: `LOAD MORE PROPERTIES`.

**Recommended structure:**

- Use a 3‑column grid on desktop, 2 on tablet, 1 on mobile. [web:16][web:23]
- Keep card heights reasonably aligned by limiting text length and keeping image ratios consistent.
- Style the “LOAD MORE PROPERTIES” button with the same primary button style as on the homepage (color, radius, typography). [web:5][web:9]

**Optional enhancements:**

- Show result range above the button:  
  `Showing 1–18 of 54 properties`.
- Later you can switch to numbered pagination using the same button/link styles.

---

## 6. Off‑Market CTA Section

**Current content:**

- Heading: `Can't find what you're looking for?`
- Body: `Our team has access to exclusive off-market properties. Let us help you find your dream home.`

**Improvements:**

**Design:**

- Make this a full-width band with contrasting background (same style as “What is your home worth?” on the homepage). [web:5][web:16]
- Center the text and add one primary CTA:
  - `Tell us what you’re looking for` (linking to a tailored enquiry form or pre-filled contact page).

**Refined copy:**

- Heading: `Can’t find what you’re looking for?`
- Body:  
  `Many of our most exclusive homes never reach the open market. Share your brief and we’ll discreetly match you with off-market opportunities.`

---

## 7. Footer Alignment

**Current:**

- Logo: `HAVEN REAL ESTATE`
- Tagline: `Australia's premier luxury real estate agency. Connecting exceptional people with exceptional properties since 2001.`
- Column headings: `PROPERTIES`, `SERVICES`, `COMPANY` (all currently empty).
- Copyright.

**To match the homepage spec:**

Populate footer links:

- **PROPERTIES**
  - `Search Homes`
  - `New Developments`
  - `Off-Market Access`
  - `Neighbourhood Guides`

- **SERVICES**
  - `Buyer Advisory`
  - `Vendor Advisory`
  - `Investment & Portfolio`
  - `Property Management`

- **COMPANY**
  - `About Haven`
  - `Our Advisors`
  - `Media & Press`
  - `Careers`
  - `Contact`

Design notes:

- Typography, colors, and spacing here must be identical to the homepage footer. [web:5][web:26]

---

## 8. Consistent Design System Tokens

To keep `index.html` and `properties.html` fully aligned:

- **Colors**  
  - Primary: same deep neutral/gold accent used on home CTAs and badges.  
  - Background: use the same light/dark section alternation as the homepage. [web:26]

- **Typography**  
  - Headings: same font family, weight, sizes as home.  
  - Body and labels: same sans-serif as home.  
  - Card titles and badges reuse home styles.

- **Spacing**  
  - Section padding: e.g. `80px` top/bottom desktop, `48px` mobile, used consistently across both pages. [web:25][web:28]  
  - Card gutters: consistent column gaps across home and properties grids.

- **Interactions**  
  - Hover states on buttons and cards should mirror home (color shift, shadow, or underline).  
  - Filter dropdowns and buttons share focus styles and active states.

---

## 9. Future Enhancements (Optional)

For future iterations inspired by top platforms: [web:23][web:25][web:28]

- Real‑time filter updates (update cards instantly when a filter changes, without pressing “Search”).
- “Save” and “Compare” features for logged‑in users.
- Map toggle (`List · Map`) to switch between grid and map view.

---

End of spec.