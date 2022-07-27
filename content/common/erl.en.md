---
author: ['mira01', 'pxgamer']
date: 1560056064
title: "erl, TLDR Pages"
description: "erl, Run and manage programs in the Erlang programming language."
categories: "common"
---
> More information: <https://www.erlang.org>.

- Compile and run sequential Erlang program as a common script and then exit:

```bash
erlc files && erl -noshell 'mymodule:myfunction(arguments), init:stop().'
```

- Connect to a running Erlang node:

```bash
erl -remsh nodename@hostname -sname custom_shortname -hidden -setcookie cookie_of_remote_node
```

- Tell the Erlang shell to load modules from a directory:

```bash
erl -pa directory_with_beam_files
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | erl: add link to homepage | 2019-06-09T06:54:24 | [bcbdc3889b1e](https://github.com/tldr-pages/tldr/commit/bcbdc3889b1e6a6c80af93a2fe6ee0f6f1c17933)
[mira01](mailto:miracech@email.cz) | erl: add page (#2364) | 2018-11-12T11:16:37 | [4904e2867881](https://github.com/tldr-pages/tldr/commit/4904e28678815011bab7bbf427df6baa0c0a783b)

