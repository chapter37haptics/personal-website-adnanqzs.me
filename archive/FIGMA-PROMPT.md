# Figma Design Prompt — Personal Website with Project Images

## Project Overview
Design a modern, minimalist two-page personal website showcasing Howard Stark's journey from teenage maker (age 15-18) to engineer and founder.

---

## Page 1: Home (No Images)

### Section 1: Hero
**Full-screen quote:**
> "The reasonable man adapts himself to his surroundings. The unreasonable man adopts the surroundings to himself. All progress depends on the unreasonable man. Invest wisely, invest in yourself."

### Section 2: My Ambition
I've been a builder since I was a kid — building my own toys, then bigger and better things. There's always a "why" behind what I build. Initially, the why was simple: personal joy. Building for the sake of building.

Now the why has evolved. I've learned that solving real problems gives me a double bonus: the joy of building something meaningful AND the satisfaction of adding value to someone else's life. That's the sweet spot.

My ambition is to have the time and resources to keep building. To learn new tools that help me tackle bigger challenges. To work with people who share that drive — collaborating to create solutions that matter, at a scale none of us could reach alone.

---

## Page 2: Projects (WITH IMAGES)

### Opening Statement (No Images)
"From toys to systems. From joy to impact. A timeline of building since age 15."

---

### College Years (2013-2016) — NO IMAGES AVAILABLE
**Text-only cards for these achievements:**

**Research Publications**
- Machine Learning for Microscopy (2015) — IIT Kharagpur Research Internship
- Astronomy Research (2016) — Co-author with Dr. Randa Asa'd, AUS Physics Department

**Leadership**
- IEEE Student Branch, AUS (2014-2016) — Organized 36 events, awarded 2nd Best Student Branch in UAE

**Academic Recognition**
- Sheikh Khalifa Presidential Scholarship (Junior Year) — Best Overall Engineer
- Chancellor's Scholarship (Freshman Year, Sept 2013) — 75% tuition coverage
- Dean's List (Every semester, 2013-2016)
- Chancellor's List Gold

---

### High School Years (2012-2015) — PROJECT IMAGES HERE

**Layout: Card grid with image + text for each project**

---

### Age 18 (2014-2015)

**Robotics Workshop**
- **Image:** `robotics-workshop_1.jpg`
- **Text:** Built line follower and obstacle avoidance robots using L293D drivers, infrared sensors, and motors. Learned C programming, PIC microcontrollers (MPLABS), and wireless control (XBEE). Completed 40-hour course in 20 hours.

---

### Age 17 (2014)

**Infrared Camera Conversion**
- **Images:** `infrared-camera_1.jpg` (setup), `infrared-camera_2.jpg` (results)
- **Text:** Hacked old camera into infrared camera by removing IR filter and adding photo film to block visible light. Could now see in the dark with an infrared LED — no lights needed.

**Earphone Repair Mastery**
- **Image:** `earphone-repair_1.jpg`
- **Text:** Learned to replace 3.5mm audio jacks. Biggest win: salvaged friend's broken Beats earphones ($99 retail) and repaired them for under $0.50 using an old AUX cable.

**LED Beats — Portable Version**
- **Image:** `led-beats-portable_1.jpg`
- **Text:** Made the woofer LED project compact using a TIP 31 transistor, 2 LEDs, 3V button cell, and 3.5mm audio jack. Prototype for entire room with beat-reactive lights.

**Solar Panel Cell Phone Charger**
- **Image:** `solar-charger_1.jpg`
- **Text:** Built "green" charger with 6V 8W solar panel, 5V regulator circuit (transistor + capacitors), and phone charging pin.

**Portable USB Charger**
- **Image:** `usb-charger_1.jpg`
- **Text:** Frequent traveler solution: 5V regulator + female USB port + 9V battery. Casing made from repurposed food container. Compact and emergency-ready.

**Photo Stand**
- **Image:** `photo-stand_1.jpg`
- **Text:** Handmade birthday gift with PVC board structure, 4 LEDs at vertices, and 10k potentiometer for variable brightness control.

**555 Timer IC Circuit**
- **Image:** `555-timer_1.jpg`
- **Text:** First attempt at blinking LEDs with capacitors, resistors, and ICs. Failed initially. Tried again days later — success. "I had advanced to the next level."

---

### Age 16 (2013)

**AIESEC Recruitment**
- **Image:** `aiesec_1.jpg`
- **Text:** Minimum age: 18. Howard's age: 16. VP of AIESEC Hyderabad initially refused. Showed portfolio of projects. Result: Recruited. Awarded kurta at first group meet for "most outstanding AIESEC'er."

**LED Beats — Woofer Version**
- **Images:** `led-beats-woofer_1.jpg` (setup), `led-beats-woofer_2.jpg` (glowing effect)
- **Text:** Made listening to music more exciting by connecting 9 LEDs in series to subwoofer. LEDs pulsed with the beat. Later upgraded with 28 white LEDs. Turned room into "mini disco."

