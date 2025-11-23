# CLAUDE.md - AI Assistant Guide for web-designs

## Repository Overview

This repository contains web design projects and assets. It serves as a collection of web designs, templates, and front-end implementations.

**Repository:** allisoncriten-maker/web-designs
**Purpose:** Web design projects, templates, and front-end development

---

## Project Structure

```
web-designs/
├── CLAUDE.md          # This file - AI assistant guidelines
├── README.md          # Project documentation (to be added)
├── assets/            # Static assets (images, fonts, icons)
├── css/               # Stylesheets
├── js/                # JavaScript files
├── pages/             # HTML pages
└── designs/           # Design mockups and references
```

---

## Development Conventions

### File Naming
- Use lowercase with hyphens for file names: `my-component.html`, `main-styles.css`
- Use descriptive names that reflect content/purpose
- Group related files in appropriate directories

### HTML Standards
- Use semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- Include proper meta tags for SEO and responsiveness
- Ensure accessibility with ARIA attributes where needed
- Use meaningful `alt` text for images

### CSS Conventions
- Use CSS custom properties (variables) for colors, fonts, and spacing
- Follow mobile-first responsive design approach
- Use BEM naming convention for classes: `block__element--modifier`
- Keep specificity low; avoid `!important`
- Organize styles logically: reset, variables, base, components, utilities

### JavaScript Standards
- Use modern ES6+ syntax
- Prefer `const` and `let` over `var`
- Use meaningful variable and function names
- Add comments for complex logic
- Handle errors gracefully

---

## Code Style Guidelines

### Indentation & Formatting
- Use 2 spaces for indentation
- Keep lines under 100 characters when possible
- Add blank lines between logical sections

### Comments
- Use comments to explain "why" not "what"
- Document any non-obvious design decisions
- Include attribution for third-party code/assets

### Accessibility
- Ensure color contrast meets WCAG 2.1 AA standards
- Support keyboard navigation
- Test with screen readers when possible
- Include skip links for navigation

---

## Common Tasks

### Creating a New Page
1. Create HTML file in `pages/` directory
2. Include standard meta tags and viewport settings
3. Link to shared stylesheets in `css/`
4. Follow existing page structure for consistency

### Adding Styles
1. Add component-specific styles to relevant CSS file
2. Use CSS custom properties for themeable values
3. Ensure responsive behavior with media queries
4. Test across multiple viewport sizes

### Adding JavaScript
1. Place scripts in `js/` directory
2. Use modules where supported
3. Initialize on `DOMContentLoaded` event
4. Avoid global namespace pollution

---

## Testing & Validation

### Before Committing
- Validate HTML using W3C validator
- Check CSS for errors and browser compatibility
- Test responsive behavior at common breakpoints:
  - Mobile: 320px, 375px, 414px
  - Tablet: 768px, 1024px
  - Desktop: 1280px, 1440px, 1920px
- Verify cross-browser compatibility (Chrome, Firefox, Safari, Edge)
- Check accessibility with browser dev tools

### Performance Considerations
- Optimize images (use WebP where supported)
- Minimize CSS and JavaScript for production
- Use lazy loading for below-fold images
- Avoid render-blocking resources

---

## Git Workflow

### Branch Naming
- Feature branches: `feature/description`
- Bug fixes: `fix/description`
- Experiments: `experiment/description`

### Commit Messages
- Use present tense: "Add header component" not "Added header component"
- Be descriptive but concise
- Reference issues when applicable

### Pull Requests
- Include description of changes
- Add screenshots for visual changes
- List testing performed

---

## AI Assistant Guidelines

### When Making Changes
1. **Read first**: Always read existing files before modifying
2. **Maintain consistency**: Follow existing patterns in the codebase
3. **Test thoroughly**: Verify changes work as expected
4. **Keep it simple**: Avoid over-engineering solutions
5. **Document decisions**: Add comments for non-obvious choices

### File Operations
- Prefer editing existing files over creating new ones
- Group related changes logically
- Maintain existing code organization

### Code Generation
- Generate accessible, semantic HTML
- Write clean, maintainable CSS
- Create performant JavaScript
- Include responsive considerations by default

### What to Avoid
- Don't add unnecessary dependencies
- Don't create files that aren't needed
- Don't over-complicate simple solutions
- Don't ignore existing conventions

---

## Resources

### Documentation
- [MDN Web Docs](https://developer.mozilla.org/)
- [Can I Use](https://caniuse.com/) - Browser compatibility
- [WCAG Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)

### Tools
- Browser DevTools for debugging
- Lighthouse for performance audits
- axe for accessibility testing

---

## Notes

This repository is in early development. As projects are added, this document should be updated to reflect:
- Specific project requirements
- Added tooling (build systems, preprocessors)
- Design system components
- Deployment procedures

---

*Last updated: 2025-11-23*
