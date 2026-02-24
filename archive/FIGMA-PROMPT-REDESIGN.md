# Figma Redesign Instructions

## Key Changes to Existing Design

### 1. HOME PAGE — Quad Grid Layout (MAJOR CHANGE)

**OLD:** Full-screen quote taking entire viewport  
**NEW:** 4 equal quadrants (2x2 grid)

```
┌──────────────────┬──────────────────┐
│  Quote           │  Photo + Bio     │
│  (1/4 page)      │  (1/4 page)      │
│  24-32px text    │  Headshot +      │
│  NOT oversized   │  short bio       │
├──────────────────┼──────────────────┤
│  My Ambition     │  Visual/Photo    │
│  (1/4 page)      │  (1/4 page)      │
│  3 paragraphs    │  Candid or       │
│  + CTA button    │  collage         │
└──────────────────┴──────────────────┘
```

**Quote size:** Medium (24-32px) — takes 1/4 of page, not full screen  
**Personal photos:** 2 needed (headshot + candid/working) — location: `assets/personal-photos/`  
**Mobile:** Stack all 4 quadrants vertically

---

### 2. PROJECTS PAGE — Two-Column Grid (MAJOR CHANGE)

**OLD:** Wide single-column or undefined layout  
**NEW:** Two-column grid for high school projects

```
┌───────────────────┬───────────────────┐
│  Project Card 1   │  Project Card 2   │
│  [Image carousel] │  [Image carousel] │
│  Title + desc     │  Title + desc     │
├───────────────────┼───────────────────┤
│  Project Card 3   │  Project Card 4   │
└───────────────────┴───────────────────┘
```

**Card width:** ~45-48% of container  
**Gap:** 24-32px between columns  
**Image height:** 250-350px per card  
**Mobile:** Single column (cards stack)

**Projects with 3+ images:** Use carousel/slider in each card  
**Projects with 1-2 images:** Show all images

---

### 3. Image Assets

**Home page:**
- 2 personal photos (Howard will provide) in `assets/personal-photos/`
- Quadrant 2: Headshot (circular or rounded square, 200-300px)
- Quadrant 4: Candid/working photo OR visual collage

**Projects page:**
- 48 project images in `assets/` folder
- All named: `project-name_1.jpg`, `project-name_2.jpg`, etc.
- See `image-mapping-for-figma.md` for complete list

**Multi-image projects (use carousels):**
- Photo Frame: 7 images
- LED Beats Woofer: 5 images
- Infrared Camera: 5 images
- Solar Charger: 4 images
- Several projects: 3 images each

---

## Quick Implementation Checklist

**Home Page:**
- [ ] Resize quote section to 1/4 page (top-left quadrant)
- [ ] Reduce quote text size to 24-32px (currently too big)
- [ ] Add Quadrant 2 (top-right): photo placeholder + bio text
- [ ] Add Quadrant 3 (bottom-left): My Ambition text + CTA button
- [ ] Add Quadrant 4 (bottom-right): photo placeholder or visual

**Projects Page:**
- [ ] Change high school projects from single/wide to two-column grid
- [ ] Ensure college section stays single column (text-only)
- [ ] Add image carousels for projects with 3+ images
- [ ] Adjust card sizing to fit two per row

**General:**
- [ ] Upload 48 project images from `assets/` folder
- [ ] Create placeholders for 2 personal photos (to be added)
- [ ] Update mobile breakpoints (stack quadrants, single column projects)

---

## Full Details

See `FIGMA-DESIGN-BRIEF.md` for complete specifications:
- Detailed quadrant content
- Typography scales
- Color palette
- Spacing tokens
- Responsive behavior
- All design principles

---

## Summary

**Problem:** Quote too big, home page too sparse, projects layout too wide  
**Solution:** Quad grid home page + two-column projects grid  
**Result:** Better space usage, more content visible, more scannable

Upload all images, implement the quad grid and two-column layouts, and we're good to go! 🦁
