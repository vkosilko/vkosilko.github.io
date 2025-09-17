# Project Structure

## Root Level Files
- `index.md` - Jekyll page that includes the CV content
- `vladimir.kosilko.cv.md` - Main CV content in Markdown
- `_config.yml` - Jekyll site configuration
- `.gitignore` - Git ignore rules

## Directories
- `_layouts/` - Jekyll layout templates
  - `cv.html` - Custom CV layout with inline CSS
- `.git/` - Git repository metadata
- `.kiro/` - Kiro AI assistant configuration and steering rules

## Content Organization
- **Single-page design** - All CV content in one Markdown file
- **Layout separation** - HTML structure in `_layouts/cv.html`
- **Content inclusion** - `index.md` uses `include_relative` to pull in CV content

## File Naming Conventions
- Use lowercase with dots for separation (e.g., `vladimir.kosilko.cv.md`)
- Jekyll convention with underscore prefixes for special directories (`_layouts/`)
- Standard web filenames for entry points (`index.md`)

## Content Guidelines
- CV content should remain in the main `vladimir.kosilko.cv.md` file
- Styling should be contained within the layout files
- Keep the structure minimal and focused on content presentation