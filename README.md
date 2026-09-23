# Testimonials Grid Section

## Preview

![Design preview for the Testimonials grid section coding challenge](./design/preview.jpg)

A responsive testimonials layout built for the [Frontend Mentor Testimonials grid section challenge](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).

## Overview

The page presents five graduate testimonials in a responsive grid. The layout adapts from a two-row desktop composition to a single-column mobile view while preserving the visual hierarchy of the original design.

### Features

- Responsive layout for mobile, tablet, and desktop screens
- Semantic HTML structure for the testimonial content
- CSS Grid areas for the desktop arrangement
- Accessible portrait alt text and a screen-reader-only page heading
- Reduced-motion support for users who prefer less animation

## Built with

- Semantic HTML5
- CSS custom properties
- CSS Grid and Flexbox
- Responsive media queries
- [Barlow Semi Condensed](https://fonts.google.com/specimen/Barlow+Semi+Condensed)

## Getting started

No package installation or build step is required. Open `index.html` directly in a browser, or serve the directory locally:

```bash
python3 -m http.server
```

Then visit [http://localhost:8000](http://localhost:8000).

## Project structure

```text
.
├── index.html              # Page markup and testimonial content
├── style.css               # Layout, typography, colors, and responsive styles
├── images/                 # Portraits and decorative image assets
├── design/                 # Challenge reference images
└── style-guide.md          # Colors, typography, and target design widths
```

## Responsive layout

- Desktop: four-column grid with the fifth testimonial spanning the right side
- Tablet: two-column grid
- Mobile: single-column layout with stacked testimonials

The reference designs target widths of `375px` for mobile and `1440px` for desktop. The stylesheet also supports intermediate viewport sizes through responsive grid changes.

## What I practiced

This challenge was an exercise in translating a static design into a reusable layout system. The main focus areas were placing items with named CSS Grid areas, keeping card content readable at different widths, and using semantic markup without adding JavaScript that the page does not need.

## Author

- Website: [Ruben de Man](https://rubendeman.nl)

## Acknowledgments

Challenge provided by [Frontend Mentor](https://www.frontendmentor.io). The original challenge assets and design guidance are included in this repository.
