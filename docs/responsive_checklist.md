# Responsiveness Testing Checklist
**Project**: Design Demo  
**Date**: May 16, 2026  
**Tester**: _____________  
**Browser**: _____________

---

## Testing Breakpoints
Test all items at these standard breakpoints:
- [ ] Mobile Small: 320px - 374px
- [ ] Mobile Medium: 375px - 424px
- [ ] Mobile Large: 425px - 767px
- [ ] Tablet Portrait: 768px - 1023px
- [ ] Tablet Landscape: 1024px - 1279px
- [ ] Desktop Small: 1280px - 1439px
- [ ] Desktop Medium: 1440px - 1919px
- [ ] Desktop Large: 1920px+

---

## 1. HTML Foundation

### Meta Tags
- [ ] Viewport meta tag present: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
- [ ] Charset meta tag present: `<meta charset="UTF-8">`
- [ ] No horizontal scrolling on any breakpoint
- [ ] Page title changes appropriately

---

## 2. Navigation Bar (Navbar)

### Structure & Layout
- [ ] Navbar visible on all breakpoints
- [ ] Logo displays correctly at all sizes
- [ ] Logo scales proportionally (not distorted)
- [ ] Menu items visible and accessible
- [ ] Navbar height appropriate for each breakpoint
- [ ] No overlapping elements
- [ ] Proper spacing between menu items

### Mobile Navigation (< 768px)
- [ ] Hamburger menu icon appears
- [ ] Hamburger icon is properly aligned (usually right side)
- [ ] Hamburger icon is touch-friendly (min 44x44px)
- [ ] Menu toggles open/close on click/tap
- [ ] Mobile menu displays full-width or slide-in
- [ ] Mobile menu items are vertically stacked
- [ ] Mobile menu items have adequate padding (min 12-15px)
- [ ] Active state visible when menu item tapped
- [ ] Menu closes when item selected
- [ ] Menu closes when clicking outside
- [ ] No horizontal overflow in mobile menu

### Tablet Navigation (768px - 1023px)
- [ ] Decide: Hamburger menu or full navbar?
- [ ] Menu items don't wrap awkwardly
- [ ] Adequate spacing between items
- [ ] Hover states work properly
- [ ] Dropdowns open correctly

### Desktop Navigation (1024px+)
- [ ] All menu items displayed horizontally
- [ ] Proper spacing and alignment
- [ ] Hover effects work smoothly
- [ ] Active page indicator visible
- [ ] Dropdown menus (if any) function correctly
- [ ] Dropdown menus don't go off-screen

### Sticky/Fixed Navbar (if applicable)
- [ ] Navbar stays fixed on scroll
- [ ] Smooth scroll behavior
- [ ] Content doesn't jump when navbar becomes sticky
- [ ] Sticky navbar height consistent
- [ ] Z-index prevents content overlap
- [ ] Background color/opacity appropriate when sticky

### Navbar Interactions
- [ ] All links clickable/tappable
- [ ] Touch targets minimum 44x44px on mobile
- [ ] Hover states visible (desktop)
- [ ] Focus states visible (keyboard navigation)
- [ ] Active states clear and distinguishable
- [ ] Transitions smooth (not janky)

---

## 3. Typography

### Headings (H1 - H6)
- [ ] H1 readable on mobile (min 24px recommended)
- [ ] H1 scales up appropriately on desktop
- [ ] H2-H6 maintain hierarchy at all sizes
- [ ] Line height appropriate (1.2-1.5 for headings)
- [ ] No text overflow or wrapping issues
- [ ] Headings don't break awkwardly

### Body Text
- [ ] Body text minimum 16px on mobile
- [ ] Line height comfortable (1.5-1.8 for body)
- [ ] Paragraph width max 60-80 characters
- [ ] Text color has sufficient contrast (WCAG AA: 4.5:1)
- [ ] No horizontal scrolling needed to read text
- [ ] Text doesn't touch screen edges (adequate padding)

### Links
- [ ] Links easily tappable on touch devices
- [ ] Link color distinguishable from body text
- [ ] Hover states work on desktop
- [ ] Active/visited states appropriate
- [ ] Underlines or clear visual indicators present

---

## 4. Images & Media

