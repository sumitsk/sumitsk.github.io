# sumitsk.github.io

Personal website of Sumit Kumar, served by GitHub Pages at https://sumitsk.github.io.

The site is plain HTML and CSS with no build step. `index.html` holds all page content and `style.css` holds all styling. The empty `.nojekyll` file tells GitHub Pages to serve the files as they are instead of building them with Jekyll.

## Editing

- Page text, links, patents and publications: edit `index.html`.
- Resume: replace `files/resume.pdf`. The page links to that path, so keep the file name.
- Images: add files under `images/` and reference them as `/images/<name>`.
- `projects/index.html` redirects the old `/projects/` URL to the Research projects section of the home page.

## Previewing locally

Run `python3 -m http.server 8000` from the repository root and open http://localhost:8000. Pushing to `master` publishes the site.
