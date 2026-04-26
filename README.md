# Mary's Boutique

A multi-page static website for **Mary's Boutique** — a boho & cutesy local shop in Orlando, FL selling affordable handmade jewelry, planners, and unique accessories.

---

## What Is This Project?

Mary's Boutique is a fully static front-end website built with plain HTML, CSS, and a small amount of JavaScript. It serves as the online presence for a boutique, giving customers a place to browse products, learn the store's story, and get in touch.

---

## Main Purpose

- Showcase the boutique's product catalog (jewelry, planners, handmade items)
- Share the owner's story and mission
- Provide store hours, location, and a contact form
- Support the boutique's community-giving initiatives

---

## Key Features

- **4-page layout** — Home, About, Shop, Contact
- **Responsive navigation** with a mobile hamburger menu
- **Product catalog** organized into three categories:
  - Jewelry (necklaces, bracelets, earrings)
  - Planners & Accessories (planners, organizers, sticker sets)
  - Handmade & Special Items (tote bags, keychains, hair clips)
- **About page** with owner bio, mission statement, and community/giving section
- **Contact page** with a form, store hours, address, phone, email, and social links
- **Google Fonts** (Playfair Display + Poppins) for a polished, boutique aesthetic
- **No build tools or dependencies** — opens directly in any browser

---

## Project Structure

```
Marys-Boutique/
├── index.html          # Home page
├── about.html          # About / owner story page
├── products.html       # Shop / product catalog page
├── contact.html        # Contact form & store info page
├── styles.css          # Global stylesheet
├── images/             # All site images (hero, products, portraits)
│   ├── hero.jpg
│   ├── feature.jpg
│   ├── extra.jpg
│   ├── mary.jpeg
│   ├── community.jpeg
│   ├── necklace.jpeg
│   ├── bracelet.jpeg
│   ├── earring.jpeg
│   ├── anklet.jpeg
│   ├── ring.jpeg
│   ├── planner.jpeg
│   ├── organizer.jpeg
│   ├── sticker.jpeg
│   ├── tote.jpeg
│   ├── keychain.jpeg
│   ├── hairclip.jpeg
│   └── ...
└── screenshots/        # Page screenshots for documentation (add yours here)
```

---

## How to Run Locally

No installation or build step is required.

Visit "" to view it live.

Otherwise:

**Option 1 — Open directly in your browser:**

1. Download or clone this repository to your computer.
2. Open the `Marys-Boutique` folder.
3. Double-click `index.html` to open the home page in your default browser.
4. Use the navigation links to move between pages.

**Option 2 — Use a local development server (recommended for accurate link behavior):**

If you have [VS Code](https://code.visualstudio.com/) installed:

1. Install the **Live Server** extension by Ritwick Dey.
2. Open the project folder in VS Code.
3. Right-click `index.html` and select **"Open with Live Server"**.
4. The site opens at `http://127.0.0.1:5500/index.html` and auto-reloads on save.

---

## Dependencies & Setup Requirements

| Dependency | How It's Loaded | Required? |
|---|---|---|
| Google Fonts (Playfair Display, Poppins) | CDN via `<link>` tag | No — site still works offline, just uses system fonts |
| Any JavaScript library | None | — |
| Build tool (npm, webpack, etc.) | None | — |

This is a **zero-dependency** project. No `npm install`, no compilation step.

---

## Store Information

| Detail | Info |
|---|---|
| Location | 123 Main Street, Orlando, FL |
| Hours | Monday – Saturday, 10 AM – 6 PM |
| Phone | (407) 555-1234 |
| Email | info@marysboutique.com |

---

## Screenshots

> Add your screenshots to a `screenshots/` folder in the project root, then replace the placeholder text below with the actual image paths.

### Home Page — Hero & Featured Products
```
[Screenshot: Home page showing the hero banner with "Chic, Cute, & Unique Finds for You" headline and the three featured product cards below]
```
`screenshots/home-page.png`

---

### Shop Page — Product Catalog
```
[Screenshot: Shop page with the three product category sections — Jewelry, Planners & Accessories, and Handmade & Special Items]
```
`screenshots/shop-page.png`

---

### About Page — Meet Mary & Mission
```
[Screenshot: About page showing Mary's photo, her story, the mission statement, and the three value icons]
```
`screenshots/about-page.png`

---

### Contact Page — Form & Store Details
```
[Screenshot: Contact page with the message form on the left and the store info cards (location, hours, phone, email, social) on the right]
```
`screenshots/contact-page.png`

---

### Mobile Navigation — Hamburger Menu
```
[Screenshot: Mobile view (< 768px) with the hamburger menu open, showing the full-screen dropdown navigation]
```
`screenshots/mobile-nav.png`

---

## License

This project is for Mary's Boutique personal/business use. All product images and brand assets are property of Mary's Boutique.
