# Project Changelog - Part 2 Implementation

All updates made to the EcoGlow Skincare project following Part 1 feedback and Part 2 rubric guidelines.

## [2.0.0] - Part 2 Submission

### Added
- **External Stylesheet (`css/style.css`):** Created a centralized external CSS file containing standard resets, desktop layouts, visual colors, and media queries.
- **Responsive Media Queries:** Integrated multi-breakpoint media queries (`@media (max-width: 900px)` and `@media (max-width: 600px)`).
- **Responsive Elements:** Added standard `<picture>` picture elements with responsive `srcset` fallback tags for mobile views.
- **Relative Units:** Replaced static pixel dimensions in typography and element spacing with scalable `rem`, `em`, and `%` units.

### Fixed
- **HTML Syntax Fixes:** Fixed the unclosed `<video>` tag in `index.html`.
- **CSS Separation:** Completely removed all embedded `<style>` blocks across `.html` documents to rely solely on `css/style.css`.
- **Navigation Layout:** Converted inline navigation into an adaptive Flexbox list that shifts to stacked view on mobile displays.

### References
- MDN Web Docs. (2026). *Responsive design*. Available at: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design
- W3C. (2026). *CSS Flexible Box Layout Module Level 1*. Available at: https://www.w3.org/TR/css-flexbox-1/