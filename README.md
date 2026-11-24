# Shrishti Soni — Personal Portfolio Website

A modern, futuristic, technology-inspired personal portfolio website for **Shrishti Soni**, positioned at the intersection of **AI, Business Research & Interactive Technology**.

> *"Curious about technology. Driven by research. Interested in what businesses can build next."*

---

## 🌟 Primary Positioning & Core Pillars

1. **AI & Business Research**: Market research, competitor intelligence, product research, business models, and practical AI applications.
2. **Business & Product Strategy**: Transforming early ideas and business questions into structured requirements, PRDs, and monetisation options.
3. **Gaming & Interactive Technology**: Industry exposure to gaming, game concepts, interactive experiences, and digital entertainment business models.
4. **Emerging Technologies (AR/VR)**: Spatial computing (Apple Vision Pro, Meta Quest) and immersive digital experiences.

---

## 🎨 Design Direction & Color Palette

Inspired by Linear, Stripe, Vercel, and Framer:
- **Background**: `#080D18` (Dark Navy)
- **Secondary Background**: `#101A2B` (Deep Navy / Card Base)
- **Primary Text**: `#EDF3FF`
- **Secondary Text**: `#A3B1C8`
- **Electric Cyan Accent**: `#70E1EE`
- **Subtle Violet Accent**: `#9B8CFF`
- **Accent Lime**: `#C4F28B`

Key Visual Features:
- Ambient radial backlights and glowing borders
- Custom real-time interactive connected node canvas in the Hero section
- Subtle glassmorphism (`backdrop-filter: blur(16px)`)
- Custom video playback modal with YouTube embed support
- Filterable gaming & media gallery with external link fallbacks
- Expandable case study modals with conceptual workflow architectures
- Interactive 5-step approach timeline ("From Questions to Clarity")
- Working interactive contact form with mailto fallback and email clipboard copy

---

## 📁 Project Structure

```
shrishti-soni-portfolio/
├── index.html              # Main single-page application structure
├── assets/
│   ├── profile.png         # Portrait photo (cutout/transparent background)
│   └── signature.png       # Signature graphic
├── css/
│   └── styles.css          # Design system, glassmorphism, animations, responsive rules
├── js/
│   ├── data.js             # Structured portfolio content, projects, media links & copy
│   ├── canvas.js           # Interactive connected particle node canvas (Hero)
│   ├── modal.js            # Modal manager (Case studies, Expertise, Video player)
│   └── app.js              # Application logic, filters, contact form & navigation
└── README.md               # Documentation & deployment guide
```

---

## 🚀 Running Locally

You can preview the website instantly using any of the following methods:

### Method 1: Direct File Opening
Double-click `index.html` or run in terminal:
```bash
open index.html
```

### Method 2: Python HTTP Server (Recommended)
From inside the `shrishti-soni-portfolio` directory:
```bash
python3 -m http.server 3000
```
Then visit: `http://localhost:3000`

---

## ✏️ How to Update Content & Projects

All editable content is organized cleanly in `js/data.js`:
- **Change personal info / email**: Edit `PORTFOLIO_DATA.profile`
- **Add / edit business projects**: Edit `PORTFOLIO_DATA.projects`
- **Add / edit videos or gaming links**: Edit `PORTFOLIO_DATA.gamingMedia`
- **Update tools**: Edit `PORTFOLIO_DATA.tools`
- **Update collaboration targets**: Edit `PORTFOLIO_DATA.collaboration`

---

## 🌐 1-Click Deployment Options

### Deploy to Vercel
1. Install Vercel CLI (`npm i -g vercel` or upload repository on [vercel.com](https://vercel.com))
2. Import project folder and click **Deploy**. Zero configuration required.

### Deploy to Netlify
1. Drag and drop the `shrishti-soni-portfolio` folder directly onto [app.netlify.com/drop](https://app.netlify.com/drop).
2. The website will be live in seconds with HTTPS.

### Deploy to GitHub Pages
1. Push this folder to a GitHub repository (e.g. `github.com/shrishtisonii/portfolio`).
2. Go to **Settings > Pages** and select `main` branch `/ (root)`.
