# Copilot Instructions for AI Agents

## Project Overview
This is a static portfolio website for "Kofi Wood". The project consists of two main files:
- `index.html`: Main HTML structure, including navigation, hero, projects, about, resume, skills, and contact sections.
- `style.css`: Custom CSS for layout, colors, and responsive design.

## Architecture & Patterns
- **Single-page structure**: All content sections are defined in `index.html` and navigated via anchor links in the navbar.
- **Styling**: All styles are in `style.css`. No CSS frameworks are used; all layout and design are custom.
- **No build tools**: This project does not use npm, webpack, or other build systems. All files are static and can be opened directly in a browser.
- **No external dependencies**: No JavaScript, libraries, or APIs are present. All logic is declarative HTML/CSS.
- **Image assets**: The hero section references `your-image.jpg`, which should be provided or replaced as needed.

## Developer Workflows
- **Preview**: Open `index.html` in a browser to view changes. No build or test commands are required.
- **Debugging**: Use browser dev tools to inspect layout and styles.
- **Adding content**: Add new sections or update existing ones directly in `index.html`. Style changes go in `style.css`.
- **Custom conventions**: 
  - Use semantic HTML for sections (`<section>`, `<header>`, `<nav>`, etc.).
  - Class names follow kebab-case (e.g., `.hero-content`, `.nav-links`).
  - Responsive design is handled via CSS only.

## Examples
- To add a new section (e.g., Testimonials), create a `<section id="testimonials">` in `index.html` and style it in `style.css`.
- To change the color scheme, update the gradient and color variables in `.hero` and `.navbar` classes in `style.css`.

## Key Files
- `index.html`: Main content and structure.
- `style.css`: All custom styles.

## Recommendations for AI Agents
- Focus on semantic, accessible HTML and clean CSS.
- Do not introduce JavaScript or external dependencies unless explicitly requested.
- When updating navigation, ensure anchor links match section IDs.
- Keep all changes browser-compatible; test by opening `index.html` locally.

---
For questions or unclear conventions, ask the user for clarification or examples.
