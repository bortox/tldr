---
author: ['pxgamer', 'Eric', 'Breck', 'Francesco Franchina']
date: 1602297505
title: "jupyter, TLDR Pages"
description: "jupyter, Web application to create and share documents that contain code, visualizations and notes."
categories: "common"
---
> Primarily used for data analysis, scientific computing and machine learning.

> More information: <https://jupyter.org>.

- Start a Jupyter notebook server in the current directory:

```bash
jupyter notebook
```

- Open a specific Jupyter notebook:

```bash
jupyter notebook example.ipynb
```

- Export a specific Jupyter notebook into another format:

```bash
jupyter nbconvert --to html|markdown|pdf|script example.ipynb
```

- Start a server on a specific port:

```bash
jupyter notebook --port=port
```

- List currently running notebook servers:

```bash
jupyter notebook list
```

- Stop the currently running server:

```bash
jupyter notebook stop
```

- Start JupyterLab, if installed, in the current directory:

```bash
jupyter lab
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Francesco Franchina](mailto:cescus92@gmail.com) | jupyter: add nbconvert example (#4582) | 2020-10-10T04:38:25 | [86a01e4aca4c](https://github.com/tldr-pages/tldr/commit/86a01e4aca4ce2157c535e794d76de84a022d169)
[pxgamer](mailto:owzie123@gmail.com) | jupyter: add link to homepage | 2019-06-06T04:42:48 | [2b7c717311a0](https://github.com/tldr-pages/tldr/commit/2b7c717311a041a397ec0bfcdf465f4baf131777)
[Breck](mailto:37387936+breckuh@users.noreply.github.com) | jupyter: add lab command (#2323) | 2018-09-11T09:10:47 | [29027da75178](https://github.com/tldr-pages/tldr/commit/29027da75178a5ca834ecaa29d6aa9d11d29fbd9)
[Eric](mailto:ericchang00@gmail.com) | jupyter: improve description and add notebook command | 2018-01-17T04:32:23 | [e028de28fa89](https://github.com/tldr-pages/tldr/commit/e028de28fa89986baed0862bffedbf1424d9cdd3)
[Eric](mailto:ericchang00@gmail.com) | jupyter: add page | 2018-01-17T04:32:23 | [6d6dcd45e5f0](https://github.com/tldr-pages/tldr/commit/6d6dcd45e5f09baf72019a8b7dbf1aa1a5279e7d)

