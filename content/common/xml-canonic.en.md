---
author: ['Daniel Birket']
date: 1629838243
title: "xml canonic"
description: "xml canonic, Make XML documents canonical."
categories: "common"
---
> More information: <http://xmlstar.sourceforge.net/docs.php>.

- Make an XML document canonical, preserving comments:

```bash
xml canonic path/to/input.xml|URI > path/to/output.xml
```

- Make an XML document canonical, removing comments:

```bash
xml canonic --without-comments path/to/input.xml|URI > path/to/output.xml
```

- Make XML exclusively canonical, using an XPATH from a file, preserving comments:

```bash
xml canonic --exc-with-comments path/to/input.xml|URI path/to/c14n.xpath
```

- Display help for the `canonic` subcommand:

```bash
xml canonic --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | xml: changes requested by marchersimon, which undo the "the" changes previously made for sbrl. The `select`, `edit`, and `transform` [...] | 2021-08-24T22:50:43 | [82f626c6937b](https://github.com/tldr-pages/tldr/commit/82f626c6937b3d3141be3468ce5326d997b9da6f)
[Daniel Birket](mailto:danielb@birket.com) | xml: Changes requested by Starbeamrainbowlabs | 2021-08-24T22:50:43 | [4f79b0d5d174](https://github.com/tldr-pages/tldr/commit/4f79b0d5d174e1556ceb14401822c34932a7bd8b)
[Daniel Birket](mailto:danielb@birket.com) | xml: draft all but 3 most complex subcommands | 2021-08-24T22:50:43 | [786342aeefb6](https://github.com/tldr-pages/tldr/commit/786342aeefb62273691c868c40eddade7fd272a1)
[Daniel Birket](mailto:danielb@birket.com) | xml: Changed "More information:" link. | 2021-08-24T22:50:43 | [cbd7a0e7cdfc](https://github.com/tldr-pages/tldr/commit/cbd7a0e7cdfcb5e3a5a703c87405cca5743302f3)
[Daniel Birket](mailto:danielb@birket.com) | xml: add pages (incomplete: sub-command templates only) | 2021-08-24T22:50:43 | [67f0a9202fbc](https://github.com/tldr-pages/tldr/commit/67f0a9202fbce1518d13c4a13ad42417fbbb4558)

