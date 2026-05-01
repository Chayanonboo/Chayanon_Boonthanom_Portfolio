# Data Analyst Portfolio - Implementation Plan

## Objective
Build a Data Analyst portfolio website for Chayanon Boonthanom using Vanilla HTML/CSS/JS with a modern dark theme and JetBrains Mono font, and prepare it for deployment to GitHub Pages.

## Tech Stack
- Vanilla HTML5
- Vanilla CSS3 (Custom variables for theming)
- Vanilla JavaScript (For basic interactions, e.g., smooth scrolling)
- Google Fonts (JetBrains Mono)

## Proposed File Structure
```
/
├── index.html
├── style.css
├── script.js
└── README.md
```

## Implementation Steps

### 1. Setup Local Environment
- Create the necessary files (`index.html`, `style.css`, `script.js`).
- Initialize a local Git repository to prepare for GitHub deployment.

### 2. Implement HTML Structure (`index.html`)
- Setup HTML5 boilerplate.
- Import 'JetBrains Mono' font from Google Fonts.
- **Navbar:** Simple top navigation (Home, Projects, Contact).
- **Hero Section:** 
  - Main Headline: Chayanon Boonthanom
  - Sub-headline: Data Analyst
- **Projects Section:** 
  - Create a responsive grid layout.
  - Add 3 placeholder project cards with titles (Project 1, Project 2, Project 3), brief descriptions, and link placeholders.
- **Contact Section:** 
  - Add placeholders for Email, LinkedIn, and GitHub links.

### 3. Implement Styling (`style.css`)
- **Theme Variables:** Define CSS variables for a modern dark theme (e.g., background `#121212`, text `#e0e0e0`, and a subtle accent color).
- **Typography:** Apply `font-family: 'JetBrains Mono', monospace;` globally.
- **Layouts:** Use Flexbox/Grid to ensure the layout is fully responsive on mobile and desktop.
- Add hover effects on project cards and contact links.

### 4. GitHub Pages Deployment Strategy
*(I will provide instructions on how to do this once the files are ready)*
- Create a new public repository on GitHub.
- Commit the local files and push them to the repository.
- Enable GitHub Pages from the repository settings (deploying from the main branch).

## Verification
- Test `index.html` locally to ensure the dark theme and JetBrains Mono font render correctly.
- Verify responsiveness across different screen sizes.