# 🚀 Yashaswini Madhusudan — Interactive Portfolio

A visually stunning, high-performance, single-file developer portfolio. This project follows the "dark-matter editorial" aesthetic, combining a mission-control dashboard feel with smooth agency-style interactions.

## 🎨 Visual Identity
- **Themes**: Deep space black-blue (`#020818`) with Electric Cyan, Bleeding Coral, and Solar Amber accents.
- **Typography**: Bebas Neue (Display), JetBrains Mono (Technical/Labels), and DM Sans (Body).
- **Glassmorphism**: Frosted glass effects on navigation and interactive cards.

## ✨ Key Features
- **Custom Cursor System**: A 2-stage trailing ring cursor that morphs during interaction.
- **3D Tilt Projection**: Project cards react to mouse position using CSS 3D perspectives.
- **GSAP Animations**: Complex scroll-triggered sequences for SVG line-drawing and staggered reveals.
- **Dynamic Starfield**: A hand-coded JS canvas particle background.
- **Floating Pills**: Antigravity code fragments drifting across the hero section.
- **Progress Tracking**: A globally fixed scroll progress bar with a tri-color gradient.

## 🛠 Tech Stack
- **Core**: Pure HTML5, CSS3, Vanilla JavaScript (ES6+).
- **Libraries (CDN)**: [GSAP](https://greensock.com/gsap/) for advanced motion and ScrollTrigger.
- **Styling**: Modern CSS Custom Properties (Variables) and HSL color tailoring.

## 🚀 How to Run Locally
Since the portfolio uses `GSAP` from a CDN and features a local resume download, the best way to view it is by using a local server:

1.  **Using VS Code**: Install the "Live Server" extension and click "Go Live".
2.  **Using Node.js**: Run `npx serve` in this directory.
3.  **Using Python**: Run `python -m http.server 8000`.

Open your browser at `http://localhost:3000` (or the corresponding port).

## 📄 Resume Integration
Your official resume is integrated into the portfolio:
- **Location**: `/resume.pdf`
- **Action**: Use the "DOWNLOAD RESUME" button in the hero section for an instant download.

---
*Built with ❤️ by Antigravity AI for Yashaswini Madhusudan.*
