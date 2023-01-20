# My CV Web Page Written in Markdown

The markdown framework used to generate the site is called [MkDocs](https://www.mkdocs.org/user-guide/)

The mkdocs theme used is [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/getting-started/)

## MkDocs Commands (for my reference)

* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.

## Deploy to GitHub Pages

1. run `mkdocs build` to generate the `site/` folder
1. commit changes to the `site/` folder
1. GitHub action will deploy the `site/` folder to pages