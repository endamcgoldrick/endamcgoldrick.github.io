# Enda McGoldrick: portfolio site

My personal site: who I am, my experience as an IT support engineer, the projects I have built, and how to reach me. It is a hand-written static site (HTML, CSS and a little JavaScript) with no framework and no build step, published with GitHub Pages at https://endamcgoldrick.github.io/.

<!-- TODO (Enda): add a screenshot of the home page as docs/screenshot-home.png, then show it here with ![The home page](docs/screenshot-home.png) -->
*Screenshot: to be added.*

## What is in it

| Path | What it is |
|---|---|
| `index.html` | The home page: experience, projects, problems I have solved, skills and contact |
| `projects/` | One case study page for each project, and the stylesheet they share (`case.css`) |
| `img/` | Images used on the pages |
| `Enda-McGoldrick-CV.pdf` | My CV |

The case studies are for Le Chéile (a calendar app) and three Microsoft 365 and Azure practice labs. Where a lab has not been run yet, its page says so and has a clearly marked `TODO (Enda)` where my results will go.

## Run it on your own computer

There is nothing to install. Open `index.html` in a browser, or serve the folder so links between pages work as they do online:

```
npx serve .
```

## Publishing

GitHub Pages publishes the `main` branch. Merging a change is what puts it live.

## Before publishing a change

- Check the page at phone width (about 390 pixels) and at desktop width. Nothing should scroll sideways.
- Search the pages for `TODO (Enda)` and fill in or remove each one. They are visible text on the page.
- Do not add tenant names, subscription IDs, real customer names or other people's details to any page or image.

## Licence

- The code (HTML, CSS and JavaScript) is under the MIT licence. See [LICENSE](LICENSE).
- The text, the CV and the images are my own and are **not** covered by that licence. All rights reserved.
