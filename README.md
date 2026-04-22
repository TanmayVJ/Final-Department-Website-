<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/Emblem_of_Madhya_Pradesh.svg/1280px-Emblem_of_Madhya_Pradesh.svg.png" alt="Emblem of Madhya Pradesh" width="100"/>

# Government of Madhya Pradesh — All Departments Portal

**A futuristic, fully responsive single-window web portal aggregating all major Madhya Pradesh Government departments, welfare schemes, and services.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![No Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen?style=for-the-badge)](/)
[![Responsive](https://img.shields.io/badge/Responsive-Yes-blue?style=for-the-badge)](/)

[Live Demo](https://tanmayvj.github.io/Final-Department-Website-/) · [Report Bug](../../issues) · [Request Feature](../../issues)

</div>

---

## 📌 About The Project

This is a project — a redesigned, modernised clone of the Madhya Pradesh Government's web presence. The original idea was simple but powerful: **give every citizen one place** to access all MP government departments, welfare schemes, and service portals without hunting across dozens of different websites.

The project takes that idea and executes it with a production-grade, futuristic UI — built with **zero external dependencies**, just pure HTML, CSS.

> ⚠️ **Disclaimer:** This is not an official government website. It is a frontend project built for educational and portfolio purposes. All external links redirect to the real, official MP Government portals.

---

## ✨ Features

- **🔴 Live News Ticker** — Scrolling banner with the latest scheme announcements and updates
- **🧭 Sticky Navbar** — Glassmorphism navigation with scroll-aware styling and mobile hamburger drawer
- **🦁 Animated Hero Section** — Full-viewport landing with floating orbs, staggered text animations, and live stats
- **📊 Stats Bar** — Key MP state statistics (health centres, farmers, students, road network, budget, forest cover)
- **🏛️ 12 Department Cards** — Health, Agriculture, Finance, Education, Transport, Women & Child, Energy, Tourism, Skill Development, Housing, Water Resources, Tribal Affairs — each with real scheme listings and direct portal links
- **🔍 Scheme Explorer with Filter** — 12 flagship welfare schemes filterable by department category
- **📜 About + Timeline** — State history from 1956 to 2024 with an animated vertical timeline
- **📬 Contact / Complaint Form** — Full form with validation, department selector, and auto-generated reference ID on submission
- **🔼 Back to Top Button** — Appears on scroll, smooth scroll to top
- **🌗 Scroll Reveal Animations** — Elements animate into view using IntersectionObserver
- **📱 Fully Responsive** — Mobile, tablet, and desktop layouts with hamburger menu

---

## 🖥️ Screenshots

| Section | Preview |
|---|---|
| Home | Full-viewport landing with MP emblem, and home stats |
| Departments | 12-card grid with per-department colour theming and hover effects |
| Schemes | Filterable scheme cards by category |
| About & Timeline | Split layout with MP history milestones |
| Contact | Two-column form with validation |

> _Add your own screenshots in a `/screenshots` folder and update the table above with `![Alt](screenshots/hero.png)` etc._

---

## 🗂️ Project Structure

```
mp-govt-portal/
│
├── index.html                  # All HTML structure + inline JavaScript
├── Final_CSS_style.css         # Complete stylesheet (CSS variables, animations, responsive)
└── README.md                   # This file
```

No build tools. No package manager. No framework. Just open `index.html` in a browser.

---

## 🚀 Getting Started

### Option 1 — Open Directly

```bash
# Clone the repository
git clone https://github.com/your-username/mp-govt-portal.git

# Navigate into the project folder
cd mp-govt-portal

# Open in your browser
open index.html         # macOS
start index.html        # Windows
xdg-open index.html     # Linux
```

### Option 2 — Live Server (Recommended for Development)

If you have VS Code installed, use the **Live Server** extension:

1. Open the project folder in VS Code
2. Right-click `index.html` → **Open with Live Server**
3. The site opens at `http://127.0.0.1:5500`

### Option 3 — Deploy to GitHub Pages

1. Push the repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Your site will be live at `https://your-username.github.io/mp-govt-portal`

---

## 🎨 Design System

The UI is built around a cohesive design language inspired by India's national colours and a futuristic government aesthetic.

### Colour Palette

| Token | Value | Usage |
|---|---|---|
| `--saffron` | `#FF6B1A` | Primary accent, CTAs, highlights |
| `--gold` | `#D4AF37` | Secondary accent, emblem glow |
| `--deep-navy` | `#0A0F2C` | Page background |
| `--navy-mid` | `#111D45` | Section alternation |
| `--green` | `#00A86B` | Success states, form feedback |
| `--white` | `#F8F5EE` | Body text |
| `--glass` | `rgba(255,255,255,0.04)` | Card backgrounds |
| `--glass-border` | `rgba(255,255,255,0.10)` | Card/input borders |

### Typography

| Role | Font | Source |
|---|---|---|
| Display / Headings | **Cinzel** | Google Fonts |
| Body / UI | **Rajdhani** | Google Fonts |
| Monospace / Labels | **JetBrains Mono** | Google Fonts |

### Responsive Breakpoints

| Breakpoint | Layout Changes |
|---|---|
| `≤ 1024px` | Hero collapses to single column, about/contact go single column |
| `≤ 768px` | Nav links hidden → hamburger drawer, dept/scheme grids go single column |
| `≤ 480px` | Stats single column, action buttons stack vertically |

---

## 🏛️ Departments Covered

| # | Department | Colour | Portal |
|---|---|---|---|
| 1 | Health & Family Welfare | 🔴 Red | [health.mp.gov.in](https://www.health.mp.gov.in/en) |
| 2 | Agriculture & Farmers Welfare | 🟢 Green | [mpkrishi.mp.gov.in](https://mpkrishi.mp.gov.in/) |
| 3 | Finance Department | 🟡 Gold | [finance.mp.gov.in](https://finance.mp.gov.in/) |
| 4 | School Education | 🔵 Blue | [educationportal.mp.gov.in](https://www.educationportal.mp.gov.in/) |
| 5 | Transport | 🟣 Purple | [transport.mp.gov.in](https://transport.mp.gov.in/) |
| 6 | Women & Child Development | 🩷 Pink | [mpwcd.nic.in](https://mpwcd.nic.in/) |
| 7 | Energy Department | 🟠 Amber | [energy.mp.gov.in](https://energy.mp.gov.in/) |
| 8 | Tourism & Culture | 🩵 Teal | [mptourism.com](https://www.mptourism.com/) |
| 9 | Skill Development & Employment | 💚 Emerald | [ssdm.mp.gov.in](https://ssdm.mp.gov.in/) |
| 10 | Housing & Urban Development | 🟠 Orange | [mphousing.nic.in](https://mphousing.nic.in/) |
| 11 | Water Resources | 🔵 Steel Blue | [water.mp.gov.in](https://water.mp.gov.in/) |
| 12 | Tribal Affairs | 🟤 Brown | [tribal.mp.gov.in](https://tribal.mp.gov.in/) |

---

## 📋 Welfare Schemes Featured

| Scheme | Department | Benefit |
|---|---|---|
| CM Ladli Bahna Yojana | Women & Child | ₹1,250/month for eligible women |
| Mukhyamantri Seekho Kamao Yojana | Skill Development | ₹8,000–10,000/month stipend + certification |
| Ayushman Bharat – AB-HWCs | Health | Free primary healthcare at wellness centres |
| PM Fasal Bima Yojana | Agriculture | Crop insurance against natural calamities |
| Ladli Laxmi Yojana 2.0 | Education | ₹1,43,000 for girl child education & marriage |
| PM Awas Yojana | Housing | ₹1.2–2.5 lakh construction grant for EWS |
| PM Surya Ghar | Energy | 300 units free electricity via rooftop solar |
| e-Uparjan | Agriculture | Online MSP crop procurement for farmers |
| Startup MP Program | Skill Development | Grants up to ₹20 lakh for youth entrepreneurs |
| Udyam Kranti Yojana | Women & Child | Collateral-free loans up to ₹50 lakh for women |
| Education Guarantee Scheme | Education | School within 1 km in tribal/remote areas |
| Atal Bal Arogya Avam Poshan Mission | Health | Child nutrition and anti-malnutrition program |

---

## ⚙️ Technical Highlights

- **Zero dependencies** — no jQuery, no Bootstrap, no npm. Ships as two files.
- **CSS Custom Properties** — entire theme controlled via `:root` variables, easy to reskin
- **IntersectionObserver API** — scroll reveal animations and active nav highlighting without scroll event listeners
- **CSS Grid + Flexbox** — fully responsive layouts without media query overload
- **Glassmorphism** — `backdrop-filter: blur()` cards with `rgba` borders
- **CSS Animations** — keyframe-driven loader, ticker, hero orbs, emblem pulse, scroll line
- **Vanilla JS only** — hamburger toggle, scheme filter, form validation, animated counter, back-to-top

---

## 🔮 Potential Future Improvements

- [ ] Add a search bar to filter departments and schemes simultaneously
- [ ] Dark/Light mode toggle
- [ ] Hindi language toggle using `data-lang` attributes
- [ ] Real-time news feed via MP Government RSS
- [ ] Interactive MP district map using SVG
- [ ] Accessibility audit (ARIA labels, focus management, keyboard nav)
- [ ] PWA support (service worker + manifest for offline use)
- [ ] Add more departments: Forest, Law & Justice, IT, Rural Development

---

## 🙌 Acknowledgements

- [Government of Madhya Pradesh](https://www.mp.gov.in) — for all the real department portals and scheme information
- [Wikipedia](https://en.wikipedia.org) — for the MP State Emblem SVG
- [Google Fonts](https://fonts.google.com) — Cinzel, Rajdhani, JetBrains Mono
- [Shields.io](https://shields.io) — for the README badges

---

<div align="center">

**Built with ❤️ from Indore, Madhya Pradesh**

Made by **Tanmay Vijayvargiya**

_"This is not just a website — it's a window to the Heart of India."_

</div>
