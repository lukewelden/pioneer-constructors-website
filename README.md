# Pioneer Constructors Marketing Site

This repository contains the static, responsive marketing landing page for **Pioneer Constructors**, a fictional construction firm set in the *Satisfactory* game world. Built with **pure HTML5 and vanilla CSS**, optimized for mobile and desktop—no JavaScript included.

---

##  Skills Gained: "Making a Website Responsive" Module

This project leverages multiple responsive design skills acquired from Codecademy’s **“Web Development Foundations”** module:

### 1. HTML and CSS basics 
   - Built the site with semantic HTML5 structure (`header`, `nav`, `main`, `section`, `footer`).  
   - Applied core CSS concepts including selectors, the box model, typography, and color.  
   - Organized styles in a separate stylesheet with inline comments for maintainability.

### 2. Fluid, Relative Sizing & Typography
- Used relative units like `rem`, `clamp()`, and percentages instead of fixed pixels.
- Enabled text, spacing, and layout elements to scale dynamically across devices (e.g., `font-size: clamp(...)`) :contentReference[oaicite:0]{index=0}.

### 3. CSS Media Queries for Breakpoints
- Defined responsive breakpoints (e.g., `@media (min-width: 700px)` and `1024px`) to transition layout from single-column (mobile) to multi-column (tablet/desktop).
- Ensured styles adapt based on viewport width for improved readability and layout clarity :contentReference[oaicite:1]{index=1}.

### 4. Flexbox & CSS Grid Layout Techniques
- Employed CSS Grid and Flexbox for layout transitions:
  - Grid for overview cards, service list, stats, and timeline.
  - Flexbox for navigation alignment, call-to-action button groups, and inner header structures.
- These approaches reflect real-world use of modern layout systems for responsive alignment :contentReference[oaicite:2]{index=2}.

### 5. Accessible, Responsive Patterns
- Included viewport-scale meta tag (`<meta name="viewport" content="width=device-width, initial-scale=1">`), critical for correct scaling on mobile devices :contentReference[oaicite:3]{index=3}.
- Made images and decorative elements responsive (e.g., `max-width: 100%; height: auto;`).
- Used semantic structure (`header`, `main`, `section`, `footer`) for accessibility and screen reader compatibility.

### 6. Responsive Design Philosophy
- Applied the **mobile-first** design principle: styles begin with a base mobile-friendly layout, then progressively enhance for larger screens via media queries.
- This aligns with modern responsive design best practices, ensuring usability across devices :contentReference[oaicite:4]{index=4}.

---

##  Project Overview

- **Technologies**:
  - HTML5 semantics (`header`, `nav`, `main`, `section`, `footer`)
  - Vanilla CSS (variables, grid, flex, clamp, gradients, no external libraries)
  - Responsive patterns with breakpoints, fluid scaling, and mobile-first layout

- **Structure**:
  - **Hero**: Strong initial messaging, CTAs, and Satisfactory-style visuals (caution stripes, conveyor divider)
  - **Overview**: Card-based summaries of company strengths
  - **Services**: Icon-accompanied service cards in a responsive grid
  - **Process**: Timeline with numbered steps and visual accents
  - **Results**: Throughput stats in grid layout
  - **Contact**: Form + aside with Satisfactory-themed metadata; functional `mailto:` form fallback
  - **Footer**: Simple nav and branding

---

##  How to Use

1. Clone or download this repo.
2. Open `index.html` in your browser.
3. Resize the viewport to see layout adapt seamlessly—from smartphone to desktop widths.
4. All styling and layout behavior is defined via CSS—no JavaScript required.

---

##  Acknowledgments & Learning References

- Codecademy: *Making a Website Responsive* module, for building understanding of media queries, fluid sizing, layout strategies, and responsive design philosophy :contentReference[oaicite:5]{index=5}.

---
