# AI Agent Instructions for FrontendOkulu2025

This is a frontend learning project organized as a series of progressive HTML/CSS lessons. Follow these guidelines when assisting with this codebase:

## Project Structure

- `/Dersler/`: Main lessons directory
  - `/Ders001/`: Basic HTML fundamentals
  - `/Ders002/`: CSS styling and layout
  - Each lesson has related HTML files with corresponding CSS files

## Key Patterns

1. **HTML Structure**
   - Use semantic HTML5 elements
   - Include viewport meta tag for responsiveness
   - Turkish language content in examples
   - Example: See `Ders001/semantic.html`

2. **CSS Organization**
   - One CSS file per concept (e.g., `flex.css`, `animation.css`)
   - Reset pattern at start of CSS files:
   ```css
   * {
       box-sizing: border-box;
       margin: 0;
       padding: 0;
   }
   ```
   - Container-based layouts with percentage widths
   - Mobile-first responsive design

3. **Flexbox Usage**
   - `.container` class for flex layouts
   - Common patterns:
     - `flex-direction: row`
     - `justify-content: center/space-evenly`
     - `align-items: center`
   - See `Ders002/flex.css` for examples

## Development Workflow

- No build process required - pure HTML/CSS
- Preview files:
  1. Open HTML files directly in browser
  2. Use VS Code Live Server extension (recommended)
  3. Python simple server: `python -m http.server 8000`

## File Naming Conventions

- Lesson folders: `DersXXX`
- Concept-specific CSS: `conceptname.css`
- Related HTML: `conceptname.html`
- Keep file names lowercase, use hyphens for spaces

When adding new content, follow existing patterns in the closest related lesson file.