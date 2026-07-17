<div align="center">

# Yan Zihao Homepage

### A minimal personal academic homepage based on the Luka Homepage template.

[中文说明](README.zh-CN.md) · [Live Demo](https://wzsyyh.github.io/luka-homepage-template/) · [Use This Template](https://github.com/wzsyyh/luka-homepage-template/generate)

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-c2714f?style=flat-square)](https://wzsyyh.github.io/luka-homepage-template/)
[![Template Ready](https://img.shields.io/badge/Template-Ready-3d3929?style=flat-square)](https://github.com/wzsyyh/luka-homepage-template/generate)
[![Stack](https://img.shields.io/badge/Stack-HTML%20%7C%20CSS%20%7C%20JS-e28a67?style=flat-square)](https://github.com/wzsyyh/luka-homepage-template)
[![License](https://img.shields.io/badge/License-MIT-8c8577?style=flat-square)](./LICENSE.md)

</div>

This repository contains Yan Zihao's personal homepage. It is a standalone static site that can be deployed directly to GitHub Pages without build tooling.

## Why This Template

- Minimal but not plain: clean typography, warm colors, and balanced spacing.
- Academic-ready layout: built for homepage content, not generic portfolio blocks.
- Static by default: deploy directly to GitHub Pages with zero build steps.
- Easy to fork: replace a few text blocks and assets, then publish.
- Mobile-friendly: desktop and phone layouts are already tuned.

## What You Get

| Section | Included |
| --- | --- |
| Personal intro | `About Me`, avatar, email, social links |
| Academic timeline | `Education`, `Experience` |
| Showcase | `Projects`, `Publications`, `Awards` |
| UX details | Dark mode toggle, smooth entrance animation, responsive layout |
| Replaceable assets | Avatar, institution logo, favicon, CV link |

## Quick Start

### 1. Create your own copy

Use GitHub's [Use This Template](https://github.com/wzsyyh/luka-homepage-template/generate) button, or copy this folder into a new repository.

Suggested repository names:

- `luka-homepage`
- `luka-homepage-template`
- `luka-academic-homepage`

### 2. Customize the content

You will mainly edit:

- `index.html` for all main content
- `assets/css/theme-luka.css` for colors, spacing, and layout
- `assets/img/avatar.png` for the profile image
- `assets/img/institution.jpg` for school branding
- `assets/cv/Yan_Zihao_CV.pdf` for the linked CV

### 3. Replace your assets

- Avatar: `assets/img/avatar.png`
- Institution logo: `assets/img/institution.jpg`
- Favicon: replace `assets/img/favicon.svg`
- Resume: `assets/cv/Yan_Zihao_CV.pdf`
- GitHub: `https://github.com/Apricity177`

### 4. Deploy to GitHub Pages

1. Open repository `Settings`
2. Go to `Pages`
3. Choose `Deploy from a branch`
4. Select `main` and `/ (root)`
5. Save and wait for deployment

## Project Structure

```text
.
├── index.html
├── README.md
├── README.zh-CN.md
├── LICENSE.md
└── assets
    ├── css
    │   ├── font_sans_serif.css
    │   └── theme-luka.css
    ├── cv
    ├── img
    └── js
        └── scale.fix.js
```

## Design Notes

- The left sidebar stays top-aligned, matching the original personal homepage layout.
- The visual language is intentionally warm and understated rather than highly decorative.
- The template keeps just enough structure for academic use while remaining easy to personalize.

## Attribution

The footer includes two lines by default:

1. Your own site copyright
2. `Luka Homepage Template by Yuheng Yang`

If you want to preserve template attribution, keep the second line.

## License

This template includes its own `LICENSE.md`, so you can publish it as an independent repository immediately.
