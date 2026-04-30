# MC Tech — Compressed Air Systems Website

## 1. Concept & Vision

MC Tech is a professional industrial B2B website selling compressed air systems (compressors, dryers, filters, full systems). The vibe is **bold industrial confidence** — clean, modern, powerful like machinery itself. Think premium factory equipment catalog meets sleek tech startup. It should feel trustworthy and engineering-sharp, not flashy or playful.

## 2. Design Language

**Aesthetic:** Industrial engineering — dark steel blues, clean whites, electric cyan accents. Bold geometric shapes. Think hydraulic precision.

**Colors:**
- Primary: `#0B1929` (deep navy — authority)
- Secondary: `#1E3A5F` (steel blue — industrial)
- Accent: `#00C2FF` (electric cyan — energy/air)
- Background: `#F5F7FA` (clean light grey)
- Dark bg sections: `#0B1929`
- Text primary: `#0B1929`
- Text light: `#FFFFFF`

**Typography:**
- Headings: 'Rajdhani', sans-serif (geometric, industrial)
- Body: 'Inter', sans-serif (clean readability)

**Motion:**
- Scroll-triggered fade-up animations
- Subtle hover lifts on cards (+translateY, shadow)
- Cyan glow pulse on CTA buttons
- Smooth section reveals

**Icons:** Lucide icons (SVG-based, clean lines)

## 3. Layout & Structure

Single-page scrolling site:

1. **Hero** — Full-width dark section, bold headline, tagline, CTA button, hero image/visual
2. **Products** — 4 product cards: Oil-Injected Compressors, Oil-Free Compressors, Refrigerated Dryers, Adsorption Dryers
3. **Applications** — 6 industry icons with labels (Power, Medical, Food, Industrial, Agriculture, Petrochemical)
4. **Why MC Tech** — 3 trust pillars: Quality, Efficiency, Service
5. **Contact** — Phone number prominently displayed, call-to-action, WeChat hint
6. **Footer** — Company name, tagline, copyright

## 4. Features & Interactions

- Smooth scroll navigation
- Product cards with hover lift + cyan glow border
- "Call Now" button triggers `tel:` link
- Responsive: mobile-first, stacks on small screens
- No backend — pure static HTML/CSS/JS

## 5. Component Inventory

**Hero Section:**
- Dark navy background with subtle geometric pattern
- H1: "Power Your Industry With Clean Compressed Air"
- Subtext about MC Tech value
- CTA: "Contact Us Today" → scrolls to contact section

**Product Card:**
- White card, subtle shadow
- Icon, product name, specs range, short description
- Hover: lift + cyan border glow

**Application Icon:**
- Circle with icon, label below
- 6 items in responsive grid

**Trust Pillar:**
- Large number/stat, bold label, description

**Contact Section:**
- Dark bg
- Phone number in large bold text
- "Tap to call" hint
- WeChat icon hint

## 6. Technical Approach

- Pure HTML5 + CSS3 + Vanilla JS
- Google Fonts (Rajdhani + Inter)
- Lucide icons via CDN
- CSS custom properties for theming
- No build tools needed — deploy straight to GitHub Pages
