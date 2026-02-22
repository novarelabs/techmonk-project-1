# ByteBites — Marking Rubric (100 Points)

This rubric is designed for consistent grading across cohorts.

---

## 1) Semantic HTML & Structure — 25 pts
**Excellent (21–25)**
- Semantic landmarks used correctly across pages
- Correct heading hierarchy (one `h1`, logical nesting)
- Clean, readable structure and consistent sectioning
- Navigation is consistent and correct everywhere

**Good (16–20)**
- Mostly semantic, minor issues (e.g., occasional div soup)
- Small heading mistakes but still usable

**Needs work (0–15)**
- Missing landmarks, incorrect structure, messy nesting
- Navigation inconsistent or broken links

---

## 2) Accessibility — 15 pts
**Excellent (13–15)**
- Skip link present + functional
- Labels correctly tied to inputs (`for` + `id`)
- Focus states clearly visible
- Reasonable contrast and usable form controls

**Good (9–12)**
- Labels present but minor issues
- Focus states exist but not consistent

**Needs work (0–8)**
- No labels or incorrect label usage
- No focus states
- Poor contrast or inaccessible structure

---

## 3) Vanilla CSS Quality — 25 pts
**Excellent (21–25)**
- Strong consistency (spacing, typography, components)
- Reusable classes (buttons/cards/grid/container)
- Clean file organization, not overly repetitive
- Makes good use of Flex/Grid without hacks

**Good (16–20)**
- Styling mostly consistent
- Some repetition or slightly messy organization

**Needs work (0–15)**
- Layout breaks, inconsistent spacing/typography
- Heavy reliance on fixed positioning/magic numbers
- Little reuse and difficult to maintain

---

## 4) Responsiveness — 20 pts
**Excellent (17–20)**
- Mobile-first works smoothly
- Grids collapse appropriately
- No horizontal scrolling
- Good spacing and readable text on mobile

**Good (12–16)**
- Mostly responsive, minor breakpoints issues

**Needs work (0–11)**
- Layout breaks on mobile/tablet
- Overflow issues and poor usability

---

## 5) Tailwind Refactor — 15 pts
**Excellent (13–15)**
- Tailwind version matches structure and layout intent of Vanilla
- Responsive utilities used properly
- Hover/focus states included
- No inline styles and minimal duplication

**Good (9–12)**
- Tailwind used correctly but inconsistent spacing/structure

**Needs work (0–8)**
- Tailwind misuse (random classes, not responsive, missing states)
- Heavy inline styles or broken layouts

---

# Bonus (Up to +10 pts)
Award bonus for:
- Deployment + working live URL (+3)
- Dark mode implementation (+2)
- Hamburger menu (basic JS) (+2)
- Menu filtering with JS (+2)
- Strong performance polish (image sizing, minimal DOM bloat) (+1)

> Total score can exceed 100 with bonus, but cap final grade if needed per program policy.