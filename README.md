# EliteHomes — Real Estate Landing Page

A modern, responsive real estate landing page built with HTML5, CSS3, Bootstrap 5, and Font Awesome.

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5      | Semantic page structure |
| CSS3       | Custom styling & animations |
| Bootstrap 5| Responsive grid, navbar, tabs, accordion, carousel |
| Font Awesome | Icons throughout the UI |
| Google Fonts (Poppins) | Typography |

---

## Features

- **Sticky Navbar** — Logo + nav links with hover underline effects; collapses into a full-height mobile sidebar on small screens.
- **Mega Dropdown** — Properties menu with Featured Properties, Property Types, Popular Locations, and Resources.
- **Hero Section** — Full-viewport background image with purple gradient overlay, floating search card, and statistics bar.
- **Search Card** — Location, Property Type, Price, Bedrooms, Bathrooms, Min/Max Sq Ft filters.
- **Featured Properties** — 3 property cards with badges (Featured, New Listing, Price Drop), favorite button, photo count, agent info, and Schedule Tour button.
- **Services Tabs** — Buying, Selling, Renting, Investing, Commercial with icon features and success stat cards.
- **Testimonials Carousel** — Client reviews with star ratings, avatars, and carousel controls.
- **FAQ Accordion** — 7 frequently asked questions with smooth expand/collapse.
- **Contact Section** — Info cards, social links, and a full contact form.
- **Footer** — Brand, copyright, and social icons.

---

## File Structure

```
project/
├── index.html              # Main page
├── css/
│   ├── bootstrap.min.css   # Bootstrap framework
│   └── style.css           # Custom styles
├── js/
│   └── bootstrap.bundle.min.js  # Bootstrap JS
├── images/                 # All project images (preserved as-is)
│   ├── hero-bg-img.png
│   ├── featured-properties-img-1.png
│   ├── featured-properties-img-2.png
│   ├── featured-properties-img-3.png
│   ├── luxury-villa.jpeg
│   ├── modern-apartment.jpeg
│   ├── new-york.jpeg
│   ├── los-angeles.jpeg
│   ├── miami.jpeg
│   ├── avatar-1.jpg
│   ├── avatar-2.jpg
│   ├── avatar-3.jpg
│   ├── avatar-5.jpg
│   ├── service-img-1.webp
│   ├── service-img-2.webp
│   ├── service-img-3.webp
│   ├── service-img-4.png
│   └── service-img-5.png
└── README.md               # This file
```

---

## Quick Start

1. Download or clone the project files.
2. Open `index.html` in any modern web browser.
3. Ensure the `css/`, `js/`, and `images/` folders are in the same directory as `index.html`.

No build step or package manager is required.

---

## Design Notes

- **Primary color:** `#6d28d9` (purple)
- **Gradient accent:** `#9333ea`
- **Typography:** All text sizes use `px` units for precise control.
- **Responsive breakpoints:**
  - Desktop: full navigation + two-column layouts
  - Tablet (≤991px): adjusted spacing, scrollable service tabs
  - Mobile (≤768px): hamburger sidebar menu, stacked cards, 2×2 stats grid

---

## Customization

- **Images:** Replace files inside `images/` while keeping the same filenames, or update the `src` attributes in `index.html`.
- **Colors:** Edit the CSS custom properties at the top of `style.css` under `:root`.
- **Content:** Update text directly in `index.html`.

---

## Browser Support

- Chrome / Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Android)

---

*Built with care for finding your dream home.*
