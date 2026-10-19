# Anshu Pratap — Portfolio

A responsive, static portfolio website built with HTML, CSS, and vanilla JavaScript. No build tools or dependencies are required.

## Preview locally

Open `index.html` in a browser. The Google Fonts used for the design load when an internet connection is available; system fonts remain as fallbacks.

## Publish

Upload the contents of this folder to a GitHub repository, then enable **Settings → Pages** and select the branch and root folder. The site is ready to serve as a static GitHub Pages website.

## Personalize before publishing

- The contact section includes a clickable email link to `anshupratap79@gmail.com`; update it in `index.html` if it changes.
- The Sales & Revenue dashboard has a GitHub link. Other project cards have no link until you add a real public repository or demo URL.
- Add more concrete internship details or project descriptions where appropriate.
- A resume download is intentionally omitted because no resume file was provided. Add a real PDF and link it from the navigation or contact area when ready.
- Project cards, profile content, colors, and layout are all editable in `index.html` and `styles.css`.

## Add another project

1. Open `index.html` and find `<div class="project-grid">`.
2. Copy one complete `<article class="project-card" ...> ... </article>` from inside that grid and paste it before the closing `</div>` for `project-grid`.
3. Update its `data-category` to `data`, `build`, or `team` so the existing filters include it.
4. Change its project number, category label, `<h3>` title, description, and tag names. You can reuse one of the existing `.project-visual` designs or adjust it in `styles.css`.
5. For a real public repository or demo, replace the existing project link with your URL. If there is no link yet, remove that `<a class="project-link" ...>` element rather than leaving a placeholder.

The project filter counts update automatically when the page loads. If you add a new category, add a matching filter button in the `.filters` group and use that same category name on the project's `data-category`.

## Files

- `index.html` — portfolio content and semantic structure
- `styles.css` — responsive layout, colors, and visual styling
- `script.js` — mobile navigation, project filters, and current footer year
- `assets/anshu-pratap.jpeg` — supplied original portrait used in the header/footer avatar and About section
- `assets/favicon.svg` — matching browser tab icon
