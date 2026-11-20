<div align="center">

<img src="favicon.svg" alt="Sizzy logo" width="80" height="80" />

# SIZZY

### Your True Size. Every Brand. Zero Guessing.

*Height, weight and build in. Your size at every brand out.*

<br/>

[![Live Demo](https://img.shields.io/badge/Live_Demo-sizzy--studio.vercel.app-C8FF3D?style=for-the-badge&logo=vercel&logoColor=black&labelColor=07080A)](https://sizzy-studio.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-C8FF3D?style=for-the-badge&labelColor=07080A)](LICENSE)

![HTML5](https://img.shields.io/badge/HTML5-07080A?style=flat-square&logo=html5&logoColor=C8FF3D)
![CSS3](https://img.shields.io/badge/CSS3-07080A?style=flat-square&logo=css3&logoColor=C8FF3D)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-07080A?style=flat-square&logo=javascript&logoColor=C8FF3D)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-07080A?style=flat-square&labelColor=07080A&color=C8FF3D)
![No Backend](https://img.shields.io/badge/Backend-None-07080A?style=flat-square&labelColor=07080A&color=C8FF3D)
![Vercel](https://img.shields.io/badge/Vercel-07080A?style=flat-square&logo=vercel&logoColor=C8FF3D)

[**Live Demo**](https://sizzy-studio.vercel.app/) · [**Source Code**](https://github.com/akshar-g/Sizzy) · [**Report a Bug**](https://github.com/akshar-g/Sizzy/issues)

</div>

---

## ✦ Overview

**Sizzy** is a fashion-tech web app that takes the guesswork out of buying clothes online.

There is no global standard for clothing sizes. A Medium at one brand fits like a Large at another. Most people don't know their exact chest measurement, but almost everyone knows their **height, weight and general build**. Sizzy turns those three numbers into **brand-specific size recommendations**, using each brand's published size charts and transparent ease calculations.

No account. No backend. No uploads. Everything runs in your browser.

---

## ✦ Features

| | Feature | What it does |
|---|---|---|
| 📏 | **Find My Size** | Enter height, weight and build (metric or imperial, men's or women's) to get estimated measurements and a recommended size at every brand. Add a size you already own to sharpen the result. |
| 📷 | **Photo Estimate** *(optional)* | Add a front and back photo for a quick body estimate. Photos are analysed on-device and never uploaded or stored. |
| 🧪 | **Fit Lab** | See your build as a pixel-art avatar wearing any size, with a live heatmap of chest and shoulder fit, from snug to oversized. |
| 👕 | **Catalog** | Browse garments across tees, polos and shirts, filter by brand, category and fit style, and see your size on every item. Add items from any brand page by entering their size-guide numbers. |
| ⚖️ | **Compare** | Put brands side by side and see how the same body maps to different size charts. |
| 🗄️ | **My Closet** | Three tabs: **Wishlist** for saved items, **Looks** for saved avatar outfits, and **Fit Journal** for sizes you've tried. |
| 🎯 | **Self-Learning Fit** | Mark a purchase as "Too tight" or "Too loose" in your Fit Journal and Sizzy nudges that brand's offset by 1 cm for all future recommendations. |
| ❓ | **Help & FAQ** | A slide-over drawer explaining where the data comes from and how every estimate is calculated. |

---

## ✦ How It Works

1. **Estimate your body.** Chest size is modeled from height and BMI, then adjusted for build (Slim −2 cm, Athletic +3 cm, up to +8 cm for Bigger builds). If you enter a size you already own, the estimate is blended 50/50 with that brand's chest midpoint.
2. **Normalize each brand.** Some brands publish body measurements and others publish flat garment widths. Sizzy converts garment widths to body circumference by subtracting standard ease (for example 10 cm for regular shirts), so every brand is compared like for like.
3. **Match and personalize.** Your numbers are matched against each brand's chart, then tuned by your fit preference and any Fit Journal feedback.

---

## ✦ Design

A dark, glassy interface with a lime accent.

- 🪟 **Liquid-glass UI** with floating blurred navbar, specular borders and spring-style motion
- 🎞️ **Scroll-driven hero** with a morphing SVG shirt
- 🕹️ **Pixel-art avatars** and original SVG garment artwork
- 🔤 **Typography:** Bricolage Grotesque, Instrument Serif and Inter
- 🎨 **Palette:** `#07080A` background · `#C8FF3D` lime · `#FF6A45` coral · `#5BB8FF` ice blue · `#FF4081` pink
- 📱 Responsive layouts and `prefers-reduced-motion` support

---

## ✦ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Structure and semantic markup |
| **CSS3** | Liquid-glass design system and animations |
| **Vanilla JavaScript** | Sizing engine, hash-based routing, and app logic |
| **SVG** | Garments, avatars, and fit heatmaps |
| **Canvas API** | On-device photo analysis |
| **LocalStorage** | Profile, wishlist, looks, and journal persistence |
| **Google Fonts** | Typography |

Zero frameworks, zero npm packages, zero build step.

---

## ✦ Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/akshar-g/Sizzy.git

# 2. Open the project directory
cd Sizzy

# 3. Launch: open index.html in any modern browser
```

> **No build. No dependencies. No backend.** Just open and go.

---

## ✦ Privacy First

Privacy is part of the architecture, not an afterthought.

- 🚫 No backend, database, or remote profile storage
- 🚫 No cookies, external tracking, or accounts
- 💾 Measurements, wishlist, looks, brand offsets and fit journal live **only in your browser's localStorage**
- 📷 Optional photos are analysed in the browser and **never uploaded or stored**
- 🔒 Your data stays on your device

<sub>Clearing your browser's site data will remove everything Sizzy has saved.</sub>

---

## ✦ Project Structure

```text
Sizzy/
├── index.html      # The complete app: styles, data engine, and logic
├── favicon.svg     # App icon
├── 404.html        # Not-found page
├── robots.txt      # Crawler rules
├── .nojekyll       # Disables Jekyll processing
├── .gitignore
├── LICENSE         # MIT License
└── README.md
```

---

## ✦ Deployment

Hosted on **Vercel** → [sizzy-studio.vercel.app](https://sizzy-studio.vercel.app/)

---

## ✦ Disclaimer

Size recommendations are estimates based on published garment sizing information and personal measurements. Charts marked as estimated are approximations. Actual fit varies by brand, product, and personal preference. Always check the official brand size guide before purchasing.

---

## ✦ License

Distributed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

<div align="center">

**SIZZY ✦**

*Find Your Fit. Own Your Style.*

Built with care.

<br/>

⭐ If you like Sizzy, consider giving it a star on [GitHub](https://github.com/akshar-g/Sizzy).

</div>
