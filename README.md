# 🛍️ Production-Ready Shopify Custom Sections (OS 2.0)

A collection of lightweight, modern Shopify Liquid & Vanilla JS sections built for **Online Store 2.0**. Designed to provide essential e-commerce functionality natively—eliminating the need for slow, costly third-party apps.

---

## 📦 What's Included

### 1. Free Shipping Goal Bar with 1-Click Upsell (`sections/free-shipping-upsell.liquid`)
- **Problem Solved:** Increases Average Order Value (AOV) natively without $15/mo apps.
- **Features:**
  - Dynamic progress calculation based on cart total.
  - Built-in 1-click upsell product card that adds to cart via Ajax.
  - Fully customizable threshold, messaging, and colors via Theme Customizer.

### 2. Sticky "Add to Cart" Bar (`sections/sticky-add-to-cart.liquid`)
- **Problem Solved:** Prevents lost conversions on long product pages (reviews, long descriptions).
- **Features:**
  - High-performance slide-in triggered using `IntersectionObserver` (no laggy scroll listeners).
  - Handles variant switching, dynamic price changes, and out-of-stock states.
  - Native Ajax Add-to-Cart with responsive desktop/mobile layouts.

### 3. Native Before / After Comparison Slider (`sections/before-after-slider.liquid`)
- **Problem Solved:** Ideal for skincare, beauty, restoration, and apparel brands wanting to show proof of results without bulky jQuery plugins.
- **Features:**
  - Zero external dependencies; 60fps smooth touch and drag performance.
  - Customizable labels, starting divider position, and container width.

---

## 🚀 Installation & Usage

1. In your Shopify Admin, go to **Online Store** > **Themes** > **Edit code**.
2. Under the **Sections** folder, click **Add a new section**.
3. Name the section matching the file (e.g., `free-shipping-upsell`) and paste the code.
4. Save the file.
5. Open the **Theme Customizer**, click **Add section**, and select your new section!

---

## 🛠 Tech Stack
- **Engine:** Shopify Liquid
- **Architecture:** Online Store 2.0 (JSON Schemas)
- **Front-End:** Vanilla JavaScript (ES6+), Modern CSS
