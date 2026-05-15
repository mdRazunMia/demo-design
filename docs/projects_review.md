# HAVEN – New Developments Page UX & Content Spec

This document defines the UX, layout, and copy direction for `projects.html`, turning it into a premium “New Developments / Off‑the‑Plan” hub consistent with the HAVEN homepage and Properties page. [web:5][web:24][web:39]

---

## 1. Page Hero & Intro

**Current:**

- Eyebrow: `COMING SOON`
- H1: `NewDevelopments`
- Subheading: `Discover off-the-plan opportunities across Australia.`

**Issues:**

- Missing space in `NewDevelopments`.
- Hero is minimal and doesn’t yet match the cinematic, editorial feel of the brand.

**Proposed structure:**

- Eyebrow: `COMING SOON`
- H1: `New Developments`
- Subheading:  
  `Discover carefully curated off-the-plan residences and masterplanned communities across Australia’s most coveted locations.`

**Design notes:**

- Reuse the homepage hero typography and spacing (same H1 scale, alignments). [web:5][web:41]
- Use a full-width hero image or subtle video loop suggesting architecture/interiors, with a dark overlay for contrast. [web:24][web:39]
- Add a primary CTA in hero: `Register your interest` (scrolls to/enables a form or links to contact). [web:24][web:39]

---

## 2. Project Listing Layout

**Current:**

- Text snippets:
  - `The EllaraNow Selling`
  - `The Ellara, South Yarra – 45 residences across 14 levels. From $1.15M`
  - `Coves at Manly – From $2.4M`
  - `Griffith Quarter – From $890K`

**Issues:**

- No visual hierarchy or imagery yet.
- No consistent card structure.
- No dedicated CTAs per project.

**Recommended structure:**

Treat each development as a “project card” with richer content.

Card elements:

1. Project hero image (fixed ratio, e.g. 16:9).
2. Status badge: `NOW SELLING`, `COMING SOON`, `REGISTER INTEREST`. [web:39][web:42]
3. Title:  
   - `The Ellara, South Yarra`  
   - `Coves at Manly`  
   - `Griffith Quarter`
4. Location line: `South Yarra, VIC`, `Manly, NSW`, `Griffith, QLD`.
5. Key facts line:
   - `45 residences across 14 levels · From $1.15M`
   - `Beachfront residences · From $2.4M`
   - `Urban village apartments · From $890K`
6. Short lifestyle paragraph (2–3 sentences).
7. Key amenity bullets (3 max).
8. CTA buttons:
   - Primary: `View project`
   - Secondary: `Register interest` / `Download brochure`.

**Design pattern:**

- Use a 2-column layout on desktop (image left, text right) OR project cards in a grid, but keep consistent style site‑wide. [web:5][web:37][web:41]
- Hover state: slight zoom of the image and highlight of the project card border.

---

## 3. Project‑Specific Content (Example Copy)

You can refine later, but this gives you a strong starting point aligned with luxury project landing pages. [web:24][web:39]

### 3.1 The Ellara, South Yarra

- Status badge: `NOW SELLING`
- Location: `South Yarra, VIC`
- Facts line: `45 residences across 14 levels · From $1.15M`

**Lifestyle paragraph:**

`The Ellara brings boutique luxury living to the heart of South Yarra, with light-filled residences, refined finishes, and sweeping city and river views.`

**Amenities bullets:**

- Residents’ club, rooftop garden, and private dining room.
- Concierge services and secure basement parking.
- Walkable to cafés, boutiques, and transport.

**CTAs:**

- `View project details`
- `Register interest`

---

### 3.2 Coves at Manly

- Status badge: `COMING SOON` (or `NOW SELLING` when appropriate)
- Location: `Manly, NSW`
- Facts line: `Beachfront residences · From $2.4M`

**Lifestyle paragraph:**

`Coves at Manly offers a collection of coastal residences with expansive ocean vistas, generous terraces, and effortless access to Manly’s cafés and surf.`

**Amenities bullets:**

- Beachfront position with ocean‑facing balconies.
- Residents’ pool, wellness studio, and secure parking.
- Coastal-inspired interiors with premium finishes.

**CTAs:**

- `Join priority list`
- `Register interest`

---

### 3.3 Griffith Quarter

- Status badge: `COMING SOON`
- Location: `Griffith, QLD`
- Facts line: `Urban village apartments · From $890K`

**Lifestyle paragraph:**

`Griffith Quarter is a new urban village bringing together contemporary apartments, landscaped green spaces, and neighbourhood dining in a connected, walkable address.`

**Amenities bullets:**

- Landscaped central park and resident terraces.
- Ground-floor retail and dining.
- Easy access to transport and key employment hubs.

**CTAs:**

- `Learn more`
- `Register interest`

---

## 4. Project Detail Navigation

Even if detailed project pages are not ready yet, plan the structure:

- Each project name and CTA should link to a future `project-detail.html` per development (or anchor sections on the same page initially). [web:37][web:39]
- Typical detail content:
  - Overview hero.
  - Apartment types & floorplans.
  - Amenities & lifestyle.
  - Location map.
  - Gallery.
  - Team (developer, architect, interior designer).
  - Enquiry form. [web:24][web:39]

---

## 5. Supporting Section: Why Buy Off‑the‑Plan with HAVEN

Add a trust/education section below the project cards.

**Section content:**

Heading: `Why buy off-the-plan with HAVEN?`

Bullets (or 3 pillars):

- `Curated developments` – We only partner with reputable developers and award‑winning design teams.  
- `Independent advice` – We help you compare projects, pricing, and timelines – not just sell a single development.  
- `End-to-end guidance` – From selection and contracts to settlement and leasing strategies.

Design:

- Use a background band style similar to “Why Haven” on the homepage. [web:6][web:16]
- Optionally include logos of developer partners or awards to build trust. [web:24][web:39]

---

## 6. Lead Capture & Contact

Because this page is high-intent, add a strong enquiry section.

**Section:**

Heading: `Register your interest`

Body:  
`Share your preferred locations, budget, and timing, and we’ll connect you with the right development and available residences.`

Fields (minimal):  
- Name  
- Email  
- Phone  
- Preferred city/area (select)  
- Budget range (select)  
- Message

Design:

- Use the same form styles as on Contact/“What is your home worth?” blocks. [web:39][web:42]
- Place this near the bottom, but also have “Register interest” buttons in each project card scroll to this form.

---

## 7. Footer Alignment

Current footer skeleton matches other pages but has empty link lists.

Populate with global links for consistency (same as home, properties, locations):

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

Ensure typography, color, spacing, and hover states match your design system. [web:5][web:41]

---

## 8. Design System Consistency

To keep `projects.html` aligned with `index.html`, `properties.html`, and `locations.html`: [web:6][web:12][web:16]

- **Typography**
  - Same heading levels and font stacks.
  - Project titles use same style as property card titles.

- **Color & Imagery**
  - Reuse primary accent color for status badges and CTAs.
  - Ensure project imagery has consistent grading and mood (luxury, calm).

- **Spacing & Layout**
  - Same section paddings and grid gutters as other pages.
  - Reuse card radius, shadows, and hover effects.

- **Interactions**
  - Consistent button states and scroll behaviour (e.g. smooth scroll to forms).

---

## 9. Future Enhancements

Once the basic structure is in place, you can add: [web:24][web:39]

- A “Project status” filter (`All · Now Selling · Coming Soon · Completed`).
- A small map highlighting each project’s location.
- Rich media per project (gallery slider, video walkthroughs, 3D tours).

---

End of spec.