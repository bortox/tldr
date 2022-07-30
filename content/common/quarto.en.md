---
author: ['Philippe Massicotte']
date: 1658965096
title: "quarto"
description: "quarto, An open-source scientific and technical publishing system built on Pandoc."
categories: "common"
---
> More information: <https://quarto.org/>.

- Create a Quarto project:

```bash
quarto create-project path/to/project
```

- Create a new website project:

```bash
quarto create-project path/to/destination_directory --type website
```

- Create a new book project:

```bash
quarto create-project path/to/destination_directory --type book
```

- Render an R Markdown file to HTML:

```bash
quarto render path/to/file.rmd --to html
```

- Render a Quarto file to HTML:

```bash
quarto render path/to/file.qmd --to html
```

- Render a Jupyter notebook to HTML:

```bash
quarto render path/to/file.ipynb --to html
```

- Render an R Markdown, Jupyter, or Quarto file to PDF:

```bash
quarto render path/to/file --to pdf
```

- Render an R Markdown, Jupyter, or Quarto file to a Microsoft `docx` document:

```bash
quarto render path/to/file --to docx
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Philippe Massicotte](mailto:pmassicotte@hotmail.com) | quarto: add page (#8254) | 2022-07-28T01:38:16 | [71a3b6921e1b](https://github.com/tldr-pages/tldr/commit/71a3b6921e1b7e3e61ba79fd07aaf15e85e3b007)

