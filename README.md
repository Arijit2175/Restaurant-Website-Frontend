# 🍽️ Restaurant Experience Dashboard

## 📌 Overview

An interactive single-page restaurant frontend that showcases a modern dining brand. It blends a responsive layout, light/dark theming, animated section reveals, and deep‑linkable menu and specials pages to give visitors a quick tour of offerings before they book or order.

---

## 🎯 Objectives

- Present the restaurant’s story, services, specials, and contact details in a clean, responsive UI.

- Provide quick navigation to menu and item detail pages with consistent styling.

- Deliver a smooth UX with sticky navigation, section‑aware highlighting, and scroll‑to‑top controls.

- Support light/dark themes with persisted user preference and theme‑aware imagery.

- Keep dependencies minimal (HTML, CSS, and JavaScript) for easy hosting.

---

## 🛠️ Tech Stack Used

| Layer / Component | Technologies Used                      | Description                                                                                          |
| ----------------- | -------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| **UI Markup**     | HTML5                                  | Semantic sections for hero, about, services, specials, app promo, contact, and footer.               |
| **Styling**       | CSS3 (custom properties, Grid/Flexbox) | Responsive layout, theme variables, cards, buttons, and spacing.                                     |
| **Interactivity** | Vanilla JavaScript                     | Mobile navigation toggle, active‑link highlighting, sticky header, scroll‑to‑top, theme persistence. |
| **Icons & Fonts** | Boxicons CDN, Google Fonts (Poppins)   | Iconography and typography.                                                                          |
| **Animations**    | ScrollReveal CDN                       | Section entrance animations.                                                                         |

---

## 🗂️ Project Structure

```
Restaurant-Website-Frontend/
├── public/
│   ├── (All the html files)
    └── assets/
        └── css/
            └── (All the css files) 
        └── img/
            └──(All the asset images)
        └── js/
            └── script.js
        └── scss/
            └── styles.scss          
└── README.md
```

---

## 🖥️ Dashboard Preview

**Key Sections**
- Hero section with primary CTA buttons (View Specials, View Menu)

- Services grid (dine‑in, fast food, delivery) with icons

- Specials cards linking to individual item detail pages

- App promotion block with store badges and theme‑aware artwork

- Contact call‑to‑action and footer with quick links

### Preview
![Preview](assets/img/preview.png)

---

## 🌐 Demonstration
This frontend was deployed in vercel, you can check the live version here:

[🔗 View Live Site](https://restaurant-website-frontend-ashen.vercel.app/)

---

## ⚙️ Application Behavior

- **Navigation**: Hamburger menu on mobile, sticky header on scroll, and active‑link highlighting based on section visibility.
- **Scroll UX**: Scroll-to-top button appears after scrolling; header shadow improves readability.
- **Theming**: Light/dark theme toggle with preference stored in `localStorage`; hero and app images update accordingly.
- **Animations**: ScrollReveal animates hero, about, services, specials, app, contact, and footer sections.
- **Menu & Specials**: Cards link to dedicated item pages (salads, burgers, sandwiches, drinks, sides) located in `public/`.

---

## 🚀 Future Scope

- Add menu search, filters, and dietary tags for easier navigation.
- Integrate reservation or online ordering APIs.
- Add localization support (language and currency).
- Improve accessibility (ARIA labels, focus states, color contrast checks).
- Introduce performance budgets and automated Lighthouse CI checks.

---