### Images
- [ ] All images load at appropriate sizes
- [ ] Images scale proportionally (no distortion)
- [ ] Images don't overflow containers
- [ ] Alt text present for accessibility
- [ ] Lazy loading implemented (if applicable)
- [ ] High-resolution images for retina displays
- [ ] Different image sizes served for mobile vs desktop

### Background Images
- [ ] Background images scale correctly
- [ ] Background-size: cover/contain used appropriately
- [ ] Background position correct at all breakpoints
- [ ] Text over backgrounds remains readable
- [ ] Background images don't cause performance issues

### Videos
- [ ] Videos responsive (width: 100%, height: auto)
- [ ] Video containers maintain aspect ratio
- [ ] Embedded videos (YouTube, Vimeo) responsive
- [ ] Video controls accessible on mobile
- [ ] Autoplay disabled on mobile (data consideration)

### Icons & SVGs
- [ ] Icons scale without pixelation
- [ ] Icon sizes appropriate for touch (min 44x44px target)
- [ ] Icons maintain aspect ratio
- [ ] Icon fonts load correctly

---

## 5. Layout & Grid

### Container/Wrapper
- [ ] Max-width set for large screens
- [ ] Containers centered properly
- [ ] Padding/margins appropriate at all sizes
- [ ] No horizontal overflow

### Grid System
- [ ] Columns stack on mobile as intended
- [ ] Grid gaps appropriate for each breakpoint
- [ ] Equal height columns (if required) work correctly
- [ ] Grid doesn't break at edge cases (e.g., 769px)
- [ ] Flexbox/Grid fallbacks for older browsers

### Sections
- [ ] Section padding scales appropriately
- [ ] Content doesn't touch screen edges on mobile
- [ ] Minimum 16-24px padding on mobile
- [ ] Sections maintain visual hierarchy
- [ ] Background colors/images work at all sizes

### Spacing
- [ ] Consistent spacing system used (e.g., 8px grid)
- [ ] Margins between sections appropriate
- [ ] Padding inside containers adequate
- [ ] No overlapping content at any breakpoint

---

## 6. Forms

### Form Structure
- [ ] Forms stack vertically on mobile
- [ ] Form width comfortable (not too wide on desktop)
- [ ] Form fields full-width on mobile
- [ ] Labels visible and associated with inputs

### Input Fields
- [ ] Input fields minimum 44px height (touch-friendly)
- [ ] Input text size minimum 16px (prevents zoom on iOS)
- [ ] Adequate padding inside inputs
- [ ] Input borders clearly visible
- [ ] Focus states clearly indicated
- [ ] Error messages visible and readable

### Buttons
- [ ] Buttons minimum 44x44px (touch targets)
- [ ] Button text readable at all sizes
- [ ] Hover states work on desktop
- [ ] Active states visible on tap
- [ ] Disabled states clearly indicated
- [ ] Buttons don't wrap text awkwardly
- [ ] Submit buttons easy to tap on mobile

### Validation
- [ ] Error messages display correctly on mobile
- [ ] Success messages visible
- [ ] Inline validation doesn't break layout

---

## 7. Buttons & CTAs

### Size & Spacing
- [ ] All buttons minimum 44x44px on mobile
- [ ] Adequate spacing between multiple buttons
- [ ] Button text doesn't overflow
- [ ] Icons in buttons scale appropriately

### States
- [ ] Default state clearly visible
- [ ] Hover state works (desktop)
- [ ] Active/pressed state on tap (mobile)
- [ ] Focus state for keyboard navigation
- [ ] Disabled state distinguishable
- [ ] Loading state (if applicable) works

### Positioning
- [ ] CTAs visible without scrolling (above fold)
- [ ] Fixed/sticky CTAs don't overlap content
- [ ] Button groups stack appropriately on mobile

---

## 8. Tables

### Mobile Tables (< 768px)
- [ ] Tables don't overflow horizontally
- [ ] Tables collapse/stack on mobile OR
- [ ] Horizontal scroll enabled with visual indicator
- [ ] Table text readable (not too small)
- [ ] Alternative layouts for complex tables

### Desktop Tables
- [ ] Column widths appropriate
- [ ] Headers clearly visible
- [ ] Row zebra striping (if used) visible
- [ ] Sortable columns work (if applicable)

---

## 9. Cards & Components

