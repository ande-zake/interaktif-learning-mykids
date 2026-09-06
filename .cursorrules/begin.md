# Context & Architecture Rules for Interaktif Learning Web

## 1. Project Overview
A web-based interactive learning tool built for a 9-year-old elementary student (Grade 3-4). 
Target environment: Apple iPad (Safari browser) hosted statically on GitHub Pages.

## 2. Directory Structure Convention
- `index.html` -> Main portal / dashboard categories (Math, English, Science).
- `math/` -> Interactive math modules (e.g., `persamaan-simple.html`).
- `english/` -> Interactive language modules.
- `science/` -> Interactive science modules.

## 3. Technology Stack & Constraints
- Pure Web Tech: Vanilla HTML5, CSS3, and JavaScript only. No npm, webpack, Tailwind CLI, React, or external build processes.
- Single File Modularity: Every interactive page inside subdirectories must contain its own `<style>` and `<script>` self-contained in a single `.html` file.
- Deployment: Fully compatible with default static GitHub Pages without backend requirements.

## 4. Touchscreen & UX Guidelines (Crucial for iPad)
- Always implement both mouse events (`dragstart`, `drop`) and mobile touch events (`touchstart`, `touchend`, `touchmove`, `elementFromPoint`).
- Set `touch-action: none;` on draggable elements to prevent Safari's default swipe-to-navigate and pinch-to-zoom gestures.
- Large interactive hit areas (minimum 44x44px buttons and large card elements).
- Colorful, cartoonish, high-contrast, playful UI (comic rounded fonts, bouncy button transitions).
- Gamification & Validation: Always enforce a challenge/rule verification before displaying success rewards.