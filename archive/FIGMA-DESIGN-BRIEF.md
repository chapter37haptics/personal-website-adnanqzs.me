# Figma Design Brief — Personal Website (Updated)

## Overview
Modern, minimalist two-page personal website for Howard Stark — engineer, founder, and lifelong builder.

---

## PAGE 1: HOME — Redesigned Layout

### Layout Structure: Quad Grid

**Full page split into 4 equal quadrants:**

```
┌──────────────────┬──────────────────┐
│  TOP LEFT        │  TOP RIGHT       │
│  Quote           │  Photo + Bio     │
│  (Quadrant 1)    │  (Quadrant 2)    │
├──────────────────┼──────────────────┤
│  BOTTOM LEFT     │  BOTTOM RIGHT    │
│  My Ambition     │  Photo/Visual    │
│  (Quadrant 3)    │  (Quadrant 4)    │
└──────────────────┴──────────────────┘
```

---

### Quadrant 1: Quote (Top Left)

**Content:**
> "The reasonable man adapts himself to his surroundings. The unreasonable man adopts the surroundings to himself. All progress depends on the unreasonable man. Invest wisely, invest in yourself."

**Design:**
- **Size:** Exactly 1/4 of viewport (50% width, 50% height)
- **Typography:** Medium size (24-32px, NOT oversized)
- **Style:** Serif or bold sans-serif for emphasis
- **Background:** Subtle texture or solid color
- **Padding:** Comfortable margins, quote should breathe
- **Optional:** Small attribution text below quote

---

### Quadrant 2: Photo + Short Bio (Top Right)

**Content:**
- **Image:** Personal photo of Howard (will be provided in `assets/personal-photos/`)
- **Name:** Howard Stark
- **One-liner:** Engineer turned founder building [current project]
- **Quick facts:** 
  - MS in Machine Learning & Robotics — UCSD
  - BS in Electrical Engineering — American University of Sharjah
  - 5 years in tech (2simple, TikTok)

**Design:**
- Photo: Circular or rounded square, 200-300px
- Text: Clean, minimal, left or center-aligned
- Layout: Photo above text OR photo left, text right
- Background: Clean white or subtle gradient

---

### Quadrant 3: My Ambition (Bottom Left)

**Content:**
I've been a builder since I was a kid — building my own toys, then bigger and better things. There's always a "why" behind what I build. Initially, the why was simple: personal joy. Building for the sake of building.

Now the why has evolved. I've learned that solving real problems gives me a double bonus: the joy of building something meaningful AND the satisfaction of adding value to someone else's life. That's the sweet spot.

My ambition is to have the time and resources to keep building. To learn new tools that help me tackle bigger challenges. To work with people who share that drive — collaborating to create solutions that matter, at a scale none of us could reach alone.

**Design:**
- Paragraph format, max-width ~500px
- Heading: "My Ambition" — bold, 24-28px
- Body text: 16-18px, comfortable line-height
- Background: Different shade/color from other quadrants
- CTA at bottom: "See my work →" button/link

---

### Quadrant 4: Photo/Visual (Bottom Right)

**Content:**
- **Option A:** Another personal photo (candid, working, building something)
- **Option B:** Collage of 2-3 small project photos
- **Option C:** Visual timeline graphic showing progression (Age 15 → Now)

**Design:**
- Full bleed or with padding
- Image should complement Quadrant 2
- Can be artistic/abstract — show personality
- No text overlay (keep it visual)

---

### Responsive Behavior (Mobile)

On mobile (<768px), quadrants stack vertically:
1. Quote (full width)
2. Photo + Bio (full width)
3. My Ambition (full width)
4. Photo/Visual (full width)

---

## PAGE 2: PROJECTS — Two-Column Layout

### Structure

**Opening statement:**
"From toys to systems. From joy to impact. A timeline of building since age 15."
- Centered, above all content
- Max-width ~700px

---

### College Years Section (2013-2016)
**Layout:** Single column, text-only cards
- Research Publications (2 items)
- Leadership (1 item)
- Academic Recognition (4 items)

**Design:**
- Clean cards with subtle borders or shadows
- Larger, featured treatment
- Icon or badge for each category (optional)

---

### High School Years Section (2012-2015)
**Layout:** TWO-COLUMN GRID

```
┌───────────────────┬───────────────────┐
│  Project Card 1   │  Project Card 2   │
├───────────────────┼───────────────────┤
│  Project Card 3   │  Project Card 4   │
├───────────────────┼───────────────────┤
│  Project Card 5   │  Project Card 6   │
└───────────────────┴───────────────────┘
```

**Each Project Card:**
```
┌─────────────────────────────┐
│  [Image Carousel/Gallery]   │  ← If 3+ images
│  OR [Single/Dual Image]     │  ← If 1-2 images
├─────────────────────────────┤
│  Project Title              │
│  Age X • Year               │
│  Short description...       │
└─────────────────────────────┘
```

