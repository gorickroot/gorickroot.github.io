<div align="center">

# Gorick Nath — Portfolio

**AI/ML Engineer · Founder & CEO of Zyntho AI · Computing Science at Griffith College Dublin**

[![Live on Vercel](https://img.shields.io/badge/Live-gorick--nath.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://gorick-nath.vercel.app/)
[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-gorickroot.github.io%2Fportfolio-181717?style=for-the-badge&logo=github&logoColor=white)](https://gorickroot.github.io/)

<img src="assets/preview.jpg" alt="Portfolio hero: 'Engineering intelligence that actually works.' over a molten orange WebGL orb" width="100%">

</div>

---

## 👨‍💻 About me

- 🎓 **BSc Computing Science** at Griffith College Dublin, Ireland
- ⚡ **Founder & CEO of Zyntho AI**: AI agents, automation and data tools for businesses
- 🧠 Working across machine learning, LLM fine-tuning, computer vision and NLP
- 🌍 Bangladesh → Italy → Dublin

## ✨ What's on the site

| Section | What it does |
|---|---|
| **Hero** | A real-time WebGL "liquid" shader that follows your cursor, with live Dublin and Dhaka clocks |
| **Approach** | A short statement that lights up word by word as you scroll |
| **Selected work** | A pinned, horizontally scrolling reel of projects with generated cover art |
| **Capabilities** | AI agents, automation, fine-tuning, computer vision and forecasting |
| **Journey** | An animated timeline from Bangladesh to Dublin and Zyntho AI |
| **World clock** | Detects the visitor's time zone, shows an analog and digital clock, and lines it up against Dublin, Dhaka, Rome, London, New York, San Francisco, Dubai and Tokyo |
| **Let's talk** | Photos, copy-to-clipboard emails and social links |

It also has a cinematic preloader, smooth scrolling, a custom magnetic cursor and film grain.

## 📱 Works everywhere

Tested on iPhone SE, iPhone 15 Pro Max, Pixel 7, Galaxy S9+, Galaxy Fold, iPad Mini, iPad Pro, and on laptops and desktops from 1366px to 1920px wide.

- **Phones and tablets:** layouts adapt to each screen, and cursor and hover effects switch off on touch screens.
- **Budget devices:** the shader renders lighter and the grain stops animating to save battery.
- **Accessibility:** it respects `prefers-reduced-motion`, has a skip link, visible keyboard focus and alt text on every photo.
- **Reliability:** if the animation libraries can't load, the page still shows all of its content.

## 🛠️ Built with

- **HTML, CSS and JavaScript** in a single self-contained `index.html`, with no build step
- **WebGL / GLSL** for the hero shader, and **Canvas 2D** for the project covers
- **[GSAP](https://gsap.com/) + ScrollTrigger** for scroll-driven animation
- **[Lenis](https://github.com/darkroomengineering/lenis)** for smooth scrolling
- **`Intl.DateTimeFormat`** for the time-zone-accurate clocks
- **Fonts:** Instrument Serif, Inter Tight and JetBrains Mono, from Google Fonts

## 📁 Structure

```
.
├── index.html          # the whole site: markup, styles, scripts and embedded photos
├── assets/
│   └── preview.jpg     # screenshot used in this README
└── README.md
```

## 🚀 Run it locally

There's no install. Clone the repo and open the file:

```bash
git clone https://github.com/gorickroot/portfolio.git
cd portfolio
open index.html        # macOS  ·  use "start index.html" on Windows
```

Or serve it locally:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

An internet connection is needed for the fonts and animation libraries, which load from CDNs.

## 🌐 Deployment

- **GitHub Pages:** serves `index.html` from the `main` branch root at [gorickroot.github.io/portfolio](https://gorickroot.github.io/portfolio/)
- **Vercel:** imports this repo with the "Other" preset and no build command, at [gorick-nath.vercel.app](https://gorick-nath.vercel.app/)

Both update automatically on every push to `main`.

## 🌐 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gorick-nath-aigeek/)
[![Zyntho AI](https://img.shields.io/badge/Zyntho_AI-zynthoai04@gmail.com-FF6A1F?style=flat-square&logo=gmail&logoColor=white)](mailto:zynthoai04@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/gorickroot)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/pep_poo_a)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white)](https://www.facebook.com/pep.poo.a.1425/)

## 🙏 Credits

Design direction was informed by the open-source [UI/UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) design database (MIT). Animation is by GSAP and Lenis, and the fonts are from Google Fonts.

---

<div align="center">

© 2026 Gorick Nath. All rights reserved. The design, photos and content may not be reused without permission.

*Patience → Progress → Perfection → Success*

</div>
