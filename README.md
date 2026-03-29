# Zachary Rufener Portfolio Site

This repository contains a minimal, static portfolio website built with plain HTML, CSS, and JavaScript for GitHub Pages.

## Files

- `index.html` - Page structure and portfolio content
- `style.css` - Typography, layout, colors, spacing, and responsive styling
- `script.js` - Mobile navigation and subtle scroll reveal behavior
- `README.md` - Editing and deployment notes

## Editing the Site

Most content is in `index.html`. Update the text in these sections:

- Hero
- About
- Projects
- Experience
- Skills
- Contact

Search for these placeholder comments and replace the links:

- `REPLACE THIS WITH YOUR RESUME LINK`
- `REPLACE THIS WITH YOUR LINKEDIN LINK`
- `REPLACE THIS WITH YOUR GITHUB LINK`
- `REPLACE THIS WITH YOUR PROJECT LINK`
- `REPLACE THIS WITH YOUR EMAIL`
- `REPLACE assets/profile.jpg WITH YOUR ACTUAL PROFESSIONAL HEADSHOT`

## Profile Photo

The hero section uses this image path:

```text
assets/profile.jpg
```

Replace that file with your actual professional headshot, or update the `img` tag in `index.html` if you want to use a different file name.

## Adjusting the Design

The main design system is defined at the top of `style.css` inside `:root`.

You can quickly change:

- Background and text colors
- Accent color
- Layout width
- Section spacing
- Typography scale

## Previewing Locally

You can open `index.html` directly in a browser, or run a simple local server:

```bash
python -m http.server
```

Then open:

```text
http://localhost:8000
```

## GitHub Pages

This repository is set up for GitHub Pages. Because the repository name is `zacharyrufener.github.io`, pushing to the `main` branch will automatically update the live site.

Expected live URL:

```text
https://zacharyrufener.github.io
```

## Recommended Next Updates

- Replace placeholder links with real profile URLs
- Add a resume PDF
- Replace `assets/profile.jpg` with a professional headshot
- Replace project placeholders with real case studies or repositories
- Add internship dates, organization names, and measurable outcomes
