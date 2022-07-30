---
author: ['Wilco']
date: 1604660353
title: "amass viz"
description: "amass viz, Visualize gathered information in a network graph."
categories: "common"
---
> More information: <https://github.com/OWASP/Amass/blob/master/doc/user_guide.md#the-viz-subcommand>.

- Generate a D3.js visualization based on database data:

```bash
amass viz -d3 -dir path/to/database_directory
```

- Generate a DOT file based on database data:

```bash
amass viz -dot -dir path/to/database_directory
```

- Generate a Gephi Graph Exchange XML Format (GEXF) file based on database data:

```bash
amass viz -gexf -dir path/to/database_directory
```

- Generate a Graphistry JSON file based on database data:

```bash
amass viz -graphistry -dir path/to/database_directory
```

- Generate a Maltego CSV file based on database data:

```bash
amass viz -maltego -dir path/to/database_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Wilco](mailto:wilcovanbeijnum@gmail.com) | amass, httprobe, sublist3r, theHarvester: add page (#4912) | 2020-11-06T11:59:13 | [2f2a1144ffa3](https://github.com/tldr-pages/tldr/commit/2f2a1144ffa33fd43055c7cc7ef5c1b8d5ad224f)

