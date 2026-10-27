# 🍔 FoodieExpress — Food Delivery Landing Page
**Topic:** Modern UI Development — Tailwind CSS & Responsive Design  
**Assignment:** Module 15 — Web Application Development  

A modern, high-converting, and responsive landing page for the fictional food delivery service **FoodieExpress**, designed with clean semantic HTML5 and styled purely with **Tailwind CSS**.

---

## 🚀 Live Preview / Quick Start

Open `index.html` directly in any web browser:
- **Direct file opening:** Double click `index.html` or drag & drop into Chrome, Edge, Firefox, or Safari.
- **VS Code Live Server:** Right-click `index.html` -> "Open with Live Server" (`http://127.0.0.1:5500/index.html`).
- **Python Local Server:** Run `python -m http.server 8000` in this directory and open `http://localhost:8000`.

---

## 📋 Project Requirements Compliance Checklist

### 1. Navbar
- [x] **Website Logo/Name:** `FoodieExpress` with stylized burger icon and brand gradient styling.
- [x] **Navigation Links:** `Home`, `Categories`, `Menu`, `About Us`, `Reviews`, `Contact`.
- [x] **"Order Now" Button:** Prominent pill button with gradient background and smooth hover effect.
- [x] **⭐ Bonus: Mobile-Friendly Navigation:** Fully responsive drawer menu with hamburger toggle (`fa-bars` / `fa-xmark`), smooth backdrop blur, and auto-close when links are clicked.

### 2. Hero Section
- [x] **Catchy Heading:** `"Delicious Food Delivered to Your Door."` with gradient text effect.
- [x] **Short Description:** Clear value proposition highlighting 500+ restaurants and sub-30 minute delivery.
- [x] **"Explore Menu" Button:** High-contrast CTA button leading directly to the food dishes section.
- [x] **Attractive Food Image:** High-definition photography with floating glassmorphism statistic cards (`🔥 Fastest Delivery: 20-30 mins`, `⭐ 100% Fresh Guaranteed`, and `Free Delivery Today`).

### 3. Popular Dishes Section
- [x] **Display At Least 3 Food Cards:** 6 cards included to showcase a diverse gourmet selection:
  1. *Supreme Bacon Cheeseburger*
  2. *Artisan Truffle Pepperoni Pizza*
  3. *Spicy Tokyo Tonkotsu Ramen*
  4. *Crispy Golden Fried Chicken Box*
  5. *Salmon & Avocado Power Bowl*
  6. *Berry Bliss Belgian Waffles*
- [x] **Food Image:** Vibrant, high-resolution food photos.
- [x] **Food Name & Description:** Descriptive culinary titles and appetizing descriptions.
- [x] **Price:** Clear pricing with slashed original price displaying customer savings.
- [x] **"Order Now" Button:** Interactive button that updates the cart badge and displays a confirmation toast.
- [x] **⭐ Bonus: Discount Badges:** Badges such as `20% OFF`, `Chef's Choice`, `Popular`, `15% OFF`, and `Healthy Choice`.

### 4. Why Choose Us? Section
- [x] **Fast Delivery:** Highlighted with 🚀 motorcycle icon, 25-30m average delivery time, and live GPS tracking.
- [x] **Fresh Ingredients:** Highlighted with 🥗 organic icon and 100% locally sourced non-GMO produce.
- [x] **Affordable Prices:** Highlighted with 💰 wallet icon, zero surge charges, and loyalty cashback.

### 5. Special Offer Section
- [x] **Promotional Heading:** `"Get 20% Off Your First Order!"`
- [x] **Short Description:** Welcoming first-time customer discount copy.
- [x] **"Claim Offer" Button:** Action button with interactive copy-to-clipboard functionality for promo code `FOODIE20` and confirmation toast.
- [x] **Promotional Graphic Badge:** Eye-catching 20% discount floating sticker card.

### 6. Footer
- [x] **Website Name & Logo:** Branded header and company mission statement.
- [x] **Copyright Text:** `© 2026 FoodieExpress Inc. All rights reserved.`
- [x] **Social Media Links:** 4 social platforms (Facebook, Instagram, Twitter/X, and YouTube) with custom hover states.
- [x] **Quick Links & Contact Details:** Address, telephone, email, and 24/7 operating hours.

---

## ⭐ Bonus Challenges Implemented

1. **Food Category Section:**
   - Filter chips for *All Dishes*, *Burgers*, *Pizza*, *Asian & Ramen*, *Salad Bowls*, and *Dessert & Drinks*.
   - Interactive selection state highlighting the active category.
2. **Discount / Promotional Badges:**
   - Prominent tags on cards (`20% OFF`, `Chef's Choice`, `15% OFF`, etc.).
3. **Mobile-Friendly Navigation Menu:**
   - Responsive hamburger navigation with clean transitions and mobile cart count.
4. **Customer Review / Testimonials Section:**
   - 3 authentic customer reviews with 5-star ratings, reviewer names, roles, and avatar images.

---

## 🎨 Design & Technical Specifications

- **CSS Framework:** Pure **Tailwind CSS** (via official CDN).
- **Typography:** `Plus Jakarta Sans` for body copy and `Outfit` for headings and display text.
- **Icons:** **Font Awesome 6** (CDN) for crisp, modern iconography.
- **Layouts:** Flexbox and CSS Grid across all sections.
- **Responsive Breakpoints:**
  - Mobile (`< 640px`): Single-column cards, hamburger drawer, stacked hero.
  - Tablet (`md: 768px`): 2-column food grid, inline category layout.
  - Desktop (`lg: 1024px+`): 3-column food grid, side-by-side hero, 5-column footer.
- **Micro-Interactions & UX:**
  - Card hover lift (`hover:-translate-y-2` + `shadow-soft`).
  - Image zoom on card hover (`group-hover:scale-110`).
  - Active button states with feedback.
  - Dynamic Toast Notifications for cart additions, wishlist favoriting, and coupon copying.
  - Glassmorphism backdrop blur on header and floating hero badges.

---

## 📁 File Structure

```text
assignment_module15dj/
├── index.html       # Complete single-page landing page (HTML5 + Tailwind CSS + Vanilla JS)
└── README.md        # Documentation and assignment rubrics audit
```
