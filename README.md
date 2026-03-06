# Accessibility Report

## Overview
This report documents the accessibility audit conducted on the index.html page of my web portfolio.

---

## Tools Used

- Chrome DevTools Lighthouse Accessibility Audit
- WAVE Web Accessibility Tool

---

## Issues Found

### 1. Image Accessibility
Some images required alternative text for screen readers.

### 2. Heading Structure
Headings were reviewed to ensure they follow proper hierarchy (h1 → h2 → h3).

### 3. Link Text
Links were checked to ensure they use descriptive text instead of vague phrases like "click here".

### 4. Form Labels
All form inputs were verified to ensure they include associated labels.

### 5. Language Attribute
The `lang="en"` attribute was added to the HTML tag.

---

## Fixes Implemented

- Added descriptive `alt` attributes to all images.
- Corrected heading order for better structure.
- Improved link text to clearly describe the destination.
- Ensured all form inputs have labels.
- Added language attribute to the HTML tag.

---

## Final Lighthouse Accessibility Score

Accessibility Score: **94**
