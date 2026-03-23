
---

## `docs/MILESTONE_CHECKLIST.md`
```md
# ByteBites — Milestone Checklist

Use this checklist to guide development and to review student submissions.

---

## Milestone 1 — HTML Skeleton (Structure + Semantics)
### Global (All Pages)
- [ ] `<!doctype html>` present
- [ ] `<html lang="en">` present
- [ ] Proper meta tags: charset + viewport
- [ ] Navigation links work across pages
- [ ] Landmarks used: `header`, `nav`, `main`, `footer`
- [ ] Only one `h1` per page
- [ ] Logical heading order (`h1` → `h2` → `h3`)
- [ ] Skip-to-content link exists and works
- [ ] Images include `alt` text (or empty alt for decorative images)

### Home (`index.html`)
- [ ] Header/nav with logo + links + CTA
- [ ] Hero section with headline, supporting text, 2 CTAs
- [ ] Featured dishes section with 3+ items (cards)
- [ ] Testimonials section (2–3 quotes)
- [ ] Footer with basic info

### Menu (`menu.html`)
- [ ] Category tabs/filters (UI only)
- [ ] Specials banner
- [ ] Menu items list/grid (name, description, price)

### Contact (`contact.html`)
- [ ] Contact info block (email/phone/address)
- [ ] Map placeholder block
- [ ] Reservation form present

### Form requirements
- [ ] Each input has a `<label for="">` paired with an `id`
- [ ] Required fields marked using `required`
- [ ] Uses correct input types: `email`, `date`, `time`
- [ ] Button has `type="submit"`

---

## Milestone 2 — Vanilla CSS Styling (Layout + Responsive)
### Core Styling
- [ ] One stylesheet: `css/styles.css` linked on all pages
- [ ] Readable CSS structure (sections/comments encouraged)
- [ ] Consistent typography (font sizes/weights/line-height)
- [ ] Consistent spacing system (padding/margins not random)
- [ ] Buttons and cards styled consistently

### Layout
- [ ] Navbar layout built using Flexbox
- [ ] Featured dishes uses Grid/Flex
- [ ] Menu layout uses Grid/Flex
- [ ] Contact page uses a responsive 2-column layout on desktop

### Responsiveness
- [ ] Mobile-first layout works under 480px
- [ ] Layout adapts well around 768px and above
- [ ] No horizontal scrolling on mobile
- [ ] Images are responsive (`max-width:100%`)

### Accessibility
- [ ] Visible focus states for links/buttons/inputs
- [ ] Good contrast between text and background
- [ ] Form inputs are easy to use on mobile (spacing + sizing)

---

## Milestone 3 — Tailwind Refactor (Same UI, Utilities Only)
### Tailwind Setup
- [ ] Tailwind pages exist under `/tailwind`
- [ ] Tailwind included via CDN or CLI (CDN acceptable)
- [ ] No external CSS file used for Tailwind version (unless using Tailwind CLI build)

### Implementation
- [ ] Same sections/components exist as Vanilla version
- [ ] Responsive utilities used appropriately (`sm:`, `md:`, `lg:`)
- [ ] Proper layout utilities used (`flex`, `grid`, `gap`, `container` pattern)
- [ ] State styles exist (`hover:`, `focus:`)
- [ ] Avoids inline `style=""` in Tailwind version

### Accessibility
- [ ] Focus styles visible (`focus:`, `focus-visible:`)
- [ ] Form labels are present and connected properly

---

## Milestone 4 (Optional) — Polish + Deploy + Extensions
- [ ] Deployed link provided (Netlify/Vercel/GitHub Pages)
- [ ] Lighthouse improvements (optional)
- [ ] Add one extension (e.g. hamburger menu, dark mode, JS filtering)
- [ ] Project README updated with deployed URL and extension notes