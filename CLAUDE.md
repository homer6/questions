# Guidelines for Questions Repository

## Project Structure
- Content is served via GitHub Pages from the `docs/` directory
- Questions are stored as HTML files in `docs/questions/`
- `docs/index.html` serves as the main navigation page

## Commands
- Preview site locally: `python -m http.server 8000 -d docs`
- Validate HTML: `npx html-validate docs/**/*.html`

## Content Guidelines
- Use semantic HTML (h1, p, ul, etc.) for accessibility 
- Keep HTML files simple and focused on content
- Question files follow naming pattern: `question-NNNN.html`
- Each question should have a clear title and concise answer
- Use relative links for navigation between pages
- Add new questions to the index page with appropriate links

## Format
- Use 2-space indentation for HTML files
- Include appropriate meta tags for SEO
- Maintain a clean, accessible structure in all pages