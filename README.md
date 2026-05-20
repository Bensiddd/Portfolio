<div align="center">

```
██     ██ ███████ ██      ██████  ██████  ███    ███ ███████ 
██     ██ ██      ██     ██      ██    ██ ████  ████ ██      
██  █  ██ █████   ██     ██      ██    ██ ██ ████ ██ █████   
██ ███ ██ ██      ██     ██      ██    ██ ██  ██  ██ ██      
 ███ ███  ███████ ███████ ██████  ██████  ██      ██ ███████ 
```

</div>

<h1 align="center">
  Aghna Damarula Prianta
</h1>

<h3 align="center">
  Network Engineer &middot; Assistant Lecturer &middot; ISP Enthusiast
</h3>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MikroTik-293239?style=for-the-badge&logo=mikrotik&logoColor=00B4FF" alt="MikroTik">
  <img src="https://img.shields.io/badge/MTCNA-DC2626?style=for-the-badge&logo=checkmarx&logoColor=white" alt="MTCNA">
  <img src="https://img.shields.io/badge/MTCRE-991B1B?style=for-the-badge&logo=checkmarx&logoColor=white" alt="MTCRE">
</p>

<p align="center">
  <a href="mailto:aghnadamrulaprianta@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-DC2626?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://github.com/Bensiddd" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://instagram.com/bens.id" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
  </a>
</p>

---

## Overview

A single-page **portfolio website** built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies. Designed with a **dark cyber-network** aesthetic featuring animated particle backgrounds, glassmorphism cards, and a bold black & red color scheme.

> 🔗 **Live Demo:** [bensiddd.github.io/Portfolio](https://bensiddd.github.io/Portfolio)

## Features

| Feature | Description |
|---|---|
| **Particle Network** | Animated canvas-based nodes with mouse interaction |
| **Typing Effect** | Terminal-style typewriter cycling through roles |
| **Lightbox Viewer** | Click certification images for fullscreen preview |
| **Scroll Animations** | Reveal-on-scroll using Intersection Observer |
| **Scroll-Aware Navbar** | Transparent to solid on scroll |
| **Glassmorphism Design** | Frosted glass cards with gradient borders |
| **Responsive Layout** | Mobile-first, adapts to all screen sizes |
| **Image Gallery** | URL-based gallery with localStorage persistence |
| **Smooth Scrolling** | Navigate between sections |

## Tech Stack

```
┌──────────────────────────────────────────────┐
│                                              │
│   Frontend                                   │
│   ├── HTML5 — Semantic structure             │
│   ├── CSS3  — Variables, Flexbox, Grid       │
│   └── JavaScript (Vanilla)                   │
│       ├── Canvas API (particles)             │
│       ├── Intersection Observer (scroll)     │
│       └── localStorage (gallery)             │
│                                              │
│   Design                                     │
│   ├── Google Fonts: Inter + Space Grotesk    │
│   ├── Color: #0a0a0f, #dc2626, #991b1b      │
│   └── Icons: Inline SVG                      │
│                                              │
└──────────────────────────────────────────────┘
```

## File Structure

```
portfolio/
├── index.html            # Main entry — single page
├── style.css             # All styling (~900 lines)
├── script.js             # All interactivity (~340 lines)
├── README.md             # This file
├── assets/
│   ├── profile.svg       # Profile photo placeholder
│   ├── cert-mtcna.svg    # MTCNA certificate placeholder
│   ├── cert-mtcre.svg    # MTCRE certificate placeholder
│   ├── MTCNA.jpg         # MTCNA certificate image
│   ├── MTCRE.jpg         # MTCRE certificate image
│   └── photo-profile.jpeg# Profile photo
└── erd.md                # Requirements document
```

## Getting Started

1. **Clone or download** this repository
2. **Open `index.html`** in your browser (double-click)
3. No build tools, no npm install, no server required

> Works on any modern browser (Chrome, Firefox, Edge, Safari).

## Customization

### Profile
- Replace `assets/photo-profile.jpeg` with your photo
- Edit bio, name, and details in `index.html` (lines 60–84)

### Certifications
- Replace `assets/MTCNA.jpg` and `assets/MTCRE.jpg` with your images
- Update dates and titles in `index.html` (lines 147–160)

### Social Links
- Edit email, GitHub, and Instagram URLs in `index.html` (lines 225–250)
- Update badge links in `README.md` (lines 34–42)

### Typing Phrases
- Edit the `phrases` array in `script.js` (lines 116–122)

### Colors
- Modify CSS variables in `style.css` (lines 2–20):
  - `--color-primary` (default: `#dc2626` / crimson red)
  - `--bg-primary` (default: `#0a0a0f` / dark)

## Design

| Token | Value | Usage |
|---|---|---|
| `--bg-primary` | `#0a0a0f` | Main background |
| `--bg-secondary` | `#12121a` | Alternating section bg |
| `--color-primary` | `#dc2626` | Accent, highlights, buttons |
| `--color-accent` | `#991b1b` | Deep red hover states |
| `--glass-bg` | `rgba(255,255,255,0.03)` | Glassmorphism cards |

## License

Built with ♥ by **Aghna Damarula Prianta** — feel free to use and modify.
