# 🛒 Shopping Cart

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

**A static shopping cart UI built with HTML and Tailwind CSS**

</div>

---

## 👤 About

**Shopping Cart** is a clean, static shopping cart page built with pure HTML and **Tailwind CSS CDN** — no JavaScript used. It displays 3 product cards on the left and a fixed Order Summary panel on the right with subtotal, shipping, tax, and total.

> This is a **Tailwind CSS practice project** to learn flex layout, card components, responsive design, and building a real e-commerce UI without writing custom CSS.

---

## 📸 Screenshots

### 🖥 Desktop View

<div align="center">
  <img width="800" alt="Shopping Cart Screenshot" src="https://github.com/user-attachments/assets/Screenshot_2026-02-22_010049.png" />
</div>

> Replace the image src above with your real GitHub uploaded image link.

**How to add your screenshot to GitHub:**
1. Open your repo on GitHub
2. Go to any Issue → drag and drop your screenshot
3. Copy the generated image link
4. Paste it in the `src=""` above

---

## ✨ Features

- 🛍 **3 Product Cards** — Each with name, quantity, price, Remove button
- 📋 **Order Summary Panel** — Shows Subtotal, Shipping, Tax, Total
- 💰 **Checkout Button** — Blue button at bottom of summary
- 📱 **Responsive Layout** — Stacks vertically on mobile, side-by-side on desktop
- 🎨 **Clean UI** — Light grey background, white cards, red remove buttons

---

## 🛍 Products in Cart

| Product | Quantity | Price |
|---|---|---|
| 🎧 Wireless Headphones | 2 | $159.99 |
| 🔌 USB-C Cable | 3 | $12.99 |
| 💻 Laptop Stand | 1 | $45.00 |

---

## 💰 Order Summary

| | Amount |
|---|---|
| Subtotal | $404.96 |
| Shipping | $9.99 |
| Tax | $41.50 |
| **Total** | **$456.45** |

---

## 🎨 Tailwind Classes Used

```html
<!-- Layout -->
flex flex-col lg:flex-row gap-6 max-w-6xl mx-auto

<!-- Product Card -->
bg-white p-6 rounded-lg shadow-md

<!-- Remove Button -->
bg-red-500 hover:bg-red-600 text-white px-4 py-2 rounded

<!-- Order Summary -->
bg-white p-6 rounded-lg border-2 border-gray-200 lg:w-80

<!-- Checkout Button -->
bg-blue-600 hover:bg-blue-700 text-white text-center py-3 rounded-lg
```

---

## 🛠 Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure & product cards |
| Tailwind CSS (CDN) | All styling via utility classes |

> ⚠️ No JavaScript, no custom CSS, no framework — HTML + Tailwind CDN only.
> ⚠️ Remove buttons do NOT work — this is a static UI only.

---

## 📁 Project Structure

```
shopping-cart/
│
└── index.html      # Entire project — HTML + Tailwind CDN in one file
```

---

## ⚙️ Installation

No installation needed!

**1. Clone the repository**

```bash
git clone https://github.com/afghanyarrami-bit/shopping-cart.git
```

**2. Open in browser**

Double-click `index.html` — or open with **Live Server** in VS Code.

> ✅ Internet connection required — Tailwind CSS is loaded via CDN.

---

## 📬 Contact

**Ramin Afghanyar** — Junior Front-End Developer 🇨🇭 Switzerland

[![GitHub](https://img.shields.io/badge/GitHub-afghanyarrami--bit-black?style=flat&logo=github)](https://github.com/afghanyarrami-bit)
[![Email](https://img.shields.io/badge/Email-afghanyarrami@gmail.com-red?style=flat&logo=gmail)](mailto:afghanyarrami@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/afghanyarrami)

---

## 📄 License

MIT License © 2026 Ramin Afghanyar
