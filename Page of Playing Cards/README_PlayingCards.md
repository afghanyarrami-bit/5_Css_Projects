# ♠ Classic Playing Cards

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

**A classic playing cards display built with pure HTML and CSS**

</div>

---

## 👤 About

**Classic Playing Cards** is a visually styled playing card display built with pure HTML and CSS — no JavaScript used. It shows 6 playing cards on a deep blue gradient background with hover animations. Cards are styled with correct left, middle, and right sections just like real playing cards.

> This is a **CSS practice project** to learn flexbox layout, card design, hover transitions, color classes, and CSS positioning.

---

## ✨ Features

- 🃏 **6 Playing Cards** — Ace, King, Queen, Jack, Ten, Seven
- ♠♥♦♣ **All 4 Suits** — Spades, Hearts, Diamonds, Clubs
- 🔴 **Red & Black Cards** — Correct colors per suit
- 🖱 **Hover Animation** — Cards lift up and rotate slightly on hover
- 🎨 **Deep Blue Background** — Gradient background like a card table
- 📐 **Real Card Layout** — Left corner, center symbol, right corner (rotated)
- 🔲 **Responsive Wrap** — Cards wrap on smaller screens using `flex-wrap`

---

## 🃏 Cards Displayed

| Card  | Suit       | Color    |
| ----- | ---------- | -------- |
| Ace   | ♠ Spades   | ⬛ Black |
| King  | ♥ Hearts   | 🔴 Red   |
| Queen | ♦ Diamonds | 🔴 Red   |
| Jack  | ♣ Clubs    | ⬛ Black |
| Ten   | ♥ Hearts   | 🔴 Red   |
| Seven | ♠ Spades   | ⬛ Black |

---

## 🎨 CSS Highlights

```css
/* Hover effect — card lifts and rotates */
.card:hover {
  transform: translateY(-10px) rotate(2deg);
  box-shadow: 0 15px 40px rgba(0, 0, 0, 0.4);
}

/* Red cards */
.card.red {
  color: #d32f2f;
}

/* Black cards */
.card.black {
  color: #1a1a1a;
}

/* Right corner flipped upside down like real cards */
.right {
  transform: rotate(180deg);
}
```

---

## 🛠 Tech Stack

| Technology | Usage                                          |
| ---------- | ---------------------------------------------- |
| HTML5      | Card structure & layout                        |
| CSS3       | Flexbox, hover transitions, gradients, shadows |

> ⚠️ No JavaScript, no Tailwind, no framework — pure HTML and CSS only.

---

## 📸 Screenshots

<img width="2815" height="1406" alt="Image" src="https://github.com/user-attachments/assets/cd5e941c-35b5-4f46-a9b2-e730792628d1" />

---

### 🖥 Main View

> Add your screenshot here after taking one!

```markdown
![Playing Cards Screenshot](./screenshot.png)
```

**How to take a screenshot:**

1. Open `index.html` in your browser
2. Press `Ctrl + Shift + S` (Windows) or `Cmd + Shift + 4` (Mac)
3. Save as `screenshot.png` in the project root folder
4. Replace the placeholder above with your real screenshot

---

## 📁 Project Structure

```
playing-cards/
│
├── index.html      # All 6 cards structure
└── style.css       # Card styles, hover effects, colors
```

---

## ⚙️ Installation

No installation needed!

**1. Clone the repository**

```bash
git clone https://github.com/afghanyarrami-bit/playing-cards.git
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
