# Figma Design Prompt — Howard Stark Personal Website (With Images)

## Overview

Design a modern, minimalist two-page personal website for Howard Stark — an engineer and founder with a builder's mindset. The site should feel clean, confident, and professional while showcasing a journey from teenage maker to researcher and leader.

**NEW: Project images are now available in the `assets/` folder and linked in the markdown files.**

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
3. **High School Years** — Chronological project timeline by age with images (2012-2015)

---

## Images Available

**16 project images** organized in `assets/` folder by project name:

### Age 15 (2012)
- `assets/monster-truck/IMG_0009.JPG` — Monster Truck LED Add-ons

### Age 16 (2013)
- `assets/portable-fan/IMG_0171.JPG` — Portable Fan
- `assets/photo-frame/IMG_0089.JPG` — Photo Frame Gift
- `assets/arc-reactor/arc reactor labelled.jpg` — Arc Reactor Model
- `assets/aiesec/IMG_0067.JPG` — AIESEC Recognition
- `assets/led-beats-woofer/IMG_0801.JPG` — LED Beats Woofer (setup)
- `assets/led-beats-woofer/LED glow according to the beats.jpg` — LED Beats (effect)

### Age 17 (2014)
- `assets/photo-stand/Picture stand .jpg` — Photo Stand Gift
- `assets/usb-charger/28102012221.jpg` — Portable USB Charger
- `assets/solar-charger/19102012200.jpg` — Solar Panel Charger
- `assets/led-beats-portable/IMG_1975.JPG` — LED Beats Portable
- `assets/earphone-repair/03072013871.jpg` — Earphone Repair (Beats)
- `assets/infrared-camera/IMG_9857.JPG` — Infrared Camera (setup)
- `assets/infrared-camera/IMG_9867.JPG` — Infrared Camera (results)
- `assets/555-timer/27092012151.jpg` — 555 Timer Circuit

### Age 18 (2014-2015)
- `assets/robotics-workshop/25062013863.jpg` — Robotics Workshop

**Note:** These are authentic photos from Howard's original scholarship portfolio — teenage engineering projects from 2012-2015. They have a DIY, maker aesthetic that should be celebrated, not hidden.

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
- **No images on this page** — keep it clean and text-focused

### Section 2: My Ambition
- **Layout:** Centered content block, max-width ~800px
- **Heading:** "My Ambition" — bold, clear
- **Body text:** 2-3 paragraphs (see `page-1-home.md` for content)
- **CTA:** Subtle "See my work →" link at bottom, transitions to Projects page
- **Spacing:** Generous padding above/below section
- **No images** — text-focused section

---

## Page 2: Projects — Detailed Specs with Images

### Opening: Pattern Statement
- **Layout:** Brief intro paragraph, centered, max-width ~600px
- **Text:** "From toys to systems. From joy to impact. A timeline of building since age 15."
- **Style:** Italicized or visually distinct from body text
- **No images** — just the tagline

### College Years Section
**Visual treatment:**
- Featured prominently — larger cards or expanded layout
- Subsections: Research Publications, Leadership, Academic Recognition
- Consider timeline visual (vertical line with nodes) or card grid

**No images available for college years** — these are academic achievements without photos. Use text-based cards or clean, minimal layout. Could use placeholder icons or abstract graphics if needed.

**Content hierarchy:**
- Achievement title — bold, large
- Role/context — medium weight
- Description — body text
- Timeline/dates — small, subtle

### High School Years Section — **IMAGE INTEGRATION KEY**

**Visual treatment:**
- Grouped by age (Age 18, Age 17, Age 16, Age 15)
- Each project = card with image + text
- Images should feel authentic, not overly polished — these are DIY maker projects

**Image display options:**

**Option A: Card Grid Layout**
- Each project = card with image on left/top, text on right/bottom
- Image size: ~300-400px width on desktop, full width on mobile
- Hover effect: Subtle zoom or overlay with full description
- Grid: 2 columns on desktop, 1 column on mobile

**Option B: Timeline with Images**
- Vertical timeline with age markers on the left
- Projects alternate left/right with images
- Images: ~400-500px width, rounded corners or subtle shadow
- Text wraps around or appears on opposite side

**Option C: Gallery with Expandable Details**
- Compact image grid (thumbnails)
- Click to expand full project details + larger image
- Modal or slide-in panel with full story

