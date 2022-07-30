---
author: ['bl-ue', 'pxgamer', 'Seth Falco', 'mattbangert']
date: 1629050349
title: "sqsc"
description: "sqsc, A command-line AWS Simple Queue Service client."
categories: "common"
---
> More information: <https://github.com/yongfei25/sqsc>.

- List all queues:

```bash
sqsc lq queue_prefix
```

- List all messages in a queue:

```bash
sqsc ls queue_name
```

- Copy all messages from one queue to another:

```bash
sqsc cp source_queue destination_queue
```

- Move all messages from one queue to another:

```bash
sqsc mv source_queue destination_queue
```

- Describe a queue:

```bash
sqsc describe queue_name
```

- Query a queue with SQL syntax:

```bash
sqsc query "SELECT body FROM queue_name WHERE body LIKE '%user%'"
```

- Pull all messages from a queue into a local SQLite database in your present working directory:

```bash
sqsc pull queue_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | sqsc: add link to homepage | 2019-05-29T14:41:10 | [890ca68563e3](https://github.com/tldr-pages/tldr/commit/890ca68563e3598109a1ebe13ba13a61375b546d)
[mattbangert](mailto:mattbangert@gmail.com) | sqsc: add page (#1992) | 2018-02-17T09:30:22 | [b78c5184a627](https://github.com/tldr-pages/tldr/commit/b78c5184a627960c846f716e983774706e484dca)

