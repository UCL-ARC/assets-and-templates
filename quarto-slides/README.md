# ARC Quarto revealjs slides template

Basic template for creating [revealjs slide decks using Quarto](https://quarto.org/docs/presentations/revealjs/) branded with UCL ARC banner or logo.

The `banner-slides.qmd` file is set up to include a banner across the top of the slides and `logo-slides.qmd` a logo in bottom right corner.
The slide metadata (for example title and author name) is specified in the YAML frontmatter in each file.
Sample Quarto Markdown content for introducing ARC is included in the `_content.qmd` file.

Assuming [Quarto is installed](https://quarto.org/docs/get-started/), to render the slides to revealjs HTML documents run

```sh
quarto render
```

from the root of the repository.
