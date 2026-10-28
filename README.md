# Vijay Reddy – AI Engineer Portfolio

A modern, high-performance personal portfolio website for Vijay Reddy, featuring an interactive Three.js 3D skills constellation background, glassmorphism cards with 3D cursor tilt effects, and comprehensive project & experience showcases.

---

## 🚀 Features

- **Interactive 3D Three.js Background**:
  - Rotating celestial globe of skills clustered and color-coded by technical area (GenAI/LLMs, Frameworks, NLP & Retrieval, Vector Databases, Cloud, Data Engineering).
  - Central wireframe geometric core (Icosahedron & Octahedron) symbolizing AI model architectures.
  - Orbiting particle signal rings and cosmic dust background.
  - Reactive mouse tracking, touch swipe controls on mobile, and scroll-depth interpolation (camera flies into the constellation on scroll).
  - High-DPI font re-rendering with `document.fonts.ready` on Google Font load.
- **Glassmorphic UI & 3D Tilt**:
  - Cards with backdrop blur, subtle borders, and dynamic perspective cursor-tilt physics.
- **Responsive Layout**:
  - Optimized for desktop, tablet, and mobile with balanced spacing and typography.
- **Accessible & Performance-tuned**:
  - `prefers-reduced-motion` compliance to respect user accessibility preferences.
  - Base64 embedded profile image with fallback avatar initials badge.
  - Zero build step required: single self-contained HTML file runnable directly in any browser.

---

## 📂 Project Structure

```
Portfolio/
├── index.html        # Complete self-contained portfolio webpage
└── README.md         # Documentation & deployment guide
```

---

## 💻 How to View Locally

Simply double-click `index.html` to open it in Chrome, Edge, Firefox, or Safari, or serve it with Python / Node:

```bash
# Using Python
python -m http.server 8000

# Using Node (npx)
npx serve .
```

Then visit `http://localhost:8000` in your browser.

---

## 🌐 Free 1-Click Deployment Options

### 1. GitHub Pages
1. Push this folder to a GitHub repository named `<your-username>.github.io` (or `portfolio`).
2. Go to **Settings** > **Pages** in GitHub.
3. Select the `main` branch, root `/` folder, and click **Save**.

### 2. Vercel
1. Run `npx vercel` in this folder, or connect your GitHub repository in the [Vercel Dashboard](https://vercel.com).
2. It will deploy automatically with global CDN caching.

### 3. Netlify
1. Drag and drop this folder directly into [Netlify Drop](https://app.netlify.com/drop).

