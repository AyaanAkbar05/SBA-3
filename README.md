# Testimonials Grid Section – Frontend Mentor Challenge

## Overview
This project is a solution to the **[Testimonials Grid Section challenge](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7)** on Frontend Mentor.  
The goal of the challenge is to build a responsive testimonials layout that matches the provided design.  

The project is built using **HTML5**, **CSS3**, and **Bootstrap 5** for the grid system, with some custom CSS for card styling.

---

## Approach
- **Layout**:  
  - Used Bootstrap’s grid system (`container`, `row`, `col-*`) to structure the testimonials into responsive columns.  
  - Implemented responsive breakpoints (`col-12`, `col-xl-*`) so the grid adapts from mobile → desktop.  

- **Custom Styling (`style.css`)**:  
  - Created reusable `.cards` class for testimonial containers.  
  - Added color variations (`.violet`, `.grayish-blue`, `.white`, `.blackish-blue`) to match the design palette.  
  - Implemented `.image` flexbox utility to align profile images and names horizontally.  
  - Used `.quotes` to position the decorative quotation mark background.  
  - Added `.h-100-card` to ensure equal card heights within Bootstrap’s `align-items-stretch`.  
  - Styled `.attribution` section at the bottom for credits.  

- **Typography**:  
  - Imported **Barlow Semi Condensed** font from Google Fonts (weights 500 & 600).  

---

## Customizations
- Slightly adjusted margins and padding (`my-4`, `g-4`) for better spacing on different screen sizes.  
- Used `w-100` and `d-flex` in the rightmost column to ensure the Kira Whittle testimonial fills the entire column height.  
- Applied semantic HTML tags (`h3`, `h4`, `p`, `small`) for accessibility and readability.  
- Optimized alt text for profile images (e.g., `"Daniel's profile"`) and left decorative assets with `alt=""`.  

---

## Challenges & Solutions
1. **Responsive alignment of cards**  
   - Challenge: Ensuring testimonial cards aligned properly in a mixed 8/4 grid layout.  
   - Solution: Used Bootstrap’s `row g-4 align-items-stretch` along with a custom `.h-100-card` class so all cards in a row stretch to equal height.  

2. **Positioning of quotation SVG**  
   - Challenge: Quotation mark was overlapping content.  
   - Solution: Applied absolute positioning with reduced opacity (`.quotes` class) to place it in the background without affecting readability.  


## ✅ Credits
- Challenge by [Frontend Mentor](https://www.frontendmentor.io?ref=challenge).  
- Coded by **Ayaan Akbar Mohammed**.  

---
