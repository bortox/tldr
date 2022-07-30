---
author: ['Daniel Birket']
date: 1629838243
title: "xml transform"
description: "xml transform, Transform XML documents using XSLT."
categories: "common"
---
> More information: <http://xmlstar.sourceforge.net/docs.php>.

- Transform an XML document using an XSL stylesheet, passing one XPATH parameter and one literal string parameter:

```bash
xml transform path/to/stylesheet.xsl -p "Count='count(/xml/table/rec)'" -s Text="Count=" path/to/input.xml|URI
```

- Display help for the `transform` subcommand:

```bash
xml transform --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | xml: marchersimon requested changes | 2021-08-24T22:50:43 | [aa67236fc342](https://github.com/tldr-pages/tldr/commit/aa67236fc342f205ad4f0309bbb3b7b2500402bb)
[Daniel Birket](mailto:danielb@birket.com) | xml: add select, edit and transform subcommands. | 2021-08-24T22:50:43 | [1202e84d48d9](https://github.com/tldr-pages/tldr/commit/1202e84d48d9c6c554f4bdf3f4b2fed83976e94c)
[Daniel Birket](mailto:danielb@birket.com) | xml: Changes requested by Starbeamrainbowlabs | 2021-08-24T22:50:43 | [4f79b0d5d174](https://github.com/tldr-pages/tldr/commit/4f79b0d5d174e1556ceb14401822c34932a7bd8b)
[Daniel Birket](mailto:danielb@birket.com) | xml: draft all but 3 most complex subcommands | 2021-08-24T22:50:43 | [786342aeefb6](https://github.com/tldr-pages/tldr/commit/786342aeefb62273691c868c40eddade7fd272a1)
[Daniel Birket](mailto:danielb@birket.com) | xml: Changed "More information:" link. | 2021-08-24T22:50:43 | [cbd7a0e7cdfc](https://github.com/tldr-pages/tldr/commit/cbd7a0e7cdfcb5e3a5a703c87405cca5743302f3)
[Daniel Birket](mailto:danielb@birket.com) | xml: add pages (incomplete: sub-command templates only) | 2021-08-24T22:50:43 | [67f0a9202fbc](https://github.com/tldr-pages/tldr/commit/67f0a9202fbce1518d13c4a13ad42417fbbb4558)

