---
author: ['Daniel Birket']
date: 1629838243
title: "xml depyx, TLDR Pages"
description: "xml depyx, Convert a PYX (ESIS - ISO 8879) document to XML format."
categories: "common"
---
> More information: <http://xmlstar.sourceforge.net/docs.php>.

- Convert a PYX (ESIS - ISO 8879) document to XML format:

```bash
xml depyx path/to/input.pyx|URI > path/to/output.xml
```

- Convert a PYX document from stdin to XML format:

```bash
cat path/to/input.pyx | xml depyx > path/to/output.xml
```

- Display help for the `depyx` subcommand:

```bash
xml depyx --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | xml: changes requested by marchersimon, which undo the "the" changes previously made for sbrl. The `select`, `edit`, and `transform` [...] | 2021-08-24T22:50:43 | [82f626c6937b](https://github.com/tldr-pages/tldr/commit/82f626c6937b3d3141be3468ce5326d997b9da6f)
[Daniel Birket](mailto:danielb@birket.com) | xml: Changes requested by Starbeamrainbowlabs | 2021-08-24T22:50:43 | [4f79b0d5d174](https://github.com/tldr-pages/tldr/commit/4f79b0d5d174e1556ceb14401822c34932a7bd8b)
[Daniel Birket](mailto:danielb@birket.com) | xml: draft all but 3 most complex subcommands | 2021-08-24T22:50:43 | [786342aeefb6](https://github.com/tldr-pages/tldr/commit/786342aeefb62273691c868c40eddade7fd272a1)
[Daniel Birket](mailto:danielb@birket.com) | xml: Changed "More information:" link. | 2021-08-24T22:50:43 | [cbd7a0e7cdfc](https://github.com/tldr-pages/tldr/commit/cbd7a0e7cdfcb5e3a5a703c87405cca5743302f3)

