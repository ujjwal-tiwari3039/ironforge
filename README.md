# 🏋️ IronForge Gym — Web Design Demo

A fully responsive, single-page gym website built as a **web design demo project** to showcase modern frontend techniques including animations, layout design, interactive components, and visual aesthetics.

---

## 📸 Project Overview

**IronForge Gym** is a fictional gym brand website designed to demonstrate professional-grade web design skills. The project focuses on visual storytelling, dark industrial aesthetics, and interactive UI elements — all built with pure HTML, CSS, and vanilla JavaScript (no frameworks).

---

## ✨ Features

### Design & Aesthetics
- Dark industrial theme with gold (`#f5c518`) and fire orange (`#ff4b00`) accents
- Custom animated cursor with lag-trail effect
- Full-screen hero section with slow Ken Burns zoom animation
- Infinite scrolling marquee ticker
- Grayscale-to-color hover effects on trainer cards
- Clipped polygon button shapes for a sharp, angular design language

### Sections
| Section | Description |
|---|---|
| **Navigation** | Fixed navbar with smooth scroll links and CTA button |
| **Hero** | Cinematic full-screen background with staggered text animations |
| **Stats Bar** | Key metrics displayed in a gold highlight bar |
| **About** | Two-column layout with feature list and badge overlay |
| **Classes** | Asymmetric CSS Grid card layout with hover reveals |
| **Trainers** | 4-column grid with grayscale photo reveal and bio animation |
| **Schedule** | Interactive day selector with dynamic class listings |
| **Pricing** | Three-tier membership cards with a featured plan |
| **Join CTA** | Sign-up form section with overlay background |
| **Footer** | Full sitemap, contact info, and social links |

### Interactivity
- **Schedule Tab Switcher** — click any day to load that day's classes dynamically via JavaScript
- **Scroll Reveal Animations** — elements fade in as you scroll using `IntersectionObserver`
- **Hover Micro-interactions** — nav links, buttons, cards, and trainer photos all have transitions
- **Custom Cursor** — animated dot + ring cursor that scales on hover over interactive elements

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Semantic structure and layout |
| **CSS3** | Animations, Grid, Flexbox, clip-path, custom properties |
| **Vanilla JavaScript** | Dynamic schedule rendering, cursor animation, scroll observer |
| **Google Fonts** | Bebas Neue (display), Barlow Condensed (UI), Barlow (body) |
| **Unsplash** | Placeholder photography via CDN |

> No frameworks. No build tools. No dependencies. Just clean, handwritten code.

---

## 📁 File Structure

```
ironforge-gym/
│
├── index.html        # Complete single-page website (HTML + CSS + JS)
└── README.md         # Project documentation
```

---

## 🚀 Getting Started

### Run Locally
1. Clone or download the repository
2. Open `index.html` in any modern browser

```bash
# Using a simple local server (optional)
npx serve .
# or
python -m http.server 8000
```

No installation, no build step — just open and go.

---

## 🎨 Design Decisions

### Color Palette
| Token | Hex | Usage |
|---|---|---|
| `--black` | `#0a0a0a` | Page background |
| `--charcoal` | `#111111` | Section backgrounds |
| `--gold` | `#f5c518` | Primary accent, CTAs |
| `--fire` | `#ff4b00` | Hover states, urgency |
| `--white` | `#f0ede8` | Body text |
| `--ash` | `#888888` | Secondary/muted text |

### Typography
- **Bebas Neue** — display headings, hero titles, large numerics
- **Barlow Condensed** — labels, navigation, buttons, tags
- **Barlow** — body copy, descriptions

### Layout Techniques
- CSS Grid for asymmetric class cards and trainer grids
- Flexbox for navigation, stats bar, and footer
- `clip-path: polygon()` for angular button shapes
- CSS custom properties (`var()`) for consistent theming
- `position: absolute` + `z-index` stacking for hero overlays

---

## 📱 Responsive Design

The layout adapts across breakpoints:

- **Desktop (> 768px)** — Full multi-column layouts, custom cursor active
- **Mobile (≤ 768px)** — Single column stacking, nav links hidden, padding reduced

---

## 💡 Key Concepts Demonstrated

- **CSS Animations** — `@keyframes`, `animation-delay`, `transition`
- **IntersectionObserver API** — Scroll-triggered reveal animations
- **CSS Grid** — Complex asymmetric layouts with `grid-row: span`
- **CSS Custom Properties** — Design token system for theming
- **DOM Manipulation** — Dynamic content rendering via JavaScript
- **`mix-blend-mode`** — Cursor blending effect
- **`clip-path`** — Non-rectangular shapes for buttons and badges
- **Pseudo-elements** — `::before`, `::after` for decorative lines and underline animations

---

## 🔮 Possible Enhancements

- [ ] Add a mobile hamburger menu
- [ ] Integrate a real booking form with form validation
- [ ] Add a testimonials / reviews carousel
- [ ] Implement a dark/light theme toggle
- [ ] Add page transitions between sections
- [ ] Connect to a backend for live schedule data

---

## 👤 Author

Built as a **web design portfolio/demo project** to practice and showcase:
- UI/UX design thinking
- Advanced CSS techniques
- Vanilla JavaScript DOM manipulation
- Responsive layout design

---

## 📄 License

This is a demo project made for learning and portfolio purposes. All images are sourced from [Unsplash](https://unsplash.com) (free to use). The gym brand "IronForge" is entirely fictional.
