---
author: ['michaeldel', 'Florian']
date: 1596303150
title: "plantuml, TLDR Pages"
description: "plantuml, Create UML diagrams from a plain text language and render them in different formats."
categories: "common"
---
> More information: <https://plantuml.com/en/command-line>.

- Render diagrams to default format (PNG):

```bash
plantuml diagram1.puml diagram2.puml
```

- Render a diagram in given format (e.g. `png`, `pdf`, `svg`, `txt`):

```bash
plantuml -t format diagram.puml
```

- Render all diagrams of a directory:

```bash
plantuml path/to/diagrams
```

- Render a diagram to the output directory:

```bash
plantuml -o path/to/output diagram.puml
```

- Render a diagram with the configuration file:

```bash
plantuml -config config.cfg diagram.puml
```

- Display help:

```bash
plantuml -help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Florian](mailto:40308458+ProfileID@users.noreply.github.com) | plantuml: fix space was missing (#4233) | 2020-08-01T19:32:30 | [4aeb0ec69d16](https://github.com/tldr-pages/tldr/commit/4aeb0ec69d165dc9639943869a11d034d38d13ad)
[michaeldel](mailto:michaeldel@protonmail.com) | plantuml: add page (#4040) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-05-12T23:47:54 | [7b7dc4815331](https://github.com/tldr-pages/tldr/commit/7b7dc48153317cb5642201bd7f43616d438c34d2)

