# The Wall That Heals — Project State
Last updated: 2026-03-23

## Folder & Repo
- **Local:** `C:\Users\Daddy\Desktop\ANVIL PROJECTS\The Wall That Heals\`
- **GitHub repo:** https://github.com/Advocate4tK/wall-that-heals-putnam
- **PICS folder:** `C:\Users\Daddy\Desktop\ANVIL PROJECTS\The Wall That Heals\PICS\` — ALL screenshots and reference images

## What This Project Is
A landing page website for the Vietnam Veterans Traveling Wall visit to Putnam, CT. Single static HTML page. Commissioned by Putnam VFW. Hosted on GitHub Pages with custom domain via GoDaddy.

---

## Hosting & Deployment
- **Live URL:** thewallthathealsputnam2026.org
- **Host:** GitHub Pages via GoDaddy custom domain
- **Deploy:** git push to main → live in ~2 minutes
- **HTTPS:** GitHub provisioning SSL cert — check back, should auto-enable
- **NOT Netlify**

---

## Event Details
- **Wall opens:** September 10, 2026
- **Wall closes:** September 13, 2026
- **Location:** Murphy Park, Putnam, CT
- **Admission:** Free, open 24 hours a day
- **Organizer:** Putnam VFW — putnamvfw.org
- **Official partner:** VVMF — https://www.vvmf.org/The-Wall-That-Heals/

---

## Design System
- **Fonts:** Cinzel (headings) + Raleway (body) — Google Fonts
- **Colors:**
  - `--gold: #c9a84c` — primary accent
  - `--bg: #0d0d0d` — page background
  - `--white: #f5f0e8` — body text
  - `--navy: #1b2d4f` — Donate CTA circle
  - `--orange: #d4845a` — Events CTA circle
  - `--green: #3d6b4f` — Tours CTA circle
  - `--tan: #b8a96a` — Volunteer CTA circle
- **Aesthetic:** Dark/gold, VVMF-inspired, solemn but welcoming
- **ANVIL ARTS trademark:** Anvil + hammer SVG in under construction banner

---

## File Structure
```
The Wall That Heals/
├── index.html          ← entire site — single page
├── CNAME               ← thewallthathealsputnam2026.org
├── CLAUDE.md           ← project rules for Claude
├── PICS/               ← all reference images and screenshots
│   ├── wall.png        ← hero image (veterans touching wall, B&W)
│   ├── buttons.png     ← CTA circle reference
│   └── ...
└── .claude-memory/
    └── PROJECT_STATE.md
```

---

## Page Sections (index.html)
| Section | Anchor | Status |
|---------|--------|--------|
| Under Construction Banner | — | Live — remove before launch |
| Nav | — | Done |
| Hero + Countdown | #hero | Done |
| CTA Circles | #cta-row | Done (Donate/Events/Tours/Volunteer) |
| About + YouTube | #about | Done — needs real copy |
| Event Info Cards | #event-info | Done |
| Schedule | #schedule | Placeholder — needs real times |
| Get Involved | #get-involved | Done |
| Sponsors | #sponsors | Placeholder — needs logos/names |
| Donate | #donate | Done — links to VVMF |
| Contact | #contact | Placeholder — needs real info |
| Footer | — | Done |

---

## Key Assets
- **Hero image:** `PICS/wall.png` — veterans touching the wall, black and white
- **YouTube embed:** https://www.youtube.com/watch?v=Qgz1q-D69WA&t=55s
- **Donate link:** https://www.vvmf.org/donate/ (via VVMF)

---

## Content Still Needed
- [ ] Real contact info for organizing committee
- [ ] Full event schedule (opening/closing ceremony times, candlelight vigil, name readings)
- [ ] Sponsor logos and names
- [ ] Volunteer sign-up form or link
- [ ] Tour registration link
- [ ] Remove under construction banner before launch

---

## PICK UP HERE NEXT SESSION
- [ ] Confirm HTTPS is active (GitHub was still provisioning SSL cert)
- [ ] Fill in real schedule details when available
- [ ] Add sponsor logos/names when available
- [ ] Add real contact info
- [ ] Option B — consolidate into ANVILPROJECTS monorepo (deferred, revisit later)
