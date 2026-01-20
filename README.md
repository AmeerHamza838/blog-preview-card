# Blog Preview Card

![Design preview for the Blog preview card coding challenge](./design/desktop-design.jpg)

## Overview

A responsive blog preview card component built with semantic HTML5, accessible CSS, and local font integration. This project showcases a clean, modern card design featuring an article preview with author information.

## Features

- **Responsive Design**: Optimized for mobile (375px) and desktop (1440px) viewports
- **Semantic HTML5**: Proper use of `<main>`, `<article>`, `<time>`, and `<footer>` elements
- **Accessibility**: ARIA labels, proper alt text, and semantic role attributes
- **Local Fonts**: Figtree variable font family (weights 500 & 800) hosted locally
- **Modern CSS**: Flexbox layout, CSS variables ready, and smooth hover effects
- **Color System**: 
  - Primary Yellow: `hsl(47, 88%, 63%)`
  - Dark Gray: `hsl(0, 0%, 7%)`
  - Light Gray: `hsl(0, 0%, 42%)`
  - White: `hsl(0, 0%, 100%)`

## What's Included

- Semantic HTML structure with microdata
- Custom typography hierarchy
- Card component with hover states
- Author section with avatar image
- Accessible link management (`rel="noopener noreferrer"`)
- Meta tags for SEO and theme color

## File Structure

```
blog-preview-card/
├── index.html                 # Main HTML file with embedded styles
├── assets/
│   ├── fonts/
│   │   ├── Figtree-VariableFont_wght.ttf
│   │   ├── Figtree-Italic-VariableFont_wght.ttf
│   │   └── ...
│   └── images/
│       ├── illustration-article.svg
│       ├── image-avatar.webp
│       └── favicon-32x32.png
├── design/
│   ├── desktop-design.jpg
│   ├── mobile-design.jpg
│   └── active-states.jpg
└── README.md
```

## Getting Started

1. Clone or download the repository
2. Open `index.html` in your browser
3. No build tools or package managers required

## Browser Support

Works on all modern browsers that support:
- CSS Flexbox
- CSS Grid
- Variable Fonts
- Semantic HTML5

## Technologies Used

- **HTML5**: Semantic markup with microdata
- **CSS3**: Flexbox, CSS Custom Properties ready
- **Fonts**: Figtree Variable Font (self-hosted)
