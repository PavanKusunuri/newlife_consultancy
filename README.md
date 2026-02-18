# NewLife IT Consultancy — Business Website

A fully responsive, multi-section business website built for **NewLife IT Consultancy**, an HR services firm based in Bangalore, India. The site bridges the gap between talented professionals and trusted companies by showcasing the firm's services, clients, and contact information.

---

## Live Preview

> Open `index.html` directly in any modern browser — no build step required.

---

## Project Purpose

This project demonstrates my ability to design and build a **production-quality, multi-section static website** from scratch. It was built to serve as a real-world business web presence for an IT consultancy firm and covers everything from responsive layout to interactive UI components.

---

## Features

- **Hero Carousel** — Auto-playing image slider with manual prev/next controls and dot navigation
- **About Section** — Company description with animated stats (10+ years, 500+ clients, 5k+ placements, 98% satisfaction)
- **Services Section** — Four service cards (HR Consulting, Recruitment, Payroll, HR Audit) with hover animations
- **Clients Section** — Grayscale-to-colour client logo reveal on hover
- **Testimonials Section** — Three-column testimonial cards with profile images
- **Contact Section** — Contact info strip (address, phone, email) + a fully styled message form
- **Sticky Navigation** — Fixed header with scroll-aware active link highlighting
- **Mobile Responsive** — Hamburger menu with animated open/close toggle for small screens
- **Back-to-Top Button** — Appears after scrolling 400 px, smooth-scrolls to top
- **Smooth Scrolling** — CSS `scroll-behavior: smooth` for anchor navigation

---

## Tech Stack & Skills Demonstrated

| Technology | Usage |
|---|---|
| **HTML5** | Semantic sectioning, accessibility attributes, form elements |
| **Tailwind CSS** (CDN) | Utility-first responsive layout, custom colour theme via `tailwind.config` |
| **Vanilla JavaScript** | Carousel logic, scroll events, mobile menu toggle, active nav detection |
| **CSS3** | Custom animations, transitions, pseudo-elements (`::after` underlines & section headings) |
| **Google Fonts** | Open Sans font family |
| **Boxicons** | Service section icons |
| **Font Awesome** | Footer social media icons |
| **Responsive Design** | Mobile-first approach; breakpoints at `sm`, `md`, `lg` |

---

## Project Structure

```
newlife_consultancy/
├── index.html          # Main single-page website
├── assets/
│   ├── css/
│   │   └── all.css     # Font Awesome icon styles
│   ├── img/
│   │   ├── home/       # Hero carousel images (img-1 to img-4)
│   │   └── clients/    # Client logo images (client-1 to client-6)
│   ├── js/
│   │   └── main.js     # Additional scripts
│   └── webfonts/       # Font Awesome webfont files
└── css/
    ├── custom.css      # Custom overrides
    └── reponsive.css   # Additional responsive rules
```

---

## Sections Overview

| Section | Description |
|---|---|
| **Home** | Full-width auto-playing hero carousel with overlay headline |
| **About Us** | Company mission + 4 key stat cards |
| **Services** | 4 animated service cards with Boxicons |
| **Clients** | 6 client logos with grayscale hover effect |
| **Testimonials** | 3 customer reviews with photo cards |
| **Contact Us** | Location / phone / email info + contact form |

---

## What I Learned / Demonstrated

- Building a complete, real-world website layout using **Tailwind CSS utility classes** with a **custom design token system** (brand colours, fonts)
- Writing modular, reusable **vanilla JavaScript** without any framework for carousel, scroll spy, and menu toggling
- Implementing **mobile-first responsive design** with a collapsible hamburger navigation
- Applying **CSS transitions and transform animations** for smooth UX interactions
- Structuring a static project with clean **file and folder organisation**

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/newlife_consultancy.git

# Open in browser
# Simply open index.html in any modern browser
```

No dependencies to install. No build tools needed.

---

## Author

**Pavan** — Frontend Developer  
Feel free to connect on [LinkedIn](https://linkedin.com/) or reach out via email.

---

## License

This project is open source and available under the [MIT License](LICENSE).
