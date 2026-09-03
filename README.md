# 🥗 Nature's Platter

A modern and responsive grocery landing page built using **HTML5 and Tailwind CSS**. 
The website showcases grocery services, popular products, promotional offers, and a newsletter subscription section.

---

## 📌 Project Overview

**Nature's Platter** is a grocery-themed landing page designed to present fresh products, grocery services, special offers, and promotional information in a clean and modern interface.

The project focuses on practicing **Tailwind CSS utility classes**, responsive layouts, CSS Grid, Flexbox, responsive navigation, product cards, promotional sections, and modern landing-page design.

The page includes:

- Responsive navigation
- Hero/banner section
- Services section
- Popular products
- Promotional offers
- Newsletter subscription section
- Social media icons
- Responsive mobile layout
- Footer section

---

## 🚀 Features

### 🧭 Responsive Navigation

The navigation bar contains:

- Nature's Platter logo
- Product link
- Services link
- Contact Us link
- Search icon
- Shopping cart icon
- Login button
- Register button

A separate mobile navigation layout is also included for smaller screens. :contentReference[oaicite:1]{index=1}

---

### 🌿 Hero Section

The hero section introduces the Nature's Platter brand with the headline:

> Freshness You Can Count On, Price You'll Love!

It also includes a short description encouraging users to shop for daily grocery essentials.

The section uses a large hero image and responsive sizing for different screen sizes. :contentReference[oaicite:2]{index=2}

---

### 🛎️ Services Section

The Services section highlights three major services:

1. **24/7 Services**
2. **Fast Delivery**
3. **Healthy Products**

Each service contains:

- Service icon
- Service title
- Description
- Card-style layout

The service cards use a responsive grid that changes from one column on smaller screens to three columns on medium and larger screens. :contentReference[oaicite:3]{index=3}

---

### 🛒 Popular Products

The Popular Products section showcases grocery items using product cards.

The section contains:

- Promotional discount card
- Product images
- Product ratings
- Product names
- Product prices

Example products represented in the UI include:

- Onion
- Potato
- Tomato

A promotional card also highlights a **30% off** offer. :contentReference[oaicite:4]{index=4}

The layout uses Tailwind CSS Grid to create a responsive product arrangement.

---

### 🎁 Arrival & Offers

The Arrival & Offers section displays promotional offers from different product brands.

The current UI includes:

#### Dawat Offer

- Cook Exotic Dishes
- Up to 20% OFF

#### Gate Offer

- World's No.1 Rice
- Up to 40% OFF

Both promotional cards use different background colors, product imagery, and responsive layouts. :contentReference[oaicite:5]{index=5}

---

### 📰 Grocery Newsletter

The footer contains a large **Get Grocery News!** subscription section.

Users can enter an email address into an email input field and click the **Subscribe** button.

The section also contains a grocery basket image. :contentReference[oaicite:6]{index=6}

> **Note:** The newsletter form is currently a frontend UI only. There is no backend or email subscription service connected to the form.

---

### 📱 Social Media Section

The footer includes social media icons for:

- Facebook
- Instagram
- LinkedIn
- YouTube

These icons are provided using **Font Awesome**. :contentReference[oaicite:7]{index=7}

---

## 📱 Responsive Design

The website is designed to work across different screen sizes using Tailwind CSS responsive utilities.

Examples include:

- Desktop navigation is displayed using `md:flex`.
- Mobile navigation is displayed using `md:hidden`.
- Service cards change from one column to three columns.
- Product layouts adjust at medium screen sizes.
- Footer content changes between one and multiple columns.
- Newsletter content changes from one column to two columns.

Example:

```html
<div class="grid grid-cols-1 md:grid-cols-3 gap-3">