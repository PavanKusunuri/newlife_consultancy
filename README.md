# NewLife IT Consultancy — Premium Business Website

> A production-grade, Apple-inspired single-page website built entirely from scratch using **HTML5, CSS3, Vanilla JavaScript and GSAP 3** — zero frameworks, zero build tools.

---

## 🔗 Quick Start

```bash
git clone https://github.com/your-username/newlife_consultancy.git
# Open index.html in any modern browser — no install, no build step.
```

---

## Project Overview

**NewLife IT Consultancy** is an HR services firm based in Bangalore, India, that connects top talent with trusted companies. This project is a **complete premium redesign** of their business website, built to deliver an immersive, high-performance user experience comparable to top-tier product websites.

The site was designed and developed solo by **Pavan**, covering everything from system-level CSS architecture and animation engineering to responsive layout and UX interaction design.

---

## Key Highlights (What Makes This Stand Out)

| Capability | Implementation |
|---|---|
| **Animation Engine** | GSAP 3 + ScrollTrigger — staggered entrance animations, timeline sequencing, scroll-driven reveals |
| **Performance** | Zero JS frameworks, lazy-loaded images, `requestAnimationFrame` cursor loop, `preconnect` font hints |
| **CSS Architecture** | Custom property design token system (`--brand`, `--ease-out`, `--radius` etc.), no utility framework |
| **UX Depth** | Custom dual-layer cursor, magnetic buttons, floating particles, animated stat counter, loading screen |
| **Typography** | Dual font pairing — Playfair Display (serif display) + Inter (UI) — mirroring agency-level design |
| **Responsive Design** | 5 breakpoints (480 / 768 / 900 / 1100 / 1280px), mobile-first, touch-safe cursor detection |
| **Accessibility** | Semantic HTML5, ARIA labels, `:focus` ring states, `prefers-reduced-motion` safe animations |

---

## Tech Stack

| Technology | Role |
|---|---|
| **HTML5** | Semantic structure, SEO meta tags, ARIA attributes, Open Graph ready |
| **CSS3** | Custom property tokens, glassmorphism nav, `clip-path` animations, `backdrop-filter`, CSS masks |
| **Vanilla JavaScript (ES6+)** | GSAP timeline orchestration, scroll spy, RAF cursor loop, slideshow engine, magnetic effect |
| **GSAP 3 + ScrollTrigger** | Hero entrance animation, scroll-triggered reveals, animated number counters |
| **Google Fonts** | Inter (300–900) + Playfair Display — loaded with `preconnect` for zero FOUT |
| **Boxicons + Font Awesome** | Iconography across services, process steps, contact, and social links |
| **Unsplash API** | High-resolution hero and about section images with optimised CDN parameters |

---

## Features Built

### Interactions & Animation
- **Loading Screen** — branded intro loader with animated progress bar, fades out on `window.load`
- **Custom Cursor** — dual-layer cursor (dot + follower ring) driven by `requestAnimationFrame`, with hover expansion and blend-mode effect; auto-hidden on touch devices
- **Magnetic Buttons** — mouse-tracking `translate()` effect on primary CTAs
- **Floating Particles** — CSS `@keyframes` particle system in the hero background
- **GSAP Hero Entrance** — staggered timeline revealing eyebrow → title → subtitle → buttons
- **Scroll-Triggered Reveals** — every section animates in with `ScrollTrigger` as the user scrolls
- **Animated Counters** — stat numbers count up from 0 on scroll using `gsap.from()`

### Navigation & Layout
- **Glassmorphism Sticky Nav** — `backdrop-filter: blur()` + `saturate()` activates on scroll
- **Scroll Spy** — active nav link updates dynamically based on current viewport section
- **Full-Screen Mobile Overlay** — animated hamburger (3-bar → X) with full-screen nav overlay
- **Smooth Anchor Scrolling** — offset-aware smooth scroll to all anchor targets

### Sections
- **Hero** — 4-slide crossfade slideshow with Ken Burns zoom, dot navigation, scroll indicator
- **Stat Ticker Bar** — infinite CSS marquee with key company metrics
- **About** — two-column layout with image parallax hover, floating badge, animated stat cards
- **Services** — 4-card grid with hover lift, icon rotation, gradient reveal and background number
- **Process** — 5-step horizontal timeline with connecting gradient line and icon hover effects
- **Clients** — infinite CSS ticker with 8 client logos, grayscale → colour on hover, edge fade mask
- **Testimonials** — 3-column review cards with star ratings, avatars, hover lift
- **CTA Banner** — radial glow background with full-bleed call-to-action
- **Contact** — two-column layout: contact info blocks + full form with service dropdown, focus states, and success animation
- **Footer** — 4-column grid with social links, quick-links, and brand description

---

## Project Structure

```
newlife_consultancy/
├── index.html              # Entire site — 1,168 lines of hand-crafted HTML/CSS/JS
├── assets/
│   ├── css/
│   │   └── all.css         # Font Awesome icon definitions
│   ├── img/
│   │   ├── home/           # Local hero images (img-1 to img-4)
│   │   └── clients/        # Client logos (client-1 to client-8)
│   ├── js/
│   │   └── main.js         # Legacy script reference
│   └── webfonts/           # Font Awesome webfont files
└── css/
    ├── custom.css          # Extended custom styles
    └── reponsive.css       # Additional responsive overrides
```

---

## Design Decisions Worth Noting

- **No CSS framework** — all layout and design written in pure CSS3 with custom properties, demonstrating deep CSS knowledge rather than relying on utility classes
- **No JS framework or bundler** — the entire interactive layer is vanilla ES6+, showing command of the language itself
- **GSAP chosen over CSS animations** for the hero** — more precise timeline control, better cross-browser easing, and easier sequencing of complex multi-element entrances
- **`requestAnimationFrame` for cursor** — smoother than `mousemove` + CSS transition alone; the follower uses lerp (linear interpolation) for a natural lag effect
- **CSS custom properties as design tokens** — a single source of truth for brand colours, spacing, easing curves and border radii, making the design system scalable

---

## Skills This Project Demonstrates

```
Frontend Development     ████████████████████  Advanced
CSS Architecture         ████████████████████  Advanced
Animation Engineering    ████████████████░░░░  Proficient
UX / Interaction Design  ████████████████░░░░  Proficient
Responsive Design        ████████████████████  Advanced
Performance Thinking     ██████████████░░░░░░  Solid
Accessibility            ████████████░░░░░░░░  Working Knowledge
```

---

## Author

**Pavan** — Frontend Developer  
Passionate about crafting interfaces that feel as good as they look.

- 🔗 [LinkedIn](https://linkedin.com/) — *replace with your profile*
- 📧 [Email](mailto:your@email.com) — *replace with your email*
- 🌐 [Portfolio](https://your-portfolio.com) — *replace with your site*

---

## License

This project is open source and available under the [MIT License](LICENSE).
