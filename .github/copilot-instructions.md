# Copilot Instructions for AI Agents

## Project Overview
This is a personal portfolio website for Jesús Ojeda Latronico, a Data Analytics Developer & Automation Specialist. The site is a static single-page application built with HTML and CSS, styled using Tailwind CSS utility classes (compiled into `style.css`).

## Key Files & Structure
- `about_me/index.html`: Main HTML file. Contains all content and structure, including About, Projects, Experience, and Education sections. Navigation is via anchor links.
- `about_me/style.css`: Main stylesheet. Contains Tailwind CSS output and custom styles/animations.
- No build scripts, frameworks, or package managers are present. All assets are static.

## Editing & Conventions
- **Directly edit `index.html` for content changes.**
  - Use semantic HTML and keep accessibility in mind.
- **CSS customizations** should be added to `style.css`.
  - Tailwind utility classes are used in HTML. If new utility classes are needed, add custom CSS rules in `style.css`.
- **Fonts** are loaded via Google Fonts in the HTML `<head>`.
- **No JavaScript frameworks** are used. Only minimal inline JS for UI effects (e.g., header background on scroll).

## Patterns & Examples
- To add a new section, follow the structure of existing `<section id="...">` blocks in `index.html`.
- For new skills or projects, add `<span>` or `<div>` elements with Tailwind classes for consistent styling.
- For icons or SVGs, embed directly in HTML as done for social/contact links.

## Deployment & Testing
- No build or deployment scripts are present. To preview, open `about_me/index.html` in a browser.
- No automated tests or CI/CD. Manual validation only.

## External Integrations
- Social/contact links (GitHub, LinkedIn, email) are hardcoded in the HTML.
- No external APIs or dynamic data sources are used.

## Project-Specific Notes
- The site is designed for clarity and simplicity. Avoid adding unnecessary dependencies or complexity.
- Keep all content and styling self-contained within the `about_me` directory.

---
For major changes, update this file to keep future AI agents productive.