### Card Layouts
- [ ] Cards stack on mobile (1 column)
- [ ] Cards arrange in 2 columns on tablet
- [ ] Cards arrange in 3-4 columns on desktop
- [ ] Card heights equal (if required)
- [ ] Card content doesn't overflow
- [ ] Images in cards responsive

### Modals/Popups
- [ ] Modals scale to viewport on mobile
- [ ] Modal padding adequate on small screens
- [ ] Modal close button easily tappable
- [ ] Modal content scrollable if too tall
- [ ] Background overlay covers entire screen

### Accordions
- [ ] Accordion headers touch-friendly (44px min)
- [ ] Content expands smoothly
- [ ] Icons indicate open/closed state
- [ ] Content readable when expanded

### Carousels/Sliders
- [ ] Touch swipe works on mobile
- [ ] Navigation arrows accessible
- [ ] Pagination dots visible and tappable
- [ ] Auto-play disabled on mobile (optional)
- [ ] Carousel doesn't break layout on any size

---

## 10. Footer

### Structure
- [ ] Footer content stacks appropriately on mobile
- [ ] Footer links easily tappable (44px targets)
- [ ] Footer stays at bottom of page
- [ ] Footer columns reorganize for mobile (1 column)
- [ ] Footer columns arrange nicely on tablet/desktop

### Content
- [ ] Social media icons sized appropriately
- [ ] Contact info readable and clickable (tel:, mailto:)
- [ ] Copyright text visible
- [ ] Footer navigation accessible
- [ ] Newsletter signup (if any) responsive

---

## 11. Performance

### Loading
- [ ] Page loads in under 3 seconds on 3G
- [ ] Above-fold content loads first
- [ ] Images optimized for web
- [ ] CSS/JS minified
- [ ] No render-blocking resources

### Interactions
- [ ] Smooth scrolling (60fps)
- [ ] No janky animations
- [ ] Hover effects performant
- [ ] Transitions smooth
- [ ] No layout shifts during load (CLS)

---

## 12. Cross-Browser Testing

### Chrome
- [ ] Mobile (DevTools)
- [ ] Tablet (DevTools)
- [ ] Desktop

### Firefox
- [ ] Mobile (Responsive Design Mode)
- [ ] Desktop

### Safari
- [ ] iPhone (actual device or simulator)
- [ ] iPad
- [ ] Desktop

### Edge
- [ ] Mobile
- [ ] Desktop

---

## 13. Real Device Testing

### Mobile Devices
- [ ] iPhone SE (375px)
- [ ] iPhone 12/13/14 (390px)
- [ ] iPhone 14 Pro Max (430px)
- [ ] Samsung Galaxy S21 (360px)
- [ ] Samsung Galaxy S21 Ultra (412px)
- [ ] Google Pixel 5 (393px)

### Tablets
- [ ] iPad (768px)
- [ ] iPad Pro (1024px)
- [ ] Samsung Galaxy Tab

---

## 14. Accessibility (a11y)

### Keyboard Navigation
- [ ] Tab through all interactive elements
- [ ] Focus indicators visible
- [ ] Skip to main content link present
- [ ] Logical tab order
- [ ] No keyboard traps

### Screen Readers
- [ ] Alt text on all images
- [ ] ARIA labels where needed
- [ ] Headings properly structured (H1 → H2 → H3)
- [ ] Form labels associated with inputs
- [ ] Button/link text descriptive

### Color & Contrast
- [ ] Text contrast ratio meets WCAG AA (4.5:1)
- [ ] Color not sole indicator of information
- [ ] Focus indicators visible

---

## 15. Orientation Testing

### Portrait Mode
- [ ] All features work in portrait
- [ ] Layout optimized for portrait
- [ ] No horizontal scrolling

### Landscape Mode
- [ ] All features work in landscape
- [ ] Layout adapts appropriately
- [ ] Content doesn't get cut off
- [ ] Fixed headers/footers don't take too much space

---

## 16. Edge Cases

### Very Long Content
- [ ] Long menu item names don't break navbar
- [ ] Long headings wrap appropriately
- [ ] Long paragraphs don't overflow
- [ ] Long URLs break or truncate gracefully

### Very Short Content
- [ ] Footer stays at bottom on short pages
- [ ] Layout doesn't look empty
- [ ] Centered content still centered

### No JavaScript
- [ ] Site usable without JavaScript
- [ ] Critical features accessible
- [ ] Mobile menu has fallback
