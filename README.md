# Project Portfolio

This repository contains a multi-page personal portfolio website designed for GitHub Pages.

## Structure
- index.html — Home page
- about.html — About Me
- projects.html — Projects overview
- resume.html — Resume and documents
- contact.html — Contact page
- projects/ — Detailed project pages
- assets/ — CSS, JavaScript, images, and documents

project-portfolio/
│
├── index.html                 ← Home
├── projects.html              ← Projects Overview
├── resume.html                ← Resume
│
├── projects/
│   ├── telecom-modernization.html
│   ├── cybersecurity-monitoring.html
│   ├── inventory-management.html
│   ├── data-federation.html
│   ├── security-lab.html
│   └── ai-digital-transformation.html  
│
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   ├── images/
│   └── documents/
│       ├── Resume.pdf
│       └── PMP_Certificate.pdf
│
└── README.md

## Publish to GitHub Pages
1. Commit and push the repository.
2. Open GitHub repository Settings → Pages.
3. Choose GitHub Actions as the deployment source.
4. The workflow in .github/workflows/deploy.yml will publish the site.


