# Google Stitch + Claude Code Workflow Guide

## Overview
You design in Google Stitch → Export → Upload to Google Drive → I enhance and generate WordPress code → Push to GitHub

---

## PART 1: Google Stitch Setup & Design

### Step 1: Go to Google Stitch
```
https://stitch.withgoogle.com/
```

### Step 2: Create New Design
- Click "Create New"
- Select "Web Design"
- Start with blank canvas or template

### Step 3: Design Landing Page
**For: /neonatologist-bangalore**

Use these specifications:
- **Color Scheme**: Professional medical (blues, whites, greens)
- **Font**: Clean sans-serif (Inter, Roboto, Poppins)
- **Layout**: Mobile-first responsive
- **Sections**:
  1. Hero section (H1 + CTA buttons)
  2. Trust strip (Stats/credentials)
  3. Services grid (6 cards)
  4. About doctor section
  5. Location/map area
  6. Testimonials
  7. FAQ accordion
  8. Final CTA

### Step 4: Design Best Practices
- ✅ Use a grid system (12-column)
- ✅ Consistent spacing (8px baseline)
- ✅ Mobile breakpoints: 320px, 768px, 1024px
- ✅ Color palette: 3-4 colors max
- ✅ Typography: 2 font families max
- ✅ High contrast for accessibility
- ✅ CTA buttons prominent
- ✅ Include whitespace

---

## PART 2: Export from Google Stitch

### Export Options:

**Option A: Export as HTML** (Recommended)
1. Click "Export" → "Code"
2. Select "HTML + CSS"
3. Download .zip file
4. Extract locally

**Option B: Export as Design JSON**
1. Click "Export" → "Design"
2. Select "JSON"
3. Save file

**Option C: Screenshot + Manual Notes**
1. Take screenshots of each section
2. Document dimensions, colors, text
3. List all components

---

## PART 3: Share with Claude Code

### Method 1: Upload to Google Drive (Recommended)
1. Create folder: `landing-pages-designs`
2. Upload exported HTML/CSS or ZIP
3. Share link with me
4. I'll access via Google Drive MCP

### Method 2: Direct ZIP Upload
1. Create ZIP of all design files
2. Upload here to Claude Code
3. I'll extract and process

### Files to Include:
```
/neonatologist-bangalore-design/
├── index.html
├── styles.css
├── images/
│   ├── hero-bg.jpg
│   ├── doctor-photo.jpg
│   └── icons/
├── assets/
│   └── fonts/
└── README.md (design notes)
```

---

## PART 4: What I'll Do with Your Export

Once you share the export, I will:

### ✅ Enhancement Phase
1. **Code Quality**
   - Clean up HTML structure
   - Optimize CSS (remove unused)
   - Add comments

2. **WordPress Integration**
   - Convert to WordPress page template
   - Add Elementor compatibility notes
   - Create Gutenberg block version
   - Add shortcodes where needed

3. **SEO Optimization**
   - Add meta tags (already approved)
   - Insert schema markup (Physician, BreadcrumbList, FAQ)
   - Optimize heading hierarchy (H1 → H2 → H3)
   - Add alt text for images
   - Implement structured data

4. **Performance**
   - Lazy load images
   - Minify CSS/JS
   - WebP image format
   - Critical CSS inline
   - Defer non-critical JS

5. **Mobile Responsiveness**
   - Test all breakpoints
   - Sticky CTA bar for mobile
   - Touch-friendly buttons (48px minimum)
   - Mobile menu optimized

6. **Functionality**
   - WhatsApp CTA (pre-filled message)
   - Phone click-to-call
   - Appointment form integration
   - Google Maps embed
   - Review section

7. **Accessibility**
   - ARIA labels
   - Keyboard navigation
   - Color contrast check
   - Screen reader friendly

### Output You'll Receive:
```
/neonatologist-bangalore-final/
├── page-neonatologist-bangalore.php (WordPress template)
├── index.html (standalone)
├── styles.css (optimized)
├── script.js (interactions)
├── schema-markup.json
├── elementor-notes.md
├── implementation-guide.md
└── performance-report.md
```

---

## PART 5: Workflow Timeline

```
Week 1:
├─ Day 1: You design in Google Stitch
├─ Day 2: Export HTML/CSS
├─ Day 3: Upload to Google Drive/share
└─ Day 4: I enhance + generate WordPress code

Week 2:
├─ Day 1: You review code
├─ Day 2: Feedback/revisions
├─ Day 3: Final tweaks
└─ Day 4: Push to GitHub
```

---

## PART 6: Communication Checklist

When you share the export, please include:

- [ ] Design file (HTML/ZIP/JSON)
- [ ] Screenshot of full page design
- [ ] Color codes used (#hex format)
- [ ] Fonts used (Google Fonts names)
- [ ] Any custom components/interactions
- [ ] Mobile design (screenshot)
- [ ] Tablet design (screenshot)
- [ ] Any notes/special requests

---

## PART 7: Design Files Needed for Each Page

For each landing page, you'll design:

**Page 1: /neonatologist-bangalore** (Start here)
**Page 2: /nicu-specialist-bangalore**
**Page 3: /pediatrician-whitefield**
**Page 4: /newborn-care**
**Page 5: /doctor-whitefield**
**Page 6: /doctor-itpl**

---

## PART 8: My Role During Design

While you design, I will:
- ✅ Wait for export
- ✅ Prepare meta tags from Excel
- ✅ Gather schema markup templates
- ✅ Plan WordPress integration
- ✅ Review design specs once shared

---

## PART 9: Questions Before You Start?

**Ask me:**
1. Color palette recommendation?
2. Component library to use?
3. Font combinations?
4. Layout inspiration examples?
5. CTA button placement strategy?

---

## Next Steps:

1. **You**: Start designing `/neonatologist-bangalore` in Google Stitch
2. **You**: Export as HTML/CSS when done
3. **You**: Upload to Google Drive or share ZIP
4. **Me**: Enhance + generate WordPress code
5. **Result**: Production-ready landing page

---

**Ready to start? Go create your design! 🎨**
When exported, come back here and share the file/link.
