---
author: ['bl-ue', 'marchersimon', 'Argishti Rostamian']
date: 1621541621
title: "httpflow, TLDR Pages"
description: "httpflow, A command-line utility to capture and dump HTTP streams."
categories: "common"
---
> More information: <https://github.com/six-ddc/httpflow>.

- Capture traffic on all interfaces:

```bash
httpflow -i any
```

- Use a bpf-style capture to filter the results:

```bash
httpflow host httpbin.org or host baidu.com
```

- Use a regular expression to filter requests by URLs:

```bash
httpflow -u 'regular_expression'
```

- Read packets from pcap format binary file:

```bash
httpflow -r out.cap
```

- Write the output to a directory:

```bash
httpflow -w path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Argishti Rostamian](mailto:1332785+WhileLoop@users.noreply.github.com) | httpflow: add page (#4493) | 2020-10-06T18:27:34 | [b16010bf8ce5](https://github.com/tldr-pages/tldr/commit/b16010bf8ce5e5421b309310deb56eeab85078b8)