**Recommendation:** Option A (Card Grid) — best balance of scannability and detail

**Image treatment:**
- Border radius: 8-12px (soften sharp edges)
- Subtle shadow or border (helps photos pop against background)
- Maintain aspect ratio (don't stretch/squash)
- Lazy load for performance
- Alt text for accessibility (use project title)

**Image quality note:**
These are photos from 2012-2015, taken with older cameras/phones. Some may have:
- Lower resolution
- Yellow/warm color cast
- DIY/unpolished look

**Don't try to hide this.** Embrace it — it's part of the authenticity. Light desaturation or consistent color grading is fine, but keep the maker aesthetic.

### Content hierarchy (per project card):
- **Image** — Primary visual anchor
- **Project title** — Bold, 18-22px
- **One-line description** — Brief, punchy
- **Age/year** — Small, subtle (e.g., "Age 17 • 2014")
- **Optional:** Expandable "Read more" for full story

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
- Images: Full width on mobile (with proper aspect ratio)
- Maintain readability and touch-friendly hit areas
- Simplify animations (performance)

---

## Technical Notes for Developer Handoff

- Smooth scroll behavior (CSS `scroll-behavior: smooth` or JS library)
- **Lazy load images** (use `loading="lazy"` attribute or Intersection Observer)
- Accessible (semantic HTML, ARIA labels, keyboard navigation)
- Image optimization:
  - Serve WebP with JPEG fallback
  - Responsive images (`srcset` for different screen sizes)
  - Compress without sacrificing quality (TinyPNG, ImageOptim)
- Fast load times (optimize assets, minimal dependencies)
- SEO-friendly (meta tags, Open Graph, structured data)

---

## Content Files

**Files available in the repository:**

1. **`page-1-home.md`** — Home page content (Intro quote + My Ambition section)
2. **`page-2-projects.md`** — Projects page content with image links embedded in markdown
3. **`timeline-draft.md`** — Full detailed timeline with context (reference material)
4. **`assets/` folder** — 16 project images organized by project name

**All images are already referenced in `page-2-projects.md` using markdown syntax:**
```markdown
![Project Name](assets/project-folder/image-name.jpg)
```

**How to use the images:**
1. Review `page-2-projects.md` to see which image goes with which project
2. Import images from `assets/` folder into Figma
3. Place images in project cards/timeline according to the markdown structure
4. Maintain the chronological order (Age 18 → Age 15)

---

## Deliverables Expected

1. **Figma file** with:
   - Desktop view (1440px width)
   - Tablet view (768px width)
   - Mobile view (375px width)
   - Component library (buttons, cards with images, typography styles)
   - Prototype with navigation flow, scroll interactions, and image hover states

2. **Design system notes:**
   - Color palette (hex codes)
   - Typography scale (font families, sizes, weights)
   - Spacing system (margins, padding)
   - Component specs (especially image card treatment)
   - Image treatment guidelines (border radius, shadows, hover effects)

3. **Developer handoff notes:**
   - Asset export requirements (image formats, sizes)
   - Animation/interaction specs
   - Responsive behavior notes
   - Image optimization recommendations

---

## Style References (Optional Inspiration)

- Minimalist portfolio sites (e.g., Awwwards winners in "Personal" category)
- Apple product pages (clean hierarchy, generous whitespace)
- Medium article layout (readable typography, centered content)
- Linear.app or Stripe marketing pages (modern, confident, clean)
- **For image galleries:** Dribbble designer portfolios, Behance project showcases

**Avoid:**
- Overly busy layouts
- Flashy, distracting animations
- Generic template aesthetics
- Poor readability (low contrast, tiny fonts)
- Over-processing the images (keep the authentic DIY aesthetic)

---

## Special Note on Images

These photos capture Howard's journey from age 15-18, building electronics projects with salvaged parts, soldering circuits on cardboard, and creating maker projects before "maker culture" was a thing. The authenticity is the story.

**Design philosophy for images:**
- Show them proudly — they're proof of a builder's mindset
- Clean presentation, but don't over-polish
- Let the images tell the story of progression: from toy truck LEDs → robotics with microcontrollers
- The evolution is the narrative arc

---

**Ready to design. All content and images are in the repository.**

GitHub repo: https://github.com/chapter37haptics/personal-website-adnanqzs.me
