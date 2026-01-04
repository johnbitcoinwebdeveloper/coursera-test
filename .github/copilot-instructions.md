# Copilot Instructions for coursera-test

## Project Overview
This is a simple static HTML website deployed to GitHub Pages. The site consists of a single page with basic HTML content.

## Architecture
- **Main Component**: `site/index.html` - The only page, containing static HTML with no JavaScript or CSS.
- **Deployment**: Automated via GitHub Actions workflow that publishes the entire repository to GitHub Pages on pushes to the `main` branch.

## Key Patterns
- Use standard HTML5 structure with `<!DOCTYPE html>`, `<html lang="en">`, and essential meta tags (`charset`, `viewport`).
- Content is hardcoded in the HTML; no dynamic elements or external dependencies.
- Example structure from `site/index.html`:
  ```html
  <!DOCTYPE html>
  <html lang="en">
  <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>My first page</title>
  </head>
  <body>
      <h1> Today is Sunday</h1>
      <p> John does not work. He stays home for sick. i love it</p>
  </body>
  </html>
  ```

## Developer Workflows
- **Editing**: Modify `site/index.html` directly in a text editor.
- **Deployment**: Commit changes and push to `main` branch; GitHub Actions handles deployment automatically (see `.github/workflows/static.yml`).
- **No Build Process**: No compilation, minification, or preprocessing required.
- **Testing**: Open `site/index.html` in a browser to preview changes locally.

## Conventions
- Keep content simple and semantic; avoid unnecessary tags or attributes.
- Title and content are informal/personal, reflecting the project's nature as a basic test site.
- No external libraries, frameworks, or build tools are used.

## Integration Points
- **GitHub Pages**: The site is hosted at the repository's Pages URL (configured via the workflow).
- **No External APIs**: All content is static and self-contained.</content>
<parameter name="filePath">/Users/brian/coursera-test/index.html/.github/copilot-instructions.md