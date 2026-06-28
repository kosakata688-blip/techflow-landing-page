# TechFlow — Modern Landing Page

A modern, responsive landing page built for a fictional tech startup / SaaS company. Designed with a dark theme, purple/blue accents, smooth animations, and a clean developer-centric aesthetic.

![TechFlow Screenshot](screenshot.png)

## 🚀 Tech Stack

- **HTML5** — Semantic, accessible markup
- **CSS3** — Custom properties, Flexbox, Grid, animations
- **Vanilla JavaScript** — No frameworks, no dependencies

## ✨ Features

- **Sticky Navigation** — Logo, smooth-scroll links, scroll-aware background
- **Mobile Hamburger Menu** — Animated toggle with CSS transitions, outside-click dismiss
- **Hero Section** — Gradient background, stats, dual CTAs
- **Feature Cards** — 3-column responsive grid with hover lift effect
- **About Section** — Two-column layout with animated visual card
- **Contact Form** — Validated inputs, success message
- **Footer** — Multi-column links, social icons
- **Scroll-to-Top Button** — Appears after scrolling, smooth return
- **Fade-in Animations** — Intersection Observer with staggered delays
- **Active Nav Highlighting** — Scroll spy updates the active link
- **Fully Responsive** — Mobile-first breakpoints at 480px, 768px, 1024px
- **Dark Theme** — CSS custom properties for easy re-theming
- **Font Awesome Icons** — CDN-loaded icon set
- **Inter Font** — Google Fonts CDN

## 📦 Setup

1. **Clone or download** the repository
2. Open `index.html` in your browser — no build step required
3. That's it! Everything runs client-side with CDN-linked assets.

### Local Development

```bash
# Serve with any static server
npx serve .
# or
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## 📁 Project Structure

```
landing-page/
├── index.html          # Main HTML document
├── css/
│   └── style.css       # All styles (CSS custom properties, responsive)
├── js/
│   └── main.js         # All interactivity (vanilla JS)
├── README.md           # This file
└── .gitignore          # Git ignore rules
```

## 🎨 Design

| Element          | Value                                      |
| ---------------- | ------------------------------------------ |
| Primary Accent   | `#7c3aed` (Purple)                         |
| Secondary Accent | `#3b82f6` (Blue)                           |
| Background       | `#0a0a0f` (Deep dark)                      |
| Typography       | Inter (Google Fonts)                       |
| Icons            | Font Awesome 6 (CDN)                       |

## 📄 License

The MIT © 2026 TechFlow