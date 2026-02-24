# Figma Design Prompt — Howard Stark Personal Website

## Overview

Design a modern, minimalist two-page personal website for Howard Stark — an engineer and founder with a builder's mindset. The site should feel clean, confident, and professional while showcasing a journey from teenage maker to researcher and leader.

---

## Site Structure

### Page 1: Home
**Sections:**
1. **Hero/Intro** — Full-screen opening quote
2. **My Ambition** — Vision and philosophy section

### Page 2: Projects
**Sections:**
1. **Pattern Statement** — Brief opening that frames the narrative
2. **College Years** — Research, leadership, academic recognition (2013-2016)
3. **High School Years** — Chronological project timeline by age (2012-2015)

---

## Design Direction

**Visual Style:**
- Modern, minimalist, clean typography
- Generous whitespace
- Bold, confident hierarchy
- Subtle animations/transitions (scroll-triggered fade-ins, parallax effects)
- Professional but not corporate — shows personality

**Color Palette:**
- Neutral base (white/off-white background, dark charcoal text)
- Single accent color for emphasis (suggest: deep blue or burnt orange)
- High contrast for readability

**Typography:**
- Sans-serif for body text (clean, modern)
- Consider serif for the opening quote (gives weight and gravitas)
- Clear hierarchy: large headings, readable body text (16-18px minimum)

**Layout:**
- Single-column, full-width sections
- Smooth scroll between sections
- Sticky navigation (minimal, unobtrusive)
- Responsive design (mobile-first considerations)

---

## Page 1: Home — Detailed Specs

### Section 1: Hero/Intro
- **Layout:** Full viewport height, centered content
- **Quote text:** Large, prominent (suggest 32-48px desktop, 24-32px mobile)
- **Optional attribution:** Small, subtle text below quote
- **Background:** Clean, possibly subtle gradient or texture
- **Animation:** Fade-in on load

### Section 2: My Ambition
- **Layout:** Centered content block, max-width ~800px
- **Heading:** "My Ambition" — bold, clear
- **Body text:** 2-3 paragraphs (see markdown for content)
- **CTA:** Subtle "See my work →" link at bottom, transitions to Projects page
- **Spacing:** Generous padding above/below section

---

## Page 2: Projects — Detailed Specs

### Opening: Pattern Statement
- **Layout:** Brief intro paragraph, centered, max-width ~600px
- **Text:** "From toys to systems. From joy to impact. A timeline of building since age 15."
- **Style:** Italicized or visually distinct from body text

### College Years Section
**Visual treatment:**
- Featured prominently — larger cards or expanded layout
- Subsections: Research Publications, Leadership, Academic Recognition
- Consider timeline visual (vertical line with nodes) or card grid

**Content hierarchy:**
- Project/achievement title — bold, large
- Role/context — medium weight
- Description — body text
- Timeline/dates — small, subtle

### High School Years Section
**Visual treatment:**
- Grouped by age (Age 18, Age 17, Age 16, Age 15)
- Compact cards or list format
- Scannable — easy to skim
- Consider expandable/collapsible cards for detailed stories

**Content hierarchy:**
- Project title — bold
- One-line description — concise
- Optional: "Read more" expansion for full story

### Design Considerations:
- **Photos/videos:** Placeholder blocks where images could be inserted (from scholarship portfolio folders)
- **Tags/filters:** Optional — could filter by type (hardware, software, leadership, research)
- **Timeline visual:** Consider vertical timeline with age markers
- **Hover states:** Subtle interactions on cards (lift, shadow, color shift)

---

## Navigation

**Style:** Minimal, fixed/sticky header
- Logo/name on left: "Howard Stark" or "HS"
- Nav links on right: "Home" | "Projects"
- Mobile: Hamburger menu
- Smooth scroll to sections on same page
- Subtle indicator for active page

---

## Responsive Breakpoints

- **Desktop:** 1200px+
- **Tablet:** 768px - 1199px
- **Mobile:** < 768px

**Mobile considerations:**
- Stack sections vertically
- Reduce font sizes proportionally
- Maintain readability and touch-friendly hit areas
- Simplify animations (performance)

---

## Technical Notes for Developer Handoff

- Smooth scroll behavior (CSS `scroll-behavior: smooth` or JS library)
- Lazy load images (if photos added later)
- Accessible (semantic HTML, ARIA labels, keyboard navigation)
- Fast load times (optimize assets, minimal dependencies)
- SEO-friendly (meta tags, Open Graph, structured data)

---

## Content Files

**I will upload the following markdown files containing all content:**

1. **`page-1-home.md`** — Home page content (Intro quote + My Ambition section)
2. **`page-2-projects.md`** — Projects page content (College years + High school timeline)
3. **`timeline-draft.md`** — Full detailed timeline with context (reference material, not for display)

**Please wait for me to upload these files before proceeding with the design.**

Once uploaded, use the content exactly as written in the markdown files. The structure is already formatted for easy parsing.

---

## Deliverables Expected

1. **Figma file** with:
   - Desktop view (1440px width)
   - Tablet view (768px width)
   - Mobile view (375px width)
   - Component library (buttons, cards, typography styles)
   - Prototype with navigation flow and scroll interactions

2. **Design system notes:**
   - Color palette (hex codes)
   - Typography scale (font families, sizes, weights)
   - Spacing system (margins, padding)
   - Component specs

3. **Developer handoff notes:**
   - Asset export requirements
   - Animation/interaction specs
   - Responsive behavior notes

---

## Style References (Optional Inspiration)

- Minimalist portfolio sites (e.g., Awwwards winners in "Personal" category)
- Apple product pages (clean hierarchy, generous whitespace)
- Medium article layout (readable typography, centered content)
- Linear.app or Stripe marketing pages (modern, confident, clean)

**Avoid:**
- Overly busy layouts
- Flashy, distracting animations
- Generic template aesthetics
- Poor readability (low contrast, tiny fonts)

---

**Ready when you are. Please upload the markdown files and I'll proceed with the design.**
