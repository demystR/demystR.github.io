# demystR.github.io

The homepage for the [demystR](https://demystr.github.io) book series. It is a small Quarto website: `_quarto.yml` sets up the site and navbar, `index.qmd` is the homepage, `about.qmd` is the About page and `styles.css` holds the demystR theme.

The book cards come from `books.yml`, laid out by `books.ejs`. To mark a book as published, give it a `path` and set its `status`: `read` for a finished book, `progress` for one that is live but still being written, `coming` for one that is not live yet (no `path`). Card images are in `images/`.

To preview locally, run `quarto preview`. Pushing to `main` renders the site and deploys it to GitHub Pages (`.github/workflows/deploy.yml`).
