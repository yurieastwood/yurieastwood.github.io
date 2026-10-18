# yurieastwood.github.io

Personal portfolio site. Plain HTML and CSS, no build step.

- `index.html` is the deployable page (GitHub Pages serves it from the repo root).
- `src/page.html` is the same content without the `<html>/<head>` wrapper, used for the Claude preview.

## Fill in before publishing
Search `index.html` for `class="todo"`. Each one marks a detail to replace (employer, dates, roles, talks/certifications). Remove the `todo` class once the text is real.

## Deploy to GitHub Pages
1. Create a public repo named `yurieastwood.github.io`.
2. Commit `index.html` (and this README) to `main`.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site goes live at https://yurieastwood.github.io. A custom domain can be added in the same settings page.
