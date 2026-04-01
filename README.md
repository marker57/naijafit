<div align="center">

# 🇳🇬 NaijaFit

### Nigerian Calorie & BMI Tracker

**The only calorie tracker built from the ground up for Nigerian food culture.**
Track eba, jollof rice, egusi, suya — not chicken caesar salads.

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_App-00D68F?style=for-the-badge)](https://yourusername.github.io/naijafit)
[![HTML](https://img.shields.io/badge/Built_With-HTML%2FCSS%2FJS-FF6B35?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/yourusername/naijafit)
[![License](https://img.shields.io/badge/License-MIT-004E89?style=for-the-badge)](LICENSE)
[![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-00D68F?style=for-the-badge)](https://github.com/yourusername/naijafit)

---

*Built for the gym-goer in Lagos, the student in Abuja, the mum in Port Harcourt —*
*anyone who wants to understand what they're actually eating.*

</div>

---

## 📸 Preview

> **Deep navy + electric green** design inspired by professional health apps.
> Clean, fast, and works entirely in your browser — no installs, no accounts.

| Feature | Screenshot |
|---|---|
| 🎯 Onboarding & Goals | Set your name, body stats, daily calorie target and weight goal in 3 steps |
| 📊 Calorie Ring | Animated progress ring that fills as you log meals throughout the day |
| ⚖️ BMI Analysis | Live BMI score with spectrum bar, category badge, and personalised Nigerian diet tip |
| 📈 Weekly Intake | Interactive bar chart with hover animations showing your 7-day history |
| 💬 Daily Quotes | 30 rotating motivation quotes — one new one every day |

---

## ✨ Features

### 🍛 100% Nigerian Food Database
Over **65 verified Nigerian meals** with calorie estimates across 10 serving units:

| Category | Examples |
|---|---|
| **Swallows** | Eba, Pounded Yam, Amala, Fufu, Semovita, Wheat Swallow |
| **Soups** | Egusi, Ogbono, Banga, Efo Riro, Afang, Okra, Oha, Edikaikong |
| **Rice Dishes** | Jollof Rice, Fried Rice, Ofada Rice, Coconut Rice |
| **Proteins** | Suya, Kilishi, Grilled Chicken, Goat Meat, Fried Fish, Moi Moi |
| **Street Food** | Puff Puff, Chin Chin, Akara, Meat Pie, Roasted Corn |
| **Drinks** | Zobo, Kunu, Chapman, Fura da Nono |
| **Staples** | Boiled Yam, Dodo, Plantain Chips, Indomie, Beans Porridge |

### 🎯 Smart Goal System
- Set a **personalised daily calorie target** (not a generic TDEE formula)
- Set a **target weight** and track how many kg to lose or gain
- All goals are editable any time via the Goals button
- Goals display as a clean dashboard with live progress

### 📊 Calorie Display
- **Animated SVG ring** with gradient stroke and glow effect
- **Progress bar** with smooth spring animation
- **3-pill summary** (eaten / goal / left)
- Turns red when you exceed your daily goal
- Top stats row: kcal today, meals logged, kcal remaining

### 💾 Data Persistence (localStorage)
- Everything saves automatically in your browser
- Come back tomorrow — your profile and goals are still there
- Today's meals reset at midnight automatically
- Weekly chart data persists across days
- One-click data clear if you want a fresh start

### ⚖️ BMI Analysis
- Calculates BMI from your weight and height
- Visual spectrum bar with animated needle
- Category badges: Underweight / Normal / Overweight / Obese
- Personalised Nigerian diet tip for each category
- Ideal body weight (IBW) calculation

### 📈 Weekly Bar Chart
- Hover animations with `scaleY` spring transform
- Floating tooltip showing exact kcal on hover
- Today's bar glows with gradient + box-shadow
- Persistent — bars remember previous days

### 💬 Daily Motivation
- 30 curated quotes including Nigeria-specific sayings
- Rotates automatically based on the date
- Never shows the same quote twice in a row

---

## 🚀 Getting Started

### Option 1 — Just open it
Download `index.html` and open it in any browser. That's it. No server needed.

```bash
git clone https://github.com/yourusername/naijafit.git
cd naijafit
open index.html   # macOS
# OR
start index.html  # Windows
```

### Option 2 — Deploy to GitHub Pages (Free)
```bash
git clone https://github.com/yourusername/naijafit.git
cd naijafit
# Push to your repo, enable GitHub Pages in Settings → Pages → main branch
```
Your live URL: `https://yourusername.github.io/naijafit`

### Option 3 — Netlify Drop (30 seconds)
Drag and drop `index.html` at **netlify.com/drop** for an instant live URL.

---

## 🏗️ Tech Stack

```
NaijaFit is intentionally zero-dependency.
No React. No Node. No build step. No npm install.
Just one HTML file that works everywhere.
```

| Layer | Technology |
|---|---|
| **Structure** | Semantic HTML5 |
| **Styling** | Pure CSS3 with custom properties (CSS variables) |
| **Logic** | Vanilla JavaScript (ES6+) |
| **Storage** | Web localStorage API |
| **Fonts** | Google Fonts — Clash Display + Plus Jakarta Sans |
| **Animations** | CSS keyframes + SVG stroke animation |
| **Charts** | Pure CSS flex bar chart |
| **Hosting** | Static — any CDN or file host |

---

## 📁 Project Structure

```
naijafit/
│
├── index.html          # The entire app — HTML + CSS + JS in one file
└── README.md           # You are here
```

This is intentional. A single file means:
- Zero deployment complexity
- Works offline after first load
- Easy to share, fork, and modify
- No broken asset paths

---

## 🔬 How Calorie Estimates Work

Calorie values are sourced from:
- Nigerian nutrition research databases
- FitNigerian.com food calorie lists
- MyFitnessPal entries for Nigerian foods (cross-referenced)
- Published nutritional content from Nigerian packaged goods

Each food has calorie values mapped across **10 serving units**:
`cup` · `wrap` · `plate` · `piece` · `spoon (tbsp)` · `gram (100g)` · `pack` · `bowl` · `skewer` · `slice`

> ⚠️ **Disclaimer:** All calorie values are estimates. Actual values vary based on cooking method, oil quantity, ingredient ratios, and portion size. This app is for general guidance only and is not a substitute for professional nutritional advice.

---

## 🗺️ Roadmap

These features are planned for future versions:

- [ ] **PWA support** — install on phone homescreen, works offline
- [ ] **Macro tracking** — protein, carbs, and fat breakdown per meal
- [ ] **Photo logging** — snap a photo of your food
- [ ] **Meal history** — view past days, not just today
- [ ] **Water intake tracker**
- [ ] **Cloud sync** — optional account to sync across devices
- [ ] **Dark/light mode toggle**
- [ ] **More foods** — expand to 200+ Nigerian dishes
- [ ] **Recipe builder** — calculate calories for home-cooked combinations

---

## 🤝 Contributing

Contributions are welcome! If you know of a Nigerian food missing from the database, or have more accurate calorie data, please open a pull request.

```bash
# 1. Fork the repository
# 2. Add your food to the DB array in index.html
# 3. Follow the existing data format:
{n:"Food name", e:"emoji", cup:XXX, wrap:XXX, plate:XXX, piece:XXX,
 gram:XXX, "spoon (tbsp)":XXX, pack:XXX, bowl:XXX, skewer:XXX, slice:XXX}
# 4. Open a pull request with a brief description
```

**Areas where help is especially welcome:**
- Northern Nigerian dishes (Miyan Kuka, Tuwon Masara, etc.)
- South-South dishes (Banga rice, Starch, etc.)
- More accurate calorie data with cited sources
- Yoruba traditional dishes
- Igbo traditional dishes

---

## 📄 License

```
MIT License — free to use, modify, and distribute.
If you build something cool with it, a mention is appreciated but not required.
```

---

## 👤 Author

Built with 🇳🇬 pride by **Ighotegunor Great**

[![Twitter](https://img.shields.io/badge/Twitter-@runoverze-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/runoverze)
[![GitHub](https://img.shields.io/badge/GitHub-marker57-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/marker57)

---

<div align="center">

**If this project helped you, please give it a ⭐ on GitHub.**

*Made for Nigeria. Built with love. Powered by jollof rice.*

🇳🇬

</div>

