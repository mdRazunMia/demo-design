# HAVEN – Our Team Page UX & Content Spec

This document defines the UX, layout, and copy direction for `team.html`, turning it into a high‑trust “Meet the Team” page that showcases HAVEN’s advisors and their track record. [web:5][web:51][web:53][web:56]

---

## 1. Page Hero & Intro

**Current:**

- Eyebrow: `MEET THE TEAM`
- H1: `Our ExpertAdvisors`
- Subheading: `Industry veterans with decades of combined experience in luxury property.`

**Issues:**

- Missing space: `ExpertAdvisors`.
- Hero is minimal; could better communicate trust, scale, and specialisation, as seen in strong real‑estate team pages. [web:51][web:56]

**Proposed structure:**

- Eyebrow: `MEET THE TEAM`
- H1: `Our Expert Advisors`
- Subheading:  
  `Industry-leading specialists with decades of experience in prestige homes, penthouses, and investment property across Australia.`

**Design notes:**

- Reuse homepage hero typography and spacing (same H1 size, alignment). [web:5]
- Consider a subtle background: group/team shot, or a blurred office/boardroom image that supports a professional, high‑trust feel. [web:51][web:56]
- Optionally add a micro‑CTA in hero: `Speak with an advisor` → scrolls to a contact/consultation form at the bottom.

---

## 2. Team Grid Layout

**Current content:**

- Sophia Chen – SENIOR ADVISOR — SYDNEY – $240M+ in Sales
- Marcus Webb – PRINCIPAL — MELBOURNE – $180M+ in Sales
- Isabelle Park – ADVISOR — BRISBANE – $95M+ in Sales
- James Howell – INVESTMENT SPECIALIST – $320M+ in Sales

**Recommended pattern:**

Create a team grid with consistent cards for each advisor.

Each card should include: [web:53][web:56]

- High‑quality portrait photo.
- Name: `Sophia Chen`
- Title & market: `Senior Advisor — Sydney`
- Key metric: `$240M+ in sales`
- Short bio (2–3 sentences).
- Contact actions: `Email · Call · View profile` (even if some are placeholders initially).

**Design notes:**

- Use a 2×2 grid on desktop, 1 column on mobile.
- Keep images consistent in framing/background to look polished and cohesive. [web:53][web:56]
- Card styling should reuse your global card design (radius, shadow, spacing).

---

## 3. Example Bios & Card Content

Use concise, luxury‑oriented bios that speak to credibility and specialisation. [web:52][web:55][web:56]

### 3.1 Sophia Chen

- Title: `Senior Advisor — Sydney`
- Metric: `$240M+ in sales`

**Bio sample:**

`Sophia specialises in prestige homes across Sydney’s Lower North Shore and Eastern Suburbs. Known for her calm negotiation style and deep suburb knowledge, she has guided executives, entrepreneurs, and families through some of the city’s most significant transactions.`

Actions:

- `Email Sophia`
- `Call Sophia`
- Optional: `View recent sales`

---

### 3.2 Marcus Webb

- Title: `Principal — Melbourne`
- Metric: `$180M+ in sales`

**Bio sample:**

`As HAVEN’s Melbourne Principal, Marcus leads sales in Toorak, South Yarra, and surrounding blue-chip suburbs. His background in finance and long-standing relationships with developers and family offices underpin his reputation for record-setting results.`

Actions:

- `Email Marcus`
- `Call Marcus`
- Optional: `View Melbourne team`

---

### 3.3 Isabelle Park

- Title: `Advisor — Brisbane`
- Metric: `$95M+ in sales`

**Bio sample:**

`Isabelle focuses on riverfront homes and premium apartments in Brisbane’s inner-city suburbs. Clients value her transparent advice, detailed market insight, and ability to uncover opportunities before they reach the open market.`

Actions:

- `Email Isabelle`
- `Call Isabelle`
- Optional: `View Brisbane listings`

---

### 3.4 James Howell

- Title: `Investment Specialist`
- Metric: `$320M+ in transactions`

**Bio sample:**

`James advises private investors and family offices on acquisitions and divestments across Sydney, Melbourne, and Brisbane. With a background in institutional investment, he provides portfolio-level strategies that balance yield, growth, and risk.`

Actions:

- `Email James`
- `Call James`
- Optional: `Discuss investment strategy`

---

## 4. “Our Approach” / Culture Section

Add a small section that explains how the team works and reinforces trust. [web:51][web:56]

**Section content:**

Heading: `Our approach`

Short paragraph:  
`HAVEN advisors work as a single, connected team – sharing insight across cities, coordinating off‑market opportunities, and collaborating on complex transactions. You’re supported by the full strength of our network, not just one individual.`

Optional bullets:

- `Collaborative, cross‑city advisory`
- `Discreet representation for high‑profile clients`
- `Data‑driven insights combined with local knowledge`

Design:

- Band with a slightly different background, similar to “Why Haven” styling.

---

## 5. Trust & Social Proof Elements

To match top luxury brokerage sites, add additional proof near or within the team page. [web:51][web:53][web:56]

Ideas:

- **Combined stats strip:**
  - `600M+` in combined sales.
  - `20+` years average advisor experience.
  - `3` capital cities covered.

- **Client quote snippet:**
  - One short testimonial referencing how a specific advisor or the team made a complex transaction smooth.

Design:

- Use a KPI strip similar to the homepage (numbers + short labels).
- Place just below hero or above the team grid.

---

## 6. Contact / Consultation CTA

Team pages usually perform well as entry points for enquiries; add a consultation CTA. [web:51][web:56]

**Section:**

Heading: `Work with our team`

Body:  
`Tell us a little about your goals and we’ll connect you with the advisor best suited to your needs.`

Form fields:

- Name  
- Email  
- Phone  
- City / Preferred location (select)  
- Service of interest (Buyer’s Advisory, Selling, Investment, Management, International)  
- Message

Design:

- Reuse the form and button styles from your Contact/Services pages for consistency.
- Place this near the bottom of the page, above the footer.

---

## 7. Footer Alignment

Populate footer lists to match other pages and the global design system. [web:5]

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

---

## 8. Design System Consistency

To keep `team.html` aligned with the rest of HAVEN: [web:5][web:31][web:53][web:56]

- **Typography**
  - Same hero H1 style as Home/Services.
  - Advisor names use a consistent heading level (e.g. H3) and weight.
  - Titles and city tags use consistent label styling.

- **Colour & Imagery**
  - Use brand accent for small elements (e.g. dividers, icons, hover states).
  - Ensure all headshots have similar backgrounds/lighting for a unified look.

- **Layout & Spacing**
  - Same section paddings and grid gutters as other pages.
  - Card radius and shadows match property and service cards.

- **Interactions**
  - Hover effects on advisor cards (slight elevation, subtle shadow) to signal clickability.
  - Email/phone links use consistent interaction styles (colour change/underline).

---

End of spec.