**Arc Reactor Model**
- **Image:** `arc-reactor_1.jpg`
- **Text:** Inspired by Iron Man. Salvaged parts from old VCR player mom was throwing away. Installed alternating blue and white LEDs. Too heavy to wear on chest, but kept as inspiration.

**Photo Frame Gift**
- **Image:** `photo-frame_1.jpg`
- **Text:** Handmade birthday gift: cardboard frame with blue and white LEDs wired in series. Magnetic attachment system allowed photo swaps.

**Portable Fan**
- **Image:** `portable-fan_1.jpg`
- **Text:** Problem: 2-hour power cuts at school. Solution: Extracted 1.5V CD-ROM motor, added 4-battery holder and clip. Later improved with magnetic mounting.

---

### Age 15 (2012)

**Monster Truck LED Add-ons**
- **Image:** `monster-truck_1.jpg`
- **Text:** First documented project. Added 3 LEDs in parallel to RC monster truck with battery holder and switch. Velcro-mounted battery for easy replacement after high-impact crashes.

---

## Design Specifications

### Visual Style
- **Modern, minimalist, clean typography**
- **Generous whitespace**
- **Bold, confident hierarchy**
- **Single accent color** (suggest: deep blue or burnt orange)
- **Professional but shows personality**

### Page 1 Layout
- Hero: Full viewport height, centered quote, large typography (32-48px desktop)
- Ambition: Centered content block, max-width ~800px, 3 paragraphs
- CTA at bottom: "See my work →" transitions to Projects page

### Page 2 Layout

**College Years Section:**
- Text-only cards or timeline
- Larger, featured treatment (these are major achievements)
- Clean, minimal layout without photos

**High School Years Section (WITH IMAGES):**
- **Card grid layout** (recommended)
- Each card: Image on left/top, text on right/bottom
- Image size: 300-400px width desktop, full width mobile
- Border radius: 8-12px on images
- Subtle shadow or border on images
- Grouped by age with clear visual separation

**Card structure:**
```
┌─────────────────────────────────────┐
│  [Image]  │  Project Title          │
│  300-400px│  Age X • Year           │
│           │  Short description...   │
└─────────────────────────────────────┘
```

### Image Treatment
- **Authentic DIY aesthetic** — these are photos from 2012-2015
- Some have warm/yellow color cast, variable lighting
- **Don't over-polish** — keep the maker aesthetic
- Border radius: 8-12px
- Subtle shadow: `0 2px 8px rgba(0,0,0,0.1)`
- Maintain aspect ratios (don't stretch/squash)

### Typography
- **Body text:** Sans-serif, 16-18px minimum
- **Hero quote:** Large serif or bold sans-serif
- **Project titles:** Bold, 18-22px
- **Age/year:** Small, subtle, 12-14px

### Responsive
- **Desktop:** 1200px+ (2-column grid for projects)
- **Tablet:** 768-1199px (1-2 column grid)
- **Mobile:** <768px (single column, full-width images)

### Navigation
- Minimal sticky header
- "Home" | "Projects"
- Smooth scroll between sections

---

## Image Upload Instructions

**I will upload 16 JPG images with these filenames:**

```
555-timer_1.jpg
aiesec_1.jpg
arc-reactor_1.jpg
earphone-repair_1.jpg
infrared-camera_1.jpg
infrared-camera_2.jpg
led-beats-portable_1.jpg
led-beats-woofer_1.jpg
led-beats-woofer_2.jpg
monster-truck_1.jpg
photo-frame_1.jpg
photo-stand_1.jpg
portable-fan_1.jpg
robotics-workshop_1.jpg
solar-charger_1.jpg
usb-charger_1.jpg
```

**Match images to projects using the mapping above.** Each project name in the text corresponds to its image filename (e.g., "Monster Truck LED Add-ons" → `monster-truck_1.jpg`).

---

## Deliverables

1. **Figma file** with desktop (1440px), tablet (768px), mobile (375px) views
2. **Component library** (project cards, typography styles, buttons)
3. **Prototype** with navigation flow and scroll interactions
4. **Design system notes** (colors, spacing, typography scale)

---

## Key Points

✅ **Page 1 = No images** (quote + ambition text only)  
✅ **Page 2 College section = No images** (text-only cards for academic achievements)  
✅ **Page 2 High School section = 16 images** (one image per project, two projects have 2 images each)  
✅ **Authentic maker aesthetic** — don't hide the DIY look, celebrate it  
✅ **Card grid layout** — image + text side by side  
✅ **Reverse chronological** — Age 18 → Age 15  

---

**Ready to design. Upload the 16 images and match them to projects using the structure above.**
