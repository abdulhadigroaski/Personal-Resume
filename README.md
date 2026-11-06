# Personal Resume Website

A responsive, accessible personal resume for **Abdul Hadi Groaski**, a BSIT student at Quaid-i-Azam University, Islamabad. It is built with only raw HTML5 and CSS3.

This project is **Task 1: Semantic HTML & CSS Personal Resume** of the Frontend Web Developer Internship at Barakah TechLabs.

## Overview

The site is a single page that presents my education, technical skills and two Java projects from my GitHub profile. The assignment focuses on semantic HTML and web accessibility, so the markup uses meaningful elements and the page works with keyboard navigation and assistive technology.

## Technologies Used

- HTML5
- CSS3 (custom properties, Flexbox, Grid, media queries)

No JavaScript, CSS frameworks, libraries or templates are used.

## Main Features

- Semantic structure using `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` and `<footer>`
- Logical heading hierarchy (one `<h1>`, then `<h2>` sections and `<h3>` items)
- Skip-to-content link and clearly visible keyboard focus styles
- Descriptive page title, meta description and `lang` attribute
- Colour palette with high text contrast
- Responsive layout for phones, tablets and desktops, with no horizontal scrolling
- Project cards with subtle hover effects and links to the GitHub repositories
- Respects the `prefers-reduced-motion` setting

## Sections

1. Header with name, title, short introduction, navigation and contact links
2. About me
3. Education
4. Technical skills
5. Projects (Expense Tracker and Student Management System)
6. Professional development
7. Footer with contact links

## Project Structure

```
personal-resume/
├── index.html   # Page content and semantic structure
├── style.css    # All styling and responsive rules
└── README.md    # Project documentation
```

## Running Locally

1. Download or clone this repository.
2. Open the `personal-resume` folder in VS Code.
3. Open `index.html` in any web browser, either by double-clicking it or by using the **Live Server** extension (right-click `index.html` and choose **Open with Live Server**).

No build step or installation is needed.

## Deploying to GitHub Pages

1. Push this project to a GitHub repository, for example `personal-resume`.
2. In the repository, open **Settings** and then **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then click **Save**.
5. After a minute or two, the site is available at:

   `https://abdulhadigroaski.github.io/personal-resume/`

## Contact

- Email: [abdulhadigroaski@gmail.com](mailto:abdulhadigroaski@gmail.com)
- LinkedIn: [Abdul Hadi Groaski](https://www.linkedin.com/in/abdul-hadi-groaski-959a49318)
- GitHub: [abdulhadigroaski](https://github.com/abdulhadigroaski)
