# Baithak & Co. — Café Website

A modern, production-ready website for **Baithak & Co.** located in Jaitala, Nagpur.

---

## Features

- **Heritage Branding**: Playfair Display headlines and Plus Jakarta Sans body typography matching the Warm Heritage Café design system.
- **Sticky Navigation & Active Scroll-Spy**: Smooth-scrolling navigation with automatic section detection for `HOME`, `MENU`, `REVIEWS`, and `ABOUT`.
- **Responsive Architecture**: Fully optimized for mobile, tablet, and desktop viewports, with a slide-out mobile drawer menu.
- **Curated Favourites & Atmosphere Gallery**: Highlighting signature Nagpur bites (Regular Vada Pav, Masala Maggi, Paneer Makhni Sandwich, Hazelnut Coffee, Lemon Mint Mojito, Chocolate Cold Coffee) and café moments.
- **Interactive Café Menu**:
  - Real-time live search with instant keyword filtering across names, descriptions, and tags.
  - 10 category filters (`All Items`, `Vada Pav`, `Maggi`, `Sandwich`, `Buns & Breads`, `Small Bites`, `Chai`, `Coffee`, `Mocktail`, `Cold Beverages`).
  - 45 authentic items with pricing and tags.
  - Empty state with reset filters button.
- **Verified Facilities & Wheelchair Accessibility**: Explicitly features verified accessibility (wheelchair-accessible entrance, seating, and toilet), free Wi-Fi, outdoor seating, parking, and family-friendly amenities.
- **Community Voices (Google Reviews)**: Google Places verified 4.9-star rating badge and verified customer testimonials with direct links to Google Maps reviews.
- **Interactive Location & Directions**: One-click address copy with clipboard feedback, embedded map card, and directions link to Jaitala Bus Stop, Nagpur.
- **Order Modal**: Interactive order modal allowing quantity selection and special dietary instructions.

---

## Project Structure

```
baithak-co/
├── app/
│   ├── globals.css          # Design system tokens and typography rules
│   ├── layout.tsx           # Google fonts & material icons preconnect
│   └── page.tsx             # Main production page assembling all sections
├── components/
│   ├── Navbar.tsx           # Sticky nav, scroll spy, mobile drawer
│   ├── Hero.tsx             # Atmospheric hero with parlor badge
│   ├── HeritageStory.tsx    # Welcome philosophy block
│   ├── FeaturedFavourites.tsx # 6 curated favorite cards
│   ├── PhotoGallery.tsx     # 6 atmosphere gallery cards
│   ├── MenuSection.tsx      # Real-time search & category filter menu
│   ├── ReviewsSection.tsx   # Verified Google 4.9 rating & customer reviews
│   ├── AboutSection.tsx     # Amenities (Wheelchair accessibility), address & map
│   ├── Footer.tsx           # Navigation links, contact & copyright
│   └── OrderModal.tsx       # Interactive order modal
├── data/
│   └── menuData.ts          # Structured catalog of 45 menu items
└── public/                  # Static assets & icons
```

---

## Getting Started

Run the development server:

```bash
cd baithak-co
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser.

To create an optimized production build:

```bash
cd baithak-co
npm run build
npm run start
```
