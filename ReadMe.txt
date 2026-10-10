# Personal Portfolio Website - Assignment 1, Zafir Sheikh 101025024

## Overview
This personal portfolio website was built using standard HTML-5 semantic markup and CSS-3 stylesheets

## Viewports and Dimensions
Three dedicated stylesheets handle responsive layout through media queries defined in each page `<head>`:
- **Desktop / Laptop (`full.css`)**: Active at `min-width: 960px`. Designed using a traditional fixed 960px container grid, establishing side-by-side floated columns (left-column for secondary navigation, right-column for primary content) and multi-column floating boxes.
- **Tablet (`tablet.css`)**: Active between `min-width: 481px` and `max-width: 960px`. Employs a fluid 100% width wrapper, stacks columns vertically (`float: none`), and adjusts inner grid boxes to 45% width across two columns.
- **Mobile Phone (`phone.css`)**: Active at `max-width: 480px`. Optimized for single-column touch navigation (`float: none`, width 90-100%), full-width block tap buttons, and expanded form input fields.

## Gradients Used
- **Angled Linear Gradient**: `linear-gradient(45deg, #1F2937 0%, #3B82F6 100%)` applied to the `body` background in `full.css` and to `#banner` in `tablet.css`.
- **Vertical Linear Gradient**: `linear-gradient(to bottom, #1F2937 0%, #3B82F6 100%)` applied to `#banner` in `full.css` and `phone.css`.

## Adobe Color Palette
Extracted 5-color harmonious palette:
1. `#1F2937` - Dark Slate (Banners, footers, body base)
2. `#3B82F6` - Electric Blue (Gradient accents)
3. `#60A5FA` - Soft Sky Blue (Buttons, feature boxes)
4. `#F3F4F6` - Light Neutral (Wrapper canvas)
5. `#F97316` - Warm Accent Orange (Hover states and action buttons)

## External Code & Citations
- Base layout structure, CSS clear fix, form input validation, and media queries follow the lecture examples from Weeks 1-4.
- All code comprises original implementations based on lecture slides.

## Deployment & Verification
- Hosted live on GitHub Pages.
- HTML validated via W3C Markup Validation Service.
- CSS validated via W3C CSS Validation Service.
- Accessibility evaluated using WAVE.