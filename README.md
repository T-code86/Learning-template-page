# Web Foundry

Web Foundry is a responsive, multi-page front-end concept for a hands-on web development learning resource. It introduces HTML, CSS, and JavaScript through dedicated topic guides, original diagrams, a learning roadmap, and detailed project briefs.

The original classroom exercise has been reorganized into a framework-free static site with page-to-page navigation, semantic markup, responsive styles, accessible interactions, and image explanations.

## Features

- Responsive layout for desktop, tablet, and mobile screens
- Separate HTML, CSS, and JavaScript learning guides
- Learning roadmap with milestones and practical deliverables
- Project briefs with original illustrations, image descriptions, skills, and next steps
- About page explaining the goals and scope of the project
- Shared mobile navigation with keyboard support on every page
- Filterable project gallery and project library
- Native, keyboard-accessible FAQ accordions
- Skip link, visible focus styles, and reduced-motion support
- Original, locally stored SVG diagrams and project illustrations
- No third-party JavaScript dependencies

## Project structure

```text
.
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── images/
│   │   ├── about-workflow.svg
│   │   ├── css-box-model.svg
│   │   ├── html-structure.svg
│   │   ├── js-dom.svg
│   │   ├── learning-path.svg
│   │   └── project-*.svg
│   ├── js/
│   │   └── main.js
│   └── favicon.svg
├── about.html
├── css.html
├── html.html
├── index.html
├── javascript.html
├── learning-path.html
├── projects.html
├── README.md
└── .gitignore
```

## Run locally

This is a static website. No package installation or compilation is needed.

1. Clone or download the repository.
2. Open `index.html` in a browser, or serve the project folder with a local development server.
3. To edit the page, open the project folder in your preferred code editor.

For example, the **Live Server** extension for Visual Studio Code can serve the page locally and refresh it when files change.

## Deploy with GitHub Pages

1. Push the project to a GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Choose **Deploy from a branch**, select the `main` branch and `/ (root)`, then save.
4. Wait for the deployment to finish and open the Pages URL shown in the settings.

All pages use relative links and assets, so they can be deployed from the repository root without a bundler or custom build command.

## Push an existing local project to GitHub

Create an empty repository on GitHub, then run these commands from the project folder. Replace the remote URL with your own:

```bash
git init
git add .
git commit -m "Build multi-page Web Foundry learning site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

If Git is already initialized, skip `git init` and add or update the `origin` remote as needed.

## Built with

- HTML
- CSS
- Vanilla JavaScript

The stylesheet loads DM Sans, Space Grotesk, and DM Mono from Google Fonts when a network connection is available. System font fallbacks are included. Page illustrations are original local SVG files and do not require a network connection.

## Scope

This is a front-end learning concept, not a production course platform. It does not include user accounts, hosted lessons, payments, a backend, or a live course delivery system. Project briefs and visual mockups are learning references, not claims of completed client work.
