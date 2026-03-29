# Zachary Rufener Portfolio Site

This repository contains a simple, fast, static engineering portfolio website built with plain HTML, CSS, and JavaScript for GitHub Pages deployment.

## Files

- `index.html` - Main page structure and portfolio content
- `style.css` - Visual design, layout, responsive behavior, and animations
- `script.js` - Mobile navigation, active section highlighting, and scroll reveal effects
- `README.md` - Editing and deployment notes

## How to Edit the Site

### Update links

Search for these comments in `index.html` and replace the placeholder values:

- `REPLACE THIS WITH YOUR RESUME LINK`
- `REPLACE THIS WITH YOUR LINKEDIN LINK`
- `REPLACE THIS WITH YOUR GITHUB LINK`
- `REPLACE THIS WITH YOUR EMAIL`

### Update content

Most site content lives in `index.html`. Edit the text inside each section:

- Hero
- About
- Projects
- Experience
- Skills
- Resume
- Contact

There is also a project placeholder labeled `ADD YOUR PROJECT HERE` that you can replace with a real project later.

### Update styling

The main theme colors and reusable design values are at the top of `style.css` inside the `:root` block.

You can easily adjust:

- Colors
- Spacing
- Border radius
- Shadows
- Layout widths

## How to Preview Locally

Because this is a static site, you can preview it in a few simple ways:

### Option 1: Open directly

Open `index.html` in a browser.

### Option 2: Use a local server

If you have Python installed:

```bash
python -m http.server
```

Then open:

```text
http://localhost:8000
```

## How GitHub Pages Works

This repository is intended to deploy automatically through GitHub Pages.

For a repository named `zacharyrufener.github.io`, GitHub serves the site directly from the default branch. After you push changes to `main`, GitHub Pages will automatically rebuild and publish the updated site.

Your live site URL should be:

```text
https://zacharyrufener.github.io
```

## Recommended Next Edits

- Replace placeholder links with real profile URLs
- Add a real resume PDF
- Swap placeholder project links for real documents, GitHub repositories, or case studies
- Add internship details, dates, and measurable outcomes
- Add screenshots or CAD renders later if desired
