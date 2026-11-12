# <p align="center">💼 The Workfolio</p>

<p align="center">
  <strong>A modern, interactive, and visually captivating portfolio website built with pure HTML5, CSS3, and JavaScript.</strong>
</p>

<p align="center">
  <a href="https://theworkfolio.com" target="_blank">
    <img src="https://img.shields.io/badge/Website-theworkfolio.com-blue?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live Website" />
  </a>
  <a href="https://github.com/theworkfolio" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-The_Workfolio-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile" />
  </a>
  <a href="./LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License" />
  </a>
  <img src="https://img.shields.io/badge/Status-Maintained-success?style=for-the-badge" alt="Status" />
</p>

---

## 🌟 Overview

**The Workfolio** is an immersive digital showcase engineered for modern developers, designers, and creative technologists. Featuring custom cursor interactions, sound and visual theme toggles, fluid keyframe physics, and eye-tracking pupil animations, **The Workfolio** delivers an engaging personal branding experience.

---

## 🎯 Key Features

- 🎨 **Visual Aesthetics & Dark/Light Mode**: Sleek dark futuristic aesthetic with a one-click toggle for Light Mode.
- 🎵 **Interactive Audio Experience**: Ambient sound player integrated directly into the preloader and interface with instant mute/play controls.
- ⚡ **Interactive Cursor Tracking**: Dual-ring cursor tracker that reacts and morphs over clickable links, buttons, and UI elements.
- 👀 **Eye-Tracking Footer Avatar**: Mathematical pupil tracking using real-time mouse coordinate transformations (`mousemove` listener).
- 📱 **Fully Responsive Layout**: Built with custom media queries supporting 4K monitors down to compact mobile displays (<300px).
- 🚀 **Smooth Scroll & Animations**: Powered by [AOS (Animate On Scroll)](https://github.com/michalsnik/aos) alongside custom CSS keyframes (jello physics, breathing glow, vibrant gradients).
- 💼 **Rich Project Showcases**: Modern cards featuring live project URLs, repository links, tags, and interactive hover states.

---

## 📑 Website Sections

| Section | Description |
|---|---|
| **Header / Navbar** | Minimal navigation with coding syntax (`</Home>`, `</AboutMe>`, `</Skills>`, `</Projects>`), brand logo, and responsive mobile drawer. |
| **Hero / Home** | Jello-bounce greeting, dynamic animated typography, "Let's Talk!" CTA, sound toggle, and theme switch. |
| **About Me** | Creative bio, background story, downloadable resume button, and portrait presentation. |
| **Tech Stack** | Grid display of tools & technologies: HTML5, CSS3, JavaScript, Tailwind, React, Next.js, Node.js, Astro, Git, GitHub, CMSs, and Figma. |
| **Projects** | Curated project cards with live demo buttons and GitHub repository redirects. |
| **Interactive Footer** | Quote badge, eye-following avatar, Back to Top button, and direct contact channels. |

---

## 🛠️ Built With

- **Markup**: [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML) (Semantic elements, Open Graph & SEO meta tags)
- **Styling**: Vanilla [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) (Custom properties, Flexbox, Grid, Keyframe animations)
- **Interactivity**: Modern [JavaScript (ES6+)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- **Animation Libraries**: [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/)
- **Typography**: [Google Fonts](https://fonts.google.com/) (`Orbitron`, `Fira Code`, `Passions Conflict`, `Six Caps`)
- **Icons & Graphics**: Scalable Vector Graphics (SVG), WebP compressed assets

---

## 📂 Project Structure

```text
The-Workfolio/
├── CNAME                    # Custom domain mapping (theworkfolio.com)
├── LICENSE                  # MIT License
├── README.md                # Project documentation
├── click.png                # Asset preview
├── cursorr.png              # Custom cursor asset
├── index.html               # Main webpage structure and content
├── main.js                  # Audio, toggles, pupil tracking & navigation logic
├── style.css                # Master styling, themes, keyframes & media queries
├── src/
│   ├── ico/                 # Project favicons
│   ├── mp3/                 # Preloader and background audio
│   ├── pdf/                 # Downloadable resumes
│   ├── png/                 # Tech stack logos, avatars & icons
│   ├── svg/                 # Scalable vector graphics
│   └── webp/                # Optimized project preview cards and visuals
└── Formatted code/          # Unminified readable source references
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/theworkfolio/theworkfolio.github.io.git
cd theworkfolio.github.io
```

### 2. Run Locally
Run the local dev server using npm:

```bash
# 1. Install dependencies
npm install

# 2. Start local live-reload dev server
npm run dev
```

The site will automatically launch at `http://localhost:3000` with live reload on file edits!

Alternatively, you can run directly with any static server:
- **VS Code Live Server**: Right-click `index.html` and click **"Open with Live Server"**.
- **Python Server**: `python -m http.server 8000`
- **Serve**: `npx serve .`

---

## ⚙️ Customization Guide

1. **Brand & Identity**:
   - Update title and Open Graph tags in `<head>` of `index.html`.
   - Customize the hero animated name inside `<article id="name">`.
2. **Projects**:
   - Update project cards inside `<section id="projects">` with your own preview images, titles, descriptions, and URLs.
3. **Contact Details**:
   - Update `mailto:` addresses, GitHub link, LinkedIn, and Instagram handles in `index.html` and `style.css`.
4. **Resume**:
   - Place your updated resume file in `src/pdf/` and point the `openURL()` function in `index.html` to it.

---

## 📬 Contact & Connect

We are always open to collaborations, frontend discussions, and new creative ventures:

- **Primary Contact**: [contact@theworkfolio.com](mailto:contact@theworkfolio.com)
- **Alternative / Inquiries**: [hello@theworkfolio.com](mailto:hello@theworkfolio.com)
- **Website**: [theworkfolio.com](https://theworkfolio.com)
- **GitHub**: [@theworkfolio](https://github.com/theworkfolio)
- **LinkedIn**: [The Workfolio](https://www.linkedin.com/company/theworkfolio)
- **Instagram**: [@theworkfolio](https://www.instagram.com/theworkfolio/)

---

## 📄 License

Distributed under the MIT License. See [`LICENSE`](./LICENSE) for full details.
