---
author: ['Daniel Birket']
date: 1629838243
title: "xml select, TLDR Pages"
description: "xml select, Select from XML documents using XPATHs."
categories: "common"
---
> Tip: use `xml elements` to display the XPATHs of an XML document.

> More information: <http://xmlstar.sourceforge.net/docs.php>.

- Select all elements matching "XPATH1" and print the value of their sub-element "XPATH2":

```bash
xml select --template --match "XPATH1" --value-of "XPATH2" path/to/input.xml|URI
```

- Match  "XPATH1" and print the value of "XPATH2" as text with new-lines:

```bash
xml select --text --template --match "XPATH1" --value-of "XPATH2" --nl path/to/input.xml|URI
```

- Count the elements of "XPATH1":

```bash
xml select --template --value-of "count(XPATH1)" path/to/input.xml|URI
```

- Count all nodes in one or more XML documents:

```bash
xml select --text --template --inp-name --output " " --value-of "count(node())" --nl path/to/input1.xml|URI path/to/input2.xml|URI
```

- Display help for the `select` subcommand:

```bash
xml select --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | xml: more requested changes | 2021-08-24T22:50:43 | [caa77bfe5ac1](https://github.com/tldr-pages/tldr/commit/caa77bfe5ac11b019f8436e093a0bda22f687d84)
[Daniel Birket](mailto:danielb@birket.com) | xml: marchersimon requested changes | 2021-08-24T22:50:43 | [aa67236fc342](https://github.com/tldr-pages/tldr/commit/aa67236fc342f205ad4f0309bbb3b7b2500402bb)
[Daniel Birket](mailto:danielb@birket.com) | xml: add select, edit and transform subcommands. | 2021-08-24T22:50:43 | [1202e84d48d9](https://github.com/tldr-pages/tldr/commit/1202e84d48d9c6c554f4bdf3f4b2fed83976e94c)
[Daniel Birket](mailto:danielb@birket.com) | xml: Changes requested by Starbeamrainbowlabs | 2021-08-24T22:50:43 | [4f79b0d5d174](https://github.com/tldr-pages/tldr/commit/4f79b0d5d174e1556ceb14401822c34932a7bd8b)
[Daniel Birket](mailto:danielb@birket.com) | xml: draft all but 3 most complex subcommands | 2021-08-24T22:50:43 | [786342aeefb6](https://github.com/tldr-pages/tldr/commit/786342aeefb62273691c868c40eddade7fd272a1)
[Daniel Birket](mailto:danielb@birket.com) | xml: Changed "More information:" link. | 2021-08-24T22:50:43 | [cbd7a0e7cdfc](https://github.com/tldr-pages/tldr/commit/cbd7a0e7cdfcb5e3a5a703c87405cca5743302f3)
[Daniel Birket](mailto:danielb@birket.com) | xml: add pages (incomplete: sub-command templates only) | 2021-08-24T22:50:43 | [67f0a9202fbc](https://github.com/tldr-pages/tldr/commit/67f0a9202fbce1518d13c4a13ad42417fbbb4558)