**Card specs:**
- Width: ~45-48% of container (with gap between)
- Gap between cards: 24-32px
- Image height: 250-350px
- Border radius: 12px
- Subtle shadow on hover

**For multi-image projects:**
- Use carousel/slider (dots or arrows)
- OR show first image with "+N more" indicator
- Clicking opens lightbox/gallery

---

### Grouping by Age

Visual separation between age groups:
- Large heading: "Age 18 (2014-2015)"
- Horizontal line or spacing above/below
- All Age 18 projects, then Age 17, etc.

---

### Responsive Behavior (Mobile)

On mobile (<768px):
- Switch to single column
- Cards stack vertically
- Full-width images
- Maintain carousel for multi-image projects

---

## Design Specifications

### Color Palette
- **Background:** White or off-white (#FAFAFA)
- **Text:** Dark charcoal (#2C2C2C)
- **Accent color:** Deep blue (#1E3A8A) OR burnt orange (#EA580C)
- **Borders/shadows:** Subtle gray (#E5E5E5)

### Typography
- **Headings:** Bold sans-serif (Inter, Poppins, or similar)
- **Quote:** Serif (Merriweather, Playfair) OR bold sans-serif
- **Body:** Sans-serif, 16-18px, line-height 1.6
- **Project titles:** 20-24px bold
- **Age/year labels:** 14px, medium weight, gray

### Spacing
- **Quadrant padding:** 40-60px
- **Card padding:** 24-32px
- **Grid gap:** 24-32px
- **Section spacing:** 80-120px between major sections

### Images
- **Border radius:** 8-12px
- **Shadow:** `0 2px 12px rgba(0,0,0,0.08)`
- **Hover effect:** Subtle lift (`translateY(-4px)`) + stronger shadow
- **Maintain aspect ratios**
- **Lazy load for performance**

---

## Image Assets

### Personal Photos (Home Page)
**Location:** `assets/personal-photos/`
- Howard will provide photos for Quadrants 2 & 4
- Suggest: 1 professional/headshot, 1 candid/working

### Project Photos (Projects Page)
**Location:** `assets/`
- 48 images total across 17 projects
- Named: `project-name_1.jpg`, `project-name_2.jpg`, etc.
- See `image-mapping-for-figma.md` for complete list

**Multi-image projects (use carousels):**
- Photo Frame Gift: 7 images
- LED Beats Woofer: 5 images
- Infrared Camera: 5 images
- Solar Panel Charger: 4 images
- Earphone Repair, USB Charger, PSP Charger, Photo Stand: 3 images each

---

## Navigation

**Style:** Minimal sticky header
- Logo/name: "Howard Stark" (left)
- Nav links: "Home" | "Projects" (right)
- Background: Semi-transparent with blur on scroll
- Mobile: Hamburger menu

---

## Responsive Breakpoints

- **Desktop:** 1200px+ (quad grid on home, two-column on projects)
- **Tablet:** 768-1199px (quad grid or stacked, single column projects)
- **Mobile:** <768px (all content stacks vertically)

---

## Key Design Principles

1. **Whitespace is your friend** — Don't cram content
2. **Hierarchy is clear** — Important things are bigger/bolder
3. **Images breathe** — Proper padding around all visuals
4. **Authentic over polished** — Project photos are DIY maker aesthetic, embrace it
5. **Consistent spacing** — Use 8px base grid system
6. **Hover states matter** — Subtle interactions make it feel alive

---

## Content Files Reference

- `page-1-home.md` — Full text for home page quadrants
- `page-2-projects.md` — All project descriptions with image links
- `image-mapping-for-figma.md` — Complete image inventory (48 images)
- `assets/personal-photos/` — Howard's personal photos (to be added)
- `assets/` — All 48 project images

---

## Deliverables

1. **Figma file** with:
   - Desktop view (1440px)
   - Tablet view (768px)
   - Mobile view (375px)
   - All states: default, hover, active
   - Component library

2. **Prototype** with:
   - Navigation flow (Home ↔ Projects)
   - Scroll interactions
   - Image carousel/lightbox interactions
   - Smooth transitions

3. **Design system notes:**
   - Color tokens
   - Typography scale
   - Spacing tokens
   - Component specs

4. **Developer handoff:**
   - Asset export guide
   - Animation specs
   - Responsive behavior notes

---

## Summary of Changes from Previous Design

### Home Page
- ❌ **Old:** Full-screen quote taking up entire viewport
- ✅ **New:** Quad grid layout (quote = 1/4 page)
- ➕ **Added:** Personal photos in Quadrants 2 & 4
- ➕ **Added:** Short bio in Quadrant 2
- **Result:** More balanced, shows personality, less empty space

### Projects Page
- ❌ **Old:** Wide single-column or unspecified layout
- ✅ **New:** Two-column grid for high school projects
- **Result:** More scannable, better use of space, fits more per screen

### Image Handling
- 📈 **Increased:** From 16 to 48 project images
- ➕ **Added:** Image carousels for multi-image projects
- **Result:** Shows full maker journey, all available photos

---

**Ready to design with complete specifications.**
