# Jacob Redding — Portfolio

A single-page, dependency-free portfolio (plain HTML/CSS/JS + a canvas low-poly background).

## Run locally
Open `index.html` in a browser, or:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy
Any static host works. For GitHub Pages: push `index.html` and `Jacob_Redding_Resume.pdf`
to the `JRedCodes.github.io` repo and the site is live at https://jredcodes.github.io.

## Editing
- **Projects**: each project is an `<article class="card ...">` in the `#projects` section.
  `data-cat` controls the filter tab (`backend`, `systems`, `oop`).
  `data-cat` values: `backend`, `systems`, `gpu`, `oop`. Copy any card to add a new project.
- **Resume**: replace `Jacob_Redding_Resume.pdf` to update the resume button.

## Credits
Tech-stack icons from [Devicon](https://devicon.dev) (MIT License, see `icons/DEVICON-LICENSE.txt`).
