# FDM — Modern Professional Website

A completely redesigned, modern, and professional version of the Financial Data Management, Inc. (fdmmd.com) medical billing website.

## What Was Done

- **Rebuilt from scratch** with a clean, trustworthy, contemporary design suitable for a professional healthcare services company.
- **Preserved all original functionality and messaging**:
  - Provider Enrollment & Credentialing
  - Medical Billing & Coding
  - Collections & Appeals (including "road trips")
  - Compliance & Audits
  - State-of-the-art technology (Medinformatix)
  - Electronic billing & EFT
  - Customized financial reporting
  - Patient engagement / appointment reminders
  - Team approach, HBMA certification, established 1988
  - Two offices (Santa Ana, CA + Coeur d’Alene, ID)
- **Major improvements**:
  - Fully responsive / mobile-first design (excellent on phones and tablets)
  - Sticky professional navigation with smooth scrolling
  - Modern typography, color palette, and visual hierarchy
  - Beautiful service cards with hover states
  - Prominent, easy-to-use contact form
  - Strong calls-to-action and trust signals
  - Accessibility and keyboard friendly
  - Self-contained single HTML file (easy to host anywhere)

## How to View / Test

1. Double-click `index.html` in this folder, or
2. Right-click `index.html` → "Open with" → your browser (Chrome, Edge, Firefox recommended), or
3. Use a local server for the best experience:

```bash
# In this directory
npx serve .
# or
python -m http.server 8000
```

Then open http://localhost:8000

## Next Steps / Customization

- **Real form submissions**: Replace the simulated form handler with Formspree, Netlify Forms, or your own backend.
- **Images / Branding**: Add your actual logo and professional photography (hero image, team, office).
- **Additional pages**: The current site is a polished single-page experience. If you prefer separate pages (/services, /about, etc.), we can split it easily.
- **Analytics / Tracking**: Add Google Analytics, Hotjar, etc.
- **SEO**: Meta tags are already strong. Add a sitemap.xml and robots.txt when deploying.
- **Domain**: Point fdmmd.com (or www.fdmmd.com) at the new hosting.

## Hosting Recommendations (Free / Easy)

- **Netlify** (drag & drop `index.html` or connect Git)
- **Vercel**
- **GitHub Pages**
- **Cloudflare Pages**

All of these support single-file static sites perfectly and give you free custom domains + HTTPS.

## Tech Stack

- Tailwind CSS (via CDN for zero build step)
- Font Awesome icons
- Vanilla JavaScript (no frameworks)
- Fully responsive with modern CSS

---

This is a production-ready starting point. Let me know if you'd like any refinements (different color scheme, added testimonials, multi-page version, logo integration, etc.).