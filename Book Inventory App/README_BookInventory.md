# 📚 Book Inventory

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

**A styled book tracking table built with pure HTML and CSS**

</div>

---

## 👤 About

**Book Inventory** is a clean, styled book tracking table built with pure HTML and CSS — no JavaScript used. It displays 8 books in a table with their title, author, category, reading status, and star rating. Each row is color-coded based on reading status.

> This is a **CSS practice project** focused on CSS attribute selectors, gradients, status badges, star rating styling, and hover effects.

---

## ✨ Features

- 📋 **Book Table** — Shows Title, Author, Category, Status, and Rating
- 🟢 **Color-coded Rows** — Green = Read, Orange = To Read, Blue = In Progress
- 🏷 **Status Badges** — Styled pill badges per reading status
- ⭐ **Star Ratings** — Visual 1, 2, or 3 star ratings using CSS only
- 🎨 **Gradient Background** — Dark blue-grey gradient page background
- 🖱 **Hover Effect** — Rows slightly scale up on hover
- 📱 **Responsive Table** — Max-width 1200px, centered layout

---

## 📖 Books in the Inventory

| Title | Author | Category | Status | Rating |
|---|---|---|---|---|
| The Great Gatsby | F. Scott Fitzgerald | Classic Fiction | ✅ Read | ⭐⭐⭐ |
| 1984 | George Orwell | Dystopian Fiction | 📌 To Read | — |
| Sapiens | Yuval Noah Harari | Non-Fiction | 🔄 In Progress | — |
| To Kill a Mockingbird | Harper Lee | Classic Fiction | ✅ Read | ⭐⭐ |
| Pride and Prejudice | Jane Austen | Romance | ✅ Read | ⭐ |
| The Hobbit | J.R.R. Tolkien | Fantasy | 📌 To Read | — |
| Atomic Habits | James Clear | Self-Help | 🔄 In Progress | — |
| The Catcher in the Rye | J.D. Salinger | Classic Fiction | ✅ Read | ⭐⭐⭐ |

---

## 🎨 CSS Highlights

This project focuses on advanced CSS selectors and styling:

```css
/* Attribute selectors for row background colors */
tr[class="read"]        → green gradient background
tr[class="to-read"]     → orange gradient background
tr[class="in-progress"] → blue gradient background

/* Star ratings using CSS only */
span[class*="one"]   → 1 star filled gold
span[class*="two"]   → 2 stars filled gold
span[class*="three"] → 3 stars filled gold

/* Hover effect on rows */
tbody tr:hover {
  transform: scale(1.01);
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}
```

---

## 🛠 Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Table structure & semantic layout |
| CSS3 | All styling — gradients, badges, stars, hover |

> ⚠️ No JavaScript, no framework — pure HTML and CSS only.

---

## 📁 Project Structure

```
book-inventory/
│
├── index.html      # Table structure with all 8 books
└── styles.css      # All styling — colors, badges, stars, hover
```

---

## ⚙️ Installation

No installation needed!

**1. Clone the repository**

```bash
git clone https://github.com/afghanyarrami-bit/book-inventory.git
```

**2. Open in browser**

Double-click `index.html` — or open with **Live Server** in VS Code.

---

## 📬 Contact

**Ramin Afghanyar** — Junior Front-End Developer 🇨🇭 Switzerland

[![GitHub](https://img.shields.io/badge/GitHub-afghanyarrami--bit-black?style=flat&logo=github)](https://github.com/afghanyarrami-bit)
[![Email](https://img.shields.io/badge/Email-afghanyarrami@gmail.com-red?style=flat&logo=gmail)](mailto:afghanyarrami@gmail.com)

---

## 📄 License

MIT License © 2026 Ramin Afghanyar
