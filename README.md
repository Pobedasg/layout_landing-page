# B&O Landing Page

A mobile-first product landing page built with plain HTML and SCSS, using BEM blocks. The page is coded from the provided **B&O** design in Figma.

**Live demo:** https://pobedasg.github.io/layout_landing-page/

## What's inside

- Mobile-first layout with tablet and desktop breakpoints (SCSS mixins `on-tablet` and `on-desktop`)
- Sections: top bar, header with a navigation menu, product, categories, recommended items, about, contacts and footer
- Hover and transition effects in CSS
- Contact form with built-in HTML5 validation (`required`, `type="email"`)
- Styles split into BEM blocks (`src/styles/blocks`) with shared variables and mixins

There is no JavaScript logic in this project: it is a layout exercise.

## Tech stack

HTML5 · SCSS · BEM · Parcel

## Run locally

```bash
git clone https://github.com/Pobedasg/layout_landing-page.git
cd layout_landing-page
git checkout develop
npm install
npm start
```

## About this project

This is a Mate academy course project, so the repository started from their template (lint and deploy scripts come from it). The markup and styles in `src/` are mine. The design is from the course materials.
