# HealthConnect — Your Health, Connected

A modern, immersive healthcare platform landing page featuring role-based portals for patients, doctors, and administrators. Built with cutting-edge web technologies and stunning 3D animations.

![HealthConnect Banner](https://img.shields.io/badge/HealthConnect-Healthcare%20Platform-blue?style=for-the-badge&logo=health)

## 🚀 Live Demo

Open `index.html` in your browser to experience the platform.

## 📋 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Key Sections](#-key-sections)
- [Animations & Effects](#-animations--effects)
- [Responsive Design](#-responsive-design)
- [Browser Support](#-browser-support)
- [License](#-license)

## ✨ Features

### Role-Based Portals

- **Patient Portal**: Book appointments, view visit history, manage medicine logs, and update personal profiles
- **Doctor Portal**: Create treatment histories, manage patient records, unflag medicines, and view consultation timelines
- **Admin Portal**: Full read/write/delete access to all records, system-wide analytics, and user access management

### Platform Capabilities

- 🗓️ Smart Scheduling with instant confirmations
- 📊 Platform Analytics and reporting
- 🔐 Role-based access control
- 📱 Fully responsive design
- 🎨 Immersive 3D animations
- ⚡ Smooth scroll experience
- 🎯 Interactive feature filtering

## 🛠️ Tech Stack

### Frontend

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with:
  - CSS Custom Properties (Variables)
  - Flexbox & CSS Grid
  - Advanced animations & transitions
  - Backdrop filters
  - Clip-path animations
  - Media queries for responsive design

### JavaScript (Vanilla)

- Pure JavaScript (ES6+)
- No external frameworks

### 3D Graphics

- **Three.js** (r128) - WebGL-powered 3D graphics
  - Particle network background
  - DNA double helix animation
  - Animated heart with ECG pulse
  - Brain outline visualization
  - Wireframe geometric shapes (TorusKnot, Icosahedron, Octahedron, Tetrahedron)

### Animation Libraries

- **GSAP** (GreenSock Animation Platform) 3.12.2
  - ScrollTrigger plugin for scroll-based animations
  - Timeline animations
  - Smooth easing functions

- **Lenis** 1.0.39 - Buttery smooth scrolling

### Typography

- **Plus Jakarta Sans** - Headings and brand elements
- **Inter** - Body text and UI elements

## 📁 Project Structure

```
health-connect/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css      # All styles (790+ lines)
│   └── js/
│       └── script.js      # All JavaScript (766+ lines)
├── LICENSE                 # Project license
└── README.md              # This file
```

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools required - pure HTML/CSS/JS

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd health-connect
```

2. Open `index.html` in your browser:
```bash
# On Windows
start index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

Or simply double-click the `index.html` file.

## 🎯 Key Sections

### Hero Section
- Animated 3D dashboard scene with patient, doctor, and admin cards
- Character-by-character title animation
- Aurora gradient background orbs
- Scroll cue indicator

### Role Portals
- **Patient Portal**: Appointment management, visit history, medicine tracking
- **Doctor Portal**: Patient list, treatment creation, medicine flagging
- **Admin Portal**: Platform overview, audit logs, user management

### Features Section
- Filterable feature cards by role
- Interactive hover effects with radial gradients
- Smooth wave stagger animations

### Statistics Section
- Animated count-up numbers
- Progress bar fills
- Platform metrics display

### Call-to-Action
- Rotating ring elements
- Portal navigation buttons
- Smooth reveal animations

## 🎨 Animations & Effects

### 3D Background
- **Particle Network**: 150 interconnected particles with dynamic edges
- **DNA Double Helix**: Rotating genetic structure with base pair dots
- **Heart with ECG**: Animated heartbeat synchronized with ECG waveform
- **Brain Outline**: Swaying brain visualization with gyri/sulci folds
- **Wireframe Shapes**: Floating geometric shapes (TorusKnot, Icosahedron, etc.)

### Scroll Animations
- Section reveals with GSAP ScrollTrigger
- Parallax effects on hero scene
- Feature card wave stagger
- Statistics count-up on scroll

### Interactive Elements
- Custom cursor with dot, ring, and trail
- 3D tilt effect on role cards
- Magnetic button hover effects
- Smooth anchor scrolling with Lenis

### Loader
- Animated loading bar with percentage
- Logo reveal animation
- Smooth transition to hero section

## 📱 Responsive Design

Fully responsive across all device sizes:

| Breakpoint | Layout |
|------------|--------|
| ≤1100px | Tablet landscape & small desktop |
| ≤900px | Tablet portrait - hamburger menu, stacked roles |
| ≤680px | Mobile landscape - single column features |
| ≤480px | Small mobile - optimized spacing |
| ≤360px | Very small - full-width buttons |

### Mobile Features
- Hamburger menu with smooth drawer animation
- Touch-optimized interactions
- Hidden custom cursor on touch devices
- Optimized 3D scene for mobile performance

## 🌐 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

**Note**: WebGL support required for 3D animations. Graceful degradation on older browsers.

## 📄 License

This project is licensed under the terms specified in the [`LICENSE`](LICENSE) file.

## 🙏 Acknowledgments

- **Three.js** for powerful 3D graphics capabilities
- **GSAP** for smooth, performant animations
- **Lenis** for buttery smooth scrolling
- **Google Fonts** for beautiful typography

---

**HealthConnect** — One Platform, Every Role, Every Need.

© 2026 HealthConnect. All rights reserved.
