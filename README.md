<div align="center">

# Swiggy — Good food, good mood

### A responsive food-delivery landing page concept with a smart, budget-aware food finder.

Built by **Aryan Tomar** · CSE (AI), 5th semester · MIET

[![HTML](https://img.shields.io/badge/HTML5-markup-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-CDN-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?logo=javascript&logoColor=222)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Layout-responsive-16A34A)](#browser-support-and-responsive-design)
[![License](https://img.shields.io/badge/License-not%20specified-lightgrey)](#project-notes)

</div>

---

## About the project

This project is a polished, responsive food-delivery landing page inspired by the familiar Swiggy experience. It brings restaurant discovery, groceries, dining, delivery services, and a small food-recommendation assistant into one easy-to-explore interface.

It is a **frontend concept**, not an official Swiggy product. The interactions and restaurant data are designed to demonstrate the experience; they do not place orders or connect to live Swiggy services.

## Try it locally

There is no build step or package installation required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. For a smoother development workflow, open the project folder in VS Code and use the **Live Server** extension.

> Tailwind CSS, Google Fonts, and food photography load from external services, so an internet connection is needed for the complete visual experience.

## Highlights

- **Responsive experience:** mobile-friendly sticky header and bottom navigation, tablet controls, and a multi-column desktop layout.
- **Location discovery:** type an area to see sample location suggestions. Browser location access is requested only when the visitor presses **Detect location**.
- **Restaurant discovery:** filter by delivery speed, rating, vegetarian options, offers, and budget; search the sample restaurant list by name or cuisine.
- **Smart Food Finder:** describe a craving and preferences such as “veg under ₹200” or “biryani under 300.” The assistant ranks the included sample restaurants using dish price, rating, review count, and estimated delivery time.
- **Neighborhood Drop concept:** explores an opt-in shared delivery window designed to make nearby deliveries more efficient.
- **Small interaction details:** sample cart feedback, FAQ accordions, food-category lanes, step-by-step order guidance, and mobile search.
- **Accessible foundations:** semantic page sections, descriptive image text, labelled controls, keyboard dismissal for the assistant, and reduced-motion support.

## Smart Food Finder

The assistant is intentionally **local and rule-based**: it filters and sorts the sample catalog directly in the browser. It does not call an AI model, search every restaurant, or access live reviews.

All restaurant names, menu prices, ratings, review counts, offers, and delivery estimates in the demo are illustrative. Delivery fees are not included in the sample dish prices.

To turn this into a real recommendation feature, connect it to an authorized restaurant/menu API through a backend. The backend can retrieve current offers and review data, apply availability and delivery-area rules, and return comparable results. Keep API credentials on the server—not in browser JavaScript.

## Neighborhood Drop

Neighborhood Drop is a product concept for grouping nearby orders into an opt-in delivery window. In this frontend demo, joining or leaving a drop only changes the preview UI; there is no real address verification, route planning, fee calculation, order sharing, or payment.

A production implementation would need delivery-zone eligibility, capacity and cutoff handling, route optimization, transparent savings calculations, order privacy, and confirmation before checkout.

## Built with

- **HTML5** for page structure
- **Tailwind CSS CDN** for utility-first styling
- **Vanilla JavaScript** for location suggestions, filtering, search, demo cart, and the food finder
- **Google Fonts** for DM Sans and Manrope
- **Unsplash** for food and lifestyle photography

## Repository structure

```text
.
├── .gitignore      # Local editor files, environment files, and assignment brief
├── index.html       # Complete landing page, styles, and browser interactions
└── README.md        # Project overview and getting-started guide
```

## Browser support and responsive design

The page uses standard HTML, CSS, and JavaScript and is designed to work in current versions of Chrome, Edge, Firefox, and Safari. Its layout was checked at mobile, tablet, desktop, and wide-screen viewport sizes.

For production use, consider compiling Tailwind into a static stylesheet, self-hosting or licensing external assets appropriately, and testing with the specific browsers and devices your users rely on.

## Project notes

- This is an independent educational frontend concept and is not affiliated with or endorsed by Swiggy.
- The project has no backend, account system, checkout, or live restaurant integrations.
- A software license has not been selected for this repository. Unless a license is added, standard copyright protections apply.

## Credits

**Designed and built by Aryan Tomar**<br>
CSE (AI) · 5th semester · MIET
