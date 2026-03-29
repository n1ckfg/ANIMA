## About This Project

ANIMA (Arts Network for Integrated Media Applications) is a historic static website from 1994-1995. It was an early web-based multimedia cultural information service focused on media arts, created by The WebWeavers Network Society in Vancouver, Canada.

Original URL: `http://www.anima.wis.net` (archived at web.archive.org)

## Project Structure

This is a static HTML website with no build system or dependencies:

- **Root directory**: Main HTML pages and GIF images for the homepage and primary sections
- **NEXUS/**: Artists projects section, including `Oliver/` subdirectory with essay/article content
- **MAT/People/**: Biographical pages for contributors
- **infomy/**: Special event pages (Epoch Rave Celebration)
- **css/**: Modern addition containing `main.css` for styling broken links

## Key Sections

The site is organized into thematic sections, each with a corresponding `*home.html` page:
- **NEXUS** - Artists projects online
- **SPECTRUM** - Arts and media publications
- **ARTWORLD** - Digital art spaces worldwide
- **ATLAS** - Resource and reference library
- **TECHNE** - Research on interface, immersion and interactivity
- **PERSONA** - Community voice/vision
- **CONNECTIONS** - Special events

## Development Notes

- All pages are plain HTML with 1990s-era markup conventions (e.g., `<blink>`, `<font>`, table-based layouts)
- Images are GIF format (both `.gif` and `.GIF` extensions exist)
- `index.html` and `ANIMAhome.html` are identical (the main homepage)
- No local development server is required; files can be opened directly in a browser

## Broken Link Convention

External links that no longer work are marked with `class="broken"`. The `css/main.css` file styles these with strikethrough formatting. When identifying dead links, add this class to preserve the historical reference while indicating the link is non-functional.
