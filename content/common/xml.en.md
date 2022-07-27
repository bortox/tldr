---
author: ['Daniel Birket']
date: 1629838243
title: "xml, TLDR Pages"
description: "xml, XMLStarlet Toolkit: Query, edit, check, convert and transform XML documents."
categories: "common"
---
> This command also has documentation about its subcommands, e.g. `xml validate`.

> More information: <http://xmlstar.sourceforge.net/docs.php>.

- Display general help, including the list of subcommands:

```bash
xml --help
```

- Execute a subcommand with input from a file or URI, printing to stdout:

```bash
xml subcommand options path/to/input.xml|URI
```

- Execute a subcommand using stdin and stdout:

```bash
xml subcommand options
```

- Execute a subcommand with input from a file or URI and output to a file:

```bash
xml subcommand options path/to/input.xml|URI > path/to/output
```

- Display help for a subcommand:

```bash
xml subcommand --help
```

- Display the version of the XMLStarlet Toolkit:

```bash
xml --version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | xml: remove list of subcommands from main `xml` description. | 2021-08-24T22:50:43 | [5fa1cc018946](https://github.com/tldr-pages/tldr/commit/5fa1cc018946f1e5e5ae031428df80c45edc21a1)
[Daniel Birket](mailto:danielb@birket.com) | xml: changes requested by marchersimon, which undo the "the" changes previously made for sbrl. The `select`, `edit`, and `transform` [...] | 2021-08-24T22:50:43 | [82f626c6937b](https://github.com/tldr-pages/tldr/commit/82f626c6937b3d3141be3468ce5326d997b9da6f)
[Daniel Birket](mailto:danielb@birket.com) | xml: Changes requested by Starbeamrainbowlabs | 2021-08-24T22:50:43 | [4f79b0d5d174](https://github.com/tldr-pages/tldr/commit/4f79b0d5d174e1556ceb14401822c34932a7bd8b)
[Daniel Birket](mailto:danielb@birket.com) | xml: draft all but 3 most complex subcommands | 2021-08-24T22:50:43 | [786342aeefb6](https://github.com/tldr-pages/tldr/commit/786342aeefb62273691c868c40eddade7fd272a1)
[Daniel Birket](mailto:danielb@birket.com) | xml: Changed "More information:" link. | 2021-08-24T22:50:43 | [cbd7a0e7cdfc](https://github.com/tldr-pages/tldr/commit/cbd7a0e7cdfcb5e3a5a703c87405cca5743302f3)
[Daniel Birket](mailto:danielb@birket.com) | xml: added escape, unescape, validate subcommands | 2021-08-24T22:50:43 | [3fd2da89bb76](https://github.com/tldr-pages/tldr/commit/3fd2da89bb7667e20f6ee1b45ea53e33d6dd3356)
[Daniel Birket](mailto:danielb@birket.com) | xml: tweaks to main command entry. | 2021-08-24T22:50:43 | [9916a0b0f7df](https://github.com/tldr-pages/tldr/commit/9916a0b0f7df9163bf66d8a0d1726dbb5ea7650d)
[Daniel Birket](mailto:danielb@birket.com) | xml: explain general input and output | 2021-08-24T22:50:43 | [bc4856feeb1c](https://github.com/tldr-pages/tldr/commit/bc4856feeb1c506edc24c5ab5c0d327059555b46)
[Daniel Birket](mailto:danielb@birket.com) | xml: add pages (incomplete: sub-command templates only) | 2021-08-24T22:50:43 | [67f0a9202fbc](https://github.com/tldr-pages/tldr/commit/67f0a9202fbce1518d13c4a13ad42417fbbb4558)

