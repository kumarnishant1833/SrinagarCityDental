# 🦷 Srinagar City Dental Center

Official website of **Srinagar City Dental Center** — a complete dental clinic in Karan Nagar, Srinagar, offering Orthodontics, Dental Implants, Full Mouth Rehabilitation, Cosmetic Dentistry, Root Canal Treatment, and Pediatric Dentistry, led by **Dr. Nasir, BDS, MDS (Orthodontics)**.

🔗 **Live site:** [https://srinagarcitydental.com](https://srinagarcitydental.com)

---

## 📋 About

This is a single-page, production-ready website built to showcase the clinic's services, doctors, patient results, and location, and to convert visitors into booked appointments via WhatsApp and phone.

## ✨ Features

- Modern, responsive single-page design
- Sticky navigation with active-section highlighting
- Animated hero section with trust badges and live stats
- Doctor/team profiles with qualifications and experience
- Full services grid (Root Canal, Implants, Braces, Full Mouth Rehab, Cosmetic Dentistry, Pediatric Dentistry)
- Clinic photo gallery (masonry layout)
- Embedded clinic tour video
- Before & after treatment comparison cards
- Patient video testimonials with scroll-triggered autoplay
- Expandable FAQ accordion
- WhatsApp-integrated appointment booking form (no backend required)
- Embedded Google Map with directions link
- Floating WhatsApp and "Book Appointment" buttons
- Scroll-reveal animations throughout
- Fully accessible markup (ARIA labels, roles, semantic HTML5)
- SEO-optimized with meta tags, Open Graph tags, and Schema.org (`Dentist`) structured data

## 🛠️ Technologies Used

- **HTML5** — semantic structure
- **CSS3** — custom properties, Grid, Flexbox, animations (no framework)
- **Vanilla JavaScript** — no dependencies, no build step
- **Font Awesome** (via CDN) — icons
- **Google Fonts** — Cormorant Garamond, Syne, DM Sans
- **Google Maps Embed** — location display

No frameworks, no bundlers, no npm packages — the entire site is one self-contained `index.html`.

## 🚀 Deployment (GitHub Pages)

This site is deployed via **GitHub Pages** directly from the `main` branch.

1. Push changes to the `main` branch.
2. GitHub Pages automatically rebuilds and redeploys the site.
3. The live site is served at the custom domain configured via the `CNAME` file.

### Custom Domain

The site uses a custom domain: **srinagarcitydental.com**, configured through:
- A `CNAME` file in the repository root
- DNS records (A/ALIAS or CNAME) pointing to GitHub Pages, set up with the domain registrar

## 🔍 SEO

- Descriptive `<title>` and meta description
- Targeted meta keywords for local dental search terms
- Open Graph tags for social sharing previews
- Canonical URL tag
- `Dentist` structured data (JSON-LD / Schema.org) with address, phone, hours, and staff
- `robots.txt` and `sitemap.xml` for search engine crawling
- Semantic HTML headings and landmark roles for accessibility and crawlability

## 📱 Responsive Design

Fully responsive across desktop, tablet, and mobile breakpoints (`1024px`, `768px`, `480px`), including:
- Collapsible mobile navigation menu
- Adaptive grid layouts for services, gallery, and testimonials
- Touch-friendly buttons and floating action buttons

## 💻 Run Locally

No build tools or dependencies are required.

```bash
# Clone the repository
git clone https://github.com/kumarnishant1833/SrinagarCityDental.git

# Move into the project folder
cd SrinagarCityDental

# Open directly in your browser
open index.html   # macOS
# or
start index.html  # Windows
```

Alternatively, serve it locally with any static server, e.g.:

```bash
npx serve .
```

## 📁 Folder Structure
