# info511-f24.github.io

## Colors

-   `#0C234B` - Arizona Blue: use against a white background and pass contrast checks.

-   `#AB0520` - Arizona Red: used for acccenting.

## Rendering

Locally, in RStudio, click *Build Website* on the Build tab or in any editor (including RStudio) run `quarto render` in the Terminal.

## Publishing

Push changes to the repo to trigger the GitHub Action that publishes the website. If any R packages are added or updated, make sure to run `renv::snapshot()` and commit and push the updated lockfile as well.
