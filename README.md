# Interactive Portfolio 📸

A responsive photographer portfolio website built strictly from a Figma design specification. This project showcases structured semantic layout alongside custom JavaScript interactive mechanics like zone-based gallery scrolling, stateful components, and modal interfaces.

🔗 **[Live Demo](https://morevna.github.io/portfolio/)**

---

## 🛠️ Tech Stack & Architecture

- **Design Translation:** Figma mockup rules, pixel-perfect modular development, fluid responsive breakpoints.
- **Interactivity & Logic:** Vanilla JavaScript (ES6+), advanced asynchronous and interval DOM state triggers.
- **Client-Side Storage:** Native Browser `localStorage` API for cross-session state persistence.

---

## 🚀 Key Technical Features

- **Advanced Dual-Mode Slider:** Engineered an interactive gallery component centered by default. Features desktop navigation via edge-detection hover zones (~30% screen boundaries) using programmatic `setInterval` loops, paired with native `touchstart`/`touchmove` gesture mapping for mobile viewports.
- **Persistent FAQ Accordion System:** Implemented an optimized single-open accordion engine. Integrates state management synced with `localStorage` to perfectly restore open questions and DOM indicator nodes (`+` / `−`) across page reloads.
- **Scroll-Locked Overlays & Menus:** Designed modal booking interfaces and a responsive burger layout. Includes synchronized toggle states that prevent underlying document viewports from scrolling (`no-scroll` class applied to `documentElement`) with transition-safe timeout clearances.
- **Clean Event Delegations:** Wired efficient overlay listeners to automatically dismiss modals when clicking outside container boundaries or hitting explicit dismiss hooks.
