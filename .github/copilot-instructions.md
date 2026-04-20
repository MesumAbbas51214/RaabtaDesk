# Raabta Desk Copilot Instructions

## Project Overview
Raabta Desk is a static landing page for an inbound revenue system SaaS product targeting Pakistani businesses. The site consists of a single HTML file (`index.html`) with associated CSS (`styles.css`) and assets.

## Architecture
- **Structure**: Single-page application with semantic HTML sections
- **Styling**: Modern CSS with custom properties, responsive grid layouts, and utility classes
- **Assets**: PDF handbook stored in `/assets/` directory

## Key Patterns
- Use CSS custom properties (e.g., `--brand: #0e5a49`) for consistent theming
- Apply responsive design with `clamp()` for fluid typography (e.g., `font-size: clamp(2.2rem, 4.5vw, 4.25rem)`)
- Leverage `color-mix()` for subtle color variations (e.g., `color-mix(in oklab, var(--border) 65%, white)`)
- Structure layouts with CSS Grid: `.hero-grid`, `.pain-grid`, `.steps-grid` etc.
- Follow BEM-like naming: `.site-header`, `.section`, `.btn`, `.btn-ghost`

## Development Workflow
- Edit `index.html` and `styles.css` directly - no build process required
- Test responsiveness across breakpoints: 980px and 700px
- Update placeholder URLs in HTML comments (AUDIT_URL, HANDBOOK_URL, etc.) when deploying

## Conventions
- Use Inter font family loaded from Google Fonts
- Maintain Urdu/Hindi phrases for cultural relevance (e.g., "Team hai. Ab system bhi hona chahiye.")
- Ensure accessibility with proper ARIA labels and focus management
- Keep content focused on inbound revenue system benefits and use cases

## File References
- `index.html`: Main landing page with hero, sections, and footer
- `styles.css`: Complete styling with CSS Grid layouts and custom properties
- `assets/raabta_desk_handbook_light (1).pdf`: Product handbook for download