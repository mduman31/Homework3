
# Homework 3: Responsive Grid Layout Website

## Student Information
* **Name:** MaryAnn Duman
* **Course:** Introduction to Information Technology
* **Project Date:** November 2026

---

## 📋 Project Overview
This project builds upon our foundational web design coursework by merging semantic HTML layout structures, component-based styling cards, and an advanced **CSS Grid layout system**. The website serves as a personal landing page highlighting family life, gaming hobbies, IT career aspirations, and an active embedded live weather tool.

---

## 🛠️ Features & Component Architecture

### 1. Homework 1: Semantic Core Blocks
* Implements semantic HTML structure using structural tags like `<header>`, `<div>`, and `<footer>`.
* Anchors an interactive **"Back to Top"** skipping mechanism targeting page elements (`#top`).

### 2. Homework 2: Component Cards
* Custom-designed layout cards mapping isolated focus categories (Family, Gaming, Career Goals, Weather).
* Styled inline call-to-action badges linking out cleanly to external targets like *Fortnite*.
* Integration of **Font Awesome v6.4** iconography for streamlined element categorization.

### 3. Homework 3: Responsive Grid System
* Transitioned page organization away from static blocking into a fluid **CSS Grid Layout** (`display: grid`).
* Implemented adaptive template mapping rules: `grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));`.
* Full responsiveness that automatically handles tablet and mobile viewports seamlessly without breaking content margins.

### 4. Third-Party Integrations
* **Live Weather Tracking:** Embedded and repaired an active script engine pointing to `weatherwidget.io`.
* Custom variables configured:
  * **Base Accent Color:** Maroon/Crimson (`#8B1E26`)
  * **Text/Highlight Schema:** Cream/Gold tint (`#F7E7C4`, `rgba(212, 175, 55, 0.35)`)
  * **Target Location:** New Castle, DE

---

## 🗄️ File Repository Directory
```text
├── index.html     # Main markup documentation containing the grid blocks
├── style.css      # Decoupled external stylesheet containing layout rules
└── README.md      # Project documentation framework (this file)
```

---

## 🎨 Design Rules applied in CSS
* **Color Palette Consistency:** Coordinated deep crimson maroon tones alongside mild charcoal texts to preserve strong readability scores across standard panels.
* **Layout Isolation:** Kept styles strictly separated from the code structure by moving all rules out of the HTML file and completely into an independent `style.css` stylesheet.
