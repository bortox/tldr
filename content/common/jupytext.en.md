---
author: ['Bradley Garrod', 'pixel']
date: 1632941775
title: "jupytext, TLDR Pages"
description: "jupytext, Tool to convert Jupyter notebooks to plain text documents, and back again."
categories: "common"
---
> More information: <https://jupytext.readthedocs.io>.

- Turn a notebook into a paired `.ipynb`/`.py` notebook:

```bash
jupytext --set-formats ipynb,py notebook.ipynb
```

- Convert a notebook to a `.py` file:

```bash
jupytext --to py notebook.ipynb
```

- Convert a `.py` file to a notebook with no outputs:

```bash
jupytext --to notebook notebook.py
```

- Convert a `.md` file to a notebook and run it:

```bash
jupytext --to notebook --execute notebook.md
```

- Update the input cells in a notebook and preserve outputs and metadata:

```bash
jupytext --update --to notebook notebook.py
```

- Update all paired representations of a notebook:

```bash
jupytext --sync notebook.ipynb
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | *: normalize readthedocs.io more information links (#6593) | 2021-09-29T20:56:15 | [d22ca9676f6c](https://github.com/tldr-pages/tldr/commit/d22ca9676f6c02b19e6e1728f5ea777e7985c9d0)
[Bradley Garrod](mailto:32489229+BreD1810@users.noreply.github.com) | jupytext: add page (#4072) | 2020-05-27T22:48:18 | [fd7b66cf9ded](https://github.com/tldr-pages/tldr/commit/fd7b66cf9ded9336b63f6cd578112237a8ff037b)

