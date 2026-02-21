# ⌚ TechWatch Pro — Product Landing Page

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)
![Responsive](https://img.shields.io/badge/Responsive-Yes-blue?style=for-the-badge)

**A fully responsive product landing page for a smartwatch — built with pure HTML and CSS**

</div>

---

## 👤 About

**TechWatch Pro** is a complete product landing page built with pure HTML and CSS — no JavaScript used. It includes a fixed navigation header, hero section, features, a video section, 3-tier pricing cards, a newsletter signup form, and a footer. Fully responsive with media queries for mobile and tablet.

> This is a **CSS practice project** focused on building a real-world landing page structure with fixed header, flexbox layout, pricing cards, forms, and responsive design.

---

## 📸 Screenshots
---
<img width="2838" height="1515" alt="Image" src="https://github.com/user-attachments/assets/b56125e2-18ed-48a2-b930-b81744e03e90" />


<img width="2830" height="1519" alt="Image" src="https://github.com/user-attachments/assets/30cadaef-db36-4ae8-9ee9-1213fca446c6" />


<img width="2831" height="1502" alt="Image" src="https://github.com/user-attachments/assets/70a10c82-c477-4eda-b445-fbd1b48a9742" />



---
### 🖥 Desktop View
> Add your screenshot here!

```markdown
![TechWatch Pro Desktop](./screenshots/desktop.png)
```

### 📱 Mobile View
> Add your mobile screenshot here!

```markdown
![TechWatch Pro Mobile](./screenshots/mobile.png)
```

**How to take a screenshot:**
1. Open `index.html` in your browser
2. Press `F12` → Toggle device toolbar to test mobile view
3. Press `Ctrl + Shift + S` (Windows) or `Cmd + Shift + 4` (Mac)
4. Save in a `screenshots/` folder inside the project
5. Replace the placeholders above with your real images

---

## ✨ Features

- 🔝 **Fixed Header** — Logo + navigation stays at top while scrolling
- 🦸 **Hero Section** — Full-width banner with headline and subtitle
- ⚡ **3 Feature Cards** — Lightning Fast, Health Tracking, Long Battery Life
- 🎬 **Video Section** — Embedded YouTube iframe
- 💰 **3 Pricing Tiers** — Basic ($299), Pro ($499), Elite ($699)
- 📧 **Newsletter Form** — Email input + Subscribe button
- 📱 **Fully Responsive** — Works on mobile, tablet, and desktop
- 🎨 **Purple Gradient Theme** — Consistent brand colors throughout

---

## 🗂 Page Sections

| Section | ID / Class | Content |
|---|---|---|
| 🔝 Header | `#header` | Fixed logo + nav links |
| 🦸 Hero | `.hero` | Headline + subtitle |
| ⚡ Features | `#features` | 3 feature cards with icons |
| 🎬 How It Works | `#how-it-works` | YouTube embedded video |
| 💰 Pricing | `#pricing` | Basic / Pro / Elite cards |
| 📧 Newsletter | `.newsletter` | Email signup form |
| 📄 Footer | `footer` | Copyright 2026 |

---

## 💰 Pricing Plans

| Plan | Price | Key Feature |
|---|---|---|
| 🥉 Basic | $299 | 1 Year Warranty + Basic Health |
| 🥈 Pro | $499 | GPS Tracking + 2 Year Warranty |
| 🥇 Elite | $699 | All Features + Lifetime Warranty |

---

## 🎨 CSS Highlights

```css
/* Fixed header stays on top while scrolling */
#header {
  position: fixed;
  top: 0;
  z-index: 1000;
}

/* Purple gradient used throughout */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Feature cards lift on hover */
.feature-card:hover {
  transform: translateY(-10px);
}

/* Responsive — mobile layout */
@media (max-width: 768px) {
  #nav-bar { flex-direction: column; }
  .features-container { flex-direction: column; }
}
```

---

## 🛠 Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Full page structure & all sections |
| CSS3 | Flexbox, gradients, transitions, media queries |

> ⚠️ No JavaScript, no framework — pure HTML and CSS only.

---

## 📁 Project Structure

```
techwatch-pro/
│
├── index.html            # Full page — all 6 sections
├── styles.css            # All styles — layout, cards, responsive
├── techwatch-logo.svg    # Logo image
└── screenshots/          # Add your screenshots here
    ├── desktop.png
    └── mobile.png
```

---

## ⚙️ Installation

No installation needed!

**1. Clone the repository**

```bash
git clone https://github.com/afghanyarrami-bit/techwatch-pro.git
```

**2. Open in browser**

Double-click `index.html` — or open with **Live Server** in VS Code.

---

## 📬 Contact

**Ramin Afghanyar** — Junior Front-End Developer 🇨🇭 Switzerland

[![GitHub](https://img.shields.io/badge/GitHub-afghanyarrami--bit-black?style=flat&logo=github)](https://github.com/afghanyarrami-bit)
[![Email](https://img.shields.io/badge/Email-afghanyarrami@gmail.com-red?style=flat&logo=gmail)](mailto:afghanyarrami@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/afghanyarrami)

---

## 📄 License

MIT License © 2026 Ramin Afghanyar
