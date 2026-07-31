# JAGARDEV — Developer Portfolio

A high-performance, modern developer portfolio built with **Astro 5** and **Tailwind CSS v4**. Designed with focus on clean architecture, smooth 60fps animations, optimized asset delivery, and responsive UI/UX.

---

## ⚡ Tech Stack

- **Framework**: [Astro 5](https://astro.build/) (Static Site Generation / Zero JavaScript runtime overhead)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Icons & Graphics**: Custom SVG illustrations & WebP optimized media
- **Typography**: Google Fonts (*Space Grotesk*, *JetBrains Mono*, *Caveat*, *Permanent Marker*)
- **Deployment & Tooling**: Node.js (>= 22.12.0), Vite

---

## ✨ Features & Engineering Highlights

- 🏎️ **Ultra-Fast Performance**: Built on Astro's HTML-first architecture with minimal JS output.
- 🖼️ **Hardware-Accelerated Carousel**: Custom dual-element crossfade system using `HTMLImageElement.decode()` pre-warming and IntersectionObservers for stutter-free image transitions.
- 🎯 **Smart Navbar Observer**: Smooth section-tracking scroll listener to detect active sections without layout thrashing.
- ✍️ **Dynamic Typewriter Effect**: Custom component for animated text switching.
- 🎨 **Sleek Dark Aesthetics**: Glassmorphism, interactive hover feedback, and custom cursor physics.
- ✨ **Native Ambient Particle Engine**: A lightweight, custom-built Vanilla JS particle system for organic floating dust and spark effects, optimized for 60fps without heavy external libraries.
- 📱 **Fully Responsive**: Mobile-first fluid design tailored for screen sizes from smartphones to ultrawide displays.

---

## 📁 Project Structure

```text
d:\Portfolio Projects\jagardev-portfolio\
├── public/                # Static media assets (WebP images, favicons)
├── src/
│   ├── components/        # Reusable UI components
│   │   ├── About.astro        # Personal story & optimized carousel
│   │   ├── Career.astro       # Professional experience timeline
│   │   ├── Contact.astro      # Contact form & social links
│   │   ├── CustomCursor.astro # Interactive custom cursor
│   │   ├── Education.astro    # Academic background
│   │   ├── Hero.astro         # Main landing hero with typewriter
│   │   ├── Projects.astro     # Showcase of featured projects
│   │   ├── Effects.astro      # Native ambient particles & background effects
│   │   ├── Tech.astro         # Tech stack & skills overview
│   │   └── Typewriter.astro   # Custom text animation component
│   ├── layouts/
│   │   └── Layout.astro       # Global layout, HTML shell & nav scroll logic
│   ├── pages/
│   │   └── index.astro        # Main entry page
│   └── styles/
│       └── global.css         # Tailwind v4 configuration & base styles
├── package.json           # Scripts & project dependencies
└── astro.config.mjs       # Astro configuration
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have **Node.js** installed (v22.12.0 or higher recommended):

```bash
node -v
```

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/jagardev/portfolio.git
   cd portfolio
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the local development server**:
   ```bash
   npm run dev
   ```
   Open your browser and navigate to `http://localhost:4321`

---

## 🧞 Available Scripts

| Command | Action |
| :--- | :--- |
| `npm run dev` | Launches local development server at `http://localhost:4321` |
| `npm run build` | Builds the production static bundle into `./dist/` |
| `npm run preview` | Previews the production build locally prior to deployment |
| `npm run astro` | Runs Astro CLI commands (`astro check`, `astro add`, etc.) |

---

## 📬 Contact & Connect

- **Portfolio**: [JAGARDEV](https://github.com/jagardev/portfolio)
- **LinkedIn**: [Jairo García Antolín](https://linkedin.com/in/jagardev)
- **GitHub**: [@jagardev](https://github.com/jagardev)